---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Legit Security - SOC2 Type II
    type: SOC 2 Type II report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Legit Security Ltd. - ISO IEC 27001 2022 Official Certificate
    type: ISO/IEC 27001:2022 certificate
  trust_center:
    url: https://trust.legitsecurity.com/
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Legit Security
provenance_date: '2026-11-09'
provider_name: Legit Security
provider_slug: legit-security
slug: legit-security-compliance
source_date: '2026-11-09'
source_filename: legit-security-compliance.yml
source_heading: Compliance
source_page: https://trust.legitsecurity.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Legit Security\naid: legit-security\nurl: https://trust.legitsecurity.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/legit-security-trust-center.yml\ntrust_center:\n  url: https://trust.legitsecurity.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Legit Security - SOC2 Type II\n- framework: ISO27001\n  type: ISO/IEC 27001:2022 certificate\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Legit Security Ltd. - ISO IEC 27001 2022 Official Certificate\n"
source_yaml_url: https://artifacts.apis.io/legit-security/compliance/legit-security-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Legit Security's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- Application Security
- ASPM
- DevSecOps
- Software Supply Chain Security
- Secrets Detection
- SAST
- Software Composition Analysis
- Compliance
- AI Security
- MCP
---
