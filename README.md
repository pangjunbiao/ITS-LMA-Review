# Large Multimodal Agents for Intelligent Transportation Systems

### Living Evidence Repository for  
**“Large Multimodal Agents for Intelligent Transportation Systems: Architectures, Evidence, and Deployment Challenges”**

This repository is the public companion resource for our review of foundation-model-centred multimodal systems and agents in intelligent transportation systems (ITS).

The review provides a structured evidence map of current ITS applications, system architectures, multimodality, functional capability, validation settings, methodological evidence, and operational authority. This repository extends the review as a **living literature and evidence resource** that will be periodically updated as new relevant studies become available.

---

## Review Snapshot

- **Manuscript evidence cutoff:** 3 August 2026
- **Primary study families in the frozen manuscript corpus:** 42
- **Mapped sources in the review:** 91
- **Primary analysis period:** January 2023 – 3 August 2026
- **Repository status:** Frozen manuscript corpus published; living updates enabled
- **Update cadence:** At least once every two months during the manuscript peer-review period

> **Important:** The quantitative results reported in the manuscript are based on the frozen evidence corpus through **3 August 2026**. Studies identified after this cutoff are maintained separately as post-cutoff updates and do not retroactively alter the manuscript results unless a formally documented review update is performed.

---

## Scope

The repository tracks foundation-model-centred transportation systems in which a foundation model has a substantive role in transportation-specific:

- multimodal evidence interpretation and grounding;
- semantic reasoning;
- retrieval and evidence organisation;
- specialist-tool orchestration;
- decision support and planning;
- simulation and scenario generation;
- bounded transportation actions; or
- outcome-responsive decision making.

The repository distinguishes **model-level**, **system-level**, and **hybrid multimodality** and preserves the boundary between foundation-model functionality and specialist forecasting, optimisation, simulation, planning, control, and safety systems.

---

## Application Domains

The frozen manuscript corpus contains **42 primary study families** across five mutually exclusive application domains:

1. [**Prediction and Network Understanding**](papers/prediction-network-understanding.md) — 1 family
2. [**Autonomous Driving and Vehicle Interaction**](papers/autonomous-driving-vehicle-interaction.md) — 17 families
3. [**Signal Control and Public Operations**](papers/signal-control-public-operations.md) — 4 families
4. [**Traffic Safety and Incident Management**](papers/traffic-safety-incident-management.md) — 7 families
5. [**Planning, Simulation, and Human–Machine Collaboration**](papers/planning-simulation-hmc.md) — 13 families

Each category page provides the frozen study-family list, C/E/P classifications, publication links, and public code or project links where verified.

---

## Evidence Framework

The review evaluates studies using several independent dimensions:

- **C0–C3:** demonstrated functional capability;
- **E0–E4:** validation setting;
- **P1–P3:** evidence for transportation semantics, evidence reconciliation, and multidimensional transportation integration;
- **Q1–Q8:** methodological-concern domains;
- system architecture, multimodality, tool use, memory, authority, feedback, adaptation, and human involvement.

These dimensions are not combined into a single study-quality score or ranking.

Detailed definitions and coding rules are provided in [`taxonomy.md`](taxonomy.md).

---

## Frozen Evidence Map and Living Updates

This repository separates two forms of evidence:

### Frozen Manuscript Corpus

The frozen evidence map corresponds to the literature included in the manuscript through **3 August 2026**. Its study-family classifications and aggregate statistics form the basis of the review's reported results.

### Post-Cutoff Literature

Relevant studies identified after the manuscript cutoff are recorded separately. They are screened using the same conceptual inclusion boundary and study-family principles but are not automatically incorporated into the frozen manuscript statistics.

This separation preserves the reproducibility of the published evidence synthesis while allowing the resource to remain current.

---

## Repository Contents

The repository currently provides:

- [application-domain paper lists](papers/);
- the [machine-readable frozen evidence map](data/frozen_evidence_map_2026-08-03.csv);
- the [ITS-LMA taxonomy and evidence framework](taxonomy.md);
- [related surveys](related-surveys.md);
- [datasets, benchmarks, and simulation resources](resources.md);
- [post-cutoff literature updates](post-cutoff-updates.md);
- the [repository update history](UPDATE_LOG.md); and
- [contribution guidelines](CONTRIBUTING.md).

---

## Authors

**Muhammad Ayub Sabir, Shaohong Zheng, Zhiyu Qu, Fatima Ashraf, and Junbiao Pang**

---

## Contributing

Suggestions for newly published studies, archival publication updates, corrected links, or other relevant resources will be welcome through GitHub issues or pull requests.

Proposed additions will be checked against the review's eligibility criteria and study-family rules before inclusion in the curated evidence map.

Detailed contribution instructions are available in [`CONTRIBUTING.md`](CONTRIBUTING.md).

---

## Maintenance

This is a living companion repository for the review.

We check the literature and update the repository **at least once every two months until the survey is accepted**. New studies, publication-version updates, and other relevant changes are recorded in [`UPDATE_LOG.md`](UPDATE_LOG.md).

The manuscript itself remains tied to its stated evidence cutoff; later additions to this repository are tracked separately.

---

## Citation

The citation for the review article will be added here once the final publication details are available.

For now, if you use this resource, please refer to:

**Large Multimodal Agents for Intelligent Transportation Systems — Living Evidence Repository**

GitHub: [pangjunbiao/ITS-LMA-Review](https://github.com/pangjunbiao/ITS-LMA-Review)

---

## Notes

The C0–C3, E0–E4, and P1–P3 labels reported here follow the definitions used in our review. They reflect our evidence-based reading of the published studies and are not labels assigned by the original authors.

These classifications are intended to support comparison across the literature; they should not be interpreted as safety certifications or overall rankings of individual studies.

## Disclaimer

The capability, validation, proposition, and methodological-concern classifications in this repository are analytical judgments made within the review framework. They are not labels assigned by the original study authors, safety certifications, or rankings of study quality.
