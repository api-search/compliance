---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent auditors
    period: null
    report_access: on_request
    scope: security, availability, and confidentiality controls
    text: Independently audited for security, availability, and confidentiality controls over an extended observation period.
    type: Type II
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Enterprise plan customers requiring HIPAA compliance
    text: Yes. We sign Business Associate Agreements for customers on our Enterprise plan who require HIPAA compliance.
    type: Business Associate Agreements
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: data subject rights and data processing agreements
    text: GDPR-Ready
    type: GDPR-ready data handling
  trust_center:
    url: https://www.warp.co/security
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Warp
provenance_date: '2026-11-09'
provider_name: Warp
provider_slug: joinwarp-com
slug: joinwarp-com-compliance
source_date: '2026-11-09'
source_filename: joinwarp-com-compliance.yml
source_heading: Compliance
source_page: https://www.warp.co/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Warp\naid: joinwarp-com\nurl: https://www.warp.co/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.warp.co/security\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: security, availability, and confidentiality controls\n  period: null\n  issuer: independent auditors\n  report_access: on_request\n  text: Independently audited for security, availability, and confidentiality controls over an extended observation\n    period.\n- framework: HIPAA\n  type: Business Associate Agreements\n  scope: Enterprise plan customers requiring HIPAA compliance\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: Yes. We sign Business Associate Agreements for customers on our Enterprise plan who require HIPAA compliance.\n- framework: GDPR\n  type: GDPR-ready data handling\n  scope: data subject rights and data processing agreements\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR-Ready\n"
source_yaml_url: https://artifacts.apis.io/joinwarp-com/compliance/joinwarp-com-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Warp's own page on 2026-11-09.
synthetic: false
tags:
- Payroll
- Benefits
- Tax Compliance
- IT Management
- Global Payroll
- HRIS
- AI Agents
---
