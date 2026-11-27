---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent auditor
    period: null
    report_access: on_request
    scope: not stated
    text: SOC 2 Type II Independently audited with zero findings, zero exceptions. Full reports available via our Trust Portal.
    type: Type II audit
  - framework: other
    issuer: Google App Defense Alliance
    period: null
    report_access: unstated
    scope: Google's App Defense Alliance
    text: CASA Tier 2 Google's App Defense Alliance security assessment, certified at Tier 2.
    type: CASA Tier 2 security assessment
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    source: https://trust.stilla.ai/
    text: We are SOC 2 Type II certified with a clean report
    type: SOC 2 Type II report
  trust_center:
    url: https://stilla.ai/security
frameworks:
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Stilla
provenance_date: '2026-11-10'
provider_name: Stilla
provider_slug: stilla
slug: stilla-compliance
source_date: '2026-11-10'
source_filename: stilla-compliance.yml
source_heading: Compliance
source_page: https://stilla.ai/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Stilla\naid: stilla\nurl: https://stilla.ai/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://stilla.ai/security\n  - https://trust.stilla.ai/\ntrust_center:\n  url: https://stilla.ai/security\nattestations:\n- framework: SOC2\n  type: Type II audit\n  scope: not stated\n  period: null\n  issuer: independent auditor\n  report_access: on_request\n  text: SOC 2 Type II Independently audited with zero findings, zero exceptions. Full reports available via our\n    Trust Portal.\n- framework: other\n  type: CASA Tier 2 security assessment\n  scope: Google's App Defense Alliance\n  period: null\n  issuer:\
  \ Google App Defense Alliance\n  report_access: unstated\n  text: CASA Tier 2 Google's App Defense Alliance security assessment, certified at Tier 2.\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: We are SOC 2 Type II certified with a clean report\n  source: https://trust.stilla.ai/\n"
source_yaml_url: https://artifacts.apis.io/stilla/compliance/stilla-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Stilla's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Productivity
- Collaboration
- MCP
- Automation
- Developer Tools
- Enterprise
---
