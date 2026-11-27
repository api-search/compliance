---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001:2022
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: regulatory compliance
  trust_center:
    url: https://trust.seamflow.com/
frameworks:
- GDPR
- ISO27001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Seamflow
provenance_date: '2026-11-10'
provider_name: Seamflow
provider_slug: seamflow
slug: seamflow-compliance
source_date: '2026-11-10'
source_filename: seamflow-compliance.yml
source_heading: Compliance
source_page: https://trust.seamflow.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Seamflow\naid: seamflow\nurl: https://trust.seamflow.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/seamflow-trust-center.yml\ntrust_center:\n  url: https://trust.seamflow.com/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022\n- framework: GDPR\n  type: regulatory compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n"
source_yaml_url: https://artifacts.apis.io/seamflow/compliance/seamflow-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Seamflow's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise Saas
- Artificial Intelligence
- Compliance
- Certification
- Regulatory
- Testing Inspection Certification
- Workflow Automation
- Medical Devices
---
