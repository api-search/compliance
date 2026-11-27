---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Primary EU storage, DPA + SCCs, documented ROPA, data-subject requests honored
    text: GDPR — primary EU storage, DPA + SCCs, documented ROPA, data-subject requests honored.
    type: Compliance posture statement
  trust_center:
    url: https://aient.ai/security
frameworks:
- GDPR
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Aient
provenance_date: '2026-11-09'
provider_name: Aient
provider_slug: aient-ai
slug: aient-ai-compliance
source_date: '2026-11-09'
source_filename: aient-ai-compliance.yml
source_heading: Compliance
source_page: https://aient.ai/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Aient\naid: aient-ai\nurl: https://aient.ai/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://aient.ai/security\nattestations:\n- framework: GDPR\n  type: Compliance posture statement\n  scope: Primary EU storage, DPA + SCCs, documented ROPA, data-subject requests honored\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR — primary EU storage, DPA + SCCs, documented ROPA, data-subject requests honored.\n"
source_yaml_url: https://artifacts.apis.io/aient-ai/compliance/aient-ai-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Aient's own page on 2026-11-09.
synthetic: false
tags:
- AI SRE
- Automated Fixes
- DevOps
---
