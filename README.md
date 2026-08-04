# Drone (drone)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Drone is an open-source, container-native continuous integration and continuous delivery platform that automates software build, testing, and deployment pipelines entirely through Docker containers. Acquired by Harness in 2021, Drone enables development teams to define pipelines as code using simple YAML configuration files committed alongside their source code. The platform provides a comprehensive REST API for managing builds, repositories, secrets, cron jobs, templates, and user accounts in both self-hosted and cloud deployments. Drone supports multiple source control providers including GitHub, GitHub Enterprise, Bitbucket, and GitLab, and is available as a free open-source edition (Apache 2 license) or a paid enterprise edition for larger organizations.

**APIs.json:** https://raw.githubusercontent.com/api-evangelist/drone/refs/heads/main/apis.yml

**Naftiko:** https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=drone-api-evangelist&utm_content=repo

## Tags

- CI/CD
- Continuous Integration
- Continuous Delivery
- DevOps
- Containers
- Docker
- Build Automation
- Open Source
- Self-Hosted

## APIs

### Drone REST API

The Drone REST API provides programmatic access to the Drone CI/CD platform, enabling management of builds, repositories, secrets, cron jobs, templates, and user accounts. Authentication is performed using bearer tokens retrieved from the Drone user interface profile page. The API supports operations across seven resource categories: builds, cron jobs, repositories, secrets, templates, individual user profile, and administrative user management.

- **Documentation:** https://docs.drone.io/api/overview/
- **Base URL:** https://your-drone-server/api

**API Resources:**

| Resource | Operations |
|----------|-----------|
| Builds | approve, create, decline, list, logs, promote, restart, stop |
| Cron | create, delete, get, list, trigger, update |
| Repos | change owner, enable, disable, get, list, repair, update |
| Secrets | create, delete, get, list, update |
| Templates | create, delete, get, list, update |
| User | get feed, get info, get repos, sync |
| Users (admin) | create, delete, get, list, update |

## Plans, Rate Limits, and FinOps

| Resource | File |
|----------|------|
| Plans and Pricing | [plans/drone-plans-pricing.yml](plans/drone-plans-pricing.yml) |
| Rate Limits | [rate-limits/drone-rate-limits.yml](rate-limits/drone-rate-limits.yml) |
| FinOps | [finops/drone-finops.yml](finops/drone-finops.yml) |

**Pricing Summary:**

| Plan | Price | Notes |
|------|-------|-------|
| Open Source Edition | Free | Apache 2 license, self-hosted, single machine |
| Enterprise Edition (Free Tier) | Free | For orgs under $1M annual revenue |
| Enterprise Edition (Paid) | From $299/month | For orgs over $1M annual revenue |

## Timestamps

- **Created:** 2026-06-12
- **Modified:** 2026-06-12

## Common

| Type | URL |
|------|-----|
| Website | https://www.drone.io/ |
| Documentation | https://docs.drone.io/ |
| GitHub Org | https://github.com/drone |
| LinkedIn | https://www.linkedin.com/company/drone-io |
| Blog | https://blog.drone.io |
| Pricing | https://docs.drone.io/enterprise/ |
| X (Twitter) | https://twitter.com/droneio |

## Maintainers

| Name | Email |
|------|-------|
| Kin Lane | kin@apievangelist.com |
