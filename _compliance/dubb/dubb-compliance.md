---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Dubb platform and customer compliance with GDPR requirements
    text: We have introduced tools and processes to ensure our compliance with requirements imposed by the GDPR and to help ensure our customers compliance.
    type: regulatory compliance statement
  trust_center:
    url: https://dubb.com/security
frameworks:
- GDPR
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Dubb
provenance_date: '2026-11-09'
provider_name: Dubb
provider_slug: dubb
slug: dubb-compliance
source_date: '2026-11-09'
source_filename: dubb-compliance.yml
source_heading: Compliance
source_page: https://dubb.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Dubb\naid: dubb\nurl: https://dubb.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://dubb.com/security\nattestations:\n- framework: GDPR\n  type: regulatory compliance statement\n  scope: Dubb platform and customer compliance with GDPR requirements\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We have introduced tools and processes to ensure our compliance with requirements imposed by the GDPR and\n    to help ensure our customers compliance.\n"
source_yaml_url: https://artifacts.apis.io/dubb/compliance/dubb-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Dubb's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
