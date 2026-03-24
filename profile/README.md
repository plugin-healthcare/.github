# Welcome to PLUGIN Healthcare 👋

**PLUGIN** is an open, federated data platform for Dutch healthcare — enabling hospitals, researchers, and data engineers to collaborate on real-world health data while keeping data where it belongs: at the source.

---

## 🏥 What is PLUGIN?

PLUGIN (**Pl**atform voor **U**itwisseling en Her*g*ebruik van Kl**i**nische Data **N**ederland) is a national initiative building the technical and semantic infrastructure for **federated, composable health data spaces** in the Netherlands. We work at the intersection of clinical informatics, data engineering, and open standards.

Our platform enables:

- 🔗 **Federated analytics** — run analyses across hospital data without centralising patient data
- 🏗️ **Composable data stations** — standardised, interoperable hospital data nodes
- 📐 **Semantic interoperability** — harmonising Dutch zib/FHIR, OMOP CDM, and openEHR standards
- 📦 **Open tooling** — reusable components for ETL, data curation, and implementation guidance

---

## 🗂️ Key Repositories

| Repository | Description |
|---|---|
| [pluginlake](https://github.com/plugin-healthcare/pluginlake) | Federated data lake — the core platform |
| [implementation-guide](https://github.com/plugin-healthcare/implementation-guide) | FHIR Implementation Guide for PLUGIN |
| [plugin-rosetta](https://github.com/plugin-healthcare/plugin-rosetta) | Integration of information models, schemas and mappings in LinkML |
| [plugin-link](https://github.com/plugin-healthcare/plugin-link) | Interactive ERD viewer for LinkML schemas |
| [plugin-c4-software-architecture](https://github.com/plugin-healthcare/plugin-c4-software-architecture) | Platform architecture in C4 model |
| [data-station-specification](https://github.com/plugin-healthcare/data-station-specification) | Specification of composable data stations |
| [federated-composable-datastack](https://github.com/plugin-healthcare/federated-composable-datastack) | Reference architecture working paper |
| [handbook](https://github.com/plugin-healthcare/handbook) | PLUGIN handbook — all things PLUGIN |

---

## 🔧 Standards & Technologies

We build with and around:

- **HL7 FHIR R4** — including Dutch [Nictiz zib2020](https://github.com/plugin-healthcare/Nictiz-R4-zib2020) profiles
- **OMOP Common Data Model** — with [OMOCL](https://github.com/plugin-healthcare/OMOCL) and [Eos](https://github.com/plugin-healthcare/Eos) for openEHR-to-OMOP ETL
- **LinkML** — for schema-first data modelling and semantic mapping
- **vantage6** — for privacy-preserving federated learning
- **openEHR** — clinical information models
- **Apache Parquet / DuckDB / dbt** — for the composable data stack

---

## 📚 Publications & Architecture

- 📖 [PLUGIN Handbook](https://plugin-healthcare.github.io/handbook/) — comprehensive documentation (Dutch & English)
- 🏛️ [C4 Software Architecture](https://plugin-healthcare.github.io/plugin-c4-software-architecture/) — interactive architecture diagrams
- 📄 [Data Interoperability in Context](https://www.jmir.org/2025/1/e66616/authors) — peer-reviewd journal paper on the importance of open-source implementations when choosing standards


---

## 🤝 Contributing

We welcome contributions from clinicians, data engineers, health informaticians, and open-source enthusiasts. Check out individual repository `CONTRIBUTING.md` files, or browse our [implementation guide discussions](https://github.com/plugin-healthcare/implementation-guide/discussions) to get started.

---

## 📬 Get in Touch

Find us on GitHub at [github.com/plugin-healthcare](https://github.com/plugin-healthcare) or explore our public repositories to learn more about how we are building the next generation of Dutch health data infrastructure.

> *Building open, federated health data infrastructure for the Netherlands — together.*
