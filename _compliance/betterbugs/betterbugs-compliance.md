---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC2 Type II Report
    type: Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: null
  trust_center:
    url: https://trust.betterbugs.io/
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: BetterBugs
provenance_date: '2026-11-09'
provider_name: BetterBugs
provider_slug: betterbugs
slug: betterbugs-compliance
source_date: '2026-11-09'
source_filename: betterbugs-compliance.yml
source_heading: Compliance
source_page: https://trust.betterbugs.io/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: BetterBugs\naid: betterbugs\nurl: https://trust.betterbugs.io/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.betterbugs.io/\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC2 Type II Report\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n"
source_yaml_url: https://artifacts.apis.io/betterbugs/compliance/betterbugs-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from BetterBugs's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Bug Tracking
- Software-as-a-Service
- Collaboration
- Software Quality
---
