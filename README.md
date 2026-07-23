# Zions Bancorporation (zions-bancorporation)

Zions Bancorporation, National Association is a nationally chartered bank and bank holding company headquartered in Salt Lake City, Utah, with roughly $87 billion in total assets. It operates a single national bank charter across seven regional divisional brands - Zions Bank, Amegy Bank, California Bank & Trust, National Bank of Arizona, Nevada State Bank, Vectra Bank Colorado, and The Commerce Bank of Washington - serving consumer, small business, and commercial/treasury clients across the Western United States.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/zions-bancorporation/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/zions-bancorporation/refs/heads/main/apis.yml)

## Open-Finance / API Posture

Zions Bancorporation exposes **no public first-party developer API**. There is no developer portal:

- `developer.zionsbank.com`, `developer.zionsbancorporation.com`, and `api.zionsbank.com` do not resolve (DNS/connection failure).
- The business digital-banking surface, **Treasury Internet Banking** (login at `treasurygateway.zionsbank.com`), is credential-gated for existing commercial clients. It supports ACH, domestic/international wire transfers, account transfers, positive pay, real-time cash position, and ERP file import/export - but publishes **no public API reference and no downloadable OpenAPI/Swagger**.

As a large depository institution, Zions falls under the CFPB **Section 1033** Personal Financial Data Rights rule, but it has not published a first-party data-access API or a documented FDX-conformant endpoint. In practice, consumer-permissioned data sharing reaches Zions through third-party **aggregators** (Plaid, MX, Finicity, Akoya) rather than a first-party API. This record is therefore identity-only and honest: no public API surface was harvested.

## Tags

- Financial Services
- Banking
- United States
- Super-Regional Bank
- Treasury Management
- Open Finance
- Data Aggregation

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

None. No public first-party developer API is documented. See the open-finance posture above.

## Common Properties

- [Website](https://www.zionsbancorporation.com/)
- [Documentation](https://www.zionsbank.com/business/treasury/treasury-internet-banking/)
- [LinkedIn](https://www.linkedin.com/company/zions-bancorporation)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
