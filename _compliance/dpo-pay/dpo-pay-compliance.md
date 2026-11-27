---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: DPO processes payments from customers all across the globe hence the requirement for us to be GDPR compliant
    type: regulatory compliance statement
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: DPO Pay is PCI DSS Level 1 Certified
    type: certification
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: POPIA (South Africa)
    text: DPO is also POPIA compiant.
    type: regulatory compliance statement
  trust_center:
    url: https://dpogroup.com/compliance/
frameworks:
- GDPR
- PCI-DSS
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: DPO Pay
provenance_date: '2026-11-09'
provider_name: DPO Pay
provider_slug: dpo-pay
slug: dpo-pay-compliance
source_date: '2026-11-09'
source_filename: dpo-pay-compliance.yml
source_heading: Compliance
source_page: https://dpogroup.com/compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: DPO Pay\naid: dpo-pay\nurl: https://dpogroup.com/compliance/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://dpogroup.com/compliance/\nattestations:\n- framework: GDPR\n  type: regulatory compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: DPO processes payments from customers all across the globe hence the requirement for us to be GDPR compliant\n- framework: PCI-DSS\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: DPO Pay is PCI DSS Level 1 Certified\n- framework: other\n  type: regulatory compliance\
  \ statement\n  scope: POPIA (South Africa)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: DPO is also POPIA compiant.\n"
source_yaml_url: https://artifacts.apis.io/dpo-pay/compliance/dpo-pay-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from DPO Pay's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Africa
- Fintech
- E-Commerce
---
