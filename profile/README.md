<p align="center">
  <a href="https://www.opentargets.org">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="./assets/ot-logo-white.svg">
      <img alt="Open Targets" src="./assets/ot-logo-colour.svg" width="360">
    </picture>
  </a>
</p>

<p align="center">
  <b>Using human genetics and genomics to systematically identify and prioritise drug targets.</b>
</p>

<p align="center">
  <a href="https://www.opentargets.org">Website</a> ·
  <a href="https://platform.opentargets.org">Platform</a> ·
  <a href="https://platform-docs.opentargets.org">Documentation</a> ·
  <a href="https://community.opentargets.org">Community</a> ·
  <a href="https://blog.opentargets.org">Blog</a>
</p>

---

## 👋 About us

**Open Targets** is a pre-competitive partnership between academic institutes and pharmaceutical companies that helps researchers choose the right drug targets.

We combine large-scale genomic experiments with new computational methods, and we release the data, code and tools we build openly, so that anyone can use them.

Our partners are [EMBL-EBI](https://www.ebi.ac.uk), the [Wellcome Sanger Institute](https://www.sanger.ac.uk), Genentech, GSK, MSD, Pfizer and Sanofi.

## 🎯 Open Targets Platform

The [**Open Targets Platform**](https://platform.opentargets.org) is a free resource that brings together public data on targets, diseases, drugs, variants and GWAS studies, and scores the evidence linking each target to each disease. It is updated quarterly.

| I want to…                         | Go to                                                                                                                                                                                                                                                      |
| ---------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Explore evidence in the browser    | [platform.opentargets.org](https://platform.opentargets.org)                                                                                                                                                                                               |
| Query programmatically             | [GraphQL API](https://platform-docs.opentargets.org/data-access/graphql-api) · [playground](https://api.platform.opentargets.org/api/v4/graphql/browser)                                                                                                   |
| Analyse everything at scale        | [Bulk downloads](https://platform.opentargets.org/downloads) in Parquet via [FTP](https://ftp.ebi.ac.uk/pub/databases/opentargets/platform/), [AWS S3](https://registry.opendata.aws/opentargets/) or [Google Cloud Storage](https://console.cloud.google.com/storage/browser/open-targets-data-releases) · [BigQuery](https://console.cloud.google.com/bigquery?p=bigquery-public-data&d=open_targets_platform)                                                             |
| Connect an AI assistant            | [MCP server](https://github.com/opentargets/platform-mcp), hosted at `https://mcp.platform.opentargets.org/mcp`                                                                                                                                           |
| Understand the data                | [Documentation](https://platform-docs.opentargets.org) · [Release notes](https://platform-docs.opentargets.org/release-notes)                                                         |

## 🧰 Featured repositories

**The Platform**

- [`platform-webapp`](https://github.com/opentargets/platform-webapp): the Platform web application (TypeScript, React)
- [`platform-api`](https://github.com/opentargets/platform-api): the GraphQL API behind the web app (Scala)
- [`pipeline`](https://github.com/opentargets/pipeline): generates each Open Targets data release (Python, PySpark, Polars)
- [`platform-deployment-standalone`](https://github.com/opentargets/platform-deployment-standalone): run your own copy of the Platform locally
- [`platform-snapshots`](https://github.com/opentargets/platform-snapshots): software versions behind every release

**Genetics, clinical data and data science**

- [`gentropy`](https://github.com/opentargets/gentropy): Python framework for post-GWAS analysis, including fine-mapping, colocalisation and locus-to-gene ([docs](https://opentargets.github.io/gentropy/))
- [`mira`](https://github.com/opentargets/mira): harmonises clinical trials, regulatory approvals, drug indications and safety evidence into traceable clinical reports ([docs](https://opentargets.org/mira/))
- [`OnToma`](https://github.com/opentargets/OnToma): maps disease and phenotype terms to ontologies
- [`otter`](https://github.com/opentargets/otter): lightweight task runner used across our pipelines

**AI and agents**

- [`platform-mcp`](https://github.com/opentargets/platform-mcp): official Model Context Protocol server for the Platform
<sub>Our stack: Python · PySpark · Scala · TypeScript · Rust · Nextflow · Google Cloud · Kubernetes</sub>

## 🤝 Get involved

- 💬 **Ask a question or share an idea** on the [Community forum](https://community.opentargets.org), the best place to reach the team.
- 🐛 **Found a bug in the Platform?** Open an issue in [`opentargets/issues`](https://github.com/opentargets/issues).
- 💡 **Want a new feature?** Post it under [Feature requests](https://community.opentargets.org/c/feature-requests/16).
- 🛠️ **Contributing code?** Pull requests are welcome, and each repository's README explains how to get started.
- 📄 **Using our data?** Please [cite the Platform](https://platform-docs.opentargets.org/citation).
- 🧑‍💻 **Join the team:** see [current vacancies](https://www.opentargets.org/jobs).

<p align="center">
  <a href="https://bsky.app/profile/opentargets.org">Bluesky</a> ·
  <a href="https://www.linkedin.com/company/open-targets">LinkedIn</a> ·
  <a href="https://x.com/opentargets">X</a> ·
  <a href="https://blog.opentargets.org">Blog</a>
</p>
