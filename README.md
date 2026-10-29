# Appcharge

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

Appcharge is a monetization and payments platform (merchant of record) for mobile game publishers. It lets studios sell in-game offers direct-to-consumer outside the app stores through a hosted web store, a mobile Checkout SDK, and Payment Links — covering checkout sessions, price localization, coupons and promo codes, refunds, web-store offers (bundles, daily bonuses, rolling/special offers, progress bars, reward calendars, triggered popups), offer components, game-portal content, media assets, translations, financial and analytics reporting, and player personalization/authentication callbacks. The REST API authenticates with an x-publisher-token API-key header; webhooks and Appcharge-to-publisher callbacks are HMAC-SHA256 signed with a replay window; and a hosted MCP server exposes agent access over OAuth 2.0 (authorization_code + PKCE).

**Areas:** Company · Payments · Monetization · Merchant of Record · Mobile Games · Gaming · Checkout · In-Game Purchases · Web Store · E-Commerce

## Appcharge on APIs.io

Everything profiled for Appcharge is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/appcharge/](https://apis.io/providers/appcharge/)** — or go straight to one of the APIs or properties below.

### APIs (17)

- [Appcharge Assets API](https://apis.io/apis/appcharge/appcharge-assets-api/) — The Assets API from Appcharge — 2 operation(s) for assets.
- [Appcharge Authentication API](https://apis.io/apis/appcharge/appcharge-authentication-api/) — The Authentication API from Appcharge — 2 operation(s) for authentication.
- [Appcharge Badges API](https://apis.io/apis/appcharge/appcharge-badges-api/) — The Badges API from Appcharge — 2 operation(s) for badges.
- [Appcharge Coupons API](https://apis.io/apis/appcharge/appcharge-coupons-api/) — The Coupons API from Appcharge — 2 operation(s) for coupons.
- [Appcharge General API](https://apis.io/apis/appcharge/appcharge-general-api/) — The General API from Appcharge — 9 operation(s) for general.
- [Appcharge Localization API](https://apis.io/apis/appcharge/appcharge-localization-api/) — The Localization API from Appcharge — 1 operation(s) for localization.
- [Appcharge Offer Designs API](https://apis.io/apis/appcharge/appcharge-offer-designs-api/) — The Offer Designs API from Appcharge — 2 operation(s) for offer designs.
- [Appcharge Offers API](https://apis.io/apis/appcharge/appcharge-offers-api/) — The Offers API from Appcharge — 5 operation(s) for offers.
- [Appcharge Orders API](https://apis.io/apis/appcharge/appcharge-orders-api/) — The Orders API from Appcharge — 1 operation(s) for orders.
- [Appcharge Personalization API](https://apis.io/apis/appcharge/appcharge-personalization-api/) — The Personalization API from Appcharge — 1 operation(s) for personalization.
- [Appcharge Popups API](https://apis.io/apis/appcharge/appcharge-popups-api/) — The Popups API from Appcharge — 1 operation(s) for popups.
- [Appcharge Portal Content API](https://apis.io/apis/appcharge/appcharge-portal-content-api/) — The Portal Content API from Appcharge — 4 operation(s) for portal content.
- [Appcharge Products API](https://apis.io/apis/appcharge/appcharge-products-api/) — The Products API from Appcharge — 2 operation(s) for products.
- [Appcharge Promo Codes API](https://apis.io/apis/appcharge/appcharge-promo-codes-api/) — The Promo Codes API from Appcharge — 3 operation(s) for promo codes.
- [Appcharge Rolling Offers API](https://apis.io/apis/appcharge/appcharge-rolling-offers-api/) — The Rolling Offers API from Appcharge — 2 operation(s) for rolling offers.
- [Appcharge Store Refresh Popups API](https://apis.io/apis/appcharge/appcharge-store-refresh-popups-api/) — The Store Refresh Popups API from Appcharge — 2 operation(s) for store refresh popups.
- [Appcharge Triggered Popups API](https://apis.io/apis/appcharge/appcharge-triggered-popups-api/) — The Triggered Popups API from Appcharge — 2 operation(s) for triggered popups.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Appcharge Events (V2) Webhooks](https://apis.io/asyncapis/appcharge/appcharge-events-asyncapi/)

#### Event channels (32)

Individual events and webhooks the provider emits.

- [/{publisherWebhookUrl}](https://apis.io/channels/appcharge/appcharge-events-v2-webhooks-publisherwebhookurl/)
- [/{publisherWebhookUrl}](https://apis.io/channels/appcharge/appcharge-events-v2-webhooks-publisherwebhookurl-10/)
- [/{publisherWebhookUrl}](https://apis.io/channels/appcharge/appcharge-events-v2-webhooks-publisherwebhookurl-11/)
- [/{publisherWebhookUrl}](https://apis.io/channels/appcharge/appcharge-events-v2-webhooks-publisherwebhookurl-12/)
- [/{publisherWebhookUrl}](https://apis.io/channels/appcharge/appcharge-events-v2-webhooks-publisherwebhookurl-13/)
- [/{publisherWebhookUrl}](https://apis.io/channels/appcharge/appcharge-events-v2-webhooks-publisherwebhookurl-14/)
- [/{publisherWebhookUrl}](https://apis.io/channels/appcharge/appcharge-events-v2-webhooks-publisherwebhookurl-15/)
- [/{publisherWebhookUrl}](https://apis.io/channels/appcharge/appcharge-events-v2-webhooks-publisherwebhookurl-16/)
- [/{publisherWebhookUrl}](https://apis.io/channels/appcharge/appcharge-events-v2-webhooks-publisherwebhookurl-17/)
- [/{publisherWebhookUrl}](https://apis.io/channels/appcharge/appcharge-events-v2-webhooks-publisherwebhookurl-18/)
- [/{publisherWebhookUrl}](https://apis.io/channels/appcharge/appcharge-events-v2-webhooks-publisherwebhookurl-19/)
- [/{publisherWebhookUrl}](https://apis.io/channels/appcharge/appcharge-events-v2-webhooks-publisherwebhookurl-2/)
- [/{publisherWebhookUrl}](https://apis.io/channels/appcharge/appcharge-events-v2-webhooks-publisherwebhookurl-20/)
- [/{publisherWebhookUrl}](https://apis.io/channels/appcharge/appcharge-events-v2-webhooks-publisherwebhookurl-21/)
- [/{publisherWebhookUrl}](https://apis.io/channels/appcharge/appcharge-events-v2-webhooks-publisherwebhookurl-22/)
- [/{publisherWebhookUrl}](https://apis.io/channels/appcharge/appcharge-events-v2-webhooks-publisherwebhookurl-23/)
- [/{publisherWebhookUrl}](https://apis.io/channels/appcharge/appcharge-events-v2-webhooks-publisherwebhookurl-24/)
- [/{publisherWebhookUrl}](https://apis.io/channels/appcharge/appcharge-events-v2-webhooks-publisherwebhookurl-25/)
- [/{publisherWebhookUrl}](https://apis.io/channels/appcharge/appcharge-events-v2-webhooks-publisherwebhookurl-26/)
- [/{publisherWebhookUrl}](https://apis.io/channels/appcharge/appcharge-events-v2-webhooks-publisherwebhookurl-27/)
- [/{publisherWebhookUrl}](https://apis.io/channels/appcharge/appcharge-events-v2-webhooks-publisherwebhookurl-28/)
- [/{publisherWebhookUrl}](https://apis.io/channels/appcharge/appcharge-events-v2-webhooks-publisherwebhookurl-29/)
- [/{publisherWebhookUrl}](https://apis.io/channels/appcharge/appcharge-events-v2-webhooks-publisherwebhookurl-3/)
- [/{publisherWebhookUrl}](https://apis.io/channels/appcharge/appcharge-events-v2-webhooks-publisherwebhookurl-30/)
- [/{publisherWebhookUrl}](https://apis.io/channels/appcharge/appcharge-events-v2-webhooks-publisherwebhookurl-31/)
- …and 7 more published on APIs.io

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [appcharge](https://apis.io/servers/appcharge/appcharge/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Appcharge Agentic Access](https://apis.io/agentic-access/appcharge/appcharge-agentic-access/)

#### Collections (34)

Postman and Open Collection request collections.

- [Appcharge Assets API](https://apis.io/collections/appcharge/open-appcharge-assets-api/)
- [Appcharge Assets Authentication API](https://apis.io/collections/appcharge/open-appcharge-authentication-api/)
- [Appcharge Assets Badges API](https://apis.io/collections/appcharge/open-appcharge-badges-api/)
- [Appcharge Assets Coupons API](https://apis.io/collections/appcharge/open-appcharge-coupons-api/)
- [Appcharge Assets General API](https://apis.io/collections/appcharge/open-appcharge-general-api/)
- [Appcharge Assets Localization API](https://apis.io/collections/appcharge/open-appcharge-localization-api/)
- [Appcharge Assets Offer Designs API](https://apis.io/collections/appcharge/open-appcharge-offer-designs-api/)
- [Appcharge Assets Offers API](https://apis.io/collections/appcharge/open-appcharge-offers-api/)
- [Appcharge Assets Orders API](https://apis.io/collections/appcharge/open-appcharge-orders-api/)
- [Appcharge Assets Personalization API](https://apis.io/collections/appcharge/open-appcharge-personalization-api/)
- [Appcharge Assets Popups API](https://apis.io/collections/appcharge/open-appcharge-popups-api/)
- [Appcharge Assets Portal Content API](https://apis.io/collections/appcharge/open-appcharge-portal-content-api/)
- [Appcharge Assets Products API](https://apis.io/collections/appcharge/open-appcharge-products-api/)
- [Appcharge Assets Promo Codes API](https://apis.io/collections/appcharge/open-appcharge-promo-codes-api/)
- [Appcharge Assets Rolling Offers API](https://apis.io/collections/appcharge/open-appcharge-rolling-offers-api/)
- [Appcharge Assets Store Refresh Popups API](https://apis.io/collections/appcharge/open-appcharge-store-refresh-popups-api/)
- [Appcharge Assets Triggered Popups API](https://apis.io/collections/appcharge/open-appcharge-triggered-popups-api/)
- [Appcharge Assets API](https://apis.io/collections/appcharge/postman-appcharge-assets-api/)
- [Appcharge Assets Authentication API](https://apis.io/collections/appcharge/postman-appcharge-authentication-api/)
- [Appcharge Assets Badges API](https://apis.io/collections/appcharge/postman-appcharge-badges-api/)
- [Appcharge Assets Coupons API](https://apis.io/collections/appcharge/postman-appcharge-coupons-api/)
- [Appcharge Assets General API](https://apis.io/collections/appcharge/postman-appcharge-general-api/)
- [Appcharge Assets Localization API](https://apis.io/collections/appcharge/postman-appcharge-localization-api/)
- [Appcharge Assets Offer Designs API](https://apis.io/collections/appcharge/postman-appcharge-offer-designs-api/)
- [Appcharge Assets Offers API](https://apis.io/collections/appcharge/postman-appcharge-offers-api/)
- …and 9 more published on APIs.io

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Appcharge Openapi Overlay](https://apis.io/overlays/appcharge/appcharge-openapi-overlay/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Appcharge Authentication](https://apis.io/security/appcharge/appcharge-authentication/)
- [Appcharge Domain Security](https://apis.io/security/appcharge/appcharge-domain-security/)
- [Appcharge Trust Center](https://apis.io/security/appcharge/appcharge-trust-center/)
- [Appcharge Vulnerability Disclosure](https://apis.io/security/appcharge/appcharge-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Appcharge Scopes](https://apis.io/scopes/appcharge/appcharge-scopes/)

#### Rate limits (1)

Published request limits.

- [Appcharge Rate Limits](https://apis.io/rate-limits/appcharge/appcharge-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://appcharge.com/)
- [Documentation](https://docs.appcharge.com/)
- [API reference](https://docs.appcharge.com/api-reference/introduction)
- [Sign up](https://dashboard.appcharge.com)
- [Support](https://help.appcharge.com/hc/en-us)
- [Blog](https://www.appcharge.com/blog)
- [Security](https://docs.appcharge.com/merchant-of-record/security/about-security-at-appcharge)
- [Compliance](https://docs.appcharge.com/merchant-of-record/security/about-security-at-appcharge)
- [Terms of service](https://www.appcharge.com/tc)
- [Privacy policy](https://www.appcharge.com/privacy-policy)
- [GitHub](https://github.com/Appcharge)
- [Status](https://appcharge.instatus.com)

## API Evangelist rating

**Kin Score 61.9** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 60.6 |
| Contract governance | 18.2 |
| Operational transparency | 65.8 |
| Developer ergonomics | 67.9 |
| Access clarity | 36.8 |

**Agent readiness 60.1** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | verified |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | yes |
| Agent Skills | yes |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | mostly |

**Regulatory alignment 41.1** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/appcharge/](https://apis.io/providers/appcharge/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Appcharge: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/appcharge/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
