---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: We are ISO 27001:2022 and SOC 2 Type 1 compliant.
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: If you are a customer and need the report or more details, please access our Trust Center .
    type: Type 1 report
  trust_center:
    url: https://www.trustedhealth.com/security
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Trusted Health
provenance_date: '2026-11-10'
provider_name: Trusted Health
provider_slug: trusted-health
slug: trusted-health-compliance
source_date: '2026-11-10'
source_filename: trusted-health-compliance.yml
source_heading: Compliance
source_page: https://www.trustedhealth.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Trusted Health\naid: trusted-health\nurl: https://www.trustedhealth.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.trustedhealth.com/security\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: We are ISO 27001:2022 and SOC 2 Type 1 compliant.\n- framework: SOC2\n  type: Type 1 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: If you are a customer and need the report or more details, please access our Trust Center .\n"
source_yaml_url: https://artifacts.apis.io/trusted-health/compliance/trusted-health-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Trusted Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketplace
- Healthcare
- Nursing
- Staffing
- Travel Nursing
- Allied Health
- Workforce
---
