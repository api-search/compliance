---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: AICPA
    period: null
    report_access: unstated
    scope: unstated
    text: AICPA SOC SOC 2 Type II Certified
    type: SOC 2 Type II
  trust_center:
    url: https://www.diagrid.io/pricing
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Diagrid
provenance_date: '2026-11-09'
provider_name: Diagrid
provider_slug: diagrid
slug: diagrid-compliance
source_date: '2026-11-09'
source_filename: diagrid-compliance.yml
source_heading: Compliance
source_page: https://www.diagrid.io/pricing
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Diagrid\naid: diagrid\nurl: https://www.diagrid.io/pricing\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/diagrid-trust-center.yml\ntrust_center:\n  url: https://www.diagrid.io/pricing\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: unstated\n  period: null\n  issuer: AICPA\n  report_access: unstated\n  text: AICPA SOC SOC 2 Type II Certified\n"
source_yaml_url: https://artifacts.apis.io/diagrid/compliance/diagrid-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Diagrid's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Developer Tools
- AI Agents
- Durable Execution
- Workflows
- Dapr
- MCP
- Microservices
- Cloud-Native
- Distributed Systems
---
