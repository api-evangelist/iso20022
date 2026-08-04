# ISO 20022

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

ISO 20022 is the international financial messaging standard published by the International Organization for Standardization (ISO) that provides a common language and model for financial data. It defines business processes, data elements, and message definitions used by banks, payment systems, securities settlement systems, and other financial institutions worldwide.

The standard covers payment messages, securities messages, trade finance, foreign exchange, and card payments. SWIFT serves as the ISO 20022 Registration Authority, maintaining the central message repository and e-Repository. As of 2025, ISO 20022 became the exclusive format for cross-border payments on the SWIFT network, with more than 60 central banks worldwide either completed or underway with migration.

**API Resources:**

- [Message Catalogue](https://www.iso20022.org/catalogue-messages) - All current ISO 20022 message definitions
- [e-Repository](https://www.iso20022.org/iso20022-repository/e-repository) - Full data dictionary and business process catalogue
- [API Resources Catalogue](https://www.iso20022.org/catalogue-api-resources-change-requests) - RESTful API resources aligned with ISO 20022
- [APIs and ISO 20022](https://www.iso20022.org/about-iso-20022/apis-and-iso-20022) - Official guidance on API development
- [Best Practices White Paper](https://www.iso20022.org/sites/default/files/media/file/ISO_20022_and_Web_APIs_An_Implementation_Best_Practices_White_Paper_10June2025.pdf) - ISO 20022 and Web APIs implementation guide

**Key Message Domains:**

- **Payments (pacs, pain, camt)** - Payment initiation, clearing, settlement, and cash management
- **Securities (sese, semt, setr, seev)** - Settlement, management, trading, and events
- **Trade Services (tsmt, tsrv)** - Trade finance messaging
- **Foreign Exchange (fxtr)** - FX trade and settlement
- **Cards (cain, caad, caam)** - Card transactions and ATM messaging

**Links:**

- [Website](https://www.iso20022.org)
- [GitHub](https://github.com/20022)
- [APIs.json](apis.yml)
