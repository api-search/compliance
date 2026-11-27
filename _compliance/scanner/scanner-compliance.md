---
api_specs:
- filename: scanner-ad-hoc-queries-api-openapi.yml
  format: yaml
  label: Scanner Ad Hoc Queries API
  slug: scanner-ad-hoc-queries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scanner/openapi/scanner-ad-hoc-queries-api-openapi.yml
- filename: scanner-detection-rules-api-openapi.yml
  format: yaml
  label: Scanner Detection Rules API
  slug: scanner-detection-rules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scanner/openapi/scanner-detection-rules-api-openapi.yml
- filename: scanner-event-sinks-api-openapi.yml
  format: yaml
  label: Scanner Event Sinks API
  slug: scanner-event-sinks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scanner/openapi/scanner-event-sinks-api-openapi.yml
- filename: scanner-indexes-api-openapi.yml
  format: yaml
  label: Scanner Indexes API
  slug: scanner-indexes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scanner/openapi/scanner-indexes-api-openapi.yml
- filename: scanner-info-api-openapi.yml
  format: yaml
  label: Scanner Info API
  slug: scanner-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scanner/openapi/scanner-info-api-openapi.yml
- filename: scanner-lookup-tables-api-openapi.yml
  format: yaml
  label: Scanner Lookup Tables API
  slug: scanner-lookup-tables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scanner/openapi/scanner-lookup-tables-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: complete SOC 2 Type II Certified
    type: SOC 2 Type II certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: complete GDPR Compliant
    type: GDPR compliance
  trust_center:
    url: https://scanner.dev/trust
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Scanner
provenance_date: '2026-11-10'
provider_name: Scanner
provider_slug: scanner
slug: scanner-compliance
source_date: '2026-11-10'
source_filename: scanner-compliance.yml
source_heading: Compliance
source_page: https://scanner.dev/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Scanner\naid: scanner\nurl: https://scanner.dev/trust\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://scanner.dev/trust\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: complete SOC 2 Type II Certified\n- framework: GDPR\n  type: GDPR compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: complete GDPR Compliant\n"
source_yaml_url: https://artifacts.apis.io/scanner/compliance/scanner-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Scanner's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- SIEM
- Log Analytics
- Threat Detection
- Security Operations
- Observability
- MCP
---
