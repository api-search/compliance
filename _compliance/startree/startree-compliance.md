---
api_specs:
- filename: startree-query-api-api-openapi.yml
  format: yaml
  label: StarTree Query API
  slug: startree-query-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/startree/openapi/startree-query-api-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 and ISO 27001 compliance ensure your data is safe and protected.
    type: compliance
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 and ISO 27001 compliance ensure your data is safe and protected.
    type: compliance
  trust_center:
    url: https://startree.ai/
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: StarTree
provenance_date: '2026-11-10'
provider_name: StarTree
provider_slug: startree
slug: startree-compliance
source_date: '2026-11-10'
source_filename: startree-compliance.yml
source_heading: Compliance
source_page: https://startree.ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: StarTree\naid: startree\nurl: https://startree.ai/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://startree.ai/\nattestations:\n- framework: SOC2\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 and ISO 27001 compliance ensure your data is safe and protected.\n- framework: ISO27001\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 and ISO 27001 compliance ensure your data is safe and protected.\n"
source_yaml_url: https://artifacts.apis.io/startree/compliance/startree-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from StarTree's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data
- Analytics
- Real-Time Analytics
- OLAP
- Apache Pinot
- Streaming
- Database
---
