---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC1
    issuer: null
    period: null
    report_access: unstated
    scope: Betterment Securities
    text: Betterment Securities SOC 1 Type II Audit Report
    type: Type II audit report
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Full SOC 2 Type II Audit Report
    type: Type II audit report
  trust_center:
    url: https://trust.betterment.com/
frameworks:
- SOC1
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Betterment
provenance_date: '2026-11-09'
provider_name: Betterment
provider_slug: betterment
slug: betterment-compliance
source_date: '2026-11-09'
source_filename: betterment-compliance.yml
source_heading: Compliance
source_page: https://trust.betterment.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Betterment\naid: betterment\nurl: https://trust.betterment.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/betterment-trust-center.yml\ntrust_center:\n  url: https://trust.betterment.com/\nattestations:\n- framework: SOC1\n  type: Type II audit report\n  scope: Betterment Securities\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Betterment Securities SOC 1 Type II Audit Report\n- framework: SOC2\n  type: Type II audit report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Full SOC 2 Type II Audit Report\n"
source_yaml_url: https://artifacts.apis.io/betterment/compliance/betterment-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Betterment's own page on 2026-11-09.
synthetic: false
tags:
- Robo-Advisor
- Automated Investing
- Financial Planning
- Tax-Loss Harvesting
- Retirement Planning
- Portfolio Management
- 401k
- Fintech
- Wealth Management
- Investment Rebalancing
- Open Banking
---
