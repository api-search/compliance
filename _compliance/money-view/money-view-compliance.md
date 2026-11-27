---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PCI DSS Certified
    type: certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Information Security Management System
    text: ISO 27001:2022 Certified Information Security Management System
    type: certification
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: RBI guidelines on data security and digital lending
    text: We follow RBI guidelines on data security and digital lending
    type: regulatory compliance statement
  trust_center:
    url: https://moneyview.in:443/security-money-view-app
frameworks:
- ISO27001
- PCI-DSS
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Money View
provenance_date: '2026-11-10'
provider_name: Money View
provider_slug: money-view
slug: money-view-compliance
source_date: '2026-11-10'
source_filename: money-view-compliance.yml
source_heading: Compliance
source_page: https://moneyview.in:443/security-money-view-app
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Money View\naid: money-view\nurl: https://moneyview.in:443/security-money-view-app\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://moneyview.in:443/security-money-view-app\nattestations:\n- framework: PCI-DSS\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI DSS Certified\n- framework: ISO27001\n  type: certification\n  scope: Information Security Management System\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022 Certified Information Security Management System\n- framework: other\n  type: regulatory compliance\
  \ statement\n  scope: RBI guidelines on data security and digital lending\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We follow RBI guidelines on data security and digital lending\n"
source_yaml_url: https://artifacts.apis.io/money-view/compliance/money-view-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Money View's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Fintech
- Lending
- Personal Loans
- Credit
- Payments
- Insurance
- India
---
