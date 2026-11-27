---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent, third-party auditors
    period: null
    report_access: unstated
    scope: Pabbly services
    text: Pabbly is currently ISO 27001:2022 and SOC2 Type 2 certified.
    type: Type 2 certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Pabbly services
    text: Pabbly is SOC2 Type 2 and ISO 27001:2022 certified.
    type: certification (ISO 27001:2022)
  trust_center:
    url: https://www.pabbly.com/security/
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Pabbly
provenance_date: '2026-11-10'
provider_name: Pabbly
provider_slug: pabbly
slug: pabbly-compliance
source_date: '2026-11-10'
source_filename: pabbly-compliance.yml
source_heading: Compliance
source_page: https://www.pabbly.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Pabbly\naid: pabbly\nurl: https://www.pabbly.com/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.pabbly.com/security/\nattestations:\n- framework: SOC2\n  type: Type 2 certification\n  scope: Pabbly services\n  period: null\n  issuer: independent, third-party auditors\n  report_access: unstated\n  text: Pabbly is currently ISO 27001:2022 and SOC2 Type 2 certified.\n- framework: ISO27001\n  type: certification (ISO 27001:2022)\n  scope: Pabbly services\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Pabbly is SOC2 Type 2 and ISO 27001:2022 certified.\n"
source_yaml_url: https://artifacts.apis.io/pabbly/compliance/pabbly-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Pabbly's own page on 2026-11-10.
synthetic: false
tags:
- Automation
- Email Marketing
- Subscription Billing
- Billing
- Payments
- Webhook
- Messaging
- WhatsApp
- Email Verification
- Forms
- No-Code
- Software-as-a-Service
---
