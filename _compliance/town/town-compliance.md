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
    text: request access to independent audit reports and certifications
    type: SOC 2 Type 1 Report
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: request access to independent audit reports and certifications
    type: SOC 2 Type 2 Report
  - framework: other
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: request access to independent audit reports and certifications
    type: CASA Tier 2 Report
  trust_center:
    url: https://trust.town.com/
frameworks:
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Town
provenance_date: '2026-11-10'
provider_name: Town
provider_slug: town
slug: town-compliance
source_date: '2026-11-10'
source_filename: town-compliance.yml
source_heading: Compliance
source_page: https://trust.town.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Town\naid: town\nurl: https://trust.town.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/town-trust-center.yml\ntrust_center:\n  url: https://trust.town.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 1 Report\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: request access to independent audit reports and certifications\n- framework: SOC2\n  type: SOC 2 Type 2 Report\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: request access to independent audit reports and certifications\n- framework: other\n  type: CASA Tier\
  \ 2 Report\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: request access to independent audit reports and certifications\n"
source_yaml_url: https://artifacts.apis.io/town/compliance/town-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Town's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Agents
- Personal Assistant
- Productivity
- Email
- Calendar
- Automation
---
