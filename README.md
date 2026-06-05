# Google reCAPTCHA (google-recaptcha)

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
