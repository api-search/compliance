---
api_specs:
- filename: dun-and-bradstreet-authentication-api-openapi.yml
  format: yaml
  label: Dun & Bradstreet Authentication API
  slug: dun-and-bradstreet-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dun-and-bradstreet/openapi/dun-and-bradstreet-authentication-api-openapi.yml
- filename: dun-and-bradstreet-data-file-api-openapi.yml
  format: yaml
  label: Dun & Bradstreet Data File API
  slug: dun-and-bradstreet-data-file-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dun-and-bradstreet/openapi/dun-and-bradstreet-data-file-api-openapi.yml
- filename: dun-and-bradstreet-enrich-api-openapi.yml
  format: yaml
  label: Dun & Bradstreet Enrich API
  slug: dun-and-bradstreet-enrich-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dun-and-bradstreet/openapi/dun-and-bradstreet-enrich-api-openapi.yml
- filename: dun-and-bradstreet-identity-resolution-api-openapi.yml
  format: yaml
  label: Dun & Bradstreet Identity Resolution API
  slug: dun-and-bradstreet-identity-resolution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dun-and-bradstreet/openapi/dun-and-bradstreet-identity-resolution-api-openapi.yml
- filename: dun-and-bradstreet-monitoring-api-openapi.yml
  format: yaml
  label: Dun & Bradstreet Monitoring API
  slug: dun-and-bradstreet-monitoring-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dun-and-bradstreet/openapi/dun-and-bradstreet-monitoring-api-openapi.yml
- filename: dun-and-bradstreet-multi-process-api-openapi.yml
  format: yaml
  label: Dun & Bradstreet Multi-Process API
  slug: dun-and-bradstreet-multi-process-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dun-and-bradstreet/openapi/dun-and-bradstreet-multi-process-api-openapi.yml
- filename: dun-and-bradstreet-research-api-openapi.yml
  format: yaml
  label: Dun & Bradstreet Research API
  slug: dun-and-bradstreet-research-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dun-and-bradstreet/openapi/dun-and-bradstreet-research-api-openapi.yml
- filename: dun-and-bradstreet-search-api-openapi.yml
  format: yaml
  label: Dun & Bradstreet Search API
  slug: dun-and-bradstreet-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dun-and-bradstreet/openapi/dun-and-bradstreet-search-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent auditor
    period: annually
    report_access: nda
    scope: null
    text: we have an independent auditor certify a SOC2 Type 2 attestation annually, demonstrating operational effectiveness of controls (available under mutual NDA)
    type: SOC 2 Type 2 attestation
  - framework: ISO27001
    issuer: null
    period: annually
    report_access: unstated
    scope: multiple locations
    text: D&B also annually certifies to the ISO/IEC 27001:2022 Information Security Management Systems (ISMS) standard at multiple locations
    type: ISO/IEC 27001:2022 ISMS certification
  - framework: other
    issuer: null
    period: annually
    report_access: unstated
    scope: null
    text: In addition, D&B annually undergoes PCI and SIG assessments.
    type: PCI assessment
  trust_center:
    url: https://www.dnb.com/en-us/utilities/our-security.html
frameworks:
- ISO27001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Dun & Bradstreet
provenance_date: '2026-11-09'
provider_name: Dun & Bradstreet
provider_slug: dun-and-bradstreet
slug: dun-and-bradstreet-compliance
source_date: '2026-11-09'
source_filename: dun-and-bradstreet-compliance.yml
source_heading: Compliance
source_page: https://www.dnb.com/en-us/utilities/our-security.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Dun & Bradstreet\naid: dun-and-bradstreet\nurl: https://www.dnb.com/en-us/utilities/our-security.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.dnb.com/en-us/utilities/our-security.html\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 attestation\n  scope: null\n  period: annually\n  issuer: independent auditor\n  report_access: nda\n  text: we have an independent auditor certify a SOC2 Type 2 attestation annually, demonstrating operational effectiveness\n    of controls (available under mutual NDA)\n- framework: ISO27001\n  type: ISO/IEC 27001:2022 ISMS certification\n  scope: multiple\
  \ locations\n  period: annually\n  issuer: null\n  report_access: unstated\n  text: D&B also annually certifies to the ISO/IEC 27001:2022 Information Security Management Systems (ISMS) standard\n    at multiple locations\n- framework: other\n  type: PCI assessment\n  scope: null\n  period: annually\n  issuer: null\n  report_access: unstated\n  text: In addition, D&B annually undergoes PCI and SIG assessments.\n"
source_yaml_url: https://artifacts.apis.io/dun-and-bradstreet/compliance/dun-and-bradstreet-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Dun & Bradstreet's own page on 2026-11-09.
synthetic: false
tags:
- Business Data
- Company Data
- D-U-N-S Number
- Credit
- Risk Management
- Master Data
- Data Enrichment
- Identity Resolution
- Compliance
- Supply Chain
- Sales Intelligence
- Monitoring
---
