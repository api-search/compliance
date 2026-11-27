---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: public
    scope: null
    text: ISO IEC 27001 Official Certificate.pdf
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II
    type: Type II report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: compliance
  trust_center:
    url: https://trust.sitoo.com/
frameworks:
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Sitoo
provenance_date: '2026-11-10'
provider_name: Sitoo
provider_slug: sitoo
slug: sitoo-compliance
source_date: '2026-11-10'
source_filename: sitoo-compliance.yml
source_heading: Compliance
source_page: https://trust.sitoo.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Sitoo\naid: sitoo\nurl: https://trust.sitoo.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.sitoo.com/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: public\n  text: ISO IEC 27001 Official Certificate.pdf\n- framework: SOC2\n  type: Type II report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II\n- framework: GDPR\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n"
source_yaml_url: https://artifacts.apis.io/sitoo/compliance/sitoo-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Sitoo's own page on 2026-11-10.
synthetic: false
tags:
- Retail
- Point-of-Sale
- Commerce
- Platform
- Company
---
