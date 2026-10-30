# Lifebit Biotech

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Lifebit Biotech Ltd is a London-founded (2017) health-data infrastructure company that builds federated Trusted Research Environments (TREs) for population-scale biomedical research and sovereign health AI. Rather than centralising sensitive patient data, Lifebit sends compute to the data: analyses execute inside each participating custodian's own infrastructure and every proposed output passes through an automated airlock (the "sixth safe") controlled by the data custodian rather than the vendor. The commercial platform, CloudOS, orchestrates Nextflow and WDL/Cromwell pipelines, interactive analysis sessions, projects, job queues and federated datasets, and exposes a REST API at https://cloudos.lifebit.ai/api (v1/v2/v3) authenticated with an apikey header. Lifebit publishes a first-party open-source Python client and command line interface, cloudos-cli, plus a GitHub Action wrapper. Product surface includes the federated TRE, Airlock Tower output disclosure control, an agentic federated TRE, AI-automated OMOP CDM v5.4 harmonisation, federated learning, a trusted data lakehouse and a trusted data marketplace. Publicly disclosed deployments include Genomics England, the US NIH National Library of Medicine, CanPath, Singapore Synapxe, Boehringer Ingelheim, Flatiron Health and 23andMe.

**Areas:** Company · Health · Genomics · Bioinformatics · Federated Learning · Trusted Research Environment · Data Governance · Life Sciences · Sovereign AI · OMOP · Workflow Orchestration

## Lifebit Biotech on APIs.io

Everything profiled for Lifebit Biotech is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/lifebit-biotech/](https://apis.io/providers/lifebit-biotech/)** — or go straight to one of the APIs or properties below.

### APIs (1)

- [Lifebit CloudOS API](https://apis.io/apis/lifebit-biotech/cloudos-api/) — The REST API behind the Lifebit Platform (CloudOS): manage workspace projects, job queues, workflows/pipelines, Nextflow and Cromwell/WDL job submission and…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [lifebit-cloudos](https://apis.io/servers/lifebit-biotech/lifebit-cloudos/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Lifebit Biotech Authentication](https://apis.io/security/lifebit-biotech/lifebit-biotech-authentication/)
- [Lifebit Biotech Domain Security](https://apis.io/security/lifebit-biotech/lifebit-biotech-domain-security/)
- [Lifebit Biotech Trust Center](https://apis.io/security/lifebit-biotech/lifebit-biotech-trust-center/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://lifebit.ai/)
- [Documentation](https://lifebit-ai.github.io/cloudos-cli/)
- [Getting started](https://lifebit-ai.github.io/cloudos-cli/getting_started.html)
- [API reference](https://lifebit-ai.github.io/cloudos-cli/cli.html)
- [Pricing](https://lifebit.ai/pricing/)
- [Support](https://lifebit.ai/contact-us/)
- [Blog](https://lifebit.ai/blog/)
- [Compliance](https://lifebit.ai/trust-center/)
- [Privacy policy](https://lifebit.ai/privacy-policy/)
- [GitHub](https://github.com/lifebit-ai)

## API Evangelist rating

**Kin Score 33.1** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 0.0 |
| Contract governance | 0.0 |
| Operational transparency | 18.4 |
| Developer ergonomics | 71.4 |
| Access clarity | 43.4 |

**Agent readiness 6.1** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 20.3** — Health

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/lifebit-biotech/](https://apis.io/providers/lifebit-biotech/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Lifebit Biotech: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/lifebit-biotech/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
