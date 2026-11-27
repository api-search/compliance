---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC1
    issuer: independent third-party auditors
    period: annually
    report_access: on_request
    scope: null
    text: The effectiveness of this program is verified through independent third-party audits conducted annually, including SOC 1 (Type II) and SOC 2 (Type II) examinations.
    type: Type II examination
  - framework: SOC2
    issuer: independent third-party auditors
    period: null
    report_access: on_request
    scope: null
    text: Audit reports can be requested from your StackAdapt Account Manager.
    type: Type II examination
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: payment card transactions handled via Stripe
    text: StackAdapt maintains compliance with the Payment Card Industry Data Security Standard (PCI DSS).
    type: compliance
  - framework: other
    issuer: U.S. Department of Commerce
    period: null
    report_access: unstated
    scope: personal data transferred from the EU, UK, and Switzerland to the United States
    text: StackAdapt has certified that it adheres to the Data Privacy Framework Principles for the processing of personal data transferred from the EU, UK, and Switzerland to the United States.
    type: EU-U.S. Data Privacy Framework certification
  trust_center:
    url: https://www.stackadapt.com/trust-and-security-center
frameworks:
- PCI-DSS
- SOC1
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: StackAdapt
provenance_date: '2026-11-10'
provider_name: StackAdapt
provider_slug: stackadapt
slug: stackadapt-compliance
source_date: '2026-11-10'
source_filename: stackadapt-compliance.yml
source_heading: Compliance
source_page: https://www.stackadapt.com/trust-and-security-center
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: StackAdapt\naid: stackadapt\nurl: https://www.stackadapt.com/trust-and-security-center\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.stackadapt.com/trust-and-security-center\nattestations:\n- framework: SOC1\n  type: Type II examination\n  scope: null\n  period: annually\n  issuer: independent third-party auditors\n  report_access: on_request\n  text: The effectiveness of this program is verified through independent third-party audits conducted annually,\n    including SOC 1 (Type II) and SOC 2 (Type II) examinations.\n- framework: SOC2\n  type: Type II examination\n  scope: null\n  period: null\n\
  \  issuer: independent third-party auditors\n  report_access: on_request\n  text: Audit reports can be requested from your StackAdapt Account Manager.\n- framework: PCI-DSS\n  type: compliance\n  scope: payment card transactions handled via Stripe\n  period: null\n  issuer: null\n  report_access: unstated\n  text: StackAdapt maintains compliance with the Payment Card Industry Data Security Standard (PCI DSS).\n- framework: other\n  type: EU-U.S. Data Privacy Framework certification\n  scope: personal data transferred from the EU, UK, and Switzerland to the United States\n  period: null\n  issuer: U.S. Department of Commerce\n  report_access: unstated\n  text: StackAdapt has certified that it adheres to the Data Privacy Framework Principles for the processing of\n    personal data transferred from the EU, UK, and Switzerland to the United States.\n"
source_yaml_url: https://artifacts.apis.io/stackadapt/compliance/stackadapt-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from StackAdapt's own page on 2026-11-10.
synthetic: false
tags:
- Programmatic Advertising
- Digital Advertising
- Campaign Management
- AdTech
- DSP
- Native Advertising
- Display Advertising
- Video Advertising
- Connected TV
- Audience Targeting
- Real-Time Bidding
- Conversion Tracking
- Performance Reporting
---
