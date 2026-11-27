---
api_specs:
- filename: verisoul-account-api-openapi.yml
  format: yaml
  label: Verisoul Account API
  slug: verisoul-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/verisoul/openapi/verisoul-account-api-openapi.yml
- filename: verisoul-email-api-openapi.yml
  format: yaml
  label: Verisoul Email API
  slug: verisoul-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/verisoul/openapi/verisoul-email-api-openapi.yml
- filename: verisoul-enrollment-api-openapi.yml
  format: yaml
  label: Verisoul Enrollment API
  slug: verisoul-enrollment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/verisoul/openapi/verisoul-enrollment-api-openapi.yml
- filename: verisoul-list-api-openapi.yml
  format: yaml
  label: Verisoul List API
  slug: verisoul-list-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/verisoul/openapi/verisoul-list-api-openapi.yml
- filename: verisoul-phone-api-openapi.yml
  format: yaml
  label: Verisoul Phone API
  slug: verisoul-phone-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/verisoul/openapi/verisoul-phone-api-openapi.yml
- filename: verisoul-public-api-openapi.yml
  format: yaml
  label: Verisoul Public API
  slug: verisoul-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/verisoul/openapi/verisoul-public-api-openapi.yml
- filename: verisoul-session-api-openapi.yml
  format: yaml
  label: Verisoul Session API
  slug: verisoul-session-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/verisoul/openapi/verisoul-session-api-openapi.yml
- filename: verisoul-verification-api-openapi.yml
  format: yaml
  label: Verisoul Verification API
  slug: verisoul-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/verisoul/openapi/verisoul-verification-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA COMPLIANT
    type: compliance badge
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: compliance badge
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II
    type: SOC 2 Type II badge
  - framework: SOC2
    issuer: ALIGN
    period: '2025'
    report_access: unstated
    scope: null
    text: SOC2 Type 2 - 2025 by ALIGN
    type: SOC 2 Type II report
  trust_center:
    url: https://trust.verisoul.ai/
frameworks:
- CCPA
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Verisoul
provenance_date: '2026-11-10'
provider_name: Verisoul
provider_slug: verisoul
slug: verisoul-compliance
source_date: '2026-11-10'
source_filename: verisoul-compliance.yml
source_heading: Compliance
source_page: https://trust.verisoul.ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Verisoul\naid: verisoul\nurl: https://trust.verisoul.ai/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.verisoul.ai/\nattestations:\n- framework: CCPA\n  type: compliance badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA COMPLIANT\n- framework: GDPR\n  type: compliance badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: SOC2\n  type: SOC 2 Type II badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II\n- framework: SOC2\n  type: SOC 2 Type II report\n\
  \  scope: null\n  period: '2025'\n  issuer: ALIGN\n  report_access: unstated\n  text: SOC2 Type 2 - 2025 by ALIGN\n"
source_yaml_url: https://artifacts.apis.io/verisoul/compliance/verisoul-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Verisoul's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fraud Prevention
- Identity Verification
- Fake Account Detection
- Device Fingerprinting
- Email Intelligence
- Bot Detection
- KYC
- Trust and Safety
- Risk Scoring
---
