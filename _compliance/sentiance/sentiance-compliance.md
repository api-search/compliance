---
api_specs:
- filename: sentiance-openapi-generated.yml
  format: yaml
  label: Sentiance API
  slug: sentiance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sentiance/openapi/_ae-authored/sentiance-openapi-generated.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: Brand Compliance, accredited by RvA (C 548)
    period: null
    report_access: unstated
    scope: null
    text: Sentiance is certified to ISO/IEC 27001:2022 and ISO/IEC 27701:2025.
    type: certification
  - framework: ISO27701
    issuer: Brand Compliance
    period: null
    report_access: unstated
    scope: null
    text: 'ISO/IEC 27701:2025 Certifying body: Brand Compliance'
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: process it only in compliance with the General Data Protection Regulation (GDPR)
    type: regulatory compliance commitment
  trust_center:
    url: https://sentiance.com/trust
frameworks:
- GDPR
- ISO27001
- ISO27701
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Sentiance
provenance_date: '2026-11-10'
provider_name: Sentiance
provider_slug: sentiance
slug: sentiance-compliance
source_date: '2026-11-10'
source_filename: sentiance-compliance.yml
source_heading: Compliance
source_page: https://sentiance.com/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Sentiance\naid: sentiance\nurl: https://sentiance.com/trust\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://sentiance.com/trust\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: Brand Compliance, accredited by RvA (C 548)\n  report_access: unstated\n  text: Sentiance is certified to ISO/IEC 27001:2022 and ISO/IEC 27701:2025.\n- framework: ISO27701\n  type: certification\n  scope: null\n  period: null\n  issuer: Brand Compliance\n  report_access: unstated\n  text: 'ISO/IEC 27701:2025 Certifying body: Brand Compliance'\n- framework: GDPR\n  type: regulatory\
  \ compliance commitment\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: process it only in compliance with the General Data Protection Regulation (GDPR)\n"
source_yaml_url: https://artifacts.apis.io/sentiance/compliance/sentiance-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Sentiance's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Behavioral-Intelligence
- Mobile
- Privacy
- On-Device
---
