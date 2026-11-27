---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: security controls and systems used to store and process users' data
    text: Salto has successfully completed a SOC 2 Type II audit, providing our customers assurance regarding our security controls and the systems used to store and process users’ data
    type: SOC 2 Type II audit
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: most recent report
    text: A copy of Salto’s most recent report is available upon request.
    type: SOC report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: AWS global infrastructure supporting Salto
    text: 'This infrastructure is designed and managed according to security best practices as well as a variety of security compliance standards : FedRAMP, HIPAA, ISO 27001:2013, AICPA SOC 1, SOC 2, SOC 3, PCI DSS, and more.'
    type: AWS infrastructure compliance standard
  trust_center:
    url: https://www.salto.io/security-overview
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Salto
provenance_date: '2026-11-10'
provider_name: Salto
provider_slug: salto
slug: salto-compliance
source_date: '2026-11-10'
source_filename: salto-compliance.yml
source_heading: Compliance
source_page: https://www.salto.io/security-overview
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Salto\naid: salto\nurl: https://www.salto.io/security-overview\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.salto.io/security-overview\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II audit\n  scope: security controls and systems used to store and process users' data\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Salto has successfully completed a SOC 2 Type II audit, providing our customers assurance regarding our\n    security controls and the systems used to store and process users’ data\n- framework: SOC2\n  type: SOC report\n  scope: most recent report\n  period:\
  \ null\n  issuer: null\n  report_access: on_request\n  text: A copy of Salto’s most recent report is available upon request.\n- framework: ISO27001\n  type: AWS infrastructure compliance standard\n  scope: AWS global infrastructure supporting Salto\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'This infrastructure is designed and managed according to security best practices as well as a variety of\n    security compliance standards : FedRAMP, HIPAA, ISO 27001:2013, AICPA SOC 1, SOC 2, SOC 3, PCI DSS, and more.'\n"
source_yaml_url: https://artifacts.apis.io/salto/compliance/salto-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Salto's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cloud Saas
- Configuration Management
- DevOps
- Change Management
- CI/CD
- Salesforce
- NetSuite
- SaaS Management
- AI Agents
- Developer Tools
---
