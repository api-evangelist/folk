# Folk (folk)

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

Folk is a collaborative CRM platform designed for agencies, investors, and sales teams who need to manage relationships at scale. It provides a REST API organized around predictable resource-oriented URLs, accepting and returning JSON-encoded payloads with standard HTTP response codes. The API enables developers to manage contacts (people and companies), pipelines and deals, notes, reminders, interactions, and custom fields programmatically. Webhooks are supported for real-time event notifications, and the platform integrates with 5,000+ tools including Gmail, Outlook, LinkedIn, WhatsApp, and Zapier. API access is available on the Premium and Enterprise plans.

- **APIs.json:** https://raw.githubusercontent.com/api-evangelist/folk/refs/heads/main/apis.yml
- **Naftiko:** https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=folk-api-evangelist&utm_content=repo

## Tags

CRM, Contacts, Pipelines, Sales, Relationships, Notes, Deals, Webhooks

## APIs

| Name | Description | Base URL |
|------|-------------|----------|
| Folk API | REST API for managing people, companies, deals, notes, reminders, interactions, groups, webhooks, and users | https://api.folk.app |

## Plans / Rate Limits / FinOps

| Resource | Path |
|----------|------|
| Plans & Pricing | [plans/folk-plans-pricing.yml](plans/folk-plans-pricing.yml) |
| Rate Limits | [rate-limits/folk-rate-limits.yml](rate-limits/folk-rate-limits.yml) |
| FinOps | [finops/folk-finops.yml](finops/folk-finops.yml) |

**Pricing summary:**
- Standard: $24/user/month (annual) — no API access
- Premium: $48/user/month (annual) — API access included
- Enterprise: from $80/user/month (annual) — API access, custom limits, dedicated support

**Rate limits:** 600 requests/minute per user; headers: `X-RateLimit-Limit`, `X-RateLimit-Remaining`, `X-RateLimit-Reset`; HTTP 429 with `Retry-After` on exceeded limits.

## Timestamps

| Field | Value |
|-------|-------|
| Created | 2026-06-12 |
| Modified | 2026-06-12 |

## Common

| Type | URL |
|------|-----|
| Website | https://www.folk.app/ |
| Documentation | https://developer.folk.app/ |
| GitHub Org | https://github.com/folk-js |
| LinkedIn | https://www.linkedin.com/company/folkhq/ |
| Blog | https://www.folk.app/blog |
| Pricing | https://www.folk.app/pricing |
| Status Page | https://status.folk.app/ |
| X | https://twitter.com/FolkHQ |
| OpenAPI | https://developer.folk.app/api-reference/openapi.json |
| Changelog | https://www.folk.app/changelog |

## Maintainers

| Name | Email |
|------|-------|
| Kin Lane | kin@apievangelist.com |
