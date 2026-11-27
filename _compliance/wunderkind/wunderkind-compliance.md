---
api_specs:
- filename: wunderkind-email-api-openapi.yml
  format: yaml
  label: Wunderkind Email API
  slug: wunderkind-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wunderkind/openapi/wunderkind-email-api-openapi.yml
- filename: wunderkind-id-resolution-api-openapi.yml
  format: yaml
  label: Wunderkind Id Resolution API
  slug: wunderkind-id-resolution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wunderkind/openapi/wunderkind-id-resolution-api-openapi.yml
- filename: wunderkind-identity-api-openapi.yml
  format: yaml
  label: Wunderkind Identity API
  slug: wunderkind-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wunderkind/openapi/wunderkind-identity-api-openapi.yml
- filename: wunderkind-send-event-api-openapi.yml
  format: yaml
  label: Wunderkind Send Event API
  slug: wunderkind-send-event-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wunderkind/openapi/wunderkind-send-event-api-openapi.yml
- filename: wunderkind-ucrm-api-openapi.yml
  format: yaml
  label: Wunderkind Ucrm API
  slug: wunderkind-ucrm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wunderkind/openapi/wunderkind-ucrm-api-openapi.yml
- filename: wunderkind-wunderhook-api-openapi.yml
  format: yaml
  label: Wunderkind Wunderhook API
  slug: wunderkind-wunderhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wunderkind/openapi/wunderkind-wunderhook-api-openapi.yml
claim_count: 8
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: In 2024, we proudly renewed both our SOC2 and ISO 27001 certifications
    type: certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: In 2024, we proudly renewed both our SOC2 and ISO 27001 certifications
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Our commitment is reflected in our adherence to privacy regulations such as the General Data Protection Regulation (GDPR) in the European Union
    type: regulation adherence
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: the California Consumer Privacy Act (CCPA) in the United States and similar U.S. state privacy laws
    type: regulation adherence
  - framework: SOC2
    issuer: null
    period: '2025'
    report_access: unstated
    scope: null
    source: https://trust.wunderkind.co/
    text: 2025 SOC 2 Type 2 Report
    type: SOC 2 Type 2 Report
  - framework: ISO27001
    issuer: null
    period: '2025'
    report_access: unstated
    scope: null
    source: https://trust.wunderkind.co/
    text: 2025 ISO 27001:2022 Certificate
    type: ISO 27001:2022 Certificate
  - framework: ISO27001
    issuer: null
    period: '2025'
    report_access: unstated
    scope: null
    source: https://trust.wunderkind.co/
    text: 2025 ISO 27001:2022 Report
    type: ISO 27001:2022 Report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.wunderkind.co/
    text: GDPR
    type: GDPR compliance
  trust_center:
    url: https://www.wunderkind.co/blog/wunderkinds-commitment-to-privacy-compliance
frameworks:
- CCPA
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Wunderkind
provenance_date: '2026-11-10'
provider_name: Wunderkind
provider_slug: wunderkind
slug: wunderkind-compliance
source_date: '2026-11-10'
source_filename: wunderkind-compliance.yml
source_heading: Compliance
source_page: https://www.wunderkind.co/blog/wunderkinds-commitment-to-privacy-compliance
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Wunderkind\naid: wunderkind\nurl: https://www.wunderkind.co/blog/wunderkinds-commitment-to-privacy-compliance\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/wunderkind-trust-center.yml\n  sources:\n  - https://trust.wunderkind.co/\n  - https://www.wunderkind.co/blog/wunderkinds-commitment-to-privacy-compliance\ntrust_center:\n  url: https://www.wunderkind.co/blog/wunderkinds-commitment-to-privacy-compliance\nattestations:\n- framework: SOC2\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: In 2024, we proudly renewed both our SOC2 and ISO 27001\
  \ certifications\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: In 2024, we proudly renewed both our SOC2 and ISO 27001 certifications\n- framework: GDPR\n  type: regulation adherence\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our commitment is reflected in our adherence to privacy regulations such as the General Data Protection\n    Regulation (GDPR) in the European Union\n- framework: CCPA\n  type: regulation adherence\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: the California Consumer Privacy Act (CCPA) in the United States and similar U.S. state privacy laws\n- framework: SOC2\n  type: SOC 2 Type 2 Report\n  scope: null\n  period: '2025'\n  issuer: null\n  report_access: unstated\n  text: 2025 SOC 2 Type 2 Report\n  source: https://trust.wunderkind.co/\n- framework: ISO27001\n  type: ISO 27001:2022 Certificate\n  scope: null\n\
  \  period: '2025'\n  issuer: null\n  report_access: unstated\n  text: 2025 ISO 27001:2022 Certificate\n  source: https://trust.wunderkind.co/\n- framework: ISO27001\n  type: ISO 27001:2022 Report\n  scope: null\n  period: '2025'\n  issuer: null\n  report_access: unstated\n  text: 2025 ISO 27001:2022 Report\n  source: https://trust.wunderkind.co/\n- framework: GDPR\n  type: GDPR compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n  source: https://trust.wunderkind.co/\n"
source_yaml_url: https://artifacts.apis.io/wunderkind/compliance/wunderkind-compliance.yml
stated_fields:
- attestations
summary_line: 8 quoted statements, read from Wunderkind's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketing
- Personalization
- Identity Resolution
- Email
- SMS
- Behavioral Data
- E-Commerce
- Webhook
- Artificial Intelligence
- Identity
---
