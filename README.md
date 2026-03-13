# Google reCAPTCHA (google-recaptcha)
Google reCAPTCHA is a security service that protects websites and applications from spam, abuse, and automated bot traffic. Its developer APIs include the reCAPTCHA Enterprise API for creating risk assessments with granular scores and reason codes, and the standard Site Verify API for validating reCAPTCHA v2/v3 tokens from client-side integrations.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/google-recaptcha/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Security, Bot Detection, CAPTCHA, Fraud Prevention, Abuse Prevention, Google Cloud

## Timestamps

- **Created:** 2026-03-13
- **Modified:** 2026-03-13

## APIs

### reCAPTCHA Enterprise API
The reCAPTCHA Enterprise API provides advanced bot detection and fraud prevention capabilities for websites and applications. It returns risk scores and reason codes for user interactions, supports creating and managing site keys, assessments, and related resources. The API enables creating assessments for tokens, annotating assessments with feedback, and managing firewall policies for automated protection.

**Human URL:** [https://cloud.google.com/recaptcha-enterprise/docs](https://cloud.google.com/recaptcha-enterprise/docs)


#### Tags:

 - Enterprise, Risk Assessment, Bot Detection

#### Properties

- [Documentation](https://cloud.google.com/recaptcha-enterprise/docs/reference/rest)
- [OpenAPI](openapi/recaptcha-enterprise-openapi.yml)
- [JSONSchema](json-schema/google-recaptcha-assessment-schema.json)

### reCAPTCHA Site Verify API
The reCAPTCHA Site Verify API is the standard verification endpoint for reCAPTCHA v2 and v3 tokens. After a user completes a reCAPTCHA challenge on the frontend, the backend sends the response token to this API to verify the interaction. The API returns whether the verification succeeded, a score (for v3), the action name, and the hostname.

**Human URL:** [https://developers.google.com/recaptcha/docs/verify](https://developers.google.com/recaptcha/docs/verify)


#### Tags:

 - Verification, Token Validation, reCAPTCHA v3

#### Properties

- [Documentation](https://developers.google.com/recaptcha/docs/verify)

## Common Properties

- [GettingStarted](https://cloud.google.com/recaptcha-enterprise/docs/getting-started)
- [Pricing](https://cloud.google.com/recaptcha-enterprise/pricing)
- [Authentication](https://cloud.google.com/recaptcha-enterprise/docs/authentication)
- [Console](https://console.cloud.google.com/security/recaptcha)
- [SDKs](https://cloud.google.com/recaptcha-enterprise/docs/libraries)
- [Support](https://cloud.google.com/recaptcha-enterprise/docs/support)
- [Status](https://status.cloud.google.com)
- [JSON-LD](json-ld/google-recaptcha-context.jsonld)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
