# Nhost (nhost)

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

Nhost is an open-source Firebase alternative that provides a fully managed backend platform built on PostgreSQL, GraphQL, and modern open-source tools. Developers get instant REST and GraphQL APIs auto-generated from their database schema, along with authentication supporting email/password, OAuth, magic links, WebAuthn, and one-time passwords. The platform includes S3-compatible file storage with CDN delivery and image transformation, serverless functions deployable as HTTP endpoints, and real-time GraphQL subscriptions. Nhost also offers a local development CLI, GitHub-based automated deployments, an AI toolkit with auto-embeddings and assistants, and managed container services—enabling teams to launch production-ready backends without infrastructure management.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/nhost/refs/heads/main/apis.yml
- Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=nhost-api-evangelist&utm_content=repo

## Tags

GraphQL, PostgreSQL, Authentication, File Storage, Serverless Functions, Real-Time, Open Source, Firebase Alternative, Backend as a Service, BaaS

## APIs

| Name | Description | Documentation |
|------|-------------|---------------|
| GraphQL API | Instant real-time GraphQL auto-generated from PostgreSQL via Hasura | https://docs.nhost.io/products/graphql/ |
| Authentication API | Full-featured auth with email, OAuth2, WebAuthn, magic links, SMS OTP | https://docs.nhost.io/products/auth/ |
| Storage API | S3-compatible file storage with CDN, image transforms, and antivirus | https://docs.nhost.io/products/storage/ |
| Serverless Functions API | JS/TS HTTP endpoints deployed from GitHub, used for webhooks and logic | https://docs.nhost.io/products/functions/ |
| AI API | GraphQL-based assistant management, auto-embeddings, and vector search | https://docs.nhost.io/products/ai/ |

## Plans / Rate Limits / FinOps

| Resource | Details |
|----------|---------|
| Plans | [plans/nhost-plans-pricing.yml](plans/nhost-plans-pricing.yml) |
| Rate Limits | [rate-limits/nhost-rate-limits.yml](rate-limits/nhost-rate-limits.yml) |
| FinOps | [finops/nhost-finops.yml](finops/nhost-finops.yml) |

**Plan summary:**

| Plan | Price | DB | Storage | Egress |
|------|-------|----|---------|--------|
| Starter | Free | 1 GB | 1 GB | 5 GB |
| Pro | $25/mo | 10 GB | 50 GB | 50 GB |
| Team | $599/mo | 10 GB | 50 GB | 50 GB |
| Enterprise | Custom | Custom | Custom | Custom |

**Default rate limits:** 100 requests per 15 minutes per IP for GraphQL, Storage, and Functions; Auth uses tiered limits (10/hour for email/SMS, 100/min global cap).

## Timestamps

- Created: 2026-06-12
- Modified: 2026-06-12

## Common

| Type | URL |
|------|-----|
| Website | https://nhost.io/ |
| Documentation | https://docs.nhost.io/ |
| GitHub Org | https://github.com/nhost |
| LinkedIn | https://www.linkedin.com/company/nhost |
| Blog | https://nhost.io/blog |
| Pricing | https://nhost.io/pricing |
| Status Page | https://status.nhost.io/ |
| X (Twitter) | https://twitter.com/nhost |

## Maintainers

- Kin Lane — kin@apievangelist.com
