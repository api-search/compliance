---
api_specs:
- filename: tana-addtonodev2-api-openapi.yml
  format: yaml
  label: Tana AddToNodeV2 API
  slug: tana-addtonodev2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tana/openapi/tana-addtonodev2-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: Prescient Assurance LLC
    period: March 30 to June 30, 2026
    report_access: nda
    scope: Tana is in scope; Tana Outliner is not in scope
    text: The report covers the period March 30 to June 30, 2026, and was issued by our independent auditor, Prescient Assurance LLC.
    type: SOC 2 Type 2 report
  trust_center:
    url: https://trust.tana.inc/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Tana
provenance_date: '2026-11-10'
provider_name: Tana
provider_slug: tana
slug: tana-compliance
source_date: '2026-11-10'
source_filename: tana-compliance.yml
source_heading: Compliance
source_page: https://trust.tana.inc/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Tana\naid: tana\nurl: https://trust.tana.inc/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/tana-trust-center.yml\ntrust_center:\n  url: https://trust.tana.inc/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: Tana is in scope; Tana Outliner is not in scope\n  period: March 30 to June 30, 2026\n  issuer: Prescient Assurance LLC\n  report_access: nda\n  text: The report covers the period March 30 to June 30, 2026, and was issued by our independent auditor, Prescient\n    Assurance LLC.\n"
source_yaml_url: https://artifacts.apis.io/tana/compliance/tana-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Tana's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Note Taking
- Knowledge Management
- Productivity
- Artificial Intelligence
- Meetings
- Agents
- Collaboration
- Outliner
---
