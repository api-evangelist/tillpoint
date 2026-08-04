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
