---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: accredited external body
    period: null
    report_access: on_request
    scope: information security management system (ISMS)
    text: Timely is ISO 27001:2022 certified
    type: certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: product
    text: Timely isn’t currently HIPAA compliant.
    type: not held
  trust_center:
    url: https://www.timely.com/security/
frameworks:
- HIPAA
- ISO27001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Timely (Memory AS)
provenance_date: '2026-11-10'
provider_name: Timely (Memory AS)
provider_slug: timely
slug: timely-compliance
source_date: '2026-11-10'
source_filename: timely-compliance.yml
source_heading: Compliance
source_page: https://www.timely.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Timely (Memory AS)\naid: timely\nurl: https://www.timely.com/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.timely.com/security/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: information security management system (ISMS)\n  period: null\n  issuer: accredited external body\n  report_access: on_request\n  text: Timely is ISO 27001:2022 certified\n- framework: HIPAA\n  type: not held\n  scope: product\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Timely isn’t currently HIPAA compliant.\n"
source_yaml_url: https://artifacts.apis.io/timely/compliance/timely-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Timely (Memory AS)'s own page on 2026-11-10.
synthetic: false
tags:
- Company
- Time Tracking
- Artificial Intelligence
- Software-as-a-Service
- Productivity
---
