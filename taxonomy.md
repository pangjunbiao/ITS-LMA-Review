# ITS-LMA Evidence Framework and Taxonomy

This page provides a concise reference for the terminology and evidence codes used in the review and in this repository.

The framework separates system architecture, multimodality, demonstrated capability, validation setting, proposition evidence, and methodological concerns. These dimensions are assessed independently and are not combined into a single study score.

---

## Multimodality

### Model-Level Multimodality

The central foundation model directly processes at least two transportation-relevant modalities, such as text, images, video, maps, trajectories, traffic time series, LiDAR, or radar.

### System-Level Multimodality

A language-centred foundation model accesses and integrates heterogeneous transportation evidence through external resources or tools, such as databases, maps, retrieval systems, sensor-processing modules, simulators, forecasters, optimisers, planners, or controllers.

### Hybrid Multimodality

The system combines both model-level and system-level multimodality.

---

## Functional Capability: C0–C3

The capability scale records what the foundation-model-centred system demonstrably does within the transportation decision pathway.

| Level | Name | Definition |
|---|---|---|
| **C0** | Pre-agentic capability | Transportation-specific representation, perception, prediction, grounding, explanation, question answering, offline generation, or training support without an actionable decision-support or action cycle. |
| **C1** | Decision support | The system provides actionable retrieval, analysis, planning, tool use, or recommendations, while implementation remains with a human or external system. |
| **C2** | Bounded action | The system executes, invokes, or governs a bounded virtual or physical transportation action without demonstrated outcome-driven later re-decision. |
| **C3** | Outcome-responsive agency | Observed transportation state or outcomes enter the foundation-model-centred decision process and demonstrably change a later transportation decision. |

Capability does **not** by itself indicate predictive superiority, methodological quality, safety, or deployment readiness.

---

## Validation Setting: E0–E4

The validation scale records the environment in which the eligible system is evaluated.

| Level | Name | Definition |
|---|---|---|
| **E0** | Conceptual | No task-level empirical evaluation of the eligible system or attributable pipeline. |
| **E1** | Offline evidence | Evaluation using fixed datasets, historical records, replay, static benchmarks, or other noninteractive evidence. |
| **E2** | Interactive simulation | System outputs cause attributable state transitions in a responsive simulator, digital twin, emulator, or virtual transportation process. |
| **E3** | Controlled operational evidence | The integrated system is evaluated in a real transportation environment under restricted, supervised, shadow-mode, test-track, or limited-pilot conditions. |
| **E4** | Sustained deployment evidence | Routine or repeated real-world operation over a task-appropriate period within a declared operational envelope and authority boundary. |

Capability and validation are coded independently. A system may therefore demonstrate high functional capability while remaining evaluated only in simulation.

---

## Evidence Propositions: P1–P3

The review examines three transportation-specific evidence propositions.

### P1 — Behaviour and Facility Semantics

Evaluates whether transportation meaning—such as actors, interactions, rules, intent, behavioural state, facility function, or event context—contributes to a transportation inference, recommendation, plan, or action.

### P2 — Evidence Reconciliation

Evaluates whether traceable provenance and explicit handling of missingness, uncertainty, or source conflict contribute to a transportation task or decision.

### P3 — Multidimensional Transportation Integration

Evaluates whether integrating substantively different transportation evidence dimensions contributes to a defined transportation task.

Examples of such dimensions include spatial or network, temporal, operational, environmental, behavioural, facility, perceptual, and textual information.

---

## Proposition Evidence Labels

Each proposition is coded independently as:

| Code | Meaning |
|---|---|
| **D** | Direct evaluation with proposition-specific comparison or perturbation and attributable outcome evidence. |
| **P** | Substantive but partial, indirect, or incomplete evaluation of the proposition. |
| **N** | No proposition-specific evaluation identified. |

A **D** label indicates direct evaluation; it does not automatically mean that the reported result is positive.

Likewise, **N** indicates absence of proposition-specific evaluation, not evidence that the proposition is ineffective.

---

## Methodological-Concern Domains: Q1–Q8

Methodological concerns are assessed separately across eight domains:

- **Q1 — Task, data, and label appropriateness**
- **Q2 — System-boundary and implementation transparency**
- **Q3 — Comparator, metric, and evaluation adequacy**
- **Q4 — Analysis completeness, ablation, and uncertainty**
- **Q5 — Setting–claim alignment and external validity**
- **Q6 — Robustness, failure, and boundary-condition analysis**
- **Q7 — Reproducibility, provenance, and traceability**
- **Q8 — Authority, safety, governance, and deployment readiness**

The Q domains are noncompensatory and are not summed or averaged into an overall study-quality ranking.

---

## Supporting System Descriptors

The review also records supporting system characteristics independently of C, E, P, and Q, including:

- foundation-model type;
- system architecture;
- multimodality;
- tool use;
- memory;
- action authority;
- transportation feedback;
- adaptation;
- human involvement.

Greater architectural complexity, additional tools, persistent memory, or richer multimodality do not automatically imply greater capability or stronger evidence.

---

## Interpretation

The framework is designed to keep several questions separate:

- **What does the system do?** → C0–C3
- **Where was it evaluated?** → E0–E4
- **What transportation-specific contribution was tested?** → P1–P3
- **What methodological limitations remain?** → Q1–Q8
- **How is the system organised?** → supporting architecture and governance descriptors

The classifications reported in this repository follow the evidence rules used in the review and should not be interpreted as safety certifications or overall rankings of individual studies.

---

[← Back to main repository](README.md)
