# PDFShift

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
