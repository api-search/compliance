---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: UXPin
    text: UXPin is certified too, as PCI DSS A-EP 3.2.
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: infrastructure hosted by AWS
    text: UXPin uses SOC 2 certified infrastructure hosted by AWS.
    type: attestation of hosting infrastructure
  trust_center:
    url: https://www.uxpin.com/security
frameworks:
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: UXPin
provenance_date: '2026-11-10'
provider_name: UXPin
provider_slug: uxpin
slug: uxpin-compliance
source_date: '2026-11-10'
source_filename: uxpin-compliance.yml
source_heading: Compliance
source_page: https://www.uxpin.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: UXPin\naid: uxpin\nurl: https://www.uxpin.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.uxpin.com/security\nattestations:\n- framework: PCI-DSS\n  type: certification\n  scope: UXPin\n  period: null\n  issuer: null\n  report_access: unstated\n  text: UXPin is certified too, as PCI DSS A-EP 3.2.\n- framework: SOC2\n  type: attestation of hosting infrastructure\n  scope: infrastructure hosted by AWS\n  period: null\n  issuer: null\n  report_access: unstated\n  text: UXPin uses SOC 2 certified infrastructure hosted by AWS.\n"
source_yaml_url: https://artifacts.apis.io/uxpin/compliance/uxpin-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from UXPin's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Design
- Prototyping
- Design Systems
- React
- Components
- Artificial Intelligence
- Developer Tools
---
