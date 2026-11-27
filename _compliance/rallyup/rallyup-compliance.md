---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PCI Level 1 Compliance through Stripe
    type: PCI Level 1 Compliance
  - framework: SOC2
    issuer: null
    period: February 23, 2023
    report_access: unstated
    scope: null
    text: RallyUp successfully completed its Service Organization Control 2 (SOC 2) Type I audit on February 23, 2023.
    type: Type I audit
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR Compliance
    type: compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA Compliance
    type: compliance
  trust_center:
    url: https://rallyup.com/security/
frameworks:
- CCPA
- GDPR
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Rally Up
provenance_date: '2026-11-10'
provider_name: Rally Up
provider_slug: rallyup
slug: rallyup-compliance
source_date: '2026-11-10'
source_filename: rallyup-compliance.yml
source_heading: Compliance
source_page: https://rallyup.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Rally Up\naid: rallyup\nurl: https://rallyup.com/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://rallyup.com/security/\nattestations:\n- framework: PCI-DSS\n  type: PCI Level 1 Compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI Level 1 Compliance through Stripe\n- framework: SOC2\n  type: Type I audit\n  scope: null\n  period: February 23, 2023\n  issuer: null\n  report_access: unstated\n  text: RallyUp successfully completed its Service Organization Control 2 (SOC 2) Type I audit on February 23, 2023.\n- framework: GDPR\n  type: compliance\n \
  \ scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR Compliance\n- framework: CCPA\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA Compliance\n"
source_yaml_url: https://artifacts.apis.io/rallyup/compliance/rallyup-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Rally Up's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fundraising
- Non-Profit
- Software-as-a-Service
- Digital Platform
---
