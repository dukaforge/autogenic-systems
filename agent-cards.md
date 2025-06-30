# Agents as the Architecture: A Functional Taxonomy for Autogenic Systems

**C.G. Djinovic**
**June 30, 2025**

---

# Table of Contents

1. Introduction  
2. Why Agents? A Systemic Design View  
3. Agent Typology: Autonomy, Scope, and Breadth  
4. Subsystem Responsibilities and Agent Roles  
5. Assisted Agents and External Support  
6. Recursive Agency and Structural Evolution  
7. Transition Paths and Upgradeability  
8. Conclusion  

**Appendices**  
A. Agent Type Cards (Printable Summary)  
B. Glossary of Terms  
C. AI Breadth and Task Scope Matrix  
D. Comparison to TMF/ETSI Agent Models  
E. MLA Reference List

---

# Executive Summary

Autogenic systems are built entirely from agents. Each agent is a bounded system of behavior—defined by its autonomy level, learning capacity, scope of operation, and task breadth. This research note provides a structured taxonomy of agent types used in autogenic architectures, explaining how they function individually and in cooperation to deliver robust, self-managing systems.

We identify four core agent types—**procedural**, **assisted**, **learning**, and **recursive**—each with increasing cognitive and functional capability. Agents are deployed across internal (system) and external (service) scopes, and are assigned to subsystems based on the minimum capability required. Recursive agents, the most powerful, are used sparingly to enable self-reflection, self-evolution, and strategic goal invention.

By grounding this classification in system needs, task scope, and architectural design principles, this note provides a practical and extensible foundation for building fully agent-based autonomous systems—both in isolated deployments and federated ecosystems.

## 1. Introduction

As autonomous systems evolve beyond fixed automation and adaptive control, their architectures increasingly rely on modular, intelligent components—agents—that reason, act, and collaborate across complex environments. In autogenic systems, where the system must manage itself, generate its own goals, and evolve its internal structure, the agent becomes the **primary architectural unit**.

This research note presents a systematic classification of agents based on their cognitive capabilities, system roles, and scope of operation. We move beyond classical distinctions between reactive and deliberative agents to offer a more functional view—focused on what tasks the agent performs, how it acquires or adapts behavior, and whether it contributes to introspective or structural reasoning.

The taxonomy we present includes four core types:
- **Procedural agents**, which execute predefined logic
- **Assisted agents**, which generate behavior under guidance but do not learn
- **Learning agents**, which adapt within bounded domains
- **Recursive agents**, which reflect, invent, and evolve behavior and goals

Each agent type is mapped to specific **subsystems**, **task scopes**, and **self-X capabilities**, enabling the construction of intelligent systems that scale in autonomy and functionality while retaining composability and traceability.

This agent classification also supports interoperability with partially autonomous or legacy systems. By understanding how agents differ in capability and purpose, autogenic systems can more effectively support mixed-agent environments—offering guidance, policy enforcement, or even surrogate reasoning when necessary.

The sections that follow explore these agent types in depth, how they relate to the system’s cognitive architecture, and how they can evolve over time within the boundaries of task scope and operational responsibility.

## 2. Why Agents? A Systemic Design View

Autogenic systems are defined not by static components but by their ability to manage themselves, adapt to change, and evolve structure and function over time. In such systems, behavior is not centralized or monolithic—it is modular, distributed, and context-aware. This makes the **agent** the natural unit of system construction.

An agent is not merely a software module. It is a **bounded cognitive unit**—a container for logic, behavior, and interface. Each agent encapsulates:
- **Intent interpretation** (what should be done)
- **Execution behavior** (how it is done)
- **Interaction protocol** (who else is involved)
- **Learning or reasoning** (how behavior adapts or evolves)

By composing systems entirely from agents, autogenic architectures achieve several key benefits:

### 2.1 Modularity by Capability
Each subsystem can be built using the **minimum necessary type of agent**—procedural for stable operations, learning for adaptive analysis, recursive for structural change. This minimizes cognitive overhead and maximizes explainability.

