---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001:2022 Certificate
    type: certificate
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II
    type: SOC 2 Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: compliance
  trust_center:
    url: https://trust.keel.so/
frameworks:
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Keel
provenance_date: '2026-11-09'
provider_name: Keel
provider_slug: keel
slug: keel-compliance
source_date: '2026-11-09'
source_filename: keel-compliance.yml
source_heading: Compliance
source_page: https://trust.keel.so/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Keel\naid: keel\nurl: https://trust.keel.so/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.keel.so/\nattestations:\n- framework: ISO27001\n  type: certificate\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022 Certificate\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II\n- framework: GDPR\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n"
source_yaml_url: https://artifacts.apis.io/keel/compliance/keel-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Keel's own page on 2026-11-09.
synthetic: false
tags:
- Company
- ERP
- Backend
- GraphQL
- Low-Code
- Developer Tools
- Workflows
- Authentication
- TypeScript
---
