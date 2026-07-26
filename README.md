# Tillpoint (tillpoint)

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