### 2.2 Dual-Scope Operation
Agents are deployed to handle both the **internal structure** of the system and the **external services** it delivers. This supports dual-scope reasoning, introspection, and federated service delivery without changing architectural principles.

### 2.3 Lifecycle Compatibility
Agents are lifecycle-aware. They can be designed, instantiated, upgraded, retired, or evolved by other agents—especially recursive ones. This enables structural self-management and graceful degradation via fallback modes.

### 2.4 Cognitive Mapping
Each agent aligns with one or more **self-X capabilities** and cognitive focus areas (e.g., analysis, planning, execution), forming a cognitive architecture that can be observed, debugged, and evolved.

In short, **agents are not add-ons to the system—they are the system**. Understanding their roles, capabilities, and interdependencies is essential for designing sustainable, evolvable autogenic platforms.

## 2. Why Agents? A Systemic Design View

Autogenic systems are defined not by static components but by their ability to manage themselves, adapt to change, and evolve structure and function over time. In such systems, behavior is not centralized or monolithic—it is modular, distributed, and context-aware. This makes the **agent** the natural unit of system construction.

An agent is not merely a software module. It is a **bounded cognitive unit**—a container for logic, behavior, and interface. Each agent encapsulates:
- **Intent interpretation** (what should be done)
- **Execution behavior** (how it is done)
- **Interaction protocol** (who else is involved)
- **Learning or reasoning** (how behavior adapts or evolves)

By composing systems entirely from agents, autogenic architectures achieve several key benefits:

### 2.1 Modularity by Capability
Each subsystem can be built using the **minimum necessary type of agent**—procedural for stable operations, learning for adaptive analysis, recursive for structural change. This minimizes cognitive overhead and maximizes explainability.

### 2.2 Dual-Scope Operation
Agents are deployed to handle both the **internal structure** of the system and the **external services** it delivers. This supports dual-scope reasoning, introspection, and federated service delivery without changing architectural principles.

### 2.3 Lifecycle Compatibility
Agents are lifecycle-aware. They can be designed, instantiated, upgraded, retired, or evolved by other agents—especially recursive ones. This enables structural self-management and graceful degradation via fallback modes.

### 2.4 Cognitive Mapping
Each agent aligns with one or more **self-X capabilities** and cognitive focus areas (e.g., analysis, planning, execution), forming a cognitive architecture that can be observed, debugged, and evolved.

In short, **agents are not add-ons to the system—they are the system**. Understanding their roles, capabilities, and interdependencies is essential for designing sustainable, evolvable autogenic platforms.

## 3. Agent Typology — Autonomy, Scope, and Breadth

Agents in autogenic systems are classified not just by how they behave, but by the range of **tasks** they can perform (breadth), the **scope** in which they operate (internal vs. external), and the **level of autonomy** they exhibit. This section introduces a four-part typology that captures these dimensions and provides the foundation for architectural role assignment.

---

### 3.1 Autonomy Levels

Each agent type reflects a degree of autonomy:

- **Procedural**: Fully predefined; executes static logic.
- **Assisted**: Reactive; generates output but depends on external direction.
- **Learning**: Adaptive; adjusts behavior through feedback within a task domain.
- **Recursive**: Reflective; modifies structure, invents goals, and manages other agents.

---

### 3.2 Task Breadth (AI Breadth)

**AI breadth** defines the range of task types an agent can perform or generalize across:

- **Narrow**: One or two predefined tasks.
- **Moderate**: Variation within a domain (e.g., all control tasks).
- **Broad**: Cross-domain capabilities including reflection, invention, and delegation.

Agents do not require learning to have moderate breadth—e.g., assisted agents can complete diverse templates using LLMs but lack memory or adaptation.

---

### 3.3 Scope of Operation

| **Scope**          | **Definition**                                                               |
|--------------------|------------------------------------------------------------------------------|
| **Internal**        | Agents that manage the system’s own structure, subsystems, or agent graph   |
| **External**        | Agents responsible for delivering services, interacting with users or peers |

Some agents (especially recursive) operate in both scopes simultaneously—planning service delivery while managing internal evolution.

---

