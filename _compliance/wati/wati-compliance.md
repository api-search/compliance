---
api_specs:
- filename: wati-contacts-api-openapi.yml
  format: yaml
  label: WATI Contacts API
  slug: wati-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wati/openapi/wati-contacts-api-openapi.yml
- filename: wati-messages-api-openapi.yml
  format: yaml
  label: WATI Messages API
  slug: wati-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wati/openapi/wati-messages-api-openapi.yml
- filename: wati-templates-api-openapi.yml
  format: yaml
  label: WATI Templates API
  slug: wati-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wati/openapi/wati-templates-api-openapi.yml
claim_count: 6
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Certified
    type: certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001 v2022 Certified
    type: certification
  - framework: ISO27701
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27701 Compliant
    type: compliance
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR Compliant
    type: compliance
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: UK GDPR
    text: UK GDPR Compliant
    type: compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CPRA (formerly CCPA) Compliant
    type: compliance
  trust_center:
    url: https://trust.wati.io/
frameworks:
- CCPA
- GDPR
- ISO27001
- ISO27701
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: WATI
provenance_date: '2026-11-10'
provider_name: WATI
provider_slug: wati
slug: wati-compliance
source_date: '2026-11-10'
source_filename: wati-compliance.yml
source_heading: Compliance
source_page: https://trust.wati.io/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: WATI\naid: wati\nurl: https://trust.wati.io/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/wati-trust-center.yml\ntrust_center:\n  url: https://trust.wati.io/\nattestations:\n- framework: SOC2\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Certified\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001 v2022 Certified\n- framework: ISO27701\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27701\
  \ Compliant\n- framework: GDPR\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR Compliant\n- framework: other\n  type: compliance\n  scope: UK GDPR\n  period: null\n  issuer: null\n  report_access: unstated\n  text: UK GDPR Compliant\n- framework: CCPA\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CPRA (formerly CCPA) Compliant\n"
source_yaml_url: https://artifacts.apis.io/wati/compliance/wati-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from WATI's own page on 2026-11-10.
synthetic: false
tags:
- WhatsApp
- Messaging
- Customer Engagement
- Chatbots
- Business Communication
- CRM
---
