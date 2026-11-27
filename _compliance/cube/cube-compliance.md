---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Cube Cloud
    text: Cube Cloud is SOC 2 Type II, HIPAA, and GDPR compliant
    type: SOC 2 Type II report
  - framework: HIPAA
    issuer: null
    period: null
    report_access: on_request
    scope: Cube Cloud
    text: Cube Cloud is SOC 2 Type II, HIPAA, and GDPR compliant
    type: compliance
  - framework: GDPR
    issuer: null
    period: null
    report_access: on_request
    scope: Cube Cloud
    text: Cube Cloud is SOC 2 Type II, HIPAA, and GDPR compliant
    type: compliance
  trust_center:
    url: https://cube.dev/security
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Cube
provenance_date: '2026-11-09'
provider_name: Cube
provider_slug: cube
slug: cube-compliance
source_date: '2026-11-09'
source_filename: cube-compliance.yml
source_heading: Compliance
source_page: https://cube.dev/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Cube\naid: cube\nurl: https://cube.dev/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/cube-trust-center.yml\ntrust_center:\n  url: https://cube.dev/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: Cube Cloud\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Cube Cloud is SOC 2 Type II, HIPAA, and GDPR compliant\n- framework: HIPAA\n  type: compliance\n  scope: Cube Cloud\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Cube Cloud is SOC 2 Type II, HIPAA, and GDPR compliant\n- framework: GDPR\n  type: compliance\n \
  \ scope: Cube Cloud\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Cube Cloud is SOC 2 Type II, HIPAA, and GDPR compliant\n"
source_yaml_url: https://artifacts.apis.io/cube/compliance/cube-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Cube's own page on 2026-11-09.
synthetic: false
tags:
- GraphQL
- Semantic Layer
- Business Intelligence
- Embedded Analytics
- Data Warehouse
---