### 3.4 Agent Type Summary

| **Agent Type**   | **Autonomy** | **AI Breadth** | **Learning** | **Reflection** | **Scope**          |
|------------------|--------------|----------------|---------------|----------------|---------------------|
| Procedural        | Low          | Very Narrow     | No          | No             | Internal + External |
| Assisted          | Low-Mod      | Narrow–Moderate | No          | No             | External            |
| Learning          | Moderate     | Moderate        | Yes         | No             | Internal + External |
| Recursive         | High         | Broad           | Yes         | Yes            | Internal + External |

This typology enables system designers to match agent capabilities to subsystem responsibilities while minimizing unnecessary complexity.

## 4. Subsystem Responsibilities and Agent Roles

Each subsystem in an autogenic system corresponds to a specific set of cognitive and operational functions. These subsystems are not monolithic; they are composed of agents whose behavior aligns with their designated responsibilities. The design principle is clear: **use the simplest agent type sufficient for the task**.

---

### 4.1 Core Subsystems

The autogenic system is composed of seven key subsystems:

| **Subsystem**       | **Primary Role**                                        | **Typical Agent Type**     |
|----------------------|----------------------------------------------------------|------------------------------|
| **Execution**         | Carries out service behavior or control actions         | Procedural                  |
| **Monitoring**        | Emits telemetry and structural state                    | Procedural                  |
| **Analysis**          | Evaluates behavior, infers patterns                     | Learning                    |
| **Planning**          | Sets or generates goals and strategies                  | Recursive                   |
| **Control**           | Enacts plans, adapts configurations, triggers recovery  | Procedural or Learning      |
| **Self-Management**   | Evolves agents, generates new logic or structures       | Recursive                   |
| **Peering**           | Aligns with peer systems and shared intent              | Recursive or Learning       |

---

### 4.2 Assignment by Capability

- **Procedural agents** dominate low-level operations like control loops, logging, and enforcement.
- **Learning agents** inhabit analysis and some dynamic control, learning from data over time.
- **Recursive agents** are placed sparingly, only where structural change or strategic invention is required.

This assignment reflects both **AI breadth** and **self-X capability** alignment. For example:
- **Self-healing** is mapped to Control (Procedural)
- **Self-reflection** is mapped to Self-Management (Recursive)
- **Self-organization** is mapped to Peering (Recursive)

---

### 4.3 Design Principle: Minimal Viable Complexity

Each subsystem is implemented using the **lowest-capability agent that fulfills the task**:
- If the task is static and well-defined → use procedural
- If the task involves reactive generative behavior → use assisted
- If it requires adaptation → use learning
- If it demands structure modification or goal invention → use recursive

This minimizes system fragility and enables fallback operation by disabling higher-capability agents when necessary.

The result is a **layered, intelligible, and evolvable system**—each part mapped clearly to function, scope, and agent class.

## 5. Assisted Agents and External Support

While autogenic systems are composed internally of autonomous agents, they often interact with **peer systems** that are not fully autonomous. These external systems may rely on **assisted agents**—entities capable of generating behavior but dependent on external systems for intent interpretation, planning, or coordination.

---

### 5.1 Defining Assisted Agents

An assisted agent:
- **Generates behavior** (e.g., LLM, template completion)
- **Does not invent goals**
- **Does not learn from feedback**
- **Relies on recursive or human guidance**

They are **not procedural**, because they exhibit generative capacity; nor are they **learning**, as they cannot adapt based on experience. They sit between these two categories, often present in external environments such as:
- Legacy enterprise systems
- LLM-based chatbots without goal memory
- Edge devices with prompt-driven control logic

---

### 5.2 Role of the Autogenic System

Autogenic systems may support assisted agents through:
- **Plan synthesis**: Translating high-level goals into executable instructions
- **Monitoring and validation**: Ensuring assisted behavior conforms to intent
- **Behavioral scaffolding**: Filling in missing reasoning or context

These interactions are grounded in validated self-X capabilities:
- **Self-organization** to coordinate roles and structure
- **Self-governance** to align behavior with policies
- **Self-learning** to understand and adapt to external agent behavior

