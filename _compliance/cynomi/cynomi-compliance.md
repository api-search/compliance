---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: security, availability, confidentiality, privacy
    text: SOC 2 Type II Demonstrates controls across security, availability, confidentiality, and privacy, ensuring reliable protection and ongoing operational maturity.
    type: SOC 2 Type II report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: information security management system
    text: Validates a robust Information Security Management System (ISMS) covering people, processes, and technology through continual risk management.
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: on_request
    scope: personal data handling
    text: Cynomi complies with GDPR and supports secure data handling, including deletion and access requests.
    type: compliance statement
  trust_center:
    url: https://cynomi.com/security/
frameworks:
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Cynomi
provenance_date: '2026-11-09'
provider_name: Cynomi
provider_slug: cynomi
slug: cynomi-compliance
source_date: '2026-11-09'
source_filename: cynomi-compliance.yml
source_heading: Compliance
source_page: https://cynomi.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Cynomi\naid: cynomi\nurl: https://cynomi.com/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://cynomi.com/security/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: security, availability, confidentiality, privacy\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Type II Demonstrates controls across security, availability, confidentiality, and privacy, ensuring\n    reliable protection and ongoing operational maturity.\n- framework: ISO27001\n  type: certification\n  scope: information security management system\n  period: null\n  issuer: null\n\
  \  report_access: on_request\n  text: Validates a robust Information Security Management System (ISMS) covering people, processes, and technology\n    through continual risk management.\n- framework: GDPR\n  type: compliance statement\n  scope: personal data handling\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Cynomi complies with GDPR and supports secure data handling, including deletion and access requests.\n"
source_yaml_url: https://artifacts.apis.io/cynomi/compliance/cynomi-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Cynomi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- Security
- Compliance
- vCISO
- Risk Management
- GRC
- MSP
- MSSP
- Vulnerability Management
---
