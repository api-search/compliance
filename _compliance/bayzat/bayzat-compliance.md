---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: nda
    scope: HR, payroll, finance and benefits platform (entire HRMS platform)
    text: Yes. Upon request and under NDA, we can share summaries of our ISO/IEC 27001:2022 certificate and SOC 2 Type II audit report to support your compliance review.
    type: certification
  - framework: SOC2
    issuer: Independent auditors
    period: null
    report_access: nda
    scope: security, availability and confidentiality Trust Services Criteria across HRMS platform
    text: Independent auditors have verified our rigorous controls for information security, system availability, data confidentiality, and comprehensive risk management against data breach covering every aspect of your HR, payroll, finance, and benefits data.
    type: Type II audit report
  trust_center:
    url: https://www.bayzat.com/security
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Bayzat
provenance_date: '2026-11-09'
provider_name: Bayzat
provider_slug: bayzat
slug: bayzat-compliance
source_date: '2026-11-09'
source_filename: bayzat-compliance.yml
source_heading: Compliance
source_page: https://www.bayzat.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Bayzat\naid: bayzat\nurl: https://www.bayzat.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.bayzat.com/security\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: HR, payroll, finance and benefits platform (entire HRMS platform)\n  period: null\n  issuer: null\n  report_access: nda\n  text: Yes. Upon request and under NDA, we can share summaries of our ISO/IEC 27001:2022 certificate and SOC 2\n    Type II audit report to support your compliance review.\n- framework: SOC2\n  type: Type II audit report\n  scope: security, availability and confidentiality Trust Services\
  \ Criteria across HRMS platform\n  period: null\n  issuer: Independent auditors\n  report_access: nda\n  text: Independent auditors have verified our rigorous controls for information security, system availability,\n    data confidentiality, and comprehensive risk management against data breach covering every aspect of your HR,\n    payroll, finance, and benefits data.\n"
source_yaml_url: https://artifacts.apis.io/bayzat/compliance/bayzat-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Bayzat's own page on 2026-11-09.
synthetic: false
tags:
- Human Resources
- Payroll
- Benefits
- Software-as-a-Service
- GCC
- Employee Benefits
---
