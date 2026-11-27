---
api_specs:
- filename: immersa-openapi-generated.yml
  format: yaml
  label: Immersa API
  slug: immersa-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/immersa/openapi/_ae-authored/immersa-openapi-generated.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: Immersa, the company behind MarcoPolo
    text: Immersa, the company behind MarcoPolo, is SOC 2 Type II compliant. The compliance report is available on request under NDA.
    type: Type II
  trust_center:
    url: https://www.marcopolo.dev/trust
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Immersa
provenance_date: '2026-11-09'
provider_name: Immersa
provider_slug: immersa
slug: immersa-compliance
source_date: '2026-11-09'
source_filename: immersa-compliance.yml
source_heading: Compliance
source_page: https://www.marcopolo.dev/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Immersa\naid: immersa\nurl: https://www.marcopolo.dev/trust\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.marcopolo.dev/trust\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: Immersa, the company behind MarcoPolo\n  period: null\n  issuer: null\n  report_access: nda\n  text: Immersa, the company behind MarcoPolo, is SOC 2 Type II compliant. The compliance report is available on\n    request under NDA.\n"
source_yaml_url: https://artifacts.apis.io/immersa/compliance/immersa-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Immersa's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- DataGateway
- Platform
- Security
---
