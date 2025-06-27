# Mapping Self-X Capabilities to Cognitive Focus
*A Practical Framework for Evaluating Autonomous Network Systems*  

**Author:** Petar Djukic, Ph.D.  
**Date:** June 2025  

## Table of Contents

1. [Introduction: Why Cognitive Focus Matters](#1-introduction-why-cognitive-focus-matters)  
2. [Cognitive Focus as a Functional Framework](#2-cognitive-focus-as-a-functional-framework)  
   - 2.1 [Execution](#21-execution)  
   - 2.2 [Awareness](#22-awareness)  
   - 2.3 [Analysis](#23-analysis)  
   - 2.4 [Decision](#24-decision)  
   - 2.5 [Intent](#25-intent)  
   - 2.6 [Experience](#26-experience)  
   - 2.7 [Evolution](#27-evolution)  
   - 2.8 [Invention](#28-invention)  
   - 2.9 [Reflection](#29-reflection)  
3. [From Function to Capability: The Mapping](#3-from-function-to-capability-the-mapping)  
4. [Mapping to Autonomy Levels](#4-mapping-to-autonomy-levels)  
5. [Why This Framework Holds Up (Even Under Scrutiny)](#5-why-this-framework-holds-up-even-under-scrutiny)  
6. [Conclusion](#6-conclusion)  

### Appendices
- [Appendix A: Capability-to-Cognition Alignment](#appendix-a-capability-to-cognition-alignment)  
- [Appendix B: Cognitive Focus Evolution Across Autonomy Levels](#appendix-b-cognitive-focus-evolution-across-autonomy-levels)  
- [Appendix C: Self-X Capabilities by Autonomy Level](#appendix-c-self-x-capabilities-by-autonomy-level)  
- [Appendix D: Cognitive Focus Advancement by Autonomy Level](#appendix-d-cognitive-focus-advancement-by-autonomy-level)  

---
## Executive Summary

This paper introduces a rigorous framework for mapping **Self-X capabilities** to the **cognitive responsibilities** that underpin true network autonomy.

We begin with a straightforward claim: **if a network claims to be autonomous, it must demonstrate specific cognitive functions — and those functions must be grounded in observable, testable Self-X behaviors.** No buzzwords. No magic. Just capabilities tied to execution.

We define nine core **Cognitive Focus** areas — from Execution and Awareness to Invention and Reflection — and show how each emerges at specific TM Forum **Autonomous Network Levels (L0–L5+)**. Each level introduces new responsibilities, new behaviors, and new demands on system architecture.

For each function, we identify:
- The **Self-X capabilities** required to enable it.
- The **autonomy level** where it must appear.
- The **evidence artifacts** that prove it’s working in the field.

What emerges is a clean diagnostic: if your system can’t reflect on its own decisions, it’s not L5+. If it can’t revise its own control logic, it’s not L5. If it can’t decompose intent into goals, it’s not L4. 

Capabilities aren’t interchangeable — **you can’t optimize what you can’t observe**, and **you can’t reason about goals you can’t invent**.

This framework is designed for architects, engineers, and system buyers who need to separate real autonomy from marketing. It aligns engineering design with measurable outcomes. And it scales — from telemetry agents to cognitive agents — as the system moves from executing what it’s told to inventing what needs to be done.

Bottom line: **if your network can think, it should show its work.**

## 1. Introduction: Why Cognitive Focus Matters

When we talk about autonomous networks, the air fills quickly with slogans — “self-healing,” “intent-driven,” “AI-powered.” You’ve heard them. I’ve heard them. They’re useful for marketing decks and press releases, but they don’t tell me what the system actually does.

So here’s a grounded claim:  
**If a system is going to call itself autonomous, it must take responsibility for specific cognitive functions — and it needs identifiable Self-X capabilities to perform them.**

We call these functions the network’s **cognitive focus**. They are not buzzwords. They are the architectural burdens the system lifts from human operators — one level at a time.

The cognitive focus model answers practical questions:
- What kind of work does the system do without human involvement?
- Which Self-X capabilities make that work possible?
- At what point can we say the system has taken responsibility for a cognitive function?

We aren’t just checking boxes. We’re tracing behavior. That’s how you distinguish **real autonomy** from **automated routines wearing a new badge**.

By mapping cognitive responsibilities to autonomy levels and their enabling capabilities, we can:
- Validate architecture maturity
- Diagnose what’s missing in an autonomy roadmap
- Design for explainability, adaptability, and trust

This is not theory. It’s a practical diagnostic model for autonomous systems — from L1 scripts to L5+ generative agents.

## 2. Cognitive Focus as a Functional Framework

Every autonomous system — from a cloud-managed switch to a multi-agent fabric — must do certain kinds of work. Not just operate. Not just automate. **Cognize**. That means sensing, interpreting, deciding, and adapting — without human supervision.

We refer to these recurring control responsibilities as the system’s **cognitive focus**.

This is the heart of the autonomy stack. Cognitive focus isn’t just a list of tasks. It’s a way to frame what the system is responsible for, and how much of that responsibility it has assumed. If it can’t handle the focus, it shouldn’t claim the capability.

Below are the nine functional areas that define the cognitive responsibilities of a self-managing system:

| **Cognitive Focus** | **Definition** |
|---------------------|----------------|
| **Execution**       | Applying changes to the system or network state |
| **Awareness**       | Observing internal state and environmental context |
| **Analysis**        | Interpreting data to identify conditions, trends, or faults |
| **Decision**        | Selecting actions based on current state, goals, and constraints |
| **Intent**          | Understanding structured goals and decomposing them into plans |
| **Experience**      | Measuring performance against intent and recognizing failure |
| **Evolution**       | Changing system architecture or behavior over time |
| **Invention**       | Formulating new goals, models, or strategies |
| **Reflection**      | Monitoring and adapting its own reasoning and decision-making |

Each of these areas appears at a different point along the TM Forum autonomy scale. But they don’t appear all at once. And they don’t all mean the same thing at every level. That’s why we trace their **gradual emergence** across L0–L5+.

Let’s define each in turn.

### 2.1 Execution

**Execution** is where autonomy meets reality. It’s the system’s ability to **apply change** — to act on its environment, on itself, or both. This includes provisioning, reconfiguration, service chaining, routing updates, and fault remediation.

In low-autonomy systems, execution is manual. Operators run playbooks. At higher levels, execution becomes event-driven. Eventually, it becomes **goal-driven** — conditional, adaptive, and revisable.

Execution is the most visible part of a network’s behavior. But that doesn’t make it simple. If a system can’t explain what it did, **can’t roll it back**, or **can’t decide when not to act**, then it isn’t safe. And safety is part of autonomy too.

To evaluate Execution in a system:
- Ask whether it can take **actions independently**
- Ask whether those actions are **tied to intent**
- Ask whether it can **revise or generate** execution paths when the old ones break

Execution isn’t about doing things. It’s about doing the right things — on purpose, for a reason, and with a fallback.

**Enabling Self-X Capabilities:**  
- Self-configuration  
- Self-healing  
- Self-protection  
- Self-optimization (L4+)  
- Self-programming (L5+)

### 2.2 Awareness

**Awareness** is how the system perceives the world — both its own internal state and its external environment. It’s the foundation of all autonomy. If you don’t know what’s happening, you can’t act intelligently — or at all.

Early stages of awareness begin with basic telemetry: collecting CPU load, link status, node health. But raw data isn’t awareness. **Awareness means the system understands its condition** — it knows when something’s wrong, how components are behaving, and what situation it’s in.

As autonomy grows, awareness shifts from **monitoring everything** to **monitoring what matters**. Higher levels of awareness include:
- Contextual modeling of services and resources
- Recognizing degradation trends
- Identifying system roles and dependencies

A system that’s “aware” can:
- Detect when it's in an unsafe or unexpected state
- Selectively observe data relevant to goals
- Update its perception as conditions evolve

Without awareness, autonomy becomes dangerous — because the system doesn’t know what it doesn’t know.

**Enabling Self-X Capabilities:**  
- Self-monitoring  
- Self-awareness  
- Self-description (to external agents)  
- Self-reflective (L5+)  

### 2.3 Analysis

**Analysis** is the system’s ability to interpret data. Not just record it — understand it. It takes the raw material of awareness and turns it into insight.

At lower levels, analysis starts with **rule-based detection** — thresholds, alert conditions, fault signatures. These are brittle but fast. They match known patterns and trigger fixed responses.

As autonomy increases, analysis becomes **correlative and adaptive**. The system begins to:
- Combine signals to detect emergent behavior
- Identify root causes of faults
- Project future states or risks based on trends
- Recognize anomalous patterns even when no prior rule exists

And at the high end, the system can **invent new analytical models**. That’s when analysis becomes generative — when the system defines its own methods to interpret new kinds of problems.

A system can’t reason if it can’t analyze. Without analysis, all it has is observation — and that’s not enough to survive in a changing world.

**Enabling Self-X Capabilities:**  
- Self-assessment  
- Self-analysis (correlates signals, rule-based detection)  
- Self-learning  
- Self-reflective (at L5+, for reasoning about inference validity)

### 2.4 Decision

**Decision** is where autonomy takes shape. It’s the system’s ability to select actions — not just based on rules, but based on goals, trade-offs, risks, and learned outcomes.

At the lowest autonomous levels, decisions are implicit. A rule fires, an action happens. There’s no deliberation.

At L3, we introduce **choice**: multiple options, selected based on policy or simple utility functions. This is the first sign that the system isn’t just reacting — it’s **selecting**.

At L4 and above, decision-making incorporates:
- Intent goals and priorities
- Policy constraints and preferences
- Feedback from past actions
- Conflict resolution between competing outcomes

At L5+, the system decides **how to decide** — switching reasoning modes, invoking different strategies, or escalating uncertainty.

Good decision logic separates adaptive systems from brittle ones. It’s the brainstem of autonomy.

**Enabling Self-X Capabilities:**  
- Self-directedness  
- Self-optimization  
- Self-governing  
- Self-assessment (for tradeoff evaluation)  
- Self-reflective (at L5+, for meta-decision strategy selection)

### 2.5 Intent

**Intent** is what autonomy is for. It’s not just what the system *can do* — it’s what the system is *supposed to do*. Intent represents the goals, policies, and desired outcomes the system must fulfill — even when no operator is watching.

At L4, intent enters the picture. The system receives structured, declarative goals — typically in the form of templates, service requests, or user-defined objectives. But autonomy doesn’t just mean accepting intent. It means **reasoning about it**.

An autonomous system must:
- Decompose complex goals into executable sub-goals
- Validate that intent is achievable
- Detect conflicts or incompatibilities
- Prioritize intent when resources are constrained

At L5+, the system must go further. It begins to generate **new goals** in response to failures, changing environments, or long-term optimization. This is where intent becomes **internal** — not just parsed, but invented.

A system that cannot process intent cannot claim to be autonomous. It can execute. It can optimize. But it cannot pursue purpose.

**Enabling Self-X Capabilities:**  
- Self-generation (to form actionable representations of goals)  
- Self-description (to expose system capabilities)  
- Self-orienting (at L5+, to invent goals)  
- Self-directedness (to align behavior with goals)  

### 2.6 Experience

**Experience** is what teaches the system what works. It’s not enough to execute a plan — the system must know whether the plan succeeded, failed, or caused collateral damage. Without experience, autonomy is just automation on repeat.

At L4, the system starts measuring success: tracking KPIs, monitoring SLA compliance, and linking outcomes to specific actions. This is the beginning of **outcome awareness**.

At L5, experience feeds back into behavior. The system starts **learning from outcomes** — adjusting models, preferences, and plans based on what actually happened. This enables improvement over time.

At L5+, experience becomes creative. The system can define new success criteria — not just metrics it was given, but **value functions it invents**. This lets it adapt to evolving missions, unknown conditions, or emergent constraints.

Experience turns reaction into adaptation — and adaptation into improvement.

**Enabling Self-X Capabilities:**  
- Self-assessment (to judge effectiveness of behavior)  
- Self-improving (to revise future plans or parameters)  
- Self-reflective (to identify learning opportunities or failure patterns)  

### 2.7 Evolution

**Evolution** is what separates adaptive systems from truly autonomous ones. It’s not just about tuning parameters — it’s about changing structure. Changing how the system thinks, plans, learns, and even how it changes.

At L5, evolution shows up as **structural adaptation**:
- Reconfiguring workflows
- Rewriting control logic
- Changing service topologies or decision paths

The system doesn’t just act — it **reorganizes itself** in response to long-term pressures. And it does this *without waiting for human redesign*.

At L5+, evolution becomes internal. The system starts modifying **its own reasoning architecture** — how it decides, how it learns, how it interprets intent. This is where autonomy becomes **autogenic**: a system that evolves its own intelligence.

Evolution is not optimization. It’s not improvement. It’s transformation.

**Enabling Self-X Capabilities:**  
- Self-evolving  
- Self-organizing  
- Self-assembly  
- Self-programming (L5+, for restructuring internal logic)  

### 2.8 Invention

**Invention** is the rarest and most powerful expression of autonomy. It’s the ability to generate something new — not by copying a pattern, not by refining a rule, but by creating new goals, models, or strategies that were never programmed in.

Invention is unnecessary at low autonomy levels — there, everything the system does is anticipated. But in unpredictable environments, in missions that evolve, **invention becomes essential**.

At L5+, invention appears in several forms:
- New goals that weren’t part of original design
- New analytical models for previously unrecognized situations
- New behaviors or control strategies for achieving internal purpose

Invention requires curiosity, flexibility, and creativity. It’s what lets the system go off-script — not as a failure, but as a strength.

**Enabling Self-X Capabilities:**  
- Self-orienting (to formulate new goals)  
- Self-generation (to express those goals)  
- Self-programming (to build new behaviors)  
- Self-inventive (as an emergent, composite capacity)  

### 2.9 Reflection

**Reflection** is autonomy looking in the mirror. It’s the ability of the system to observe, evaluate, and revise its own reasoning — not just its actions, but the strategies behind them.

Without reflection, a system can learn — but it can’t know *when* it should learn. It can optimize — but it can’t tell *whether* its optimization strategy still fits. Reflection is what gives the system a kind of self-doubt — the capacity to question itself.

At L5+, reflection takes form as:
- Monitoring the validity of plans and models
- Recognizing when reasoning no longer fits reality
- Switching strategies or escalating decisions
- Even choosing how to decide — selecting a planning mode or reasoning pathway

This is the **governor of cognition**. The system becomes not just aware of the world — but aware of how it thinks.

**Enabling Self-X Capabilities:**  
- Self-reflective  
- Self-assessment  
- Self-awareness  
- Self-destruction (as a protective, last-resort form of reasoning-based failure containment)  

## 3. From Function to Capability: The Mapping

Each cognitive focus is backed by specific Self-X capabilities. These are not marketing labels. They’re operational requirements. If a system lacks the capabilities, it can’t perform the function — not fully, not reliably.

This mapping helps engineers test claims. If a system says it’s “self-optimizing,” but can’t observe or assess itself, it’s not. If it claims to be “intent-driven,” but can’t decompose goals or adjust behaviors in light of outcomes, it’s just automating.

The following table shows the relationship between **Cognitive Focus** and **Enabling Self-X Capabilities**. This mapping is **functional** — based on what must be true for a capability to support the behavior in question.

| **Cognitive Focus** | **Enabling Self-X Capabilities** |
|---------------------|----------------------------------|
| Execution           | Self-configuration, Self-healing, Self-protection, Self-synchronization, Self-replication, Self-destruction |
| Awareness           | Self-monitoring, Self-awareness |
| Analysis            | Self-assessment, Self-analysis, Self-learning |
| Decision            | Self-directedness, Self-optimization, Self-governing, Self-assessment, Self-reflective |
| Intent              | Self-generation, Self-description, Self-orienting, Self-directedness |
| Experience          | Self-assessment, Self-improving, Self-reflective |
| Evolution           | Self-evolving, Self-organizing, Self-assembly, Self-programming, Self-replication |
| Invention           | Self-orienting, Self-generation, Self-programming, Self-inventive |
| Reflection          | Self-reflective, Self-awareness, Self-assessment, Self-destruction |

These are the functional muscles behind autonomous behavior. Without them, a system can’t think for itself — it just repeats patterns.

## 4. Mapping to Autonomy Levels

Not every system needs to invent goals or reprogram its behavior. But if it claims to be “Level 5 autonomous,” it better do more than run scripts. The TM Forum defines six levels of network autonomy — from L0 (Manual) to L5+ (Autogenic).

Each level represents a shift in cognitive responsibility — what the system must be able to handle on its own.

Here’s how cognitive focus maps across the autonomy levels:

| **Autonomy Level** | **Primary Cognitive Focus Functions** |
|--------------------|----------------------------------------|
| L0 – Manual         | None — system executes operator intent manually |
| L1 – Assisted       | Execution, Awareness (scripted actions, basic monitoring) |
| L2 – Partial Autonomy | Execution, Awareness, Analysis (automated reactions, basic fault detection) |
| L3 – Conditional Autonomy | Adds Decision (policy-based choices, optimization logic) |
| L4 – High Autonomy  | Adds Intent, Experience (goal-driven planning, outcome tracking) |
| L5 – Full Autonomy  | Adds Evolution, deepens Decision and Experience (adaptive structures, self-improvement) |
| L5+ – Autogenic     | Adds Invention, Reflection (goal synthesis, meta-reasoning, architectural transformation) |

This isn’t just a checklist — it’s a capability pyramid. Each level builds on the last. And each new focus area adds a new kind of responsibility:
- **Perception** at L1
- **Reaction** at L2
- **Choice** at L3
- **Purpose** at L4
- **Adaptation** at L5
- **Agency** at L5+

If a system doesn’t demonstrate the cognitive functions expected at its level, it doesn’t qualify — no matter what the brochure says.

## 5. Why This Framework Holds Up (Even Under Scrutiny)

This framework isn’t built on theory. It’s built on trenches. Years of engineering work in complex, distributed systems. Observability pipelines that couldn’t scale. Control loops that misfired. “AI-enabled” modules that just added noise.

What we learned was this: **if a system can’t perform a cognitive function, it can’t support autonomy**. Period.

Here’s how we know the mapping works:

- **Execution** without self-configuration? You’re still waiting for human clicks.
- **Intent** without goal decomposition? You’re just running scripts with fancier labels.
- **Reflection** without meta-reasoning? You’re stuck in loops when the world changes.

This isn’t about ideal systems — it’s about *testable behavior*. You can observe it. You can trace it. You can map it to the architecture.

It also gives engineers something they rarely get in autonomy conversations: **a functional contract**.

If a vendor says “Level 4,” you ask:
- What decisions does it make on its own?
- How does it interpret goals?
- What feedback does it use to adapt?

If they can’t point to the cognitive functions — and the self-* capabilities that support them — they’re selling automation in autonomy’s clothes.

This framework holds up because it was built to explain what works, what breaks, and what matters — when the humans step back.

## 6. Conclusion

Autonomy isn’t a slogan. It’s a shift in responsibility — from human to machine, from manual configuration to cognitive capability.

If you’re building or buying autonomous systems, don’t ask “Does it have AI?”  
Ask:
- **What cognitive functions are delegated to the system?**
- **Which Self-X capabilities enable those functions?**
- **What evidence supports their presence?**

Without those answers, you don’t have autonomy. You have automation with a fancy name.

This framework gives you a structured way to:
- Evaluate what’s really inside the system
- Design for capability progression
- Spot what’s missing — and what’s mislabeled

The goal isn’t to make everything L5+. It’s to be honest about what level you’re at, and what leap comes next.

Because if the system can’t act, decide, adapt, or reflect on its own — then someone else still has to.

And that someone is you.

## Glossary of Terms

### Autonomous Network (AN)
A network capable of managing itself with minimal human intervention by executing decisions, adapting to changing conditions, and learning from experience. The TM Forum defines six levels of autonomy from L0 (Manual) to L5+ (Autogenic).

### Cognitive Focus
A functional domain representing what type of reasoning or cognition a system must perform. Includes Execution, Awareness, Analysis, Decision, Intent, Experience, Evolution, Invention, and Reflection.

### Self-X Capabilities
A family of self-managing behaviors that enable autonomous systems to operate, adapt, and evolve. Each capability supports specific cognitive functions and autonomy levels.

---

### Cognitive Focus Terms

- **Execution**: Applying changes to network/system state.
- **Awareness**: Sensing and interpreting internal and external state.
- **Analysis**: Extracting insight or structure from data.
- **Decision**: Choosing an action or strategy based on reasoning.
- **Intent**: Interpreting and decomposing high-level goals.
- **Experience**: Evaluating outcomes to guide future behavior.
- **Evolution**: Changing architecture or control logic over time.
- **Invention**: Creating new goals, models, or strategies.
- **Reflection**: Regulating and evaluating one's own reasoning process.

---

### Self-X Capability Definitions

| **Capability**          | **Definition**                                                                 |
|-------------------------|----------------------------------------------------------------------------------|
| Self-configuration      | System configures and reconfigures automatically.                                |
| Self-healing            | Detects, diagnoses, and repairs faults.                                         |
| Self-optimization       | Improves behavior or performance based on goals.                                |
| Self-protection         | Defends against threats or risks automatically.                                 |
| Self-directedness       | Plans and initiates actions independently to achieve tasks.                     |
| Self-learning           | Learns from operational experience.                                             |
| Self-improving          | Enhances performance or structure over time through accumulated experience.     |
| Self-organizing         | Adjusts its own structure to meet global goals via local adaptation.            |
| Self-monitoring         | Observes state, metrics, and operational context.                               |
| Self-awareness          | Maintains structured understanding of internal state.                           |
| Self-synchronization    | Coordinates actions across components or agents for shared goals.               |
| Self-description        | Provides machine-readable representation of its own structure and capabilities. |
| Self-assembly           | Dynamically builds systems from modular parts.                                  |
| Self-assessment         | Judges its own performance or risk condition.                                   |
| Self-replication        | Creates duplicates of components or logic.                                      |
| Self-destruction        | Terminates harmful or malfunctioning processes.                                 |
| Self-generation         | Creates internal models or plans for novel goals.                               |
| Self-evolution          | Modifies its own cognitive architecture.                                        |
| Self-orienting          | Invents or selects new goals not externally defined.                            |
| Self-programming        | Writes new executable behavior to pursue goals.                                 |
| Self-reflection         | Evaluates its own reasoning and adjusts strategy accordingly.                   |

---

### Additional Concepts

- **Autogenic System**: A system capable of self-programming, self-evolution, and self-orienting; required for L5+ autonomy.
- **Meta-cognition**: The ability of a system to monitor, regulate, and modify its own reasoning processes.
- **Capability Evidence**: Logs, traces, models, or changes that demonstrate Self-X functionality during runtime.

## References

1. TM Forum. *IG1252: Autonomous Networks Levels Evaluation Methodology*, v1.1.0, 2023.  
   Describes the six levels of network autonomy and the evaluation methodology used to determine a system’s level.

2. TM Forum. *IG1251: Autonomous Networks Reference Architecture*, v1.0.1, 2023.  
   Provides architecture principles, roles, and functions that support autonomous behavior in networks.

3. TM Forum. *IG1230 Series: Autonomous Networks Technical Architecture, Scenario Realizations, and Industry Standards Alignment*, 2023.  
   A series of documents defining how Self-X capabilities relate to real-world network automation.

4. ETSI ENI. *GR ENI 051: Context-Aware System Architecture for Autonomic Network Management and Control*, v4.1.1, 2023.  
   Describes cognitive architecture for intent-based and self-adaptive networks using AI agents.

5. Hrabia, C., & Reich, C. "A Metrics Framework for Quantifying Autonomy in Complex Systems." *2022 IEEE International Conference on Autonomic Computing and Self-Organizing Systems*.  
   Provides metrics for assessing different autonomy levels and system behaviors.

6. Horn, P., "Autonomic Computing: IBM’s Perspective on the State of Information Technology." IBM Research White Paper, 2001.  
   Introduces the original Self-X taxonomy in computing systems.

7. Sterritt, R., "Autonomic Computing." *Innovations in Systems and Software Engineering*, 2005.  
   Discusses the principles behind self-managing systems and the emergence of autonomy.

8. Russell, S., & Norvig, P. *Artificial Intelligence: A Modern Approach*. 4th ed., Pearson, 2021.  
   Covers foundational concepts in agent reasoning, learning, and meta-cognition.

9. Djukic, P. (2025). *Mapping Self-X Capabilities to Cognitive Focus in Network Autonomy*.  
   This report introduces the alignment between Self-X traits and cognitive requirements in networks, proposing a framework for measurable autonomy.

10. OpenAI. *Autogenic Systems Research*, 2025.  
    Exploratory material on self-evolving and self-programming systems, drawing on emerging AI-native design patterns.


## Appendix A: Capability-to-Cognition Alignment

This appendix provides a functional justification for each Self-X capability by mapping it to the cognitive focus it enables. These mappings are grounded in practical behavior — not theory. If a system cannot demonstrate the capability, it cannot fulfill the corresponding cognitive role.

Each entry includes:
- The **cognitive focus** the capability supports
- A **brief explanation** of its contribution
- The **operational consequence** if it’s missing

---

### A.1 Self-configuration
- **Cognitive Focus**: Execution  
- **Contribution**: Allows the system to change its own configuration in response to external triggers or internal conditions.  
- **Consequence if absent**: System requires human intervention to adapt, making closed loops impossible.

---

### A.2 Self-healing
- **Cognitive Focus**: Execution, Experience  
- **Contribution**: Detects and remediates faults without external commands.  
- **Consequence if absent**: System may detect issues but cannot recover without operator action.

---

### A.3 Self-optimization
- **Cognitive Focus**: Decision, Experience  
- **Contribution**: Adjusts parameters and behavior to improve performance toward specific objectives.  
- **Consequence if absent**: System remains static even when underperforming.

---

### A.4 Self-protection
- **Cognitive Focus**: Execution, Decision  
- **Contribution**: Detects and responds to security threats or harmful conditions.  
- **Consequence if absent**: System may execute unsafe actions or expose critical components.

---

### A.5 Self-directedness
- **Cognitive Focus**: Decision, Intent  
- **Contribution**: Allows the system to pursue high-level goals without constant instruction.  
- **Consequence if absent**: Autonomy collapses into predefined workflows; system cannot adapt to new tasks.

---

### A.6 Self-learning
- **Cognitive Focus**: Analysis, Decision  
- **Contribution**: Refines behavior or models based on observed outcomes.  
- **Consequence if absent**: System cannot improve or adjust over time.

---

### A.7 Self-improving
- **Cognitive Focus**: Experience, Evolution  
- **Contribution**: Iteratively improves internal mechanisms — from logic to control strategies.  
- **Consequence if absent**: The system plateaus and cannot evolve its own performance.

---

### A.8 Self-organizing
- **Cognitive Focus**: Evolution, Execution  
- **Contribution**: Rearranges internal roles, topologies, or coordination based on system goals.  
- **Consequence if absent**: Structural rigidity limits scalability and resilience.

---

### A.9 Self-monitoring
- **Cognitive Focus**: Awareness  
- **Contribution**: Observes system and environmental state.  
- **Consequence if absent**: The system becomes blind to changes, invalidating any claims of autonomy.

---

### A.10 Self-awareness
- **Cognitive Focus**: Awareness, Reflection  
- **Contribution**: Builds internal representations of current state, context, or role.  
- **Consequence if absent**: System can measure, but not understand, its own condition.

---

### A.11 Self-synchronization
- **Cognitive Focus**: Execution, Intent  
- **Contribution**: Coordinates timing and state among distributed components.  
- **Consequence if absent**: Actions may conflict or duplicate across the system.

---

### A.12 Self-description
- **Cognitive Focus**: Intent, Awareness  
- **Contribution**: Exposes internal structure, APIs, and capabilities in machine-readable form.  
- **Consequence if absent**: External reasoning and orchestration are blocked.

---

### A.13 Self-assembly
- **Cognitive Focus**: Evolution, Execution  
- **Contribution**: Enables components to dynamically form systems or services.  
- **Consequence if absent**: Reuse and composability become brittle and slow.

---

### A.14 Self-assessment
- **Cognitive Focus**: Analysis, Experience, Reflection  
- **Contribution**: Evaluates its own performance, reliability, and error conditions.  
- **Consequence if absent**: The system may function, but cannot tell if it's functioning well.

---

### A.15 Self-replication
- **Cognitive Focus**: Execution, Evolution  
- **Contribution**: Creates additional copies of itself or its subcomponents.  
- **Consequence if absent**: Cannot scale or recover through duplication.

---

### A.16 Self-destruction
- **Cognitive Focus**: Execution, Reflection  
- **Contribution**: Decommissions unsafe or degraded components autonomously.  
- **Consequence if absent**: Risk containment and fault isolation are delayed or externalized.

---

### A.17 Self-generation
- **Cognitive Focus**: Intent, Invention  
- **Contribution**: Constructs internal representations, strategies, or goals.  
- **Consequence if absent**: System cannot operate on abstract objectives or adapt them.

---

### A.18 Self-orienting
- **Cognitive Focus**: Invention, Intent  
- **Contribution**: Selects or invents new goals in response to context or experience.  
- **Consequence if absent**: Goal space is fixed; cannot adapt to new missions or conditions.

---

### A.19 Self-programming
- **Cognitive Focus**: Invention, Execution  
- **Contribution**: Generates new executable behaviors from internal reasoning or feedback.  
- **Consequence if absent**: Autonomy halts when existing behaviors are no longer viable.

---

### A.20 Self-evolving
- **Cognitive Focus**: Evolution  
- **Contribution**: Revises internal architecture, learning paths, or control logic.  
- **Consequence if absent**: System adapts within constraints but cannot redefine those constraints.

---

### A.21 Self-reflective
- **Cognitive Focus**: Reflection, Experience  
- **Contribution**: Modulates reasoning strategies, escalates failures, or questions assumptions.  
- **Consequence if absent**: System continues faulty logic or decisions without meta-awareness.

## Appendix B: Capability Mapping Tables for Network Autonomy Evaluation

This appendix includes structured mappings between TM Forum Autonomous Network (AN) Levels, Cognitive Focus areas, and Self-X Capabilities. These tables support grounded evaluation of autonomy claims — helping engineers, architects, and assessors determine whether capabilities are present, partial, or missing.

---

### B.1 Cognitive Focus Activation by Network Autonomy Level

| **Cognitive Focus** | **L0** | **L1** | **L2** | **L3** | **L4** | **L5** | **L5+** |
|---------------------|--------|--------|--------|--------|--------|--------|--------|
| Execution           | None   | Partial| Full   | Full   | Full   | Full   | Full   |
| Awareness           | None   | Partial| Full   | Full   | Full   | Full   | Full   |
| Analysis            | None   | None   | Partial| Full   | Full   | Full   | Full   |
| Decision            | None   | None   | None   | Partial| Full   | Full   | Full   |
| Intent              | None   | None   | None   | None   | Partial| Full   | Full   |
| Experience          | None   | None   | None   | None   | Partial| Full   | Full   |
| Evolution           | None   | None   | None   | None   | None   | Partial| Full   |
| Invention           | None   | None   | None   | None   | None   | None   | Full   |
| Reflection          | None   | None   | None   | None   | None   | None   | Partial|

---

### B.2 Self-X Capabilities by Network Autonomy Level

| **Autonomy Level**  | **Required Self-X Capabilities**                                                                                   |
|---------------------|----------------------------------------------------------------------------------------------------------------------|
| L0 – Manual          | None. All actions are operator-driven.                                                                              |
| L1 – Assisted        | Self-monitoring, Self-awareness, Self-configuration                                                                 |
| L2 – Partial         | + Self-healing, Self-protection, Self-analysis                                                                      |
| L3 – Conditional     | + Self-directedness, Self-optimization, Self-assessment                                                             |
| L4 – High            | + Self-learning, Self-generation, Self-orienting                                                                    |
| L5 – Full            | + Self-evolving, Self-organizing, Self-governing, Self-improving                                                    |
| L5+ – Autogenic      | + Self-programming, Self-reflective, Self-replication, Self-inventive                                               |

_Note: Capabilities are cumulative. Each level includes all those required at lower levels._

---

### B.3 Observable Evidence of Self-X Capabilities by Autonomy Level

| **Level** | **Key Self-X Capabilities**                             | **Observable Evidence**                                                                 |
|-----------|----------------------------------------------------------|------------------------------------------------------------------------------------------|
| L1        | Self-monitoring, Self-awareness, Self-configuration       | Metric capture, health probes, policy-triggered scripts                                  |
| L2        | Self-healing, Self-protection, Self-analysis             | Auto-remediation logs, firewall actions, rule-based fault detection                      |
| L3        | Self-directedness, Self-optimization, Self-assessment   | Policy decisions, optimization reports, SLA deviation logs                               |
| L4        | Self-learning, Self-generation, Self-orienting           | Model checkpoints, goal decomposition traces, adaptive plan generation                   |
| L5        | Self-evolving, Self-organizing, Self-governing           | Dynamic topology changes, role reassignment, control reconfiguration                     |
| L5+       | Self-programming, Self-reflective, Self-replication      | Runtime behavior synthesis, internal strategy changes, spawned subsystems or services    |

## Appendix C: Why and How Cognitive Focus Evolves Across Autonomy Levels

This appendix explains the progression of each cognitive focus area from L0 to L5+, based on engineering requirements and functional thresholds. It focuses on three questions:

- **What** new capability emerges at this level?
- **Why** is it introduced?
- **How** was that reasoning derived from system behavior or design needs?

---

### C.1 Execution

| **Level** | **What Changes**                           | **Why It Changes**                                                                 | **How I Reasoned About It**                                                      |
|-----------|---------------------------------------------|-------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|
| L1        | Executes scripts or configurations          | Removes toil for routine actions                                                   | Most systems start with playbooks and event triggers                            |
| L2        | Executes based on fault or rule triggers    | Enables reaction without human                                                      | Rule engines represent first real autonomy surface                              |
| L3        | Chooses between execution strategies        | Introduces trade-off awareness                                                      | Engineers at this level tune strategy: canary, fast-fail, rollback              |
| L4        | Aligns execution to decomposed goals        | Required for intent realization                                                     | Goals constrain execution — choices aren’t just event-driven                    |
| L5        | Modifies its own execution logic            | Enables improvement via learning or experience                                      | Without this, misfiring logic can’t be corrected autonomously                   |
| L5+       | Synthesizes novel behaviors                 | Enables survival in novel or undefined conditions                                   | Predefined plans fail under novelty — system must compose action logic          |

---

### C.2 Awareness

| **Level** | **What Changes**                           | **Why It Changes**                                                                 | **How I Reasoned About It**                                                      |
|-----------|---------------------------------------------|-------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|
| L1        | Captures telemetry                          | Needed for alerting, scripting                                                     | Raw input collection precedes all autonomous action                             |
| L2        | Detects events based on patterns            | Enables rule-based action                                                          | Fault pattern detection enables L2 closed loops                                 |
| L3        | Correlates signals                          | Supports conditional execution                                                     | Understanding requires correlation, not just observation                        |
| L4        | Builds internal context models              | Needed to decompose and track intent                                               | Intent systems must “know themselves” and their structure                       |
| L5        | Refines what to observe                     | Reduces telemetry cost, improves relevance                                         | Awareness becomes dynamic, tied to current goals                                |
| L5+       | Chooses its own sensors or probes           | Supports novel goal pursuit                                                        | Reflective agents prioritize what to attend to — attention is a strategy        |

---

### C.3 Analysis

| **Level** | **What Changes**                           | **Why It Changes**                                                                 | **How I Reasoned About It**                                                      |
|-----------|---------------------------------------------|-------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|
| L2        | Rule-based detection                        | Detects known patterns                                                             | Entry-level inference; fault != anomaly                                         |
| L3        | Learns general patterns                     | Adapts to variations                                                               | ML models replace static rules                                                  |
| L4        | Refines models with experience              | Learns from outcomes                                                               | Closing the loop between analysis and performance                               |
| L5        | Performs cross-domain reasoning             | Needed for full-system diagnosis                                                   | Real failures cascade — reasoning must cross layers                             |
| L5+       | Invents new analysis strategies             | Detects novel patterns                                                             | Required to operate in unknown environments                                     |

---

### C.4 Decision

| **Level** | **What Changes**                           | **Why It Changes**                                                                 | **How I Reasoned About It**                                                      |
|-----------|---------------------------------------------|-------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|
| L3        | Selects actions from options                | Needed for basic autonomy                                                           | Adds choice logic to execution                                                  |
| L4        | Aligns decisions with goals                 | Required by intent                                                                  | Planning requires reasoning beyond rules                                        |
| L5        | Weighs trade-offs and history               | Balances competing constraints                                                      | Real-world autonomy requires compromise                                         |
| L5+       | Chooses how to choose                      | Adapts decision strategy                                                            | Adds meta-decision logic: pick planner vs. heuristic vs. brute-force            |

---

### C.5 Intent

| **Level** | **What Changes**                           | **Why It Changes**                                                                 | **How I Reasoned About It**                                                      |
|-----------|---------------------------------------------|-------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|
| L4        | Parses and decomposes goal structures       | Enables goal-driven operation                                                       | Intent systems must understand what they’re being asked                         |
| L5        | Resolves and prioritizes conflicting goals  | Supports safe, rational behavior                                                    | Goals often conflict: a system must choose what matters                         |
| L5+       | Generates its own goals                     | Enables autonomy in novel contexts                                                  | Inventing purpose is essential in non-scripted environments                     |

---

### C.6 Experience

| **Level** | **What Changes**                           | **Why It Changes**                                                                 | **How I Reasoned About It**                                                      |
|-----------|---------------------------------------------|-------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|
| L4        | Evaluates outcomes against goals            | Enables intent feedback                                                             | Measures success and failure — essential for trust                              |
| L5        | Learns from outcomes                        | Refines strategy and behavior                                                       | Memory improves performance                                                     |
| L5+       | Defines new success criteria                | Needed when goals change                                                            | If system generates new goals, it must invent its own KPIs                      |

---

### C.7 Evolution

| **Level** | **What Changes**                          | **Why It Changes**                                                          | **How I Reasoned About It**                                                  |
|-----------|--------------------------------------------|------------------------------------------------------------------------------|------------------------------------------------------------------------------|
| L5        | Modifies architecture or logic             | Enables long-term adaptability                                               | Static systems can't handle evolving goals, traffic, or fault patterns       |
| L5+       | Evolves its own cognitive architecture     | Enables intelligence transformation                                          | If goals and environments change, so must reasoning models and control paths |

---

### C.8 Invention

| **Level** | **What Changes**                          | **Why It Changes**                                                          | **How I Reasoned About It**                                                  |
|-----------|--------------------------------------------|------------------------------------------------------------------------------|------------------------------------------------------------------------------|
| L5+       | Invents new goals, behaviors, and models   | Required for autonomy in undefined or open-ended situations                  | You can't pre-code for everything — generative capability becomes survival   |

---

### C.9 Reflection

| **Level** | **What Changes**                          | **Why It Changes**                                                          | **How I Reasoned About It**                                                  |
|-----------|--------------------------------------------|------------------------------------------------------------------------------|------------------------------------------------------------------------------|
| L5+       | Monitors and regulates its reasoning       | Enables self-correction, safety, and mode switching                          | Without reflection, a generative system cannot tell when it's wrong          |

---

### Final Note

Each cognitive focus evolves due to system constraints: more complexity, less predictability, higher coordination needs.  
These transitions are not linear upgrades — they are leaps that depend on **enabling capabilities** and **intentional architecture**.

In short: autonomy isn’t built — it is **earned**, one layer of cognition at a time.

## Appendix D: Mapping Cognitive Focus Evolution to Self-X Capabilities

This appendix presents a unified view of how each **Cognitive Focus** progresses across TM Forum autonomy levels (L0–L5+), and which **Self-X capabilities** enable each leap. Each row in the table represents a capability threshold that transforms system behavior.

The reasoning behind each mapping comes from observed gaps in system operation:
- What couldn’t be done at the previous level?
- What new function had to emerge?
- Which capability made that function possible?

---

### D.1 Summary Table: Cognitive Focus Evolution by Autonomy Level

| **Level** | **Cognitive Focus** | **New Capability Introduced**              | **Enabling Self-X Capability**             |
|-----------|---------------------|---------------------------------------------|--------------------------------------------|
| **L1**    | Execution           | Executes predefined scripts                 | Self-configuration                          |
|           | Awareness           | Collects metrics                            | Self-monitoring                             |
| **L2**    | Execution           | Reactive autonomous action                  | Self-healing, Self-protection               |
|           | Awareness           | Detects known events                        | Self-awareness                              |
|           | Analysis            | Performs rule-based detection               | Self-analysis                               |
| **L3**    | Execution           | Chooses among execution plans               | Self-directedness                           |
|           | Awareness           | Correlates multiple signals                 | Self-analysis                               |
|           | Analysis            | Learns from data patterns                   | Self-learning                               |
|           | Decision            | Policy/plan selection                       | Self-directedness                           |
| **L4**    | Execution           | Goal-aligned execution                      | Self-generation, Self-optimization          |
|           | Awareness           | Models system context                       | Self-learning                               |
|           | Analysis            | Refines analysis with experience            | Self-assessment                             |
|           | Decision            | Intent-driven planning                      | Self-learning, Self-generation              |
|           | Intent              | Decomposes structured goals                 | Self-orienting                              |
|           | Experience          | Evaluates outcome vs. intent                | Self-assessment                             |
| **L5**    | Execution           | Modifies execution logic                    | Self-evolving, Self-organizing              |
|           | Awareness           | Refines observation strategy                | Self-evolving                               |
|           | Analysis            | Performs cross-domain inference             | Self-governing                              |
|           | Decision            | Multi-goal optimization                     | Self-optimization, Self-assessment          |
|           | Intent              | Resolves conflicting goals                  | Self-governing, Self-assessment             |
|           | Experience          | Learns from feedback                        | Self-learning, Self-optimization            |
|           | Evolution           | Architecture self-modification              | Self-evolving, Self-organizing              |
| **L5+**   | Execution           | Synthesizes new behaviors                   | Self-programming                            |
|           | Awareness           | Directs its own observation strategy        | Self-reflective, Self-orienting             |
|           | Analysis            | Invents new analytical models               | Self-evolution, Self-programming            |
|           | Decision            | Chooses how to decide                       | Self-reflective                             |
|           | Intent              | Generates new goals                         | Self-orienting, Self-generation             |
|           | Experience          | Defines new success criteria                | Self-reflective, Self-inventive             |
|           | Evolution           | Modifies cognitive architecture             | Self-programming, Self-reflective           |
|           | Invention           | Novel goal/model/plan synthesis             | Self-inventive, Self-orienting              |
|           | Reflection          | Reasoning process regulation                | Self-reflective                             |

---

This structure allows architects, evaluators, and system designers to reason backward:
If a system claims to perform a cognitive function, **what Self-X capabilities must be present?**
And if a capability is claimed, **what behavior should you observe?**

This is how we separate **real autonomy** from **decorated automation**.

## Appendix E: Observable Evidence for Self-X Capabilities

This appendix maps each Self-X capability to practical **evidence artifacts** — logs, outputs, traces, or changes that a system should emit or manifest during operation. These artifacts allow for verifiable validation of autonomy claims.

The goal here is simple: if you say the system has it, prove it.

---

### E.1 Evidence Mapping Table

| **Self-X Capability**  | **Expected Evidence**                                                                 |
|------------------------|----------------------------------------------------------------------------------------|
| Self-configuration     | Change logs, config snapshots, automatic resource mapping events                      |
| Self-healing           | Fault resolution timelines, recovery actions, remediation logs                        |
| Self-optimization      | Performance improvement records, resource reallocation decisions                      |
| Self-protection        | Intrusion detection triggers, isolation actions, blocked threat logs                  |
| Self-directedness      | Goal planning traces, path selection reports, scheduling autonomy                     |
| Self-learning          | Model updates, checkpoint files, behavior drift signatures                            |
| Self-improving         | KPI trends post-policy update, before/after performance delta                         |
| Self-organizing        | Dynamic topology graphs, role reassignment records                                    |
| Self-monitoring        | Live metric streams, probe activations, telemetry dashboards                          |
| Self-awareness         | Internal state model exports, component health summaries                              |
| Self-synchronization   | Coordinated event logs across agents, consensus records                               |
| Self-description       | Machine-readable APIs, self-published schema, component metadata                      |
| Self-assembly          | Dynamic service graph creation, inter-component handshake logs                        |
| Self-assessment        | Internal scoring systems, threshold violation records, confidence ratings             |
| Self-replication       | Clone initiation logs, replica instantiation, replication control loops               |
| Self-destruction       | Component deactivation events, risk-triggered service shutdowns                       |
| Self-generation        | Policy creation traces, model synthesis logs, intent transformer output               |
| Self-evolution         | Architectural diff logs, module replacement records, version lineage tracking         |
| Self-orienting         | Novel goal creation, scenario-driven task selection, autonomous prioritization        |
| Self-programming       | Workflow generation files, pipeline code builds, function synthesis traces            |
| Self-reflection        | Meta-model logs, reasoning strategy switch traces, self-correction triggers           |

---

### E.2 How to Use This Table

- **For system designers**: Ensure each claimed capability emits testable outputs.
- **For evaluators**: Ask for this evidence during demos or audits.
- **For architects**: Treat these as instrumentation targets — if you can’t see it, you can’t trust it.

The presence of Self-X capability must leave **behavioral residue** in the system’s observable outputs.  
If it doesn’t leave a trace — it didn’t happen.

---

