---
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: security, availability, and confidentiality
    text: Avrea is SOC 2 Type II certified and undergoes annual audits covering security, availability, and confidentiality.
    type: SOC 2 Type II
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: information security management system
    text: Avrea's information security management system is certified to ISO/IEC 27001, the international standard for systematic security controls.
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: data protection requirements
    text: Avrea complies with GDPR requirements through strong data protection, access controls, logging, and retention practices.
    type: compliance
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.avrea.com/
    text: Avrea - ISO 27001 Certificate Apr-2026
    type: certificate
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.avrea.com/
    text: Avrea SOC 2 Type 2 Attestation Confirmation
    type: Type 2
  trust_center:
    url: https://avrea.com/trust-security
frameworks:
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Avrea
provenance_date: '2026-11-09'
provider_name: Avrea
provider_slug: avrea
slug: avrea-compliance
source_date: '2026-11-09'
source_filename: avrea-compliance.yml
source_heading: Compliance
source_page: https://avrea.com/trust-security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Avrea\naid: avrea\nurl: https://avrea.com/trust-security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://avrea.com/trust-security\n  - https://trust.avrea.com/\ntrust_center:\n  url: https://avrea.com/trust-security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: security, availability, and confidentiality\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Avrea is SOC 2 Type II certified and undergoes annual audits covering security, availability, and confidentiality.\n- framework: ISO27001\n  type: certification\n  scope: information security management system\n  period:\
  \ null\n  issuer: null\n  report_access: unstated\n  text: Avrea's information security management system is certified to ISO/IEC 27001, the international standard\n    for systematic security controls.\n- framework: GDPR\n  type: compliance\n  scope: data protection requirements\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Avrea complies with GDPR requirements through strong data protection, access controls, logging, and retention\n    practices.\n- framework: ISO27001\n  type: certificate\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Avrea - ISO 27001 Certificate Apr-2026\n  source: https://trust.avrea.com/\n- framework: SOC2\n  type: Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Avrea SOC 2 Type 2 Attestation Confirmation\n  source: https://trust.avrea.com/\n"
source_yaml_url: https://artifacts.apis.io/avrea/compliance/avrea-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Avrea's own page on 2026-11-09.
synthetic: false
tags:
- Company
- CI/CD
- Continuous Integration
- GitHub Actions
- Build Infrastructure
- Runners
- Caching
- Observability
- DevOps
- Developer Tools
---
