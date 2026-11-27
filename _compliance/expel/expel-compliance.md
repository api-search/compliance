---
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: '2026'
    report_access: unstated
    scope: null
    text: Expel - 2026 SOC 2 Type 2 - Report.pdf
    type: SOC 2 Type 2 report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001:2022 Certificate
    type: ISO 27001:2022 certificate
  - framework: ISO27701
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: we maintain SOC 2, ISO 27001, ISO 27701, NIST 800-171, and others - all Third Party verified
    type: ISO 27701 certification
  - framework: NIST-800-53
    issuer: null
    period: '2026'
    report_access: unstated
    scope: null
    text: Expel - 2026 NIST 800-171 Compliance Assessment - Report (1).pdf
    type: NIST 800-171 compliance assessment report
  - framework: GDPR
    issuer: null
    period: '2026'
    report_access: unstated
    scope: null
    text: Expel - 2026 GDPR Type 1 .pdf
    type: GDPR Type 1 report
  trust_center:
    url: https://security.expel.com/
frameworks:
- GDPR
- ISO27001
- ISO27701
- NIST-800-53
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Expel
provenance_date: '2026-11-09'
provider_name: Expel
provider_slug: expel
slug: expel-compliance
source_date: '2026-11-09'
source_filename: expel-compliance.yml
source_heading: Compliance
source_page: https://security.expel.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Expel\naid: expel\nurl: https://security.expel.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/expel-trust-center.yml\ntrust_center:\n  url: https://security.expel.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: null\n  period: '2026'\n  issuer: null\n  report_access: unstated\n  text: Expel - 2026 SOC 2 Type 2 - Report.pdf\n- framework: ISO27001\n  type: ISO 27001:2022 certificate\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022 Certificate\n- framework: ISO27701\n  type: ISO 27701 certification\n  scope: null\n  period:\
  \ null\n  issuer: null\n  report_access: unstated\n  text: we maintain SOC 2, ISO 27001, ISO 27701, NIST 800-171, and others - all Third Party verified\n- framework: NIST-800-53\n  type: NIST 800-171 compliance assessment report\n  scope: null\n  period: '2026'\n  issuer: null\n  report_access: unstated\n  text: Expel - 2026 NIST 800-171 Compliance Assessment - Report (1).pdf\n- framework: GDPR\n  type: GDPR Type 1 report\n  scope: null\n  period: '2026'\n  issuer: null\n  report_access: unstated\n  text: Expel - 2026 GDPR Type 1 .pdf\n"
source_yaml_url: https://artifacts.apis.io/expel/compliance/expel-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Expel's own page on 2026-11-09.
synthetic: false
tags:
- Cybersecurity
- MDR
- Managed Detection and Response
- SOC
- SIEM
- Workbench
---
