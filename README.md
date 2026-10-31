# PagBank

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

PagBank (formerly PagSeguro) is a Brazilian digital bank and payment platform operated by PagoSeguro Internet Instituição de Pagamento S/A, a subsidiary of Universo Online (UOL). It provides REST APIs for Pix instant transfers, credit and debit card processing, e-commerce checkout, boleto bancário, recurring payments, POS terminal integration, and financial account management. PagBank serves e-commerce merchants, SaaS platforms, and marketplaces across Brazil and supports over 29.5 million customers.

**Areas:** Payments · Digital Banking · Brazil · Pix · Fintech · E-Commerce · Point-of-Sale · Recurring Payments · Boleto

## PagBank on APIs.io

Everything profiled for PagBank is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/pagbank/](https://apis.io/providers/pagbank/)** — or go straight to one of the APIs or properties below.

### APIs (18)

- [PagBank PIX API](https://apis.io/apis/pagbank/pagbank-pix-api/) — Dedicated API for PIX instant payment infrastructure in Brazil. Supports immediate charge creation via QR codes, payment receipt confirmation, and real-time…
- [PagBank Recurring Payments API](https://apis.io/apis/pagbank/pagbank-recurring-payments-api/) — Subscription billing API for managing recurring charges. Handles subscription creation, billing cycles, payment method updates, and recurring payment…
- [PagBank Boleto API](https://apis.io/apis/pagbank/boleto/) — Boleto Bancário issuance and collection. Generates a printable / scannable boleto tied to an Order, with status callbacks once the buyer pays at a bank,…
- [PagBank Marketplace / Split API](https://apis.io/apis/pagbank/split/) — Payment-division (split) settlement for marketplaces and platforms. Splits a single charge across multiple receivers (with optional custody / release…
- [PagBank EDI API](https://apis.io/apis/pagbank/edi/) — Electronic Data Interchange surface for downloading transaction and settlement statements for reconciliation — a structured replacement for manual CSV/PDF…
- [PagBank Digital Certificate (mTLS) API](https://apis.io/apis/pagbank/certificates/) — Issues digital certificates for mTLS authentication, layered on top of bearer-token auth for higher-trust integrations and sensitive payouts / Pix Bacen flows.
- [PagBank Accounts API](https://apis.io/apis/pagbank/pagbank-accounts-api/) — The Accounts API from PagBank — 2 operation(s) for accounts.
- [PagBank Charges API](https://apis.io/apis/pagbank/pagbank-charges-api/) — The Charges API from PagBank — 4 operation(s) for charges.
- [PagBank Checkout API](https://apis.io/apis/pagbank/pagbank-checkout-api/) — The Checkout API from PagBank — 4 operation(s) for checkout.
- [PagBank Connect API](https://apis.io/apis/pagbank/pagbank-connect-api/) — The Connect API from PagBank — 6 operation(s) for connect.
- [PagBank Coupons API](https://apis.io/apis/pagbank/pagbank-coupons-api/) — The Coupons API from PagBank — 2 operation(s) for coupons.
- [PagBank Invoices API](https://apis.io/apis/pagbank/pagbank-invoices-api/) — The Invoices API from PagBank — 2 operation(s) for invoices.
- [PagBank Orders API](https://apis.io/apis/pagbank/pagbank-orders-api/) — The Orders API from PagBank — 2 operation(s) for orders.
- [PagBank Plans API](https://apis.io/apis/pagbank/pagbank-plans-api/) — The Plans API from PagBank — 4 operation(s) for plans.
- [PagBank Public Keys API](https://apis.io/apis/pagbank/pagbank-public-keys-api/) — The Public Keys API from PagBank — 2 operation(s) for public keys.
- [PagBank Refunds API](https://apis.io/apis/pagbank/pagbank-refunds-api/) — The Refunds API from PagBank — 2 operation(s) for refunds.
- [PagBank Subscribers API](https://apis.io/apis/pagbank/pagbank-subscribers-api/) — The Subscribers API from PagBank — 3 operation(s) for subscribers.
- [PagBank Subscriptions API](https://apis.io/apis/pagbank/pagbank-subscriptions-api/) — The Subscriptions API from PagBank — 5 operation(s) for subscriptions.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Pagbank Domain Security](https://apis.io/security/pagbank/pagbank-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Pagbank Plans Pricing](https://apis.io/plans/pagbank/pagbank-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Pagbank Rate Limits](https://apis.io/rate-limits/pagbank/pagbank-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Pagbank Finops](https://apis.io/finops/pagbank/pagbank-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://pagbank.com.br/)
- [Documentation](https://developer.pagbank.com.br/docs/apis-pagbank)
- [Getting started](https://developer.pagbank.com.br/docs/primeiros-passos)
- [API reference](https://developer.pagbank.com.br/reference/introducao)
- [Pricing](https://pagbank.com.br/)
- [Blog](https://developer.pagbank.com.br/changelog)
- [Status](https://status.pagbank.com.br/)

## API Evangelist rating

**Kin Score 26.8** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 45.3 |
| Contract governance | 0.0 |
| Operational transparency | 21.1 |
| Developer ergonomics | 26.2 |
| Access clarity | 15.8 |

**Agent readiness 17.8** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
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

**Regulatory alignment 5.4** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/pagbank/](https://apis.io/providers/pagbank/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for PagBank: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/pagbank/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
