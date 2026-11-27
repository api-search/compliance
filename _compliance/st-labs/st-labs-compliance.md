---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: STLabs platform
    text: STLabs is SOC 2 compliant.
    type: SOC 2 compliant claim
  trust_center:
    url: https://stlabs.com/security
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: ST Labs
provenance_date: '2026-11-10'
provider_name: ST Labs
provider_slug: st-labs
slug: st-labs-compliance
source_date: '2026-11-10'
source_filename: st-labs-compliance.yml
source_heading: Compliance
source_page: https://stlabs.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: ST Labs\naid: st-labs\nurl: https://stlabs.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/st-labs-trust-center.yml\ntrust_center:\n  url: https://stlabs.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 compliant claim\n  scope: STLabs platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: STLabs is SOC 2 compliant.\n"
source_yaml_url: https://artifacts.apis.io/st-labs/compliance/st-labs-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from ST Labs's own page on 2026-11-10.
synthetic: false
tags:
- Company
- ITSM
- IT Operations
- AI Agents
- Workflow Automation
- Service Desk
- Digital Twin
- Enterprise Software
---
