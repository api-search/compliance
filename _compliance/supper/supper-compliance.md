---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: Annual audit
    report_access: on_request
    scope: Supper platform
    text: SOC 2 Type II Annual audit · report on request
    type: SOC 2 Type II audit
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: EU data handling & residency controls
    text: GDPR-compliant EU data handling & residency controls
    type: GDPR-compliant EU data handling
  - framework: other
    issuer: third-party
    period: null
    report_access: on_request
    scope: Regular third-party tests
    text: Regular third-party tests · summary available
    type: Penetration testing
  trust_center:
    url: https://www.supper.co/security
frameworks:
- GDPR
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Supper
provenance_date: '2026-11-10'
provider_name: Supper
provider_slug: supper
slug: supper-compliance
source_date: '2026-11-10'
source_filename: supper-compliance.yml
source_heading: Compliance
source_page: https://www.supper.co/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Supper\naid: supper\nurl: https://www.supper.co/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.supper.co/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II audit\n  scope: Supper platform\n  period: Annual audit\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Type II Annual audit · report on request\n- framework: GDPR\n  type: GDPR-compliant EU data handling\n  scope: EU data handling & residency controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR-compliant EU data handling & residency controls\n- framework: other\n  type: Penetration\
  \ testing\n  scope: Regular third-party tests\n  period: null\n  issuer: third-party\n  report_access: on_request\n  text: Regular third-party tests · summary available\n"
source_yaml_url: https://artifacts.apis.io/supper/compliance/supper-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Supper's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data
- Analytics
- Artificial Intelligence
- MCP
- Business Intelligence
- Semantic Layer
- Data Agent
---
