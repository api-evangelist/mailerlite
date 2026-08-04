# MailerLite (mailerlite)

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

MailerLite is an email marketing and automation platform. The current REST API exposes subscribers, groups, segments, fields, campaigns, automations, forms, webhooks, and more, with a deprecated Classic API still serving legacy accounts.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/mailerlite/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/mailerlite/refs/heads/main/apis.yml)

## Tags

- Email Marketing
- Automation
- Newsletters
- Subscribers

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-30

## APIs

### MailerLite API

The MailerLite REST API supports Bearer-token authentication using account-issued API keys. It exposes subscribers, groups, segments, fields, campaigns, automations, forms, webhooks, batched requests, and more. Versioning is controlled with the X-Version header.

- **Human URL:** [https://developers.mailerlite.com/docs/](https://developers.mailerlite.com/docs/)
- **Base URL:** `https://connect.mailerlite.com/api`

#### Tags

- Email Marketing
- Subscribers
- Campaigns
- Automations
- Forms
- Webhooks

#### Properties

- [Documentation](https://developers.mailerlite.com/docs/)
- [Authentication](https://developers.mailerlite.com/docs/#authentication)
- [OpenAPI](openapi/mailerlite-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mailerlite.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mailerlite.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/mailerlite-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [SDK](https://github.com/mailerlite/mailerlite-php)
- [SDK](https://github.com/mailerlite/mailerlite-nodejs)
- [SDK](https://github.com/mailerlite/mailerlite-python)
- [SDK](https://github.com/mailerlite/mailerlite-go)
- [SDK](https://github.com/mailerlite/mailerlite-ruby)

### MailerLite Classic API (Legacy)

The MailerLite Classic API serves legacy MailerLite Classic accounts. New integrations should target the current API at connect.mailerlite.com.

- **Human URL:** [https://classic.developers.mailerlite.com/](https://classic.developers.mailerlite.com/)
- **Base URL:** `https://api.mailerlite.com/api/v2`

#### Tags

- Email Marketing
- Legacy
- Deprecated

#### Properties

- [Documentation](https://classic.developers.mailerlite.com/)
- [Postman Collection](collections/mailerlite.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mailerlite.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/mailerlite-international)
- [Website](https://www.mailerlite.com/)
- [Portal](https://developers.mailerlite.com/)
- [GitHub Organization](https://github.com/mailerlite)
- [Pricing](https://www.mailerlite.com/pricing)
- [Plans](plans/mailerlite-plans-pricing.yml)
- [Rate Limits](rate-limits/mailerlite-rate-limits.yml)
- [Fin Ops](finops/mailerlite-finops.yml)
- [Integrations](https://www.mailerlite.com/integrations)
- [M C P Server](https://github.com/mailerlite/canny-mcp-server)
- [Agent Skill](https://github.com/mailerlite/mailerlite-skills)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
