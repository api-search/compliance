---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: Sensiba
    period: null
    report_access: unstated
    scope: Security
    text: Mabel’s SOC 2 Type II report had Security in scope, and did not have any noted exceptions — it was issued with a “clean” audit opinion from Sensiba.
    type: SOC 2 Type II
  - framework: HIPAA
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Customers and prospects who are interested in discussing our commitment to security and reviewing our HIPAA compliance reports can contact privacy@getmabel.com .
    type: HIPAA compliance reports
  trust_center:
    url: https://getmabel.com/soc2-compliance
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Mabel
provenance_date: '2026-11-10'
provider_name: Mabel
provider_slug: mabel
slug: mabel-compliance
source_date: '2026-11-10'
source_filename: mabel-compliance.yml
source_heading: Compliance
source_page: https://getmabel.com/soc2-compliance
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Mabel\naid: mabel\nurl: https://getmabel.com/soc2-compliance\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://getmabel.com/soc2-compliance\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: Security\n  period: null\n  issuer: Sensiba\n  report_access: unstated\n  text: Mabel’s SOC 2 Type II report had Security in scope, and did not have any noted exceptions — it was issued\n    with a “clean” audit opinion from Sensiba.\n- framework: HIPAA\n  type: HIPAA compliance reports\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Customers and prospects who are\
  \ interested in discussing our commitment to security and reviewing our HIPAA\n    compliance reports can contact privacy@getmabel.com .\n"
source_yaml_url: https://artifacts.apis.io/mabel/compliance/mabel-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Mabel's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Medicare
- Accountable Care
- Voluntary Alignment
- Beneficiary Engagement
- Compliance
- HIPAA
---
