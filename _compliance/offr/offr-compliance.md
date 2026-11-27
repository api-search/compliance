---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Offr's AWS data center partners
    text: Our data center partners are SOC 2 Type II and ISO 27001 certified
    type: data center partner certification
  trust_center:
    url: https://offr.io/security
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Offr
provenance_date: '2026-11-10'
provider_name: Offr
provider_slug: offr
slug: offr-compliance
source_date: '2026-11-10'
source_filename: offr-compliance.yml
source_heading: Compliance
source_page: https://offr.io/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Offr\naid: offr\nurl: https://offr.io/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/offr-trust-center.yml\ntrust_center:\n  url: https://offr.io/security\nattestations:\n- framework: SOC2\n  type: data center partner certification\n  scope: Offr's AWS data center partners\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our data center partners are SOC 2 Type II and ISO 27001 certified\n"
source_yaml_url: https://artifacts.apis.io/offr/compliance/offr-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Offr's own page on 2026-11-10.
synthetic: false
tags:
- Company
- PropTech
- Real Estate
- Property Transactions
- Auctions
- Lettings
- Offer Management
- Ireland
---
