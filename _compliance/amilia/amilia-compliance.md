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
    text: Amilia SOC 2 Type 2 Report
    type: Type 2
  - framework: PCI-DSS
    issuer: null
    period: January 2026
    report_access: unstated
    scope: null
    text: Amilia PCI DSS Service Provider Level 1 | Attestation of Compliance (AOC) January 2026
    type: Attestation of Compliance (AOC), Service Provider Level 1
  trust_center:
    url: https://trust.amilia.com/
frameworks:
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Amilia
provenance_date: '2026-11-09'
provider_name: Amilia
provider_slug: amilia
slug: amilia-compliance
source_date: '2026-11-09'
source_filename: amilia-compliance.yml
source_heading: Compliance
source_page: https://trust.amilia.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Amilia\naid: amilia\nurl: https://trust.amilia.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.amilia.com/\nattestations:\n- framework: SOC2\n  type: Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Amilia SOC 2 Type 2 Report\n- framework: PCI-DSS\n  type: Attestation of Compliance (AOC), Service Provider Level 1\n  scope: null\n  period: January 2026\n  issuer: null\n  report_access: unstated\n  text: Amilia PCI DSS Service Provider Level 1 | Attestation of Compliance (AOC) January 2026\n"
source_yaml_url: https://artifacts.apis.io/amilia/compliance/amilia-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Amilia's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Software
- Membership
- Recreation
- Facilities
- Payments
---
