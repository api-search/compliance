---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: public
    scope: null
    text: Download the Type II report
    type: Type II certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: HIPAA compliance documentation & BAA template (Upon Request)
    type: HIPAA compliant & independently audited
  trust_center:
    url: https://www.nomad-data.com/security
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Nomad
provenance_date: '2026-11-10'
provider_name: Nomad
provider_slug: nomad-data-com
slug: nomad-data-com-compliance
source_date: '2026-11-10'
source_filename: nomad-data-com-compliance.yml
source_heading: Compliance
source_page: https://www.nomad-data.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Nomad\naid: nomad-data-com\nurl: https://www.nomad-data.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.nomad-data.com/security\nattestations:\n- framework: SOC2\n  type: Type II certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: public\n  text: Download the Type II report\n- framework: HIPAA\n  type: HIPAA compliant & independently audited\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: HIPAA compliance documentation & BAA template (Upon Request)\n"
source_yaml_url: https://artifacts.apis.io/nomad-data-com/compliance/nomad-data-com-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Nomad's own page on 2026-11-10.
synthetic: false
tags:
- Data Catalog
- Document Insights
- Data Relationship Manager
- AI Search
- Data Spend Management
---
