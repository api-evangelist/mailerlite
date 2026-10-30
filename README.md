# MailerLite

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

MailerLite is an email marketing and automation platform used by creators, e-commerce sellers and small businesses to build lists, send campaigns and run behavioural automations. The current REST API at connect.mailerlite.com exposes subscribers, groups, segments, custom fields, campaigns, automations, forms, webhooks, batching, and a full e-commerce surface (shops, products, categories, customers, orders, carts) that drives abandoned-cart and post-purchase automations. Authentication is a bearer API key minted in the dashboard; responses are cursor-paginated and the API version can be pinned with an X-Version date header. Alongside the REST API, MailerLite ships six official SDKs, a first-party Go CLI with an interactive TUI, a published Agent Skill, and a hosted OAuth-protected MCP server at mcp.mailerlite.com exposing roughly 76 tools to AI assistants. A legacy Classic API v2 still serves older accounts.

**Areas:** Email Marketing · Automation · Newsletters · Subscribers · Campaigns · Webhook · E-Commerce · Segmentation · Transactional Email · MCP · Email

## MailerLite on APIs.io

Everything profiled for MailerLite is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/mailerlite/](https://apis.io/providers/mailerlite/)** — or go straight to one of the APIs or properties below.

### APIs (9)

- [MailerLite Classic API (Legacy)](https://apis.io/apis/mailerlite/mailerlite-classic-api/) — The MailerLite Classic API serves legacy MailerLite Classic accounts. New integrations should target the current API at connect.mailerlite.com. Corrected…
- [MailerLite Automations API](https://apis.io/apis/mailerlite/mailerlite-automations-api/) — The Automations API from MailerLite — 1 operation(s) for automations.
- [MailerLite Campaigns API](https://apis.io/apis/mailerlite/mailerlite-campaigns-api/) — The Campaigns API from MailerLite — 2 operation(s) for campaigns.
- [MailerLite Fields API](https://apis.io/apis/mailerlite/mailerlite-fields-api/) — The Fields API from MailerLite — 1 operation(s) for fields.
- [MailerLite Forms API](https://apis.io/apis/mailerlite/mailerlite-forms-api/) — The Forms API from MailerLite — 1 operation(s) for forms.
- [MailerLite Groups API](https://apis.io/apis/mailerlite/mailerlite-groups-api/) — The Groups API from MailerLite — 2 operation(s) for groups.
- [MailerLite Segments API](https://apis.io/apis/mailerlite/mailerlite-segments-api/) — The Segments API from MailerLite — 1 operation(s) for segments.
- [MailerLite Subscribers API](https://apis.io/apis/mailerlite/mailerlite-subscribers-api/) — The Subscribers API from MailerLite — 4 operation(s) for subscribers.
- [MailerLite Webhooks API](https://apis.io/apis/mailerlite/mailerlite-webhooks-api/) — The Webhooks API from MailerLite — 2 operation(s) for webhooks.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [MailerLite Webhooks](https://apis.io/asyncapis/mailerlite/mailerlite-webhooks-asyncapi/)

#### Event channels (1)

Individual events and webhooks the provider emits.

- [/](https://apis.io/channels/mailerlite/untitled/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [MailerLite MCP Server](https://apis.io/servers/mailerlite/mailerlite-mcp-server/)

#### Agent skills (1)

Agent skills built on the API.

- [MailerLite](https://apis.io/agent-skills/mailerlite/mailerlite/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Mailerlite Agentic Access](https://apis.io/agentic-access/mailerlite/mailerlite-agentic-access/)

#### Collections (9)

Postman and Open Collection request collections.

- [MailerLite API](https://apis.io/collections/mailerlite/open-mailerlite/)
- [MailerLite Automations API](https://apis.io/collections/mailerlite/open-mailerlite-automations-api/)
- [MailerLite Automations Campaigns API](https://apis.io/collections/mailerlite/open-mailerlite-campaigns-api/)
- [MailerLite Automations Fields API](https://apis.io/collections/mailerlite/open-mailerlite-fields-api/)
- [MailerLite Automations Forms API](https://apis.io/collections/mailerlite/open-mailerlite-forms-api/)
- [MailerLite Automations Groups API](https://apis.io/collections/mailerlite/open-mailerlite-groups-api/)
- [MailerLite Automations Segments API](https://apis.io/collections/mailerlite/open-mailerlite-segments-api/)
- [MailerLite Automations Subscribers API](https://apis.io/collections/mailerlite/open-mailerlite-subscribers-api/)
- [MailerLite Automations Webhooks API](https://apis.io/collections/mailerlite/open-mailerlite-webhooks-api/)

#### Overlays (16)

OpenAPI overlays, including conversational phrasing for each operation.

- [Mailerlite Automations Api Overlay](https://apis.io/overlays/mailerlite/mailerlite-automations-api-overlay/)
- [Mailerlite Automations Api Phrasing Overlay](https://apis.io/overlays/mailerlite/mailerlite-automations-api-phrasing-overlay/)
- [Mailerlite Campaigns Api Overlay](https://apis.io/overlays/mailerlite/mailerlite-campaigns-api-overlay/)
- [Mailerlite Campaigns Api Phrasing Overlay](https://apis.io/overlays/mailerlite/mailerlite-campaigns-api-phrasing-overlay/)
- [Mailerlite Fields Api Overlay](https://apis.io/overlays/mailerlite/mailerlite-fields-api-overlay/)
- [Mailerlite Fields Api Phrasing Overlay](https://apis.io/overlays/mailerlite/mailerlite-fields-api-phrasing-overlay/)
- [Mailerlite Forms Api Overlay](https://apis.io/overlays/mailerlite/mailerlite-forms-api-overlay/)
- [Mailerlite Forms Api Phrasing Overlay](https://apis.io/overlays/mailerlite/mailerlite-forms-api-phrasing-overlay/)
- [Mailerlite Groups Api Overlay](https://apis.io/overlays/mailerlite/mailerlite-groups-api-overlay/)
- [Mailerlite Groups Api Phrasing Overlay](https://apis.io/overlays/mailerlite/mailerlite-groups-api-phrasing-overlay/)
- [Mailerlite Segments Api Overlay](https://apis.io/overlays/mailerlite/mailerlite-segments-api-overlay/)
- [Mailerlite Segments Api Phrasing Overlay](https://apis.io/overlays/mailerlite/mailerlite-segments-api-phrasing-overlay/)
- [Mailerlite Subscribers Api Overlay](https://apis.io/overlays/mailerlite/mailerlite-subscribers-api-overlay/)
- [Mailerlite Subscribers Api Phrasing Overlay](https://apis.io/overlays/mailerlite/mailerlite-subscribers-api-phrasing-overlay/)
- [Mailerlite Webhooks Api Overlay](https://apis.io/overlays/mailerlite/mailerlite-webhooks-api-overlay/)
- [Mailerlite Webhooks Api Phrasing Overlay](https://apis.io/overlays/mailerlite/mailerlite-webhooks-api-phrasing-overlay/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [MailerLite — asyncapi rules](https://apis.io/rules/mailerlite/mailerlite-asyncapi-spectral-rules/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Mailerlite Authentication](https://apis.io/security/mailerlite/mailerlite-authentication/)
- [Mailerlite Domain Security](https://apis.io/security/mailerlite/mailerlite-domain-security/)
- [Mailerlite Trust Center](https://apis.io/security/mailerlite/mailerlite-trust-center/)
- [Mailerlite Vulnerability Disclosure](https://apis.io/security/mailerlite/mailerlite-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Mailerlite Plans Pricing](https://apis.io/plans/mailerlite/mailerlite-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Mailerlite Rate Limits](https://apis.io/rate-limits/mailerlite/mailerlite-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Mailerlite Finops](https://apis.io/finops/mailerlite/mailerlite-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.mailerlite.com/)
- [Documentation](https://developers.mailerlite.com/)
- [Getting started](https://developers.mailerlite.com/getting-started)
- [API reference](https://developers.mailerlite.com/api/subscribers)
- [Pricing](https://www.mailerlite.com/pricing)
- [Sign up](https://www.mailerlite.com/signup)
- [Support](https://www.mailerlite.com/help)
- [Blog](https://www.mailerlite.com/blog)
- [Security](https://www.mailerlite.com/legal/responsible-disclosure-program)
- [Compliance](https://www.mailerlite.com/trust-page)
- [Terms of service](https://www.mailerlite.com/legal/terms-of-service)
- [Privacy policy](https://www.mailerlite.com/legal/privacy-policy)
- [GitHub](https://github.com/mailerlite)
- [Status](https://status.mailerlite.com/)

## API Evangelist rating

**Kin Score 71.4** — exemplar · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 51.8 |
| Contract governance | 29.5 |
| Operational transparency | 57.9 |
| Developer ergonomics | 88.1 |
| Access clarity | 92.1 |

**Agent readiness 55.3** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | yes |
| Well Known Catalog | — |
| Consent Identity | yes |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 35.8** — Telecommunications

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/mailerlite/](https://apis.io/providers/mailerlite/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for MailerLite: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/mailerlite/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
