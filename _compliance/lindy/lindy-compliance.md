---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: security controls
    text: HIPAA Compliance Security controls mapped to HIPAA requirements.
    type: compliance
  - framework: SOC2
    issuer: Johanson Group
    period: null
    report_access: on_request
    scope: null
    text: SOC 2 Type II Certified Audited by Johanson Group.
    type: SOC 2 Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: security controls
    text: GDPR Compliance Validates operational effectiveness of security controls.
    type: compliance
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PIPEDA Compliance Regular testing and independent verification.
    type: PIPEDA compliance
  trust_center:
    url: https://www.lindy.ai/security
frameworks:
- GDPR
- HIPAA
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Lindy
provenance_date: '2026-11-09'
provider_name: Lindy
provider_slug: lindy
slug: lindy-compliance
source_date: '2026-11-09'
source_filename: lindy-compliance.yml
source_heading: Compliance
source_page: https://www.lindy.ai/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Lindy\naid: lindy\nurl: https://www.lindy.ai/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.lindy.ai/security\nattestations:\n- framework: HIPAA\n  type: compliance\n  scope: security controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA Compliance Security controls mapped to HIPAA requirements.\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: null\n  issuer: Johanson Group\n  report_access: on_request\n  text: SOC 2 Type II Certified Audited by Johanson Group.\n- framework: GDPR\n  type: compliance\n  scope: security controls\n  period: null\n\
  \  issuer: null\n  report_access: unstated\n  text: GDPR Compliance Validates operational effectiveness of security controls.\n- framework: other\n  type: PIPEDA compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PIPEDA Compliance Regular testing and independent verification.\n"
source_yaml_url: https://artifacts.apis.io/lindy/compliance/lindy-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Lindy's own page on 2026-11-09.
synthetic: false
tags:
- AI Agents
- AI Automation
- MCP
- Workflow Automation
- Virtual Assistant
- Productivity
- Email
- Meetings
- Slack
- A2A
---
