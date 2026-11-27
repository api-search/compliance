---
api_specs:
- filename: azuga-azuga-ws-oauth-api-openapi.yml
  format: yaml
  label: Azuga Azuga Ws Oauth API
  slug: azuga-azuga-ws-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/azuga/openapi/azuga-azuga-ws-oauth-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: third-party evaluation
    period: null
    report_access: on_request
    scope: Azuga infrastructure and information
    text: Request access to more information about Azuga's SOC2 certification
    type: Type 2 certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: software applications, internal operational processes, and Azuga Fleet hardware devices
    text: Azuga is ISO/IEC 27001:2022 certified based on the International Standard for Information Security Management Systems (ISMS).
    type: ISO/IEC 27001:2022 certification
  trust_center:
    url: https://www.azuga.com/security
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Azuga
provenance_date: '2026-11-09'
provider_name: Azuga
provider_slug: azuga
slug: azuga-compliance
source_date: '2026-11-09'
source_filename: azuga-compliance.yml
source_heading: Compliance
source_page: https://www.azuga.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Azuga\naid: azuga\nurl: https://www.azuga.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.azuga.com/security\nattestations:\n- framework: SOC2\n  type: Type 2 certification\n  scope: Azuga infrastructure and information\n  period: null\n  issuer: third-party evaluation\n  report_access: on_request\n  text: Request access to more information about Azuga's SOC2 certification\n- framework: ISO27001\n  type: ISO/IEC 27001:2022 certification\n  scope: software applications, internal operational processes, and Azuga Fleet hardware devices\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: Azuga is ISO/IEC 27001:2022 certified based on the International Standard for Information Security Management\n    Systems (ISMS).\n"
source_yaml_url: https://artifacts.apis.io/azuga/compliance/azuga-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Azuga's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fleet Management
- GPS Tracking
- Telematics
- Software-as-a-Service
---
