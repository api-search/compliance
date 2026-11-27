---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: Licensed SOC 1 and SOC 2 Auditor
    period: null
    report_access: on_request
    scope: security
    text: We have been externally audited by a Licensed SOC 1 and SOC 2 Auditor, and are compliant with the SOC 2 Type II standard for security with no control exceptions.
    type: SOC 2 Type II audit
  - framework: ISO27001
    issuer: The Centre for Assessment
    period: null
    report_access: on_request
    scope: Information Security Management System
    text: The Centre for Assessment confirms that our Information Security Management System has been audited and the requirements met for ISO/IEC 27001:2022.
    type: ISO/IEC 27001:2022 certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: data protection
    text: GDPR is a priority to us.
    type: GDPR compliance
  trust_center:
    url: https://youcanbook.me/security
frameworks:
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: YouCanBook.me
provenance_date: '2026-11-10'
provider_name: YouCanBook.me
provider_slug: youcanbook-me
slug: youcanbook-me-compliance
source_date: '2026-11-10'
source_filename: youcanbook-me-compliance.yml
source_heading: Compliance
source_page: https://youcanbook.me/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: YouCanBook.me\naid: youcanbook-me\nurl: https://youcanbook.me/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://youcanbook.me/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II audit\n  scope: security\n  period: null\n  issuer: Licensed SOC 1 and SOC 2 Auditor\n  report_access: on_request\n  text: We have been externally audited by a Licensed SOC 1 and SOC 2 Auditor, and are compliant with the SOC 2\n    Type II standard for security with no control exceptions.\n- framework: ISO27001\n  type: ISO/IEC 27001:2022 certification\n  scope: Information Security Management System\n  period:\
  \ null\n  issuer: The Centre for Assessment\n  report_access: on_request\n  text: The Centre for Assessment confirms that our Information Security Management System has been audited and\n    the requirements met for ISO/IEC 27001:2022.\n- framework: GDPR\n  type: GDPR compliance\n  scope: data protection\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR is a priority to us.\n"
source_yaml_url: https://artifacts.apis.io/youcanbook-me/compliance/youcanbook-me-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from YouCanBook.me's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Scheduling
- Software-as-a-Service
- Automation
- Integration
---