---

### 5.3 Use Cases

| **Context**                      | **Assisted Agent Role**                   | **Autogenic System Behavior**            |
|----------------------------------|-------------------------------------------|------------------------------------------|
| Industrial IoT                   | Edge device executes plans on demand      | Autogenic system plans, monitors         |
| Smart city systems               | Traffic agent reacts to inputs            | Autogenic system coordinates goals       |
| Metaverse or game engine AI      | NPC generates actions but cannot adapt    | Autogenic system supervises environment  |

---

### 5.4 Architectural Implication

Assisted agents are **not part of the autogenic system**, but they are **within its sphere of influence**. Peering subsystems must be able to detect, interpret, and guide them without assuming internal autonomy.

This capability extends autogenic control to **mixed-autonomy environments**, enabling system-wide coordination without requiring uniform intelligence across all participants.

## 6. Recursive Agency and Structural Evolution

Recursive agents are the defining feature of autogenic systems. They enable not only behavioral adaptation, but **structural evolution**—the ability to modify, generate, or deprecate other agents and control the system's architecture over time.

---

### 6.1 What Makes an Agent Recursive?

A recursive agent is distinguished by its capacity to:
- **Reflect** on its own reasoning or on other agents
- **Invent new goals** or sub-goals
- **Generate or restructure agents, plans, or logic**
- **Control its own behavior dynamically, including fallback**

Recursive agents often operate in paired roles:
- A **producer**, which proposes plans or structures
- A **critic**, which evaluates their effectiveness, coherence, or compliance

This producer–critic architecture underlies planning, self-management, and structural resilience.

---

### 6.2 Roles in the System

Recursive agents are used **sparingly**, due to their complexity. They appear in:

| **Subsystem**       | **Recursive Role**                                           |
|---------------------|---------------------------------------------------------------|
| **Planning**         | Invention of new strategies, goal decomposition              |
| **Self-Management**  | Agent lifecycle management, topology reconfiguration         |
| **Peering**          | Aligning with or guiding assisted or autonomous peer agents  |

Each recursive agent may operate across both internal (system) and external (service) scope, depending on its assigned authority.

---

### 6.3 Structural Evolution

Recursive agents enable **self-evolution** by:
- Instantiating new agents as needed for new capabilities
- Retiring or replacing underperforming agents
- Revising internal policies, control hierarchies, or goal networks
- Triggering fallback modes when capability boundaries are exceeded

In essence, they allow the system to **change its own architecture**, making autogenic systems qualitatively distinct from adaptive or autonomic systems.

---

### 6.4 Containment and Governance

To ensure traceability and safety:
- Recursive agents are launched from **validated templates**
- Their outputs are subject to **runtime evaluation** or **sandboxing**
- Their interactions are scoped and monitored via **intent boundaries**

This enables recursive control without exposing the system to runaway logic or misalignment.

Recursive agency is what empowers a system to become **self-improving, self-reflective, and self-evolving**—a minimal requirement for L5+ autonomy.

## 7. Transition Paths and Upgradeability

Autogenic systems are not static; they evolve over time—both in capability and internal structure. This evolution is made possible by **agent-level upgrade paths**, where agents transition from one type to another based on system needs, observed behavior, or reflective evaluation.

---

### 7.1 Principles of Upgrade

- **Agents are upgraded only when needed**: If a procedural agent suffices, it is retained.
- **Upgrades are triggered by structural change, goal expansion, or environment shift**.
- **Recursive agents manage upgrades**, instantiating or retiring agents through introspection and policy.

---

### 7.2 Valid Upgrade Paths

| **From**       | **To**           | **Condition**                                                     |
|----------------|------------------|--------------------------------------------------------------------|
| Procedural      | Learning          | Requires adaptation or policy tuning                               |
| Assisted        | Replaced          | Assisted agents are external; not upgraded internally              |
| Learning        | Recursive         | Requires goal invention, structure evolution, or agent generation  |
| Recursive       | N/A               | Terminal class; may spawn new agents or downgrade itself if needed |

---

