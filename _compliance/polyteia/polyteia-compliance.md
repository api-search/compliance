---
api_specs:
- filename: polyteia-organization-api-openapi.yml
  format: yaml
  label: Polyteia Organization API
  slug: polyteia-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polyteia/openapi/polyteia-organization-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: all areas
    text: Polyteia ensures compliance with the GDPR in all areas and relies on standards and recommendations from Bitkom-Consult.
    type: GDPR compliance statement
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: IT security concept
    text: Polyteia maintains an IT security concept in accordance with the IT protection of the German Federal Office for Information Security (BSI).
    type: BSI IT protection concept
  trust_center:
    url: https://www.polyteia.com/resources/data-security
frameworks:
- GDPR
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Polyteia
provenance_date: '2026-11-10'
provider_name: Polyteia
provider_slug: polyteia
slug: polyteia-compliance
source_date: '2026-11-10'
source_filename: polyteia-compliance.yml
source_heading: Compliance
source_page: https://www.polyteia.com/resources/data-security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Polyteia\naid: polyteia\nurl: https://www.polyteia.com/resources/data-security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/polyteia-trust-center.yml\ntrust_center:\n  url: https://www.polyteia.com/resources/data-security\nattestations:\n- framework: GDPR\n  type: GDPR compliance statement\n  scope: all areas\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Polyteia ensures compliance with the GDPR in all areas and relies on standards and recommendations from\n    Bitkom-Consult.\n- framework: other\n  type: BSI IT protection concept\n  scope: IT security concept\n  period: null\n\
  \  issuer: null\n  report_access: unstated\n  text: Polyteia maintains an IT security concept in accordance with the IT protection of the German Federal Office\n    for Information Security (BSI).\n"
source_yaml_url: https://artifacts.apis.io/polyteia/compliance/polyteia-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Polyteia's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Ai Enterprise Software
- GovTech
- Public Sector
- Data Platform
- Government
- Data Analytics
- Germany
- Business Intelligence
- No-Code
---
