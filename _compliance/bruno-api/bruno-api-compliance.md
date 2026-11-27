---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: AICPA Trust Services Criteria
    text: SOC 2 Type II Certified Independently audited against the AICPA Trust Services Criteria.
    type: Type II
  trust_center:
    url: https://www.usebruno.com/security
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Bruno
provenance_date: '2026-11-09'
provider_name: Bruno
provider_slug: bruno-api
slug: bruno-api-compliance
source_date: '2026-11-09'
source_filename: bruno-api-compliance.yml
source_heading: Compliance
source_page: https://www.usebruno.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Bruno\naid: bruno-api\nurl: https://www.usebruno.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/bruno-api-trust-center.yml\ntrust_center:\n  url: https://www.usebruno.com/security\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: AICPA Trust Services Criteria\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II Certified Independently audited against the AICPA Trust Services Criteria.\n"
source_yaml_url: https://artifacts.apis.io/bruno-api/compliance/bruno-api-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Bruno's own page on 2026-11-09.
synthetic: false
tags:
- API Client
- API Testing
- Developer Tools
- Open Source
- Git-Native
- CLI
- Postman Alternative
- A2A
- Testing
---
