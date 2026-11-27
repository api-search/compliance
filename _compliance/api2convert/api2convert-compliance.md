---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: company
    text: Our company complies with the General Data Protection Regulation (GDPR)
    type: self-stated compliance
  trust_center:
    url: https://www.api2convert.com/security
frameworks:
- GDPR
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Api2Convert
provenance_date: '2026-11-09'
provider_name: Api2Convert
provider_slug: api2convert
slug: api2convert-compliance
source_date: '2026-11-09'
source_filename: api2convert-compliance.yml
source_heading: Compliance
source_page: https://www.api2convert.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Api2Convert\naid: api2convert\nurl: https://www.api2convert.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/api2convert-trust-center.yml\ntrust_center:\n  url: https://www.api2convert.com/security\nattestations:\n- framework: GDPR\n  type: self-stated compliance\n  scope: company\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our company complies with the General Data Protection Regulation (GDPR)\n"
source_yaml_url: https://artifacts.apis.io/api2convert/compliance/api2convert-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Api2Convert's own page on 2026-11-09.
synthetic: false
tags:
- Public APIs
- File Conversion
- Documents
---
