---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: '2026'
    report_access: unstated
    scope: null
    text: 2026 EarnIn PCI DSS v4.0.1 AOC
    type: Attestation of Compliance
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: EarnIn SOC 2 Type 2 Report
    type: Type 2 report
  trust_center:
    url: https://trust.earnin.com/
frameworks:
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Earnin
provenance_date: '2026-11-09'
provider_name: Earnin
provider_slug: earnin
slug: earnin-compliance
source_date: '2026-11-09'
source_filename: earnin-compliance.yml
source_heading: Compliance
source_page: https://trust.earnin.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Earnin\naid: earnin\nurl: https://trust.earnin.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.earnin.com/\nattestations:\n- framework: PCI-DSS\n  type: Attestation of Compliance\n  scope: null\n  period: '2026'\n  issuer: null\n  report_access: unstated\n  text: 2026 EarnIn PCI DSS v4.0.1 AOC\n- framework: SOC2\n  type: Type 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: EarnIn SOC 2 Type 2 Report\n"
source_yaml_url: https://artifacts.apis.io/earnin/compliance/earnin-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Earnin's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Earned Wage Access
- Consumer Finance
- Payments
- Banking
- Mobile App
- Payroll
---
