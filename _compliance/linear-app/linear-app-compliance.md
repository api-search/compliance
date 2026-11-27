---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Linear undergoes regular Service Organization Controls audits (SOC 2 Type II). Request SOC 2 →
    type: SOC 2 Type II audit
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Committed to compliance with Europe’s General Data Protection Regulation (GDPR).
    type: compliance commitment
  - framework: HIPAA
    issuer: null
    period: null
    report_access: on_request
    scope: Protected Health Information (PHI)
    text: Privacy and security measures to ensure that Protected Health Information (PHI) is appropriately safeguarded. Request BAA →
    type: privacy and security measures
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: information security management system
    text: Linear has achieved ISO/IEC 27001:2022 certification for its information security management system. Request ISO →
    type: certification
  trust_center:
    url: https://linear.app/security
frameworks:
- GDPR
- HIPAA
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Linear
provenance_date: '2026-11-09'
provider_name: Linear
provider_slug: linear-app
slug: linear-app-compliance
source_date: '2026-11-09'
source_filename: linear-app-compliance.yml
source_heading: Compliance
source_page: https://linear.app/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Linear\naid: linear-app\nurl: https://linear.app/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/linear-app-trust-center.yml\ntrust_center:\n  url: https://linear.app/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II audit\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Linear undergoes regular Service Organization Controls audits (SOC 2 Type II). Request SOC 2 →\n- framework: GDPR\n  type: compliance commitment\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Committed to compliance with Europe’s General\
  \ Data Protection Regulation (GDPR).\n- framework: HIPAA\n  type: privacy and security measures\n  scope: Protected Health Information (PHI)\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Privacy and security measures to ensure that Protected Health Information (PHI) is appropriately safeguarded.\n    Request BAA →\n- framework: ISO27001\n  type: certification\n  scope: information security management system\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Linear has achieved ISO/IEC 27001:2022 certification for its information security management system. Request\n    ISO →\n"
source_yaml_url: https://artifacts.apis.io/linear-app/compliance/linear-app-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Linear's own page on 2026-11-09.
synthetic: false
tags:
- Project Management
- Issue Tracking
- Productivity
- Software-as-a-Service
- GraphQL
- Developer Tools
- Agents
---
