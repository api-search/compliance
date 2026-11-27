---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: RB2B is SOC2 Type 2 Certified and CCPA Compliant.
    type: Type 2 certification
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: RB2B is SOC2 Type 2 Certified and CCPA Compliant.
    type: compliance
  trust_center:
    url: https://www.rb2b.com/security
frameworks:
- CCPA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: RB2B
provenance_date: '2026-11-10'
provider_name: RB2B
provider_slug: rb2b
slug: rb2b-compliance
source_date: '2026-11-10'
source_filename: rb2b-compliance.yml
source_heading: Compliance
source_page: https://www.rb2b.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: RB2B\naid: rb2b\nurl: https://www.rb2b.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/rb2b-trust-center.yml\ntrust_center:\n  url: https://www.rb2b.com/security\nattestations:\n- framework: SOC2\n  type: Type 2 certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: RB2B is SOC2 Type 2 Certified and CCPA Compliant.\n- framework: CCPA\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: RB2B is SOC2 Type 2 Certified and CCPA Compliant.\n"
source_yaml_url: https://artifacts.apis.io/rb2b/compliance/rb2b-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from RB2B's own page on 2026-11-10.
synthetic: false
tags:
- Identity Resolution
- Visitor Identification
- B2B Data
- Lead Generation
- Sales Intelligence
- Marketing
- Data Enrichment
- LinkedIn Enrichment
- Hashed Email
- Mobile Ad ID
- Firmographics
- Webhook
- Pixel
- AdTech
- Identity Graph
- MCP
---
