# Signal Control and Public Operations

This page lists the primary study families assigned to the **Signal Control and Public Operations** domain in the review.

The manuscript evidence map is frozen through **3 August 2026**. Studies identified after this cutoff are tracked separately and are not mixed with the frozen manuscript corpus.

## Frozen Manuscript Corpus

**Families in this domain: 4**

| Study family | Year / venue | C | E | P1 | P2 | P3 | Paper | Code / project |
|---|---|---|---|---|---|---|---|---|
| **LLMLight: Large Language Models as Traffic Signal Control Agents** | 2025 / KDD | C3 | E2 | P | N | P | [Paper](https://doi.org/10.1145/3690624.3709379) | [Code](https://github.com/usail-hkust/LLMTSCS) |
| **The Crossroads of LLM and Traffic Control: A Study on Large Language Models in Adaptive Traffic Signal Control** | 2025 / IEEE T-ITS | C3 | E2 | P | N | P | [Paper](https://doi.org/10.1109/TITS.2024.3498735) | — |
| **Large Language Models as Traffic Control Systems at Urban Intersections: A New Paradigm** | 2025 / Vehicles | C1 | E1 | P | N | P | [Paper](https://doi.org/10.3390/vehicles7010011) | — |
| **TransitGPT: A Generative AI-Based Framework for Interacting with GTFS Data Using Large Language Models** | 2025 / Public Transport | C1 | E1 | P | P | P | [Paper](https://doi.org/10.1007/s12469-025-00395-w) | [Code](https://github.com/UTEL-UIUC/TransitGPT) |

> **Note:** A dash in the **Code / project** column means that no official public artefact has been linked on this page. It should not be interpreted as evidence that no implementation or private artefact exists.

## Aggregate Evidence Profile

Across the **four Signal Control and Public Operations study families**:

- **Capability:** C0 / C1 / C2 / C3 = **0 / 2 / 0 / 2**
- **Validation:** E1 / E2 / E3 / E4 = **2 / 2 / 0 / 0**
- **P1:** D / P / N = **0 / 4 / 0**
- **P2:** D / P / N = **0 / 1 / 3**
- **P3:** D / P / N = **0 / 4 / 0**

LLMLight and *The Crossroads of LLM and Traffic Control* demonstrate **C3/E2** because transportation-state feedback in interactive simulation informs subsequent foundation-model traffic-control decisions.

The urban-intersection study and TransitGPT remain **C1/E1** because their demonstrated foundation-model roles provide analysis, guidance, or tool-mediated decision support without an executed outcome-responsive transportation action cycle.

Across the domain, P1 and P3 remain **partial in all four families**. P2 is partially evaluated only in TransitGPT and is not proposition-specifically evaluated in the other three families.

The current evidence therefore supports language-mediated traffic-data access, traffic-state interpretation, high-level decision support, explanation, and simulated signal-control reasoning. It does not establish LMA-specific traffic-control superiority, controlled field readiness, or sustained operational authority.

Verified optimisation, phase-feasibility logic, coordination, hard safety constraints, monitoring, fallback, and rollback remain important specialist-system responsibilities.

For the complete family-level taxonomy, Q1–Q8 methodological-concern profile, and principal limitations, see the [frozen evidence map](../data/frozen_evidence_map_2026-08-03.csv).

---

### Coding Note

C, E, and P labels are analytical classifications assigned in the review rather than labels used by the original study authors. Definitions are provided in the [ITS-LMA evidence framework and taxonomy](../taxonomy.md).

The application-domain assignment follows each study family's **principal evaluated foundation-model role**, not simply the wording of the paper title. In particular, TransitGPT is included here because its principal evaluated role concerns public-transport data access and operational decision support.

---

[← Back to main repository](../README.md)
