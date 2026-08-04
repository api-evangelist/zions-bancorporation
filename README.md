# Zions Bancorporation (zions-bancorporation)

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
