---
claim_count: 3
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
  - framework: CyberEssentials
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: UK Cyber Essentials Plus
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 report
    type: report
  trust_center:
    url: https://trust.fyld.ai/
frameworks:
- CyberEssentials
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: FYLD
provenance_date: '2026-11-09'
provider_name: FYLD
provider_slug: fyld
slug: fyld-compliance
source_date: '2026-11-09'
source_filename: fyld-compliance.yml
source_heading: Compliance
source_page: https://trust.fyld.ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: FYLD\naid: fyld\nurl: https://trust.fyld.ai/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/fyld-trust-center.yml\ntrust_center:\n  url: https://trust.fyld.ai/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022\n- framework: CyberEssentials\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: UK Cyber Essentials Plus\n- framework: SOC2\n  type: report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2\
  \ report\n"
source_yaml_url: https://artifacts.apis.io/fyld/compliance/fyld-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from FYLD's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Industrial, Energy & Iot
- Field Operations
- Utilities
- Energy
- Construction
- Artificial Intelligence
- Frontline Intelligence
- Infrastructure
- Safety
---
