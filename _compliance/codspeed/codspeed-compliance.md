---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: SOC 2 Type 2 Practitioner Report Request access
    type: SOC 2 Type 2
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://codspeed.io/docs/security
    text: CodSpeed is GDPR compliant.
    type: null
  trust_center:
    url: https://trust.codspeed.io/
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: CodSpeed
provenance_date: '2026-11-09'
provider_name: CodSpeed
provider_slug: codspeed
slug: codspeed-compliance
source_date: '2026-11-09'
source_filename: codspeed-compliance.yml
source_heading: Compliance
source_page: https://trust.codspeed.io/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: CodSpeed\naid: codspeed\nurl: https://trust.codspeed.io/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/codspeed-trust-center.yml\n  sources:\n  - https://codspeed.io/docs/security\n  - https://trust.codspeed.io/\ntrust_center:\n  url: https://trust.codspeed.io/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Type 2 Practitioner Report Request access\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CodSpeed is GDPR compliant.\n  source:\
  \ https://codspeed.io/docs/security\n"
source_yaml_url: https://artifacts.apis.io/codspeed/compliance/codspeed-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from CodSpeed's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Performance
- Benchmarking
- Continuous Integration
- Developer Tools
- Observability
- Testing
- DevOps
- Artificial Intelligence
- MCP
---
