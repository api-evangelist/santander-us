# Santander US (santander-us)

Santander Bank, N.A. (santanderbank.com) is the US retail and commercial banking subsidiary of Spain's Banco Santander S.A., headquartered in Boston, Massachusetts. It is a nationally chartered bank (National Association, regulated by the OCC) operating a branch network across the Northeast US, positioning it as a super-regional bank.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/santander-us/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/santander-us/refs/heads/main/apis.yml)

## Open-Finance / API Posture

The US retail franchise (Santander Bank, N.A.) exposes **no public, first-party developer API**. `developer.santanderbank.com` does not resolve, `santanderbank.com/developers` and `santanderbank.com/api` return 404, and the site's sitemap publishes no developer, API, or open-banking pages.

US open finance is voluntary and fragmented — there is no single mandated open-banking contract as in the UK or Australia. Santander US's consumer-permissioned data is reached today through **aggregators rather than a direct API**:

- **Plaid** supports "Santander - Personal" for Assets, Auth, Balance, and Transactions.
- No documented first-party FDX (Financial Data Exchange) participation or published CFPB Section 1033 posture was found for the US retail entity; broader US data sharing is moving industry-wide through aggregator networks (Plaid; FDX/Akoya).
- No downloadable OpenAPI/Swagger specification is published for the US entity.

Note on related-but-distinct entities: Santander's **UK developer portal** ([developer.santander.co.uk](https://developer.santander.co.uk/sanuk/external/)) and the group's **Corporate & Investment Banking API marketplace** ([apimarket.santandercib.com](https://apimarket.santandercib.com/scib/external/api)) are operated by separate Banco Santander legal entities and are **not** the US retail bank's surface. They are intentionally not listed as Santander US APIs.

## Tags

- Financial Services
- Banking
- United States
- Super-Regional Bank
- Retail Banking
- Open Finance
- Data Aggregation

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

No public first-party developer APIs. `apis[]` is intentionally empty — Santander US consumer data access is aggregator-mediated (see Plaid above), not a documented first-party API surface.

## Common Properties

- [Website](https://www.santanderbank.com)
- [LinkedIn](https://www.linkedin.com/company/santander-bank-na)
- [Privacy Policy](https://www.santanderbank.com/online-privacy-policy)
- [Terms of Service](https://www.santanderbank.com/terms-and-conditions)
- [Support / Security Center](https://www.santanderbank.com/personal/security-center)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
