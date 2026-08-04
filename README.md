# Google reCAPTCHA (google-recaptcha)

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

Google reCAPTCHA is a security service that protects websites and applications from spam and abuse by verifying that interactions are from real humans rather than bots, offering Enterprise and standard APIs for site verification and risk assessment.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/google-recaptcha/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/google-recaptcha/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Abuse Prevention
- Bot Detection
- CAPTCHA
- Fraud Prevention
- Google Cloud
- Security

## Timestamps

- **Created:** 2026-03-13
- **Modified:** 2026-05-19

## APIs

### reCAPTCHA Enterprise API

The reCAPTCHA Enterprise API provides advanced bot detection and fraud prevention capabilities for websites and applications. It returns risk scores and reason codes for user interactions, supports creating and managing site keys, assessments, and related resources. The API enables creating assessments for tokens, annotating assessments with feedback, and managing firewall policies for automated protection.

- **Human URL:** [https://cloud.google.com/recaptcha-enterprise/docs](https://cloud.google.com/recaptcha-enterprise/docs)
- **Base URL:** `https://recaptchaenterprise.googleapis.com`

#### Tags

- Bot Detection
- Enterprise
- Risk Assessment

#### Properties

- [Documentation](https://cloud.google.com/recaptcha-enterprise/docs/reference/rest)
- [OpenAPI](openapi/recaptcha-enterprise-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/recaptcha-enterprise.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/recaptcha-enterprise.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/google-recaptcha-assessment-schema.json) — [JSON Schema](https://json-schema.org/specification)

### reCAPTCHA Site Verify API

The reCAPTCHA Site Verify API is the standard verification endpoint for reCAPTCHA v2 and v3 tokens. After a user completes a reCAPTCHA challenge on the frontend, the backend sends the response token to this API to verify the interaction. The API returns whether the verification succeeded, a score (for v3), the action name, and the hostname.

- **Human URL:** [https://developers.google.com/recaptcha/docs/verify](https://developers.google.com/recaptcha/docs/verify)
- **Base URL:** `https://www.google.com/recaptcha/api`

#### Tags

- reCAPTCHA V3
- Token Validation
- Verification

#### Properties

- [Documentation](https://developers.google.com/recaptcha/docs/verify)
- [Postman Collection](collections/recaptcha-enterprise.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/recaptcha-enterprise.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/google)
- [Getting Started](https://cloud.google.com/recaptcha-enterprise/docs/getting-started)
- [Pricing](https://cloud.google.com/recaptcha-enterprise/pricing)
- [Authentication](https://cloud.google.com/recaptcha-enterprise/docs/authentication)
- [Console](https://console.cloud.google.com/security/recaptcha)
- [S D Ks](https://cloud.google.com/recaptcha-enterprise/docs/libraries)
- [Support](https://cloud.google.com/recaptcha-enterprise/docs/support)
- [Status Page](https://status.cloud.google.com)
- [JSON-LD](json-ld/google-recaptcha-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Integrations](https://cloud.google.com/marketplace)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
