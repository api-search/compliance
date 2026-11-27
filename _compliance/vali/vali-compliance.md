---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: home care agency services
    text: Vali is HIPAA-compliant, signs a Business Associate Agreement (BAA) with every home care agency customer
    type: compliance with regulation as business associate
  trust_center:
    url: https://vali.health/security
frameworks:
- HIPAA
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Vali
provenance_date: '2026-11-10'
provider_name: Vali
provider_slug: vali
slug: vali-compliance
source_date: '2026-11-10'
source_filename: vali-compliance.yml
source_heading: Compliance
source_page: https://vali.health/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Vali\naid: vali\nurl: https://vali.health/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://vali.health/security\nattestations:\n- framework: HIPAA\n  type: compliance with regulation as business associate\n  scope: home care agency services\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Vali is HIPAA-compliant, signs a Business Associate Agreement (BAA) with every home care agency customer\n"
source_yaml_url: https://artifacts.apis.io/vali/compliance/vali-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Vali's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Home Care
- Healthcare
- Workforce
---