### 7.3 Downgrade and Fallback

In some cases, agents are **downgraded** to reduce complexity or preserve functionality:
- Recursive agents may be suspended in constrained environments.
- Learning agents may revert to cached policies or procedural fallbacks.
- Procedural agents may be preferred during degraded modes or limited execution budgets.

These fallback transitions are part of the system’s **resilience strategy** and are controlled via **self-management policies**.

---

### 7.4 Example Scenarios

| **Trigger**                     | **Action**                                | **Result**                         |
|----------------------------------|--------------------------------------------|------------------------------------|
| New data patterns emerge         | Learning agent replaces fixed logic        | Improved anomaly detection         |
| Service faces new user demands   | Recursive planner generates new agent      | New service logic instantiated      |
| Peer system loses connectivity   | Peering agent downgraded to procedural     | Maintains status, halts negotiation |
| Model misalignment detected      | Recursive critic retires misbehaving agent | System integrity preserved         |

---

### 7.5 Managing Evolution Safely

Upgrade paths are managed through:
- **Agent metadata** (versioning, capability declarations)
- **Policies** (who can replace whom, under what conditions)
- **Runtime introspection** (goal alignment and compliance)

Together, these mechanisms allow autogenic systems to grow in complexity when needed, but remain stable, explainable, and resilient under pressure.

## 8. Conclusion

Autogenic systems represent a shift in how intelligent architectures are conceived: they are no longer built from monolithic control structures, but from intelligent, cooperating agents that reason, adapt, and evolve. This research note has presented a structured typology of agent types—procedural, assisted, learning, and recursive—each with specific autonomy levels, task breadth, and system roles.

By matching each subsystem to the **lowest-capability agent** required to fulfill its function, system designers can maintain clarity, reduce unnecessary complexity, and enable graceful degradation. At the same time, recursive agents introduce the capacity for **self-reflection, structural evolution, and long-term adaptation**, ensuring that the system can evolve with its environment.

Incorporating assisted agents into the broader architecture highlights how autogenic systems can operate in **mixed-autonomy environments**, providing external support without compromising internal autonomy.

Ultimately, this agent classification provides a **designable foundation** for building self-managing, evolvable systems that are modular, resilient, and aligned to well-scoped capabilities. As future work extends these ideas into more expressive planning, hybrid agent structures, and self-verifying agents, this taxonomy will continue to serve as a reliable and extensible baseline.

## Appendix A: Agent Type Cards (Printable Summary)

---

### Procedural Agent

- **Autonomy**: Low  
- **AI Breadth**: Very Narrow  
- **Scope**: Internal + External  
- **Learning**: ✘  
- **Reflection**: ✘  
- **Behavior**: Executes fixed, pre-defined logic  
- **Example Task**: Emit metrics, restart a failed process  
- **Subsystems**: Execution, Monitoring, Control  
- **Role**: Backbone of stable service behavior and basic control  

---

### Assisted Agent

- **Autonomy**: Low (externally guided)  
- **AI Breadth**: Narrow to Moderate  
- **Scope**: External only (peer systems)  
- **Learning**: ✘  
- **Reflection**: ✘  
- **Behavior**: Generates behavior on prompt; does not learn or adapt  
- **Example Task**: Generate plan based on prompt, simulate output  
- **Subsystems**: Appears outside system boundary  
- **Role**: Present in legacy or partially automated systems; assisted via peering  

---

### Learning Agent

- **Autonomy**: Moderate  
- **AI Breadth**: Moderate (task-specific)  
- **Scope**: Internal + External  
- **Learning**: ✔  
- **Reflection**: ✘  
- **Behavior**: Adapts via feedback; optimizes policies or patterns  
- **Example Task**: Detect anomaly, refine control logic, classify failures  
- **Subsystems**: Analysis, Peering (support), Control (adaptive)  
- **Role**: Enables autonomy in operation and optimization  

---

### Recursive Agent

