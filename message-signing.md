# 🛡️ Research Note: Message Signing & Provenance in Messaging Systems


## 1. Apache Pulsar

* **Message signing**: ❌ Not natively supported.
* **Hash chaining / provenance**: ❌ Not supported.
* **Security features**:

  * End-to-end encryption (E2EE) with AES–RSA/ECDSA key wrapping ([pulsar.apache.org][1]).
  * TLS/mTLS transport encryption .
  * Authentication via OAuth2/JWT, Kerberos .
* **Workaround**: Implement signing via Pulsar Functions or client logic:

  1. Calculate a SHA‑256 hash of the message.
  2. Sign with a private key.
  3. Attach `signature`, `signerId`, and `prevHash` in message properties.
  4. Downstream functions verify before processing.

---

## 2. Apache Kafka

* **Message signing**: ❌ Not native.
* **Hash chaining / provenance**: ❌ Not supported.
* **Security features**:

  * TLS and SASL for transport encryption and authentication.
  * ACLs for access control.
* **Workaround**: Use producer interceptors, Kafka Streams, or Connect SMTs to compute and embed signature + chain metadata in headers or payload.

---

## 3. Azure Service Bus

* **Message signing / provenance**: ❌ Not supported.
* **Security features**:

  * SAS tokens (HMAC-SHA256) and OAuth for access control ([pulsar.apache.org][2], [cloud.ibm.com][3], [pulsar.apache.org][4], [ibm.com][5], [pulsar.apache.org][1]).
* **Workaround**: Manually embed signing and chaining metadata in message content or headers.

---

## 4. IBM MQ + Advanced Message Security (AMS)

* **Message signing**: ✅ Fully supported via AMS policies. AMS supports:

  * Integrity (digital signatures)
  * Privacy (sign + encrypt)
  * Confidentiality (encryption only) ([cloud.ibm.com][3]).
* **Hash chaining / provenance**: ✅ Yes—end-to-end protection with PKI and policy enforcement .
* **Security features**: PKI-based signing, encryption, keystore management, and audit capabilities.

---

## 5. Enterprise Service Buses (ESBs: Apache Camel, IBM ACE, Oracle OSB)

* **Message signing**: ✅ Supported via ESB security components.
* **Provenance**: ⚠️ Varies; supported through integration flow policies.
* **Security features**: TLS transport, and optional payload-level signing/encryption.

---

## 6. ZeroMQ (CurveZMQ)

* **Transport-level security**: ✅ CurveZMQ (ZMTP v3.0) offers authentication and encryption.
* **Message-level signing**: ❌ Not built-in; requires application-level implementation.

---

### 🔍 Summary Table

| System                     | Message Signing | Hash Chaining / Provenance | Transport Security                   |
| -------------------------- | --------------- | -------------------------- | ------------------------------------ |
| **Apache Pulsar**          | ❌               | ❌                          | ✅ E2EE, TLS/mTLS, OAuth/JWT/Kerberos |
| **Apache Kafka**           | ❌               | ❌                          | ✅ TLS, SASL, ACLs                    |
| **Azure Service Bus**      | ❌               | ❌                          | ✅ SAS tokens, OAuth                  |
| **IBM MQ + AMS**           | ✅               | ✅                          | ✅ TLS, PKI, AMS                      |
| **ESBs (Camel, ACE, OSB)** | ✅ (via ESB)     | ⚠️ Varies                  | ✅ TLS, encryption policies           |
| **ZeroMQ (CurveZMQ)**      | ❌               | ❌ (app-level)              | ✅ Transport-level via CurveZMQ       |

---

## ✅ Recommendations

* **Enterprise-grade signing & provenance**: Choose **IBM MQ + AMS** or an ESB with integrated signing.
* **Cloud/microservices (Pulsar/Kafka/Azure SB)**:

  1. Secure transport channels (TLS/SASL/E2EE).
  2. Add message-level signing and chaining via custom code/functions/interceptors.
  3. Verify signatures downstream to preserve an audit trail.
* **ZeroMQ-based systems**: Use CurveZMQ for transport security, and layer message signing in your application logic if needed.

---

📌 *Need implementation examples?* I can provide:

* **IBM MQ AMS** policy configuration,
* **Pulsar Function** for signing/chaining,
* **Kafka interceptor** injecting signature metadata.

[1]: https://pulsar.apache.org/docs/4.0.x/security-encryption/?utm_source=chatgpt.com "End-to-End Encryption | Apache Pulsar"
[2]: https://pulsar.apache.org/docs/2.6.0/cookbooks-message-queue/?utm_source=chatgpt.com "Using Pulsar as a message queue"
[3]: https://cloud.ibm.com/docs/mqcloud?topic=mqcloud-mqoc_app_ams&utm_source=chatgpt.com "Enabling application Advanced Message Security (AMS) - IBM Cloud"
[4]: https://pulsar.apache.org/docs/next/concepts-messaging/?utm_source=chatgpt.com "Messaging - Apache Pulsar"
[5]: https://www.ibm.com/docs/en/ibm-mq/9.4.x?topic=security-using-keystores-certificates-ams&utm_source=chatgpt.com "Using keystores and certificates with AMS - IBM® MQ"
