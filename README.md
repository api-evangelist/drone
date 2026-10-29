# Drone

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

Drone is an open-source, container-native continuous integration and continuous delivery platform that automates software build, testing, and deployment pipelines entirely through Docker containers. Acquired by Harness in 2021, Drone enables development teams to define pipelines as code using simple YAML configuration files committed alongside their source code. The platform provides a comprehensive REST API for managing builds, repositories, secrets, cron jobs, templates, and user accounts in both self-hosted and cloud deployments. Drone supports multiple source control providers including GitHub, GitHub Enterprise, Bitbucket, and GitLab, and is available as a free open-source edition (Apache 2 license) or a paid enterprise edition for larger organizations.

**Areas:** CI/CD · Continuous Integration · Continuous Delivery · DevOps · Containers · Docker · Build Automation · Open Source · Self-Hosted

## Drone on APIs.io

Everything profiled for Drone is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/drone/](https://apis.io/providers/drone/)** — or go straight to one of the APIs or properties below.

### APIs (11)

- [Drone Builds API](https://apis.io/apis/drone/drone-builds-api/) — Build creation, management, and log access.
- [Drone Cron API](https://apis.io/apis/drone/drone-cron-api/) — Cron job scheduling for automated builds.
- [Drone Nodes API](https://apis.io/apis/drone/drone-nodes-api/) — Runner node management.
- [Drone Queue API](https://apis.io/apis/drone/drone-queue-api/) — Build queue management.
- [Drone Repos API](https://apis.io/apis/drone/drone-repos-api/) — Repository activation and management.
- [Drone Secrets API](https://apis.io/apis/drone/drone-secrets-api/) — Secret variable management for repos and organizations.
- [Drone System API](https://apis.io/apis/drone/drone-system-api/) — System information.
- [Drone Templates API](https://apis.io/apis/drone/drone-templates-api/) — Reusable pipeline template management.
- [Drone User API](https://apis.io/apis/drone/drone-user-api/) — Current authenticated user operations.
- [Drone Users API](https://apis.io/apis/drone/drone-users-api/) — User account management (admin).
- [Drone Server REST API](https://apis.io/apis/drone/rest/) — Bearer-token authenticated REST API exposed by every Drone server. Endpoints under /api/ for repos, builds, cron, secrets, users, templates, logs and queue…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Drone Agentic Access](https://apis.io/agentic-access/drone/drone-agentic-access/)

#### JSON Schema (3)

The data models the API reads and writes.

- [Build](https://apis.io/schemas/drone/drone-build/)
- [Repository](https://apis.io/schemas/drone/drone-repo/)
- [Secret](https://apis.io/schemas/drone/drone-secret/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Drone Context](https://apis.io/jsonld/drone/drone-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Drone CI/CD Vocabulary](https://apis.io/vocabularies/drone/drone-vocabulary/)

#### Examples (3)

Example requests and responses.

- [Drone Build Example](https://apis.io/examples/drone/drone-build-example/)
- [Drone Repo Example](https://apis.io/examples/drone/drone-repo-example/)
- [Drone Secret Example](https://apis.io/examples/drone/drone-secret-example/)

#### Collections (10)

Postman and Open Collection request collections.

- [Drone REST Builds API](https://apis.io/collections/drone/open-drone-builds-api/)
- [Drone REST Builds Cron API](https://apis.io/collections/drone/open-drone-cron-api/)
- [Drone REST Builds Nodes API](https://apis.io/collections/drone/open-drone-nodes-api/)
- [Drone REST Builds Queue API](https://apis.io/collections/drone/open-drone-queue-api/)
- [Drone REST Builds Repos API](https://apis.io/collections/drone/open-drone-repos-api/)
- [Drone REST Builds Secrets API](https://apis.io/collections/drone/open-drone-secrets-api/)
- [Drone REST Builds System API](https://apis.io/collections/drone/open-drone-system-api/)
- [Drone REST Builds Templates API](https://apis.io/collections/drone/open-drone-templates-api/)
- [Drone REST Builds User API](https://apis.io/collections/drone/open-drone-user-api/)
- [Drone REST Builds Users API](https://apis.io/collections/drone/open-drone-users-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Drone — jsonschema rules](https://apis.io/rules/drone/drone-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Drone Authentication](https://apis.io/security/drone/drone-authentication/)
- [Drone Domain Security](https://apis.io/security/drone/drone-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Drone Plans Pricing](https://apis.io/plans/drone/drone-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Drone Rate Limits](https://apis.io/rate-limits/drone/drone-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Drone Finops](https://apis.io/finops/drone/drone-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.drone.io/)
- [Documentation](https://docs.drone.io/)
- [Pricing](https://docs.drone.io/enterprise/)
- [Blog](https://blog.drone.io)

## API Evangelist rating

**Kin Score 33.5** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 55.9 |
| Contract governance | 23.5 |
| Operational transparency | 5.3 |
| Developer ergonomics | 31.0 |
| Access clarity | 18.4 |

**Agent readiness 19.6** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 16.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/drone/](https://apis.io/providers/drone/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Drone: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/drone/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