- **Autonomy**: High  
- **AI Breadth**: Broad  
- **Scope**: Internal + External  
- **Learning**: ✔  
- **Reflection**: ✔  
- **Behavior**: Introspective, generative, self-evolving  
- **Example Task**: Generate new goal, create agent, evaluate fallback mode  
- **Subsystems**: Planning, Self-Management, Peering  
- **Role**: Enables self-reflection, structural change, cross-system intelligence  

## Appendix B: Glossary of Terms

---

**Agent**  
A bounded, modular unit of behavior responsible for interpreting intent, executing logic, and interacting with other agents or systems. Agents vary in autonomy, scope, and cognitive capability.

---

**Procedural Agent**  
An agent with fixed, pre-defined behavior. It cannot learn, adapt, or reflect. Used for low-level execution, monitoring, and control.

---

**Assisted Agent**  
An externally guided agent capable of generating behavior (e.g., via templates or LLMs) but unable to learn, adapt, or reflect. Typically found in peer or legacy systems.

---

**Learning Agent**  
An adaptive agent that modifies its behavior through feedback. It can optimize control policies or detect patterns but cannot invent goals or modify system structure.

---

**Recursive Agent**  
A reflective agent capable of goal invention, structural modification, and agent generation. It enables self-management, planning, and introspective control.

---

**Scope (Internal/External)**  
Defines the agent’s operational domain. Internal agents manage the autogenic system itself; external agents control or support service delivery or interaction with peers.

---

**AI Breadth**  
The range of task types an agent can generalize across. Narrow agents perform specific, limited functions. Broad agents can invent tasks, reflect on decisions, and coordinate across roles.

---

**Fallback Mode**  
A degraded operational state where higher-capability agents (e.g., recursive) are disabled or suspended, and lower-capability agents (e.g., procedural) maintain core functionality.

---

**Subsystem**  
A functional cluster of agents performing a defined system role. Includes execution, monitoring, analysis, planning, control, self-management, and peering.

---

**Upgrade Path**  
The system-defined progression of an agent from one type to another (e.g., procedural → learning → recursive), managed by recursive oversight.

---

**Mixed-Autonomy Environment**  
A setting in which autogenic systems interact with peer systems of varying autonomy levels, including those with assisted or procedural agents.

## Appendix C: AI Breadth and Task Scope Matrix

This appendix clarifies how agent types differ based on their ability to perform diverse tasks, generalize behavior, and operate across domains. AI Breadth is defined here in terms of **task variety**, not model complexity or algorithmic depth.

---

### C.1 AI Breadth by Agent Type

| **Agent Type**   | **Task Breadth**       | **Behavioral Characteristics**                                          |
|------------------|------------------------|-------------------------------------------------------------------------|
| Procedural        | Very Narrow            | Executes only predefined tasks without variation                       |
| Assisted          | Narrow to Moderate     | Generates context-sensitive output but lacks memory or goal ownership  |
| Learning          | Moderate (domain-bounded) | Adapts behavior based on feedback within its task scope               |
| Recursive         | Broad                  | Invents new tasks, manages other agents, evolves goals and structures  |

---

### C.2 Scope of Task Execution

| **Agent Type**   | **Internal Tasks**                           | **External Tasks**                             |
|------------------|----------------------------------------------|------------------------------------------------|
| Procedural        | Emit logs, trigger control actions           | Deliver service, expose telemetry              |
| Assisted          | N/A (not used internally)                   | Complete prompts, simulate actions             |
| Learning          | Analyze anomalies, optimize subsystems       | Tune service behavior, detect policy drift     |
| Recursive         | Manage agent lifecycles, revise topology     | Coordinate peers, invent service-level plans   |

---

### C.3 Summary

- **Breadth** reflects **task diversity**, not just sophistication.
- Agents may be highly capable in narrow domains (e.g., RL for resource allocation) without qualifying as broad-breadth agents.
- Only **recursive agents** operate with full breadth across internal and external scopes, enabling structural and strategic innovation.

This matrix supports clearer role assignment in both system design and upgrade planning.

## Appendix D: Comparison to TMF/ETSI Agent Models

Autogenic systems do not conflict with existing TM Forum and ETSI architectural models but extend them by formalizing agent roles, scopes, and upgrade paths. This appendix compares the agent framework in this note with two major reference points:

