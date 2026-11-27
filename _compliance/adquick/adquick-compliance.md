---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: AdQuick Inc. SOC2 Type II 04.23.25
    type: SOC 2 Type II report
  - framework: SOC3
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: AdQuick, Inc. SOC 3 Report 5.6.26.pdf
    type: SOC 3 report
  trust_center:
    url: https://trust.adquick.com/
frameworks:
- SOC2
- SOC3
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: AdQuick
provenance_date: '2026-11-09'
provider_name: AdQuick
provider_slug: adquick
slug: adquick-compliance
source_date: '2026-11-09'
source_filename: adquick-compliance.yml
source_heading: Compliance
source_page: https://trust.adquick.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: AdQuick\naid: adquick\nurl: https://trust.adquick.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/adquick-trust-center.yml\ntrust_center:\n  url: https://trust.adquick.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AdQuick Inc. SOC2 Type II 04.23.25\n- framework: SOC3\n  type: SOC 3 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AdQuick, Inc. SOC 3 Report 5.6.26.pdf\n"
source_yaml_url: https://artifacts.apis.io/adquick/compliance/adquick-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from AdQuick's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Enterprise Saas
- Advertising
- Out-of-Home Advertising
- Digital Out Of Home
- Programmatic Advertising
- Media Buying
- Marketing
- MCP
---
