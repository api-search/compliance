---
api_specs:
- filename: geckoboard-datasets-api-openapi.yml
  format: yaml
  label: Geckoboard Datasets API
  slug: geckoboard-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geckoboard/openapi/geckoboard-datasets-api-openapi.yml
- filename: geckoboard-health-api-openapi.yml
  format: yaml
  label: Geckoboard Health API
  slug: geckoboard-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geckoboard/openapi/geckoboard-health-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: Geckoboard
    text: Payment Card Industry Data Security Standard (PCI DSS) compliance
    type: compliance
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Geckoboard
    text: Cloud Application Security Assessment (CASA) certification
    type: certification (CASA)
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Geckoboard
    text: General Data Protection Regulation (GDPR) compliance
    type: compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: Geckoboard
    text: California Consumer Privacy Act (CCPA) compliance
    type: compliance
  trust_center:
    url: https://support.geckoboard.com/en/articles/6055694-how-geckoboard-protects-your-data
frameworks:
- CCPA
- GDPR
- PCI-DSS
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Geckoboard
provenance_date: '2026-11-09'
provider_name: Geckoboard
provider_slug: geckoboard
slug: geckoboard-compliance
source_date: '2026-11-09'
source_filename: geckoboard-compliance.yml
source_heading: Compliance
source_page: https://support.geckoboard.com/en/articles/6055694-how-geckoboard-protects-your-data
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Geckoboard\naid: geckoboard\nurl: https://support.geckoboard.com/en/articles/6055694-how-geckoboard-protects-your-data\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/geckoboard-trust-center.yml\ntrust_center:\n  url: https://support.geckoboard.com/en/articles/6055694-how-geckoboard-protects-your-data\nattestations:\n- framework: PCI-DSS\n  type: compliance\n  scope: Geckoboard\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Payment Card Industry Data Security Standard (PCI DSS) compliance\n- framework: other\n  type: certification (CASA)\n  scope: Geckoboard\n  period: null\n \
  \ issuer: null\n  report_access: unstated\n  text: Cloud Application Security Assessment (CASA) certification\n- framework: GDPR\n  type: compliance\n  scope: Geckoboard\n  period: null\n  issuer: null\n  report_access: unstated\n  text: General Data Protection Regulation (GDPR) compliance\n- framework: CCPA\n  type: compliance\n  scope: Geckoboard\n  period: null\n  issuer: null\n  report_access: unstated\n  text: California Consumer Privacy Act (CCPA) compliance\n"
source_yaml_url: https://artifacts.apis.io/geckoboard/compliance/geckoboard-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Geckoboard's own page on 2026-11-09.
synthetic: false
tags:
- Dashboards
- Data Visualization
- Business Intelligence
- KPI Tracking
- Real-Time Reporting
- TV Dashboards
---