- TM Forum’s Autonomous Networks Framework (IG1251, IG1252)
- ETSI ENI 051 (AI-based network function management)

---

### D.1 TM Forum IG1251/1252 – Controllers as Agents

| **TMF Role**               | **Equivalent Agent Type**        | **Notes**                                                  |
|----------------------------|----------------------------------|------------------------------------------------------------|
| Domain Controller          | Learning or Procedural Agent     | Executes and adapts within bounded functional areas        |
| Intent Handler             | Recursive Agent                  | Decomposes and interprets abstract goals                   |
| Service Controller         | Learning Agent                   | Controls service lifecycle, may contain learning logic     |
| Meta-Controller            | Recursive Agent                  | Manages orchestration across controllers (multi-domain)    |

- TMF does not explicitly distinguish scope or AI breadth but implies autonomy layering.
- Autogenic agent roles clarify which subsystems use which kind of controller behavior.

---

### D.2 ETSI ENI 051 – Functional Architecture and Reasoning Agents

| **ENI Component**          | **Equivalent Agent Type**        | **Notes**                                                  |
|----------------------------|----------------------------------|------------------------------------------------------------|
| Situation Awareness        | Procedural or Learning Agent     | Collects context data for use in policies and reasoning    |
| Analysis                   | Learning Agent                   | Detects anomalies, recommends policies                     |
| Decision Engine            | Recursive Agent                  | Plans adaptations based on policy evaluation               |
| Knowledge Management       | Recursive Agent (critic role)    | Updates models and goal structures                         |

- ENI provides a strong alignment with agent roles in analysis and reasoning.
- Recursive agency helps formalize ENI’s open-ended reasoning loop as an agent pattern.

---

### D.3 Distinguishing Features of Autogenic Agent Model

| **Feature**                         | **TMF/ETSI**     | **Autogenic Agent Framework**                        |
|-------------------------------------|------------------|------------------------------------------------------|
| Explicit Agent Typing               | Implicit         | Fully defined (Procedural → Recursive)               |
| Scope Modeling (Internal/External)  | Implicit         | Explicitly supported                                 |
| Upgrade/Downgrade Paths             | Not defined      | Explicit paths and fallback mechanisms               |
| Self-Evolution Support              | Partial (L5 only)| Fully formalized via recursive agents                |

This appendix shows that autogenic agent design is not only compatible with TMF/ETSI frameworks but **extends and sharpens** their abstraction layers—providing a basis for higher degrees of self-management and autonomy in complex, agent-based systems.

## Appendix E: MLA Reference List

1. TM Forum. *IG1251 Autonomous Networks Reference Architecture v1.0.1*. 2023.

2. TM Forum. *IG1252 Autonomous Networks Levels and Evaluation Methodology v1.1.0*. 2023.

3. TM Forum. *IG1230 Autonomous Networks Technical Architecture v1.1.1*. 2023.

4. ETSI. *GR ENI 051 V4.1.1: Experiential Networked Intelligence (ENI); System Architecture*. 2023.

5. Hrabia, Christopher, et al. “A Metrics Framework for Quantifying Autonomy in Complex Systems.” *IEEE Access*, vol. 9, 2021, pp. 139565–139582.

6. Lemos, Rogério, et al. “An Overview of Self-Engineering for Autonomic Systems.” *Software Engineering for Self-Adaptive Systems II*, Springer, 2013, pp. 3–32.

7. Djukic, Petar. *Autogenic Systems v2*. Internal Working Note, June 2025.

8. ACM Collective of Authors. *Self-X Characterization of Autonomous Systems*. *ACM Journal*, 2023.

9. Kalai, Adam Tauman, et al. "Self-taught Optimizer (STOP): Recursively Self-Improving Code Generation." *First Conference on Language Modeling*, 2024.

10. Ding, Li, et al. “Quality Diversity through Human Feedback: Toward Open-Ended Diversity-Driven Optimization.” *Proceedings of the Genetic and Evolutionary Computation Conference*, 2021.

