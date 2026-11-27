---
claim_count: 6
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: '2026'
    report_access: unstated
    scope: null
    text: SOC2 Type 2 Report 2026
    type: SOC 2 Type II report
  - framework: SOC3
    issuer: null
    period: '2026'
    report_access: unstated
    scope: null
    text: SOC 3 Report 2026
    type: SOC 3 report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: GDPR compliance
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: security, availability, and confidentiality
    source: https://devicie.com/security-operations
    text: Our SOC 2 Type 2 report is available on request to partners and customers under NDA.
    type: Type 2
  - framework: SOC3
    issuer: null
    period: null
    report_access: on_request
    scope: security, availability, and confidentiality
    source: https://devicie.com/security-operations
    text: The SOC 3 report is also available on request.
    type: null
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: privacy
    source: https://devicie.com/security-operations
    text: Devicie also maintains a privacy program to adhere to the requirements of the GDPR EU and UK Privacy regulations
    type: null
  trust_center:
    url: https://trust.devicie.com/
frameworks:
- GDPR
- SOC2
- SOC3
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Devicie
provenance_date: '2026-11-09'
provider_name: Devicie
provider_slug: devicie
slug: devicie-compliance
source_date: '2026-11-09'
source_filename: devicie-compliance.yml
source_heading: Compliance
source_page: https://trust.devicie.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Devicie\naid: devicie\nurl: https://trust.devicie.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://devicie.com/security-operations\n  - https://trust.devicie.com/\ntrust_center:\n  url: https://trust.devicie.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: null\n  period: '2026'\n  issuer: null\n  report_access: unstated\n  text: SOC2 Type 2 Report 2026\n- framework: SOC3\n  type: SOC 3 report\n  scope: null\n  period: '2026'\n  issuer: null\n  report_access: unstated\n  text: SOC 3 Report 2026\n- framework: GDPR\n  type: GDPR compliance\n  scope: null\n  period: null\n  issuer:\
  \ null\n  report_access: unstated\n  text: GDPR\n- framework: SOC2\n  type: Type 2\n  scope: security, availability, and confidentiality\n  period: null\n  issuer: null\n  report_access: nda\n  text: Our SOC 2 Type 2 report is available on request to partners and customers under NDA.\n  source: https://devicie.com/security-operations\n- framework: SOC3\n  type: null\n  scope: security, availability, and confidentiality\n  period: null\n  issuer: null\n  report_access: on_request\n  text: The SOC 3 report is also available on request.\n  source: https://devicie.com/security-operations\n- framework: GDPR\n  type: null\n  scope: privacy\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Devicie also maintains a privacy program to adhere to the requirements of the GDPR EU and UK Privacy regulations\n  source: https://devicie.com/security-operations\n"
source_yaml_url: https://artifacts.apis.io/devicie/compliance/devicie-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from Devicie's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- Device Management
- Endpoint Management
- Microsoft Intune
- Endpoint Security
- Compliance
- Patch Management
---
