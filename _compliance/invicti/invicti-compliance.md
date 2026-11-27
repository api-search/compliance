---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: security, availability, processing integrity, confidentiality, and data privacy
    text: Our SOC 2 Type 2 report validates internal controls and systems related to security availability, processing integrity, confidentiality, and data privacy.
    type: SOC 2 Type 2 report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: Information Security Management Systems
    text: Our Information Security Management Systems meet international security standards in data protection.
    type: ISO 27001:2025 certificate
  trust_center:
    url: https://www.invicti.com/compliance
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Invicti
provenance_date: '2026-11-09'
provider_name: Invicti
provider_slug: invicti
slug: invicti-compliance
source_date: '2026-11-09'
source_filename: invicti-compliance.yml
source_heading: Compliance
source_page: https://www.invicti.com/compliance
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Invicti\naid: invicti\nurl: https://www.invicti.com/compliance\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/invicti-trust-center.yml\ntrust_center:\n  url: https://www.invicti.com/compliance\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: security, availability, processing integrity, confidentiality, and data privacy\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Our SOC 2 Type 2 report validates internal controls and systems related to security availability, processing\n    integrity, confidentiality, and data privacy.\n- framework: ISO27001\n  type:\
  \ ISO 27001:2025 certificate\n  scope: Information Security Management Systems\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Our Information Security Management Systems meet international security standards in data protection.\n"
source_yaml_url: https://artifacts.apis.io/invicti/compliance/invicti-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Invicti's own page on 2026-11-09.
synthetic: false
tags:
- API Security
- DAST
- Security
- Vulnerability Scanning
---
