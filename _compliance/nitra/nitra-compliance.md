---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 TYPE II
    type: Type II
  trust_center:
    url: https://nitra.com/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Nitra
provenance_date: '2026-11-10'
provider_name: Nitra
provider_slug: nitra
slug: nitra-compliance
source_date: '2026-11-10'
source_filename: nitra-compliance.yml
source_heading: Compliance
source_page: https://nitra.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Nitra\naid: nitra\nurl: https://nitra.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/nitra-trust-center.yml\ntrust_center:\n  url: https://nitra.com/\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 TYPE II\n"
source_yaml_url: https://artifacts.apis.io/nitra/compliance/nitra-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Nitra's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Financial Services
- Healthcare
- Fintech
- Banking
- Payments
- Practice Management
- Spend Management
---
