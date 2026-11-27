---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC2 type 2 report
    type: Type 2 report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: 'ISO 27001 : 2022'
    type: ISO 27001:2022
  - framework: SOC2
    issuer: unstated
    period: null
    report_access: unstated
    scope: unstated
    source: https://www.deployferry.io/security
    text: SOC 2 Type II certified
    type: Type II
  trust_center:
    url: https://app.bastion.tech/trust-center/d63fae56-11f8-4d0d-9a1a-f68210c9e57d
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Ferry
provenance_date: '2026-11-09'
provider_name: Ferry
provider_slug: ferry
slug: ferry-compliance
source_date: '2026-11-09'
source_filename: ferry-compliance.yml
source_heading: Compliance
source_page: https://app.bastion.tech/trust-center/d63fae56-11f8-4d0d-9a1a-f68210c9e57d
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Ferry\naid: ferry\nurl: https://app.bastion.tech/trust-center/d63fae56-11f8-4d0d-9a1a-f68210c9e57d\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/ferry-trust-center.yml\n  sources:\n  - https://app.bastion.tech/trust-center/d63fae56-11f8-4d0d-9a1a-f68210c9e57d\n  - https://www.deployferry.io/security\ntrust_center:\n  url: https://app.bastion.tech/trust-center/d63fae56-11f8-4d0d-9a1a-f68210c9e57d\nattestations:\n- framework: SOC2\n  type: Type 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC2 type 2 report\n- framework: ISO27001\n  type: ISO 27001:2022\n\
  \  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'ISO 27001 : 2022'\n- framework: SOC2\n  type: Type II\n  scope: unstated\n  period: null\n  issuer: unstated\n  report_access: unstated\n  text: SOC 2 Type II certified\n  source: https://www.deployferry.io/security\n"
source_yaml_url: https://artifacts.apis.io/ferry/compliance/ferry-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Ferry's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Industrial AI
- Manufacturing
- Manufacturing Execution System
- Edge Computing
- Industrial IoT
- Data Integration
- AI Agents
- AWS IoT Greengrass
- Azure IoT Edge
---
