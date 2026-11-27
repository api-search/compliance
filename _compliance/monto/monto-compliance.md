---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: unstated
    period: consecutively for the past 3 years
    report_access: on_request
    scope: Monto SaaS platform
    text: Monto has been operating in a framework based on SOC 2 type ii, which it has successfully been audited consecutively for the past 3 years.
    type: SOC 2 Type II
  trust_center:
    url: https://montopay.com/compliance-and-security-page/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Monto
provenance_date: '2026-11-10'
provider_name: Monto
provider_slug: monto
slug: monto-compliance
source_date: '2026-11-10'
source_filename: monto-compliance.yml
source_heading: Compliance
source_page: https://montopay.com/compliance-and-security-page/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Monto\naid: monto\nurl: https://montopay.com/compliance-and-security-page/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://montopay.com/compliance-and-security-page/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: Monto SaaS platform\n  period: consecutively for the past 3 years\n  issuer: unstated\n  report_access: on_request\n  text: Monto has been operating in a framework based on SOC 2 type ii, which it has successfully been audited consecutively\n    for the past 3 years.\n"
source_yaml_url: https://artifacts.apis.io/monto/compliance/monto-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Monto's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- B2B Payments
- Accounts Payable
- Invoicing
- Collection
- Supplier Portals
- ERP Integration
---
