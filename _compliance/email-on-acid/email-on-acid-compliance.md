---
api_specs:
- filename: email-on-acid-authentication-api-openapi.yml
  format: yaml
  label: Email on Acid Authentication API
  slug: email-on-acid-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/email-on-acid/openapi/email-on-acid-authentication-api-openapi.yml
- filename: email-on-acid-email-clients-api-openapi.yml
  format: yaml
  label: Email on Acid Email Clients API
  slug: email-on-acid-email-clients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/email-on-acid/openapi/email-on-acid-email-clients-api-openapi.yml
- filename: email-on-acid-email-testing-api-openapi.yml
  format: yaml
  label: Email on Acid Email Testing API
  slug: email-on-acid-email-testing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/email-on-acid/openapi/email-on-acid-email-testing-api-openapi.yml
- filename: email-on-acid-spam-testing-api-openapi.yml
  format: yaml
  label: Email on Acid Spam Testing API
  slug: email-on-acid-spam-testing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/email-on-acid/openapi/email-on-acid-spam-testing-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: information security program
    text: ISO 27001 Certified
    type: certification
  - framework: ISO27701
    issuer: null
    period: null
    report_access: unstated
    scope: information security and privacy program
    text: ISO 27701 Certified
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: operational, security, availability, and confidentiality controls
    text: All reports can be found at https://security.mailgun.com.
    type: Type II audit report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: products
    text: Our products abide by this privacy law
    type: compliance statement
  trust_center:
    url: https://www.emailonacid.com/security/
frameworks:
- GDPR
- ISO27001
- ISO27701
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Email on Acid
provenance_date: '2026-11-09'
provider_name: Email on Acid
provider_slug: email-on-acid
slug: email-on-acid-compliance
source_date: '2026-11-09'
source_filename: email-on-acid-compliance.yml
source_heading: Compliance
source_page: https://www.emailonacid.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Email on Acid\naid: email-on-acid\nurl: https://www.emailonacid.com/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/email-on-acid-trust-center.yml\ntrust_center:\n  url: https://www.emailonacid.com/security/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: information security program\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001 Certified\n- framework: ISO27701\n  type: certification\n  scope: information security and privacy program\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27701 Certified\n- framework:\
  \ SOC2\n  type: Type II audit report\n  scope: operational, security, availability, and confidentiality controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: All reports can be found at https://security.mailgun.com.\n- framework: GDPR\n  type: compliance statement\n  scope: products\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our products abide by this privacy law\n"
source_yaml_url: https://artifacts.apis.io/email-on-acid/compliance/email-on-acid-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Email on Acid's own page on 2026-11-09.
synthetic: false
tags:
- Email Testing
- Email Previews
- Email Client
- Spam Testing
- Accessibility
- HTML Validation
- Email Quality Assurance
- Pre-Deployment Testing
---
