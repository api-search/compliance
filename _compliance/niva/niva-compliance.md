---
api_specs:
- filename: niva-openapi-generated.yml
  format: yaml
  label: Niva API
  slug: niva-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/niva/openapi/_ae-authored/niva-openapi-generated.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: SOC 2 Type I
    type: SOC 2 Type I
  - framework: SOC2
    issuer: null
    period: 2025 - 2026
    report_access: on_request
    scope: null
    text: View all SOC 2 Type II (2025 - 2026)
    type: SOC 2 Type II
  trust_center:
    url: https://trust.niva.co/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Niva
provenance_date: '2026-11-10'
provider_name: Niva
provider_slug: niva
slug: niva-compliance
source_date: '2026-11-10'
source_filename: niva-compliance.yml
source_heading: Compliance
source_page: https://trust.niva.co/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Niva\naid: niva\nurl: https://trust.niva.co/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.niva.co/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type I\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Type I\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: 2025 - 2026\n  issuer: null\n  report_access: on_request\n  text: View all SOC 2 Type II (2025 - 2026)\n"
source_yaml_url: https://artifacts.apis.io/niva/compliance/niva-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Niva's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Identity Verification
- Artificial Intelligence
- Compliance
---
