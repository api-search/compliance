---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: '2026'
    report_access: unstated
    scope: null
    text: SOC 2 Type II 2026
    type: SOC 2 Type II
  - framework: PCI-DSS
    issuer: null
    period: '2026'
    report_access: unstated
    scope: null
    text: PCI ROC AOC 2026
    type: PCI ROC AOC
  trust_center:
    url: https://trust.jaris.com/
frameworks:
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Jaris
provenance_date: '2026-11-09'
provider_name: Jaris
provider_slug: jaris
slug: jaris-compliance
source_date: '2026-11-09'
source_filename: jaris-compliance.yml
source_heading: Compliance
source_page: https://trust.jaris.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Jaris\naid: jaris\nurl: https://trust.jaris.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.jaris.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: '2026'\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II 2026\n- framework: PCI-DSS\n  type: PCI ROC AOC\n  scope: null\n  period: '2026'\n  issuer: null\n  report_access: unstated\n  text: PCI ROC AOC 2026\n"
source_yaml_url: https://artifacts.apis.io/jaris/compliance/jaris-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Jaris's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Embedded Finance
- Fintech
- Payments
- Lending
- Banking as a Service
- Instant Payouts
- Merchant Onboarding
- KYB
- Settlement
---
