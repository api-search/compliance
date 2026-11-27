---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: FedRAMP
    issuer: unstated
    period: null
    report_access: unstated
    scope: unstated
    text: ✓ FedRAMP Ready for Agency Authorization
    type: FedRAMP Ready for Agency Authorization
  - framework: NIST-CSF
    issuer: a leading global research and advisory firm
    period: '2025'
    report_access: unstated
    scope: Equifax corporate security program
    text: with a 2025 National Institute of Standards Technology (NIST) Cybersecurity Framework (CSF) score of 4.4
    type: NIST Cybersecurity Framework score assessed by third-party advisory firm
  trust_center:
    url: https://www.equifax.com/about-equifax/security/
frameworks:
- FedRAMP
- NIST-CSF
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Equifax
provenance_date: '2026-11-09'
provider_name: Equifax
provider_slug: equifax
slug: equifax-compliance
source_date: '2026-11-09'
source_filename: equifax-compliance.yml
source_heading: Compliance
source_page: https://www.equifax.com/about-equifax/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Equifax\naid: equifax\nurl: https://www.equifax.com/about-equifax/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/equifax-trust-center.yml\ntrust_center:\n  url: https://www.equifax.com/about-equifax/security/\nattestations:\n- framework: FedRAMP\n  type: FedRAMP Ready for Agency Authorization\n  scope: unstated\n  period: null\n  issuer: unstated\n  report_access: unstated\n  text: ✓ FedRAMP Ready for Agency Authorization\n- framework: NIST-CSF\n  type: NIST Cybersecurity Framework score assessed by third-party advisory firm\n  scope: Equifax corporate security program\n  period: '2025'\n\
  \  issuer: a leading global research and advisory firm\n  report_access: unstated\n  text: with a 2025 National Institute of Standards Technology (NIST) Cybersecurity Framework (CSF) score of 4.4\n"
source_yaml_url: https://artifacts.apis.io/equifax/compliance/equifax-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Equifax's own page on 2026-11-09.
synthetic: false
tags:
- Credit
- Credit History
- Credit Reporting
- Identity
- Fraud Prevention
- Fortune 1000
---
