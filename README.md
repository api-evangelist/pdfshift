# PDFShift

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

PDFShift is an HTML to PDF conversion REST API that generates pixel-perfect PDFs from HTML and CSS using Chromium rendering. It supports custom headers, footers, watermarks, password protection, JavaScript execution, screenshot capture (PNG, JPEG, WebP), webhook notifications, and direct export to Amazon S3 and Google Cloud Storage.

Over 300 million conversions served for 15,000+ developers with average conversion times of 1.5 seconds and 99.9% uptime.

## API

- **Base URL:** `https://api.pdfshift.io/v3`
- **Authentication:** API Key via `X-API-Key` header
- **Documentation:** [docs.pdfshift.io](https://docs.pdfshift.io/)
- **OpenAPI Spec:** [openapi.json](https://docs.pdfshift.io/api-reference/openapi.json)

### Key Endpoints

- `POST /convert/pdf` — Convert HTML or URL to PDF
- `POST /convert/png` — Convert HTML or URL to PNG screenshot
- `POST /convert/jpeg` — Convert HTML or URL to JPEG screenshot
- `POST /convert/webp` — Convert HTML or URL to WebP screenshot
- `GET /usage` — Retrieve account credit usage
- Templates and logging endpoints also available

## Plans

| Plan       | Monthly Price | Credits/Month | Cost per Credit |
|------------|--------------|---------------|-----------------|
| Free       | $0           | 50            | —               |
| Startup    | $9           | 500           | ~$0.04          |
| Boost      | $24          | 2,500         | ~$0.03          |
| Growth     | $39          | 5,000         | ~$0.025         |
| Enterprise | Custom       | Custom        | Custom          |

See [plans/pdfshift-plans-pricing.yml](plans/pdfshift-plans-pricing.yml) for full details.

## Links

- [Website](https://pdfshift.io/)
- [Documentation](https://docs.pdfshift.io/)
- [GitHub Organization](https://github.com/pdfshift)
- [Status Page](https://status.pdfshift.io/)
- [Pricing](https://pdfshift.io/pricing/)
- [LinkedIn](https://www.linkedin.com/company/pdfshift-io)
- [X / Twitter](https://x.com/pdfshift)

## APIs.json

This repository contains an [APIs.json 0.19](apis.yml) profile for PDFShift maintained by [API Evangelist](https://apievangelist.com).
