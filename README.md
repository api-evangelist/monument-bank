# Monument Bank (monument-bank)

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

Monument Bank Limited is a UK challenger bank headquartered at 33 Cavendish Square, London, purpose-built for the "mass affluent" - professionals, entrepreneurs, and savers historically underserved between mainstream retail and private banking. It holds a full UK banking licence (granted November 2021), is authorised by the PRA and regulated by the FCA and PRA under FRN 849724, and offers app-only savings products with FSCS-protected deposits. It is not one of the CMA9 mandated banks and does not publish a public developer portal; where it participates in UK Open Banking it conforms to the Open Banking Implementation Entity (OBIE) Open Data and Read/Write API Standards under the PSD2 / FCA framework.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/monument-bank/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/monument-bank/refs/heads/main/apis.yml)

## Tags

- Financial Services
- Banking
- Open Banking
- PSD2
- OBIE
- United Kingdom
- Savings
- Challenger Bank
- Account Information
- Payments

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

> Monument does not publish a public developer portal or a confirmed Open Data endpoint. Its API host `api.monument.co` resolves but responds `403` (access-controlled). The API entries below are represented against the **shared OBIE UK Open Banking standards** and the harvested specs are the standard documents, **not** Monument-proprietary contracts.

### Monument Bank Open Data API

UK Open Banking Open Data API - the PUBLIC, unauthenticated reference-data surface (products, ATMs, branches, PCA/BCA, SME loans, commercial credit cards) defined by the OBIE Open Data Standard. Unverified for Monument.

- **Human URL:** [https://github.com/OpenBankingUK/opendata-api-spec-compiled](https://github.com/OpenBankingUK/opendata-api-spec-compiled)
- **Base URL:** `https://api.monument.co/open-data/v2.3` (unverified / gated)

#### Tags

- Open Data
- Reference Data
- Public

#### Properties

- [OpenAPI](openapi/obie-opendata-swagger.json) — shared OBIE Open Data Standard (Swagger 2.0)
- [Documentation](https://github.com/OpenBankingUK/opendata-api-spec-compiled)
- [API Reference](https://openbankinguk.github.io/opendata-api-docs-pub/)

### Monument Bank Account and Transaction Information API

UK Open Banking Read/Write Account & Transaction Information (AIS) API per the OBIE Read/Write API Standard - accounts, balances, transactions, standing orders, direct debits, statements, and parties. FAPI-secured (OAuth2/OIDC, mTLS, PSD2 SCA). Unverified for Monument.

- **Human URL:** [https://github.com/OpenBankingUK/read-write-api-specs](https://github.com/OpenBankingUK/read-write-api-specs)
- **Base URL:** `https://api.monument.co/open-banking/v3.1/aisp` (unverified / gated)

#### Tags

- Account Information
- AIS
- Read/Write

#### Properties

- [OpenAPI](openapi/obie-account-info-openapi.yaml) — shared OBIE Read/Write Standard (OpenAPI 3.0)
- [Documentation](https://github.com/OpenBankingUK/read-write-api-specs)
- [API Reference](https://openbankinguk.github.io/read-write-api-docs-pub/v3.1.11/)

### Monument Bank Payment Initiation API

UK Open Banking Read/Write Payment Initiation (PIS) API per the OBIE Read/Write API Standard - domestic, scheduled, standing-order, international, and file payments. FAPI-secured (OAuth2/OIDC, mTLS, PSD2 SCA). Unverified for Monument.

- **Human URL:** [https://github.com/OpenBankingUK/read-write-api-specs](https://github.com/OpenBankingUK/read-write-api-specs)
- **Base URL:** `https://api.monument.co/open-banking/v3.1/pisp` (unverified / gated)

#### Tags

- Payment Initiation
- PIS
- Read/Write

#### Properties

- [OpenAPI](openapi/obie-payment-initiation-openapi.yaml) — shared OBIE Read/Write Standard (OpenAPI 3.0)
- [Documentation](https://github.com/OpenBankingUK/read-write-api-specs)
- [API Reference](https://openbankinguk.github.io/read-write-api-docs-pub/v3.1.11/)

### Monument Bank Confirmation of Funds API

UK Open Banking Read/Write Confirmation of Funds (CBPII) API per the OBIE Read/Write API Standard - confirms availability of funds for card-based payment instrument issuers. FAPI-secured (OAuth2/OIDC, mTLS, PSD2 SCA). Unverified for Monument.

- **Human URL:** [https://github.com/OpenBankingUK/read-write-api-specs](https://github.com/OpenBankingUK/read-write-api-specs)
- **Base URL:** `https://api.monument.co/open-banking/v3.1/cbpii` (unverified / gated)

#### Tags

- Confirmation of Funds
- CBPII
- Read/Write

#### Properties

- [OpenAPI](openapi/obie-confirmation-funds-openapi.yaml) — shared OBIE Read/Write Standard (OpenAPI 3.0)
- [Documentation](https://github.com/OpenBankingUK/read-write-api-specs)
- [API Reference](https://openbankinguk.github.io/read-write-api-docs-pub/v3.1.11/)

## Common Properties

- [Website](https://www.monument.co/)
- [About](https://www.monument.co/about)
- [Blog](https://www.monument.co/blog)
- [News](https://www.monument.co/news)
- [LinkedIn](https://www.linkedin.com/company/monument-bank/)
- [Support](https://www.monument.co/contact-us)
- [FAQ](https://www.monument.co/faq)
- [Terms of Service](https://www.monument.co/terms-and-conditions)
- [Privacy Policy](https://www.monument.co/privacy)
- [Compliance (FCA Register, FRN 849724)](https://register.fca.org.uk/s/firm?id=0010X00004ksS6tQAE)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
