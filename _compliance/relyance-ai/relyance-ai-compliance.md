---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Request SOC 2 Type 2 Report
    type: Type 2 report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Request ISO 27001 Certificate
    type: Certificate
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Request CSA CAIQv4
    type: CAIQv4 questionnaire
  trust_center:
    url: https://trust.relyance.ai/
frameworks:
- CSA-STAR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Relyance Ai
provenance_date: '2026-11-10'
provider_name: Relyance Ai
provider_slug: relyance-ai
slug: relyance-ai-compliance
source_date: '2026-11-10'
source_filename: relyance-ai-compliance.yml
source_heading: Compliance
source_page: https://trust.relyance.ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Relyance Ai\naid: relyance-ai\nurl: https://trust.relyance.ai/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.relyance.ai/\nattestations:\n- framework: SOC2\n  type: Type 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Request SOC 2 Type 2 Report\n- framework: ISO27001\n  type: Certificate\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Request ISO 27001 Certificate\n- framework: CSA-STAR\n  type: CAIQv4 questionnaire\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Request CSA\
  \ CAIQv4\n"
source_yaml_url: https://artifacts.apis.io/relyance-ai/compliance/relyance-ai-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Relyance Ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data Security
- Privacy
- AI Security
- AI Governance
- Data Governance
- Compliance
- Consent Management
- Data Discovery
---
