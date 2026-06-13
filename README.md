# Nhost (nhost)

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
