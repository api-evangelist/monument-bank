# Monument Bank (monument-bank)

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
