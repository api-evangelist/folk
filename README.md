# Folk (folk)

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
