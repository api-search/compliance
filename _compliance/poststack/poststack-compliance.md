---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Built around GDPR Articles 28 and 32 with a published DPA.
    type: compliance statement
  trust_center:
    url: https://poststack.dev/trust
frameworks:
- GDPR
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: PostStack
provenance_date: '2026-11-10'
provider_name: PostStack
provider_slug: poststack
slug: poststack-compliance
source_date: '2026-11-10'
source_filename: poststack-compliance.yml
source_heading: Compliance
source_page: https://poststack.dev/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: PostStack\naid: poststack\nurl: https://poststack.dev/trust\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/poststack-trust-center.yml\ntrust_center:\n  url: https://poststack.dev/trust\nattestations:\n- framework: GDPR\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Built around GDPR Articles 28 and 32 with a published DPA.\n"
source_yaml_url: https://artifacts.apis.io/poststack/compliance/poststack-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from PostStack's own page on 2026-11-10.
synthetic: false
tags:
- Email
- Public APIs
---
