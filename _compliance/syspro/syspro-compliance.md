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
    text: ISO 27001 Compliance
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR Ready
    type: readiness claim
  trust_center:
    url: https://trust.syspro.com/
frameworks:
- GDPR
- ISO27001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: SYSPRO
provenance_date: '2026-11-10'
provider_name: SYSPRO
provider_slug: syspro
slug: syspro-compliance
source_date: '2026-11-10'
source_filename: syspro-compliance.yml
source_heading: Compliance
source_page: https://trust.syspro.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: SYSPRO\naid: syspro\nurl: https://trust.syspro.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/syspro-trust-center.yml\ntrust_center:\n  url: https://trust.syspro.com/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001 Compliance\n- framework: GDPR\n  type: readiness claim\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR Ready\n"
source_yaml_url: https://artifacts.apis.io/syspro/compliance/syspro-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from SYSPRO's own page on 2026-11-10.
synthetic: false
tags:
- ERP
- Manufacturing
- Distribution
- Inventory
- Production Orders
- Purchasing
- Sales
- Financial Accounting
- Supply Chain
---
