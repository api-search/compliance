---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Akur8 information security management system
    text: ISO 27001-certified
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: security, availability, and confidentiality controls
    text: Can I get a copy of the SOC 2 Type II report? Yes. SOC 2 Type II reports are available through the Akur8 Trust Center. Request access here.
    type: Type II report
  trust_center:
    url: https://www.akur8.com/security
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Akur8
provenance_date: '2026-11-09'
provider_name: Akur8
provider_slug: akur8
slug: akur8-compliance
source_date: '2026-11-09'
source_filename: akur8-compliance.yml
source_heading: Compliance
source_page: https://www.akur8.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Akur8\naid: akur8\nurl: https://www.akur8.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/akur8-trust-center.yml\ntrust_center:\n  url: https://www.akur8.com/security\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: Akur8 information security management system\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001-certified\n- framework: SOC2\n  type: Type II report\n  scope: security, availability, and confidentiality controls\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Can I get a copy of the SOC 2 Type II report?\
  \ Yes. SOC 2 Type II reports are available through the Akur8\n    Trust Center. Request access here.\n"
source_yaml_url: https://artifacts.apis.io/akur8/compliance/akur8-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Akur8's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Insurtech
- Actuarial
- Pricing
- GLM
- Rating Engine
---
