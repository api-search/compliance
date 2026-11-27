---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: security controls
    text: Report available under NDA.
    type: SOC 2 Type 1 report
  - framework: GDPR
    issuer: null
    period: null
    report_access: on_request
    scope: EU data protection requirements
    text: DPA available on request.
    type: aligned
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: California Consumer Privacy Act requirements
    text: California Consumer Privacy Act requirements met.
    type: compliant
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: ISMS controls
    text: ISMS controls implementation and evidence collection in progress.
    type: in progress
  trust_center:
    url: https://viktor.com/security
frameworks:
- CCPA
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Viktor
provenance_date: '2026-11-10'
provider_name: Viktor
provider_slug: viktor
slug: viktor-compliance
source_date: '2026-11-10'
source_filename: viktor-compliance.yml
source_heading: Compliance
source_page: https://viktor.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Viktor\naid: viktor\nurl: https://viktor.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://viktor.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 1 report\n  scope: security controls\n  period: null\n  issuer: null\n  report_access: nda\n  text: Report available under NDA.\n- framework: GDPR\n  type: aligned\n  scope: EU data protection requirements\n  period: null\n  issuer: null\n  report_access: on_request\n  text: DPA available on request.\n- framework: CCPA\n  type: compliant\n  scope: California Consumer Privacy Act requirements\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: California Consumer Privacy Act requirements met.\n- framework: ISO27001\n  type: in progress\n  scope: ISMS controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISMS controls implementation and evidence collection in progress.\n"
source_yaml_url: https://artifacts.apis.io/viktor/compliance/viktor-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Viktor's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cloud Saas
- Artificial Intelligence
- AI Agents
- Automation
- Slack
- Microsoft Teams
- Productivity
- Workflows
---
