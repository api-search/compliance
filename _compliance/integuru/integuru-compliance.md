---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: integrations touching protected health information
    text: Integuru is HIPAA-compliant and signs Business Associate Agreements at no additional cost, for any integration that touches protected health information.
    type: HIPAA compliance and BAA
  trust_center:
    url: https://www.integuru.com/trust
frameworks:
- HIPAA
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Integuru
provenance_date: '2026-11-09'
provider_name: Integuru
provider_slug: integuru
slug: integuru-compliance
source_date: '2026-11-09'
source_filename: integuru-compliance.yml
source_heading: Compliance
source_page: https://www.integuru.com/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Integuru\naid: integuru\nurl: https://www.integuru.com/trust\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.integuru.com/trust\nattestations:\n- framework: HIPAA\n  type: HIPAA compliance and BAA\n  scope: integrations touching protected health information\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Integuru is HIPAA-compliant and signs Business Associate Agreements at no additional cost, for any integration\n    that touches protected health information.\n"
source_yaml_url: https://artifacts.apis.io/integuru/compliance/integuru-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Integuru's own page on 2026-11-09.
synthetic: false
tags:
- Company
- API Generation
- Automation
- Integration
- Y Combinator
---
