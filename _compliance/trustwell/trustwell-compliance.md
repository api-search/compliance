---
api_specs:
- filename: trustwell-compliance-api-openapi.yml
  format: yaml
  label: Trustwell Compliance API
  slug: trustwell-compliance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustwell/openapi/trustwell-compliance-api-openapi.yml
- filename: trustwell-products-api-openapi.yml
  format: yaml
  label: Trustwell Products API
  slug: trustwell-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustwell/openapi/trustwell-products-api-openapi.yml
- filename: trustwell-quality-api-openapi.yml
  format: yaml
  label: Trustwell Quality API
  slug: trustwell-quality-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustwell/openapi/trustwell-quality-api-openapi.yml
- filename: trustwell-recalls-api-openapi.yml
  format: yaml
  label: Trustwell Recalls API
  slug: trustwell-recalls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustwell/openapi/trustwell-recalls-api-openapi.yml
- filename: trustwell-suppliers-api-openapi.yml
  format: yaml
  label: Trustwell Suppliers API
  slug: trustwell-suppliers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustwell/openapi/trustwell-suppliers-api-openapi.yml
- filename: trustwell-traceability-api-openapi.yml
  format: yaml
  label: Trustwell Traceability API
  slug: trustwell-traceability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustwell/openapi/trustwell-traceability-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: committed to security with SOC 2 Type II certification
    type: SOC 2 Type II certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO‑27001‑aligned controls
    type: ISO-27001-aligned controls
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR Compliance Policy
    type: GDPR compliance policy
  - framework: SOC2
    issuer: null
    period: '2026'
    report_access: unstated
    scope: null
    text: SOC2 Type II (2026)
    type: SOC2 Type II report
  trust_center:
    url: https://trust.trustwell.com/
frameworks:
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Trustwell
provenance_date: '2026-11-10'
provider_name: Trustwell
provider_slug: trustwell
slug: trustwell-compliance
source_date: '2026-11-10'
source_filename: trustwell-compliance.yml
source_heading: Compliance
source_page: https://trust.trustwell.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Trustwell\naid: trustwell\nurl: https://trust.trustwell.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/trustwell-trust-center.yml\ntrust_center:\n  url: https://trust.trustwell.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: committed to security with SOC 2 Type II certification\n- framework: ISO27001\n  type: ISO-27001-aligned controls\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO‑27001‑aligned controls\n- framework: GDPR\n  type: GDPR compliance\
  \ policy\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR Compliance Policy\n- framework: SOC2\n  type: SOC2 Type II report\n  scope: null\n  period: '2026'\n  issuer: null\n  report_access: unstated\n  text: SOC2 Type II (2026)\n"
source_yaml_url: https://artifacts.apis.io/trustwell/compliance/trustwell-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Trustwell's own page on 2026-11-10.
synthetic: false
tags:
- FoodIndustry
- Food Safety
- Nutrition
- Supply Chain
- Food Labeling
- Traceability
- Compliance
- Food Technology
- Quality Management
- Recall
- Artificial Intelligence
---
