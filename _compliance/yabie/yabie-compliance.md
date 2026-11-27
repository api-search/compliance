---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: unstated
    period: '2026'
    report_access: on_request
    scope: unstated
    text: PCI-DSS AoC 2026
    type: Attestation of Compliance (AoC)
  - framework: GDPR
    issuer: unstated
    period: null
    report_access: unstated
    scope: unstated
    text: GDPR Compliance Policy
    type: policy document
  trust_center:
    url: https://trust.yabie.com/
frameworks:
- GDPR
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Yabie
provenance_date: '2026-11-10'
provider_name: Yabie
provider_slug: yabie
slug: yabie-compliance
source_date: '2026-11-10'
source_filename: yabie-compliance.yml
source_heading: Compliance
source_page: https://trust.yabie.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Yabie\naid: yabie\nurl: https://trust.yabie.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/yabie-trust-center.yml\ntrust_center:\n  url: https://trust.yabie.com/\nattestations:\n- framework: PCI-DSS\n  type: Attestation of Compliance (AoC)\n  scope: unstated\n  period: '2026'\n  issuer: unstated\n  report_access: on_request\n  text: PCI-DSS AoC 2026\n- framework: GDPR\n  type: policy document\n  scope: unstated\n  period: null\n  issuer: unstated\n  report_access: unstated\n  text: GDPR Compliance Policy\n"
source_yaml_url: https://artifacts.apis.io/yabie/compliance/yabie-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Yabie's own page on 2026-11-10.
synthetic: false
tags:
- Company
---
