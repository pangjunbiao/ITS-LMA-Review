# Planning, Simulation, and Human–Machine Collaboration

This page lists the primary study families assigned to the **Planning, Simulation, and Human–Machine Collaboration** domain in the review.

The manuscript evidence map is frozen through **3 August 2026**. Studies identified after this cutoff are tracked separately and are not mixed with the frozen manuscript corpus.

## Frozen Manuscript Corpus

**Families in this domain: 13**

| Study family | Year / venue | C | E | P1 | P2 | P3 | Paper | Code / project |
|---|---|---|---|---|---|---|---|---|
| **Agentic Large Language Models for Day-to-Day Route Choices** | 2025 / TRC | C3 | E2 | D | N | P | [Paper](https://doi.org/10.1016/j.trc.2025.105307) | [Code](https://github.com/georgewanglz2019/LLMTraveler) |
| **ChatSUMO: Large Language Model for Automating Traffic Scenario Generation in Simulation of Urban Mobility** | 2025 / IEEE T-IV | C1 | E1 | P | P | P | [Paper](https://doi.org/10.1109/TIV.2024.3508471) | — |
| **Speak to Simulate: An LLM-Guided Agentic Framework for Traffic Simulation in SUMO** | 2025 / GeoSIM | C2 | E2 | P | P | P | [Paper](https://doi.org/10.1145/3764921.3770151) | — |
| **Automating Traffic Model Enhancement With AI Research Agent** | 2025 / TRC | C2 | E1 | P | P | P | [Paper](https://doi.org/10.1016/j.trc.2025.105187) | [Code](https://github.com/Guoxs/TR-Agent) |
| **Editable Scene Simulation for Autonomous Driving via Collaborative LLM-Agents** | 2024 / CVPR | C2 | E1 | D | N | D | [Paper](https://arxiv.org/abs/2402.05746) | [Code](https://github.com/yifanlu0227/ChatSim) |
| **GATSim: Urban Mobility Simulation with Generative Agents** | 2026 / TRC | C3 | E2 | D | P | D | [Paper](https://doi.org/10.1016/j.trc.2026.105576) | [Code](https://github.com/qiliuchn/gatsim) |
| **Large Language Model as Parking Planning Agent in the Context of Mixed Period of Autonomous Vehicles and Human-Driven Vehicles** | 2024 / Sustainable Cities and Society | C1 | E1 | D | P | P | [Paper](https://doi.org/10.1016/j.scs.2024.105940) | — |
| **Bridging AI and Traffic Simulation: A Robust and Comprehensive Framework for LLM-Based AI Replanning Agents in MATSim** | 2026 / Procedia Computer Science | C3 | E2 | P | P | P | [Paper](https://doi.org/10.1016/j.procs.2026.04.079) | — |
| **Agentic Traffic Intelligence: Augmented Human-in-the-Loop Scenario Generation for Microscopic Traffic Simulation** | 2026 / Artificial Intelligence for Transportation | C2 | E2 | P | P | P | [Paper](https://doi.org/10.1016/j.ait.2026.100057) | — |
| **Large Language Model-Assisted Multi-Objective Optimization for an Integrated Multimodal E-Mobility Platform** | 2026 / TRIP | C1 | E1 | D | P | D | [Paper](https://doi.org/10.1016/j.trip.2026.101948) | — |
| **Virtual Traffic Police: Large Language Model-Augmented Traffic Signal Control for Unforeseen Incidents** | 2025 / IEEE ITSC + linked 2026 preprint | C2 | E2 | D | P | D | [Paper](https://doi.org/10.1109/ITSC60802.2025.11423524) | — |
| **An Efficient Simulation Scene Generation Method Based on Extracted Road Network Topology and Large Language Models** | 2026 / Future Transportation | C2 | E2 | D | N | P | [Paper](https://doi.org/10.3390/futuretransp6020081) | — |
| **ChatSUMO Agent: An LLM-Based Agent for Conversational Traffic Simulation in SUMO** | 2026 / SSRN preprint at cutoff | C3 | E2 | P | P | P | [Frozen source](https://doi.org/10.2139/ssrn.6000335) | [Code](https://github.com/ChrisLi1221/ChatSUMO-Agent) |

> **Note:** A dash in the **Code / project** column means that no study-specific public artefact has been linked on this page. It should not be interpreted as evidence that no implementation or private artefact exists.

> **Source-version note:** ChatSUMO Agent is represented by the cutoff-valid SSRN preprint used in the frozen manuscript corpus. Later publication metadata does not retroactively change the frozen evidence map unless a dated source-version amendment is recorded.

## Aggregate Evidence Profile

Across the **13 Planning, Simulation, and Human–Machine Collaboration study families**:

- **Capability:** C0 / C1 / C2 / C3 = **0 / 3 / 6 / 4**
- **Validation:** E1 / E2 / E3 / E4 = **5 / 8 / 0 / 0**
- **P1:** D / P / N = **7 / 6 / 0**
- **P2:** D / P / N = **0 / 10 / 3**
- **P3:** D / P / N = **4 / 9 / 0**

Four families demonstrate **C3/E2 outcome-responsive capability in virtual transportation environments**:

- Agentic Large Language Models for Day-to-Day Route Choices;
- GATSim;
- the MATSim replanning-agent family; and
- ChatSUMO Agent.

In these studies, transportation or simulation outcomes influence subsequent foundation-model-centred decisions. This demonstrates outcome-responsive behaviour within simulation, but not operational authority over a real transportation network.

Six families demonstrate **C2 bounded-action capability**:

- Speak to Simulate;
- Automating Traffic Model Enhancement With AI Research Agent;
- Editable Scene Simulation;
- Agentic Traffic Intelligence;
- Virtual Traffic Police; and
- An Efficient Simulation Scene Generation Method Based on Extracted Road Network Topology and Large Language Models.

These systems execute or orchestrate bounded simulation, modelling, scene-generation, or controller-configuration actions, but do not demonstrate the outcome-responsive foundation-model decision cycle required for C3.

The remaining three families—ChatSUMO, the parking-planning agent, and the multimodal e-mobility optimisation framework—are classified as **C1/E1 decision-support systems**, because external users or specialist optimisation components retain implementation authority.

Across the domain, direct evidence is stronger for **transportation semantics (P1)** than for **multidimensional integration (P3)**, while **P2 evidence reconciliation remains entirely partial or absent**. No family directly evaluates the complete P2 proposition.

The evidence supports preference interpretation, scenario and artefact generation, simulation setup, tool orchestration, model enhancement, virtual replanning, route and planning assistance, explanation, and human-in-the-loop collaboration.

It does not establish that an LMA-generated transportation plan is necessarily feasible, optimal, behaviourally realistic, causally valid, or operationally deployable. Optimisation, demand and route-choice modelling, network loading, simulation calibration, physical and policy constraints, verification of generated artefacts, and final execution therefore remain important specialist-system and accountable-human responsibilities.

For the complete family-level taxonomy, Q1–Q8 methodological-concern profile, and principal limitations, see the [frozen evidence map](../data/frozen_evidence_map_2026-08-03.csv).

---

### Coding Note

C, E, and P labels are analytical classifications assigned in the review rather than labels used by the original study authors. Definitions are provided in the [ITS-LMA evidence framework and taxonomy](../taxonomy.md).

The application-domain assignment follows each study family's **principal evaluated foundation-model role**, not simply the wording of the paper title.

In particular, **Virtual Traffic Police** is assigned to this domain because the evaluated foundation-model contribution configures specialist traffic-signal controllers within simulation, while the lower-level specialist controllers retain the actual traffic-control function.

---

[← Back to main repository](../README.md)
