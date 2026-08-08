# Traffic Safety and Incident Management

This page lists the primary study families assigned to the **Traffic Safety and Incident Management** domain in the review.

The manuscript evidence map is frozen through **3 August 2026**. Studies identified after this cutoff are tracked separately and are not mixed with the frozen manuscript corpus.

## Frozen Manuscript Corpus

**Families in this domain: 7**

| Study family | Year / venue | C | E | P1 | P2 | P3 | Paper | Code / project |
|---|---|---|---|---|---|---|---|---|
| **Using Multimodal Large Language Models for Automated Detection of Traffic Safety-Critical Events** | 2024 / Vehicles | C0 | E1 | P | N | P | [Paper](https://doi.org/10.3390/vehicles6030074) | — |
| **VRU-Accident: A Vision-Language Benchmark for Video Question Answering and Dense Captioning for Accident Scene Understanding** | 2025 / ICCV Workshops | C0 | E1 | P | N | P | [Paper](https://openaccess.thecvf.com/content/ICCV2025W/2COOOL/html/Kim_VRU-Accident_A_Vision-Language_Benchmark_for_Video_Question_Answering_and_Dense_ICCVW_2025_paper.html) | [Code / data](https://github.com/Kimyounggun99/VRU-Accident) |
| **SafePLUG: Empowering Multimodal LLMs with Pixel-Level Insight and Temporal Grounding for Traffic Accident Understanding** | 2026 / CHAIN | C0 | E1 | D | P | D | [Paper](https://doi.org/10.23919/CHAIN.2026.000005) | [Project](https://zihaosheng.github.io/SafePLUG/) |
| **AITP: Traffic Accident Responsibility Allocation via Multimodal Large Language Models** | 2026 / CVPR Findings | C0 | E1 | D | P | D | [Paper](https://openaccess.thecvf.com/content/CVPR2026F/html/Zhou_AITP_Traffic_Accident_Responsibility_Allocation_via_Multimodal_Large_Language_Models_CVPRF_2026_paper.html) | [Code](https://github.com/Songan-Lab/AITP) |
| **ChatScene: Knowledge-Enabled Safety-Critical Scenario Generation for Autonomous Vehicles** | 2024 / CVPR | C2 | E2 | D | P | D | [Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Zhang_ChatScene_Knowledge-Enabled_Safety-Critical_Scenario_Generation_for_Autonomous_Vehicles_CVPR_2024_paper.html) | [Code](https://github.com/javyduck/ChatScene) |
| **LLMScenario: Large Language Model Driven Scenario Generation** | 2024 / IEEE TSMC | C0 | E1 | P | P | P | [Paper](https://doi.org/10.1109/TSMC.2024.3392930) | — |
| **Automating the Loop in Traffic Incident Management on Highway** | 2025 / L4DC (PMLR) | C1 | E1 | D | P | D | [Paper](https://proceedings.mlr.press/v283/cercola25a.html) | — |

> **Note:** A dash in the **Code / project** column means that no official public artefact has been linked on this page. It should not be interpreted as evidence that no implementation or private artefact exists.

## Aggregate Evidence Profile

Across the **seven Traffic Safety and Incident Management study families**:

- **Capability:** C0 / C1 / C2 / C3 = **5 / 1 / 1 / 0**
- **Validation:** E1 / E2 / E3 / E4 = **6 / 1 / 0 / 0**
- **P1:** D / P / N = **4 / 3 / 0**
- **P2:** D / P / N = **0 / 5 / 2**
- **P3:** D / P / N = **4 / 3 / 0**

Most evidence in this domain remains **offline and analytical**. Five of the seven families are C0 systems that evaluate accident detection, scene understanding, grounding, responsibility-support reasoning, or offline scenario generation without an executed transportation action cycle.

**ChatScene** reaches **C2/E2** because generated safety-critical scenarios are executed in CARLA, while **Automating the Loop in Traffic Incident Management on Highway** remains **C1/E1** because the evaluated system provides decision support and human operators remain responsible for implementation.

Direct evidence is stronger for **transportation semantics (P1)** and **multidimensional integration (P3)** than for **evidence reconciliation (P2)**. No family directly evaluates the complete P2 proposition.

The evidence supports event interpretation, evidence localisation, structured accident description, safety-critical scenario generation, explanation, responsibility-support reasoning, and analyst or operator assistance. It does not establish prospective safety improvement from an LMA-mediated intervention, autonomous emergency-response authority, legal adjudication authority, or sustained operational deployment.

Validated detection and risk models, causal analysis, optimisation, emergency procedures, source traceability, and accountable human adjudication therefore remain important specialist-system and governance boundaries.

For the complete family-level taxonomy, Q1–Q8 methodological-concern profile, and principal limitations, see the [frozen evidence map](../data/frozen_evidence_map_2026-08-03.csv).

---

### Coding Note

C, E, and P labels are analytical classifications assigned in the review rather than labels used by the original study authors. Definitions are provided in the [ITS-LMA evidence framework and taxonomy](../taxonomy.md).

The application-domain assignment follows each study family's **principal evaluated foundation-model role**, not simply the wording of the paper title. ChatScene is therefore included in this domain because its principal evaluated contribution is safety-critical scenario generation and testing rather than general autonomous-driving control.

---

[← Back to main repository](../README.md)
