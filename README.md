# Drone (drone)

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
