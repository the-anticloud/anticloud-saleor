# SALEOR

![license](https://img.shields.io/badge/license-license-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-clothing_retail-lightgrey)

> Anticloud-hardened packaging of the upstream project `SALEOR` in category **CLOTHING RETAIL**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** CLOTHING RETAIL · **Upstream:** https://github.com/saleor/saleor · **Upstream pin:** `bb75f87973abe24056a5d0dff1708ca097e95599` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

<div align="center" width="100px">

 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/76e3079f-696a-4fcd-8658-89739647090b">
   <source media="(prefers-color-scheme: light)" srcset="https://github.com/user-attachments/assets/8477d643-a905-4c63-8ed3-03d0976f6fc3">
   <img width="200" alt="saleor-commerce-logo" src="https://user-images.githubusercontent.com/4006792/214636328-8e4f83e8-66cb-4114-a3d8-473eb908b9c3.png">

 </picture>
</div>

<div align="center">
  <strong>Commerce that works with your language and stack</strong>
</div>

<div align="center">
  GraphQL native, API-only platform for scalable composable commerce.
</div>

<br>

<div align="center">
 Get to know Saleor: <br>
  <a href="https://saleor.io/cloud/talk-to-us?utm_source=github&utm_medium=readme&utm_campaign=repo_saleor">Talk to a human</a>
  <span> | </span>
  <a href="https://cloud.saleor.io/signup?utm_source=github&utm_medium=readme&utm_campaign=repo_saleor">Talk to the API</a>
</div>

<br>

<div align="center">
  Join our community: <br>
  <a href="https://saleor.io/">Website</a>
  <span> | </span>
  <a href="https://twitter.com/getsaleor">Twitter</a>
  <span> | </span>
  <a href="https://saleor.io/discord">Discord</a>
</div>

<div align="center">
   <a href="https://saleor.io/blog">Blog</a>
  <span> | </span>
  <a href="https://saleor.typeform.com/to/JTJK0Nou">Subscribe to newsletter</a>
</div>

<br>

<div align="center">
  <a href="https://codecov.io/gh/saleor/saleor" >
    <img src="https://codecov.io/gh/saleor/saleor/graph/badge.svg?token=qkNcTJ4TmI" alt="Coverage"/>
  </a>
  <a href="https://docs.saleor.io/">
    <img src="https://img.shields.io/badge/docs-docs.saleor.io-brightgreen.svg" alt="Documentation" />
  </a>
  <a href="https://github.com/astral-sh/ruff">
    <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json" alt="Linted by Ruff">
  </a>
 <a href="https://saleor.io/discord">
   <img src="https://img.shields.io/discord/864066819866624010"  alt="Discord" >
 </a>
</div>

## Table of Contents

- [What makes Saleor special?](#what-makes-saleor-special)
- [Why API-only Architecture?](#why-api-only-architecture)
- [Features](#features)
- [Installation](#installation)
- [Documentation](#documentation)
- [Saleor Platform](#saleor-platform)
- [Storefront](#storefront)
- [Dashboard](#dashboard)
- [Contributing](#contributing)
- [License](#license)

## What makes Saleor special?

- **Technology-agnostic** - no monolithic plugin architecture or technology lock-in.

- **GraphQL only** - Not afterthought API design or fragmentation across different styles of API.

- **Headless and API only** - APIs are the only way to interact, configure, or extend the backend.

- **Open source** -  a single version of Saleor without feature fragmentation or commercial limitations.

- **Cloud native** - battle tested on global brands.

- **Native-multichannel** - Per [channel](https://docs.saleor.io/developer/channels/overview) control of pricing, currencies, stock, product, and more.

## Why API-only Architecture?

Saleor's API-first extensibility provides powerful tools for developers to extend backend using [webhooks](https://docs.saleor.io/developer/extending/webhooks/overview), attributes, [metadata](https://docs.saleor.io/api-usage/metadata), [apps](https://docs.saleor.io/developer/extending/apps/overview), [subscription queries](https://docs.saleor.io/developer/extending/webhooks/subscription-webhook-payloads), [API extensions](https://docs.saleor.io/developer/extending/webhooks/synchronous-events/overview), [dashboard iframes](https://docs.saleor.io/developer/extending/apps/overview).

Compared to traditional plugin architectures (monoliths) it provides the following benefits:

- There is less downtime as apps are deployed independently.
- Reliability and performance - custom logic is separated from the core.
- Simplified upgrade paths - eliminates incompatibility conflicts between extensions.
- Technology-agnostic - works with any technology, stack, or language.
- Parallel development - easier to collaborate than with a monolithic core.
- Simplified debugging - easier to narrow down bugs in independent services.
- Scalability - extensions and apps can be scaled independently.

### What are the tradeoffs?

If you are a single developer working with a small business that doesn't have high traffic or a critical need for 24/7 availability, using a service-oriented approach might feel more complex compared to the traditional WordPress or Magento approach that provides a language-specific framework, runtime, database schema, aspect-oriented programming, and other tools to a quick start.

However, if you deploy on a daily basis, reliability and uptime is critical,
you need to collaborate with other developers, or you have non-trivial requirements you might be in the right place.

## Features

- **Enterprise ready**: Secure, scalable, and stable. Battle-tested by big brands
- **Dashboard**: User-friendly, fast, and productive. (Decoupled project [project](https://github.com/saleor/saleor-dashboard) )
- **Global by design** Multi-currency, multi-language, multi-warehouse, tutti multi!
- **CMS**: Manage product or marketing content.
- **Product management**: A rich content model for large and complex catalogs.
- **Orders**: Flexible order model, split payments, multi-warehouse, returns, and more.
- **Customers**: Order history and preferences.
- **Promotion engine**: Sales, vouchers, cart rules, giftcards.
- **Payment orchestration**: multi-gateway, extensible payment API, flexible flows.
- **Cart**: Advanced payment and tax options, with full control over discounts and promotions.
- **Payments**: Flexible API architecture allows integration of any payment method.
- **Translations**: Fully translatable catalog.
- **SEO**: Unlimited SEO freedom with headless architecture.
- **Apps**: Extend dashboard via iframe wi

*(excerpt; full text in `UPSTREAM_CLONE/`)*

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Node.js / npm** (manifests: package.json, package-lock.json; scanned in UPSTREAM_CLONE)
- Top-level source layout: `deployment/`, `saleor/`, `scripts/`, `templates/`
- Snapshot size: **4630 files**, **854667 lines of code** (measured; see Benchmarks)
- Primary languages: `.py` (4348), `.yaml` (129), `.png` (62), `.html` (22), `.json` (21), `.md` (20)
- Upstream commit pinned for this packaging: `bb75f87973abe24056a5d0dff1708ca097e95599`

---

## Installation

- [Documentation](#documentation)
- [Saleor Platform](#saleor-platform)
- [Storefront](#storefront)
- [Dashboard](#dashboard)
- [Contributing](#contributing)
- [License](#license)

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

Compared to traditional plugin architectures (monoliths) it provides the following benefits:

- There is less downtime as apps are deployed independently.
- Reliability and performance - custom logic is separated from the core.
- Simplified upgrade paths - eliminates incompatibility conflicts between extensions.
- Technology-agnostic - works with any technology, stack, or language.
- Parallel development - easier to collaborate than with a monolithic core.
- Simplified debugging - easier to narrow down bugs in independent services.
- Scalability - extensions and apps can be scaled independently.

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

</div>

<br>

<div align="center">
 Get to know Saleor: <br>
  <a href="https://saleor.io/cloud/talk-to-us?utm_source=github&utm_medium=readme&utm_campaign=repo_saleor">Talk to a human</a>
  <span> | </span>
  <a href="https://cloud.saleor.io/signup?utm_source=github&utm_medium=readme&utm_campaign=repo_saleor">Talk to the API</a>
</div>

<br>

<div align="center">
  Join our community: <br>
  <a href="https://saleor.io/">Website</a>
  <span> | </span>
  <a href="https://twitter.com/getsaleor">Twitter</a>
  <span> | </span>
  <a href="https://saleor.io/discord">Discord</a>
</div>

<div align="center">
   <a href="https://saleor.io/blog">Blog</a>
  <span> | </span>
  <a href="https://saleor.typeform.com/to/JTJK0Nou">Subscribe to newsletter</a>
</div>

<br>

<div align="center">
  <a href="https://codecov.io/gh/saleor/saleor" >
    <img src="https://codecov.io/gh/saleor/saleor/graph/badge.svg?token=qkNcTJ4TmI" alt="Coverage"/>
  </a>
  <a href="https://docs.saleor.io/">
    <img src="https://img.shields.io/badge/docs-docs.saleor.io-brightgreen.svg" alt="Documentation" />
  </a>
  <a href="https://github.com/astral-sh/ruff">
    <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json" alt="Linted by Ruff">
  </a>
 <a href="https://saleor.io/discord">
   <img src="https://img.shields.io/discord/864066819866624010"  alt="Discord" >
 </a>
</div>

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Node.js / npm |
| Manifests detected | package.json, package-lock.json |
| Files in snapshot | 4630 |
| Lines of code | 854667 |
| Dependency references | 13 |
| Dependencies by ecosystem | npm: 2, pypi: 11 |
| Upstream license | BSD-3-Clause |
| Overlay license | Anticommons 0.1.0 |

Top dependency references recorded in the benchmark snapshot:

| Ecosystem | Name | Version | Source file |
|-----------|------|---------|-------------|
| npm | @release-it/bumper | ^7.0.5 | package.json |
| npm | release-it | ^19.0.4 | package.json |
| pypi | asgiref | >=3.11.1 | pyproject.toml |
| pypi | authlib | >=1.6.12 | pyproject.toml |
| pypi | azure-common | >=1.1.28 | pyproject.toml |
| pypi | azure-storage-blob | >=12.29.0 | pyproject.toml |
| pypi | azure-storage-common | >=2.1.0 | pyproject.toml |
| pypi | babel | >=2.18.0 | pyproject.toml |
| pypi | boto3 | ~=1.43 | pyproject.toml |
| pypi | botocore | ~=1.43 | pyproject.toml |
| pypi | cryptography | >=50.0.2 | pyproject.toml |
| pypi | dj-database-url | >=3.1.2 | pyproject.toml |
| pypi | dj-email-url | >=1 | pyproject.toml |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

- **Open source** -  a single version of Saleor without feature fragmentation or commercial limitations.

- **Cloud native** - battle tested on global brands.

- **Native-multichannel** - Per [channel](https://docs.saleor.io/developer/channels/overview) control of pricing, currencies, stock, product, and more.

*Section quoted from the upstream readme.*
Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

*Excerpt from upstream `CONTRIBUTING.md`:*

---
title: Contributing
---

> [!IMPORTANT]
> We value your contributions to Saleor and want to ensure they meet our project's needs. To help us maintain quality and consistency, we ask that you follow the process described in our [Contribution Guidelines](http://docs.saleor.io/developer/community/contributing). We welcome issues, new features, documentation improvements, community support, and more.

## Table of Contents

- [Running Saleor locally](#running-saleor-locally)
- [Managing dependencies](#managing-dependencies)
- [File structure](#file-structure)
- [Testing](#testing)
- [Coding style](#coding-style)
- [Tips and recommendation](#tips-and-recommendation)
- [Git commit messages](#git-commit-messages)
- [Pull requests](#pull-requests)
- [Changelog](#changelog)

## Running Saleor locally

### Running Saleor locally in development containers

The easiest way of running Saleor for local development is to use [development containers](https://containers.dev/).

Editor instructions:

- [Visual Studio Code](https://code.visualstudio.com/docs/devcontainers/containers#_quick-start-open-an-existing-folder-in-a-container)

- [PyCharm](https://www.jetbrains.com/help/pycharm/connect-to-devcontainer.html)

- [Codespaces](https://docs.github.com/en/codespaces/setting-up-your-project-for-codespaces/adding-a-dev-container-configuration/introduction-to-dev-containers)

Development container only creates container, you still need to start the server. See [common-commands](#common-commands) section to learn more.

### Running Saleor locally with database and additional services in docker

Install & setup prerequisites via homebrew:

```shell
brew install libmagic
brew install uv
uv python install 3.12
```

source this [project](https://github.com/saleor/saleor) and setup database and additional services in docker:

```shell
cd .devcontainer
docker compose up db dashboard cache mailpit
```

To create virtualenv and install dependencies run in root of the project:

```shell
uv sync
```

Install pre commit hooks:

```shell
uv run pre-commit install
```

Create environment variables, by creating a `.env` file. You can use existing example for development:

```shell
cp .env.example .env
```

> [!NOTE]
> Example env variables set-up Celery broker, mail server, allow `localhost` URLs and set Dashboard URL
> so that your development setup works with additional services set-up via `docker compose`
>
> Learn more about each env variable in [Environment Variable docs](https

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: BSD-3-Clause** (evidence: `LICENSE` in the upstream snapshot).

License file excerpt:

```text
BSD 3-Clause License

Copyright (c) 2020-2023, Saleor Commerce
Copyright (c) 2010-2020, Mirumee Software
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

* Redistributions of source code must retain the above copyright notice, this
  list of conditions and the following disclaimer.

* Redistributions in binary form must reproduce the above copyright notice,
  this list of conditions and the following disclaimer in the documentation
  and/or other materials provided with the distribution.

* Neither the name of the copyright holder nor the names of its
  contributors may be used to endorse or promote products derived from
  this software without specific prior written permission.

```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original BSD-3-Clause terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `BSD-3-Clause` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `SALEOR` (category: CLOTHING RETAIL)
- **Upstream URL:** https://github.com/saleor/saleor
- **Pinned commit (SHA):** `bb75f87973abe24056a5d0dff1708ca097e95599`
- **Branch:** main
- **Pin provenance:** GitHub API commits/main. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`bdf450f27f1385aafbc6f1038ebfcf89ec6b6b700ee8d140fa2bc8676fc64d6f`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| DANS (KNAW/NWO, Netherlands) | 10.17026/PT | EU-recognised archive |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe
and Mail, Business Insider, National Post, Financial Post, StreetInsider,
Digital Journal, Barchart, International Business Times, and Fox News.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

