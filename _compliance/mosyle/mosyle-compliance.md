---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: AICPA certified auditor
    period: null
    report_access: on_request
    scope: Mosyle controls protecting confidentiality, integrity, and availability of customer data
    text: In 2020, we first achieved our SOC 2 Type II certification.
    type: Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Mosyle services
    text: Mosyle is compliant with GDPR.
    type: compliance statement
  trust_center:
    url: https://business.mosyle.com/security
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Mosyle
provenance_date: '2026-11-10'
provider_name: Mosyle
provider_slug: mosyle
slug: mosyle-compliance
source_date: '2026-11-10'
source_filename: mosyle-compliance.yml
source_heading: Compliance
source_page: https://business.mosyle.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Mosyle\naid: mosyle\nurl: https://business.mosyle.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://business.mosyle.com/security\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: Mosyle controls protecting confidentiality, integrity, and availability of customer data\n  period: null\n  issuer: AICPA certified auditor\n  report_access: on_request\n  text: In 2020, we first achieved our SOC 2 Type II certification.\n- framework: GDPR\n  type: compliance statement\n  scope: Mosyle services\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Mosyle is compliant with\
  \ GDPR.\n"
source_yaml_url: https://artifacts.apis.io/mosyle/compliance/mosyle-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Mosyle's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Apple
- Device Management
- MDM
- Endpoint Security
- Identity
- SSO
- macOS
- iOS
- IT Operations
- Security
---
