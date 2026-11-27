---
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: Johanson Group LLP
    period: January 15th 2025 to January 14th 2026
    report_access: nda
    scope: null
    text: Our SOC 2 Type II Report (available under NDA) as well as our SOC 3 Report (available publicly) by auditors Johanson Group LLP for the period January 15th 2025 to January 14th 2026 are available for download now.
    type: SOC 2 Type II report
  - framework: SOC3
    issuer: Johanson Group LLP
    period: January 15th 2025 to January 14th 2026
    report_access: public
    scope: null
    text: our SOC 3 Report (available publicly) by auditors Johanson Group LLP for the period January 15th 2025 to January 14th 2026
    type: SOC 3 report
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: SAQ A
    text: PCI DSS - SAQ A
    type: self-assessment questionnaire
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: compliance statement
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA COMPLIANT
    type: compliance statement
  trust_center:
    url: https://trust.gigs.com/
frameworks:
- CCPA
- GDPR
- PCI-DSS
- SOC2
- SOC3
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Gigs
provenance_date: '2026-11-09'
provider_name: Gigs
provider_slug: gigs
slug: gigs-compliance
source_date: '2026-11-09'
source_filename: gigs-compliance.yml
source_heading: Compliance
source_page: https://trust.gigs.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Gigs\naid: gigs\nurl: https://trust.gigs.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.gigs.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: null\n  period: January 15th 2025 to January 14th 2026\n  issuer: Johanson Group LLP\n  report_access: nda\n  text: Our SOC 2 Type II Report (available under NDA) as well as our SOC 3 Report (available publicly) by auditors\n    Johanson Group LLP for the period January 15th 2025 to January 14th 2026 are available for download now.\n- framework: SOC3\n  type: SOC 3 report\n  scope: null\n  period: January 15th 2025 to January\
  \ 14th 2026\n  issuer: Johanson Group LLP\n  report_access: public\n  text: our SOC 3 Report (available publicly) by auditors Johanson Group LLP for the period January 15th 2025 to\n    January 14th 2026\n- framework: PCI-DSS\n  type: self-assessment questionnaire\n  scope: SAQ A\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI DSS - SAQ A\n- framework: GDPR\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: CCPA\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA COMPLIANT\n"
source_yaml_url: https://artifacts.apis.io/gigs/compliance/gigs-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Gigs's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Telecommunications
- Connectivity
- eSIM
- MVNO
- Mobile
- Subscription
- Payments
- Webhook
- Embedded Finance
---
