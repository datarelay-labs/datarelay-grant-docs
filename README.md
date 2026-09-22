<p align="center">
  <img src="favicon.svg" width="88" height="88" alt="DataRelay Grant icon">
</p>

<h1 align="center">DataRelay Grant Documentation</h1>

<p align="center">
  <strong>Public Product Documentation for DataRelay Grant.</strong>
</p>

<p align="center">
  Patent-backed product definition for a reusable human-approval and execution-control layer.
</p>

<p align="center">
  <a href="https://github.com/datarelay-labs/datarelay-grant">Product Repository</a> ·
  <a href="index.mdx">English</a> ·
  <a href="ko/index.mdx">한국어</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-Coming%20Soon-7C3AED?style=flat-square" alt="Coming Soon">
  <img src="https://img.shields.io/badge/docs-Mintlify-2563EB?style=flat-square" alt="Mintlify">
  <img src="https://img.shields.io/badge/US%20Patent-12%2C056%2C667%20B1-16A34A?style=flat-square" alt="US Patent 12,056,667 B1">
  <img src="https://img.shields.io/badge/KR%20Patent-10--2567118%20B1-16A34A?style=flat-square" alt="KR Patent 10-2567118 B1">
</p>

---

## Documentation for the approval layer

This repository contains the Mintlify source for the public **DataRelay Grant** product site and documentation.

DataRelay Grant is an upcoming DataRelay Labs product designed to place an explicit human approval decision between a requested action and its automated execution.

> **Request → Human Approval → Controlled Execution**

The current documentation is intentionally **product-definition-first**. It explains the patent-backed technical foundation and planned product role without presenting unreleased capabilities as implemented.

## Documentation scope

| Area | Current documentation |
|---|---|
| **Product overview** | What DataRelay Grant is intended to solve and where it fits |
| **Approval model** | Request, approve, pending, deny, and controlled execution |
| **Patent foundation** | Technical concepts from US 12,056,667 B1 and KR 10-2567118 B1 |
| **Integration direction** | Planned relationship with DataRelay Link, DataRelay Control, and external systems |
| **Product status** | Clear distinction between public patent foundation and unreleased implementation |
| **Languages** | English and Korean |

## Site structure

```text
datarelay-grant-docs/
├── docs.json
├── index.mdx
├── patent-foundation.mdx
└── ko/
    ├── index.mdx
    └── patent-foundation.mdx
```

The navigation and public content are configured through `docs.json`.

## Patent foundation

| Jurisdiction | Patent | Priority | Grant / publication |
|---|---|---|---|
| United States | [US 12,056,667 B1](https://patents.google.com/patent/US12056667B1/en) | 2023-03-13 | 2024-08-06 |
| Republic of Korea | [KR 10-2567118 B1](https://patents.google.com/patent/KR102567118B1/ko) | 2023-03-13 | 2023-08-16 |

The documentation describes the two patents as a shared product technology foundation while avoiding claims that their issued legal scopes are identical.

## Current status

Current documentation status: **Coming Soon / pre-release product definition**

Published now:

- product positioning
- patent-backed approval workflow
- approval / pending / denial model
- modular automation concepts described by the patent foundation
- external-system integration concept
- planned relationship with other DataRelay products
- English and Korean landing content

Not yet documented as implemented:

- production APIs
- authentication and authorization contracts
- deployment procedures
- administration workflows
- security architecture
- release procedures
- GA feature matrix

Those sections should be added only as implementation and validation evidence becomes available.

## Product repository

The implementation repository is:

[datarelay-labs/datarelay-grant](https://github.com/datarelay-labs/datarelay-grant)

The product repository is the future source for implementation evidence. This documentation repository must not promote roadmap or patent-described concepts into claims of current implementation without matching evidence.

## Key files

| File | Purpose |
|---|---|
| [`index.mdx`](index.mdx) | English product landing page |
| [`patent-foundation.mdx`](patent-foundation.mdx) | English patent and technical foundation |
| [`ko/index.mdx`](ko/index.mdx) | Korean product landing page |
| [`ko/patent-foundation.mdx`](ko/patent-foundation.mdx) | Korean patent and technical foundation |
| [`docs.json`](docs.json) | Mintlify site and navigation configuration |

## Documentation principles

- Clearly separate **patent-described concepts**, **planned product behavior**, and **implemented behavior**.
- Do not describe an unreleased API, security model, deployment method, or integration contract as available.
- Keep DataRelay Link, DataRelay Control, and DataRelay Grant as separate product boundaries.
- Treat the official issued patent records and claims as the legal reference for patent scope.
- Keep English and Korean product messaging aligned.

---

<p align="center">
  <strong>Request. Approve. Execute.</strong>
</p>

<p align="center">
  <a href="https://github.com/datarelay-labs/datarelay-grant">Product Repository</a> ·
  <a href="index.mdx">English Docs</a> ·
  <a href="ko/index.mdx">한국어 문서</a>
</p>
