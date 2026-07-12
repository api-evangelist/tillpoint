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

### Tillpoint Point of Sale API

Logical Point of Sale capability - ringing up sales, applying discounts, splitting payments, issuing receipts and refunds, and reconciling tills. Endpoints modeled, not documented.

- **Human URL:** [https://www.tillpoint.com/](https://www.tillpoint.com/)

#### Tags

- Point of Sale
- POS
- Sales
- Retail

### Tillpoint Inventory API

Logical Inventory and Products capability - product catalog, variants, pricing, real-time stock levels, low-stock alerts, and multi-location transfers. Endpoints modeled, not documented.

- **Human URL:** [https://www.tillpoint.com/](https://www.tillpoint.com/)

#### Tags

- Inventory
- Products
- Stock
- Retail

### Tillpoint Customers (CRM) API

Logical Customers/CRM capability - customer records, purchase history, loyalty programs, and marketing sync (pushed to Mailchimp via a pre-built integration). Endpoints modeled, not documented.

- **Human URL:** [https://www.tillpoint.com/](https://www.tillpoint.com/)

#### Tags

- Customers
- CRM
- Loyalty
- Retail

### Tillpoint Accounting API

Logical Accounting capability - built-in double-entry accounting plus sync to QuickBooks Online and Xero through pre-built integrations. Endpoints modeled, not documented.

- **Human URL:** [https://www.tillpoint.com/](https://www.tillpoint.com/)

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
