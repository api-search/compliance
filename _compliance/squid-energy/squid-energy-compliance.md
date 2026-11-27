---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001:2022 certified.
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type I and Type II certified.
    type: SOC 2 Type I and Type II certification
  trust_center:
    url: https://www.squid.energy/security
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Squid
provenance_date: '2026-11-10'
provider_name: Squid
provider_slug: squid-energy
slug: squid-energy-compliance
source_date: '2026-11-10'
source_filename: squid-energy-compliance.yml
source_heading: Compliance
source_page: https://www.squid.energy/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Squid\naid: squid-energy\nurl: https://www.squid.energy/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.squid.energy/security\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022 certified.\n- framework: SOC2\n  type: SOC 2 Type I and Type II certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type I and Type II certified.\n"
source_yaml_url: https://artifacts.apis.io/squid-energy/compliance/squid-energy-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Squid's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Energy
- Power Systems
- Modeling
- Grid Planning
---
