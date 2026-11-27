---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent third-party auditor
    period: null
    report_access: on_request
    scope: 'Core BrightAI platform: data ingestion and processing, cloud infrastructure, identity and access management, monitoring and logging'
    text: Security and procurement teams can request our SOC 2 Type II report directly at https://trust.bright.ai/ .
    type: SOC 2 Type II
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.bright.ai/
    text: SOC 2 Certified
    type: Certified
  trust_center:
    url: https://www.bright.ai/trust-and-security
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: BrightAI
provenance_date: '2026-11-09'
provider_name: BrightAI
provider_slug: brightai
slug: brightai-compliance
source_date: '2026-11-09'
source_filename: brightai-compliance.yml
source_heading: Compliance
source_page: https://www.bright.ai/trust-and-security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: BrightAI\naid: brightai\nurl: https://www.bright.ai/trust-and-security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/brightai-trust-center.yml\n  sources:\n  - https://trust.bright.ai/\n  - https://www.bright.ai/trust-and-security\ntrust_center:\n  url: https://www.bright.ai/trust-and-security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: 'Core BrightAI platform: data ingestion and processing, cloud infrastructure, identity and access management,\n    monitoring and logging'\n  period: null\n  issuer: independent third-party auditor\n  report_access: on_request\n  text: Security\
  \ and procurement teams can request our SOC 2 Type II report directly at https://trust.bright.ai/\n    .\n- framework: SOC2\n  type: Certified\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Certified\n  source: https://trust.bright.ai/\n"
source_yaml_url: https://artifacts.apis.io/brightai/compliance/brightai-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from BrightAI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Physical AI
- Industrial IoT
- Infrastructure Monitoring
- Predictive Maintenance
- Edge AI
- Foundation Models
- MCP
- Energy and Utilities
- Water and Wastewater
---
