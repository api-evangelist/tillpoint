# Tillpoint (tillpoint)

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

Tillpoint is a modular, cloud-based EPOS (electronic point of sale) and business management platform for retail, hospitality, and services. A single subscription bundles 25+ modules - Point of Sale, Inventory, Customers/CRM, Staff, Accounting, Purchase Orders, and Reporting - and runs on anything from one register to thousands of locations.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/tillpoint/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/tillpoint/refs/heads/main/apis.yml)

## Access Model (Important)

As of this review (2026-07-11), **Tillpoint does not publish a documented public or partner developer API.** There is:

- No developer portal (no `developer.tillpoint.com`)
- No public API reference or OpenAPI
- No documented authentication, webhooks, or WebSocket endpoints

Third-party software directories confirm this: GetApp lists the API capability with zero mentions, and SaaSworthy and SoftwareWorld state Tillpoint does not provide an API. Programmatic connectivity is delivered through **pre-built integrations** rather than an open API:

- QuickBooks Online (accounting)
- Xero (accounting)
- WooCommerce (e-commerce)
- PayPal (payments)
- Worldpay (payments)
- Mailchimp (CRM / marketing sync)

Developer or partner-level programmatic access would require contacting Tillpoint directly.

The four API entries below are **logical capability areas** of the platform, catalogued so this provider surfaces for point-of-sale discovery. They are marked `endpointsModeled: true` and **no endpoints are fabricated**.

## Tags

- Point of Sale
- POS
- EPOS
- Retail
- Business Management
- Inventory
- Hospitality
- CRM
- Accounting

## Timestamps

- **Created:** 2026-07-11
- **Modified:** 2026-07-11

## APIs (Modeled Capability Areas)


#### Tags

- Point of Sale
- POS
- Sales
- Retail


#### Tags

- Inventory
- Products
- Stock
- Retail


#### Tags

- Customers
- CRM
- Loyalty
- Retail


#### Tags

- Accounting
- Finance
- Business Management

## Pricing

Tillpoint is a per-register monthly subscription bundling all 25+ modules, with a 14-day free trial. Entry pricing starts around GBP/USD 29 per register per month; a Multi-store plan (reported around USD 79/month billed annually) adds two terminals across unlimited locations and unlimited users. See [plans/tillpoint-plans-pricing.yml](plans/tillpoint-plans-pricing.yml).

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/tillpoint)
- [Website](https://www.tillpoint.com)
- [Documentation](https://www.tillpoint.com/pos-system-integration/)
- [Plans](plans/tillpoint-plans-pricing.yml)
- [Fin Ops](finops/tillpoint-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
