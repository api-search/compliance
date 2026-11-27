---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: payment gateway partners (PayPal, Stripe) and donations and payments made through Giveffect
    text: We encrypt all donations and payments made at the highest security standard - PCI Level 1 Compliance
    type: PCI Level 1 compliance
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: certified data centers where private information is stored
    text: certified data centers with SSAE16 certifications, 24x7 monitoring
    type: SSAE16 certification of data centers
  trust_center:
    url: https://www.giveffect.com/security
frameworks:
- PCI-DSS
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Giveffect
provenance_date: '2026-11-09'
provider_name: Giveffect
provider_slug: giveffect
slug: giveffect-compliance
source_date: '2026-11-09'
source_filename: giveffect-compliance.yml
source_heading: Compliance
source_page: https://www.giveffect.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Giveffect\naid: giveffect\nurl: https://www.giveffect.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.giveffect.com/security\nattestations:\n- framework: PCI-DSS\n  type: PCI Level 1 compliance\n  scope: payment gateway partners (PayPal, Stripe) and donations and payments made through Giveffect\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We encrypt all donations and payments made at the highest security standard - PCI Level 1 Compliance\n- framework: other\n  type: SSAE16 certification of data centers\n  scope: certified data centers where private information\
  \ is stored\n  period: null\n  issuer: null\n  report_access: unstated\n  text: certified data centers with SSAE16 certifications, 24x7 monitoring\n"
source_yaml_url: https://artifacts.apis.io/giveffect/compliance/giveffect-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Giveffect's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Non-Profit
- Fundraising
- CRM
- Donations
- Volunteer Management
- Marketing Automation
- Software-as-a-Service
---
