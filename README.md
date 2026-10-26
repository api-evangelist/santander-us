# Santander US (santander-us)

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
