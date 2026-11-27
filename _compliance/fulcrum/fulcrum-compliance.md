---
api_specs:
- filename: fulcrum-audio-api-openapi.yml
  format: yaml
  label: Fulcrum Audio API
  slug: fulcrum-audio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fulcrum/openapi/fulcrum-audio-api-openapi.yml
- filename: fulcrum-changesets-api-openapi.yml
  format: yaml
  label: Fulcrum Changesets API
  slug: fulcrum-changesets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fulcrum/openapi/fulcrum-changesets-api-openapi.yml
- filename: fulcrum-choice-lists-api-openapi.yml
  format: yaml
  label: Fulcrum Choice Lists API
  slug: fulcrum-choice-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fulcrum/openapi/fulcrum-choice-lists-api-openapi.yml
- filename: fulcrum-classification-sets-api-openapi.yml
  format: yaml
  label: Fulcrum Classification Sets API
  slug: fulcrum-classification-sets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fulcrum/openapi/fulcrum-classification-sets-api-openapi.yml
- filename: fulcrum-forms-api-openapi.yml
  format: yaml
  label: Fulcrum Forms API
  slug: fulcrum-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fulcrum/openapi/fulcrum-forms-api-openapi.yml
- filename: fulcrum-layers-api-openapi.yml
  format: yaml
  label: Fulcrum Layers API
  slug: fulcrum-layers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fulcrum/openapi/fulcrum-layers-api-openapi.yml
- filename: fulcrum-memberships-api-openapi.yml
  format: yaml
  label: Fulcrum Memberships API
  slug: fulcrum-memberships-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fulcrum/openapi/fulcrum-memberships-api-openapi.yml
- filename: fulcrum-photos-api-openapi.yml
  format: yaml
  label: Fulcrum Photos API
  slug: fulcrum-photos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fulcrum/openapi/fulcrum-photos-api-openapi.yml
- filename: fulcrum-projects-api-openapi.yml
  format: yaml
  label: Fulcrum Projects API
  slug: fulcrum-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fulcrum/openapi/fulcrum-projects-api-openapi.yml
- filename: fulcrum-query-api-openapi.yml
  format: yaml
  label: Fulcrum Query API
  slug: fulcrum-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fulcrum/openapi/fulcrum-query-api-openapi.yml
- filename: fulcrum-records-api-openapi.yml
  format: yaml
  label: Fulcrum Records API
  slug: fulcrum-records-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fulcrum/openapi/fulcrum-records-api-openapi.yml
- filename: fulcrum-roles-api-openapi.yml
  format: yaml
  label: Fulcrum Roles API
  slug: fulcrum-roles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fulcrum/openapi/fulcrum-roles-api-openapi.yml
- filename: fulcrum-signatures-api-openapi.yml
  format: yaml
  label: Fulcrum Signatures API
  slug: fulcrum-signatures-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fulcrum/openapi/fulcrum-signatures-api-openapi.yml
- filename: fulcrum-videos-api-openapi.yml
  format: yaml
  label: Fulcrum Videos API
  slug: fulcrum-videos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fulcrum/openapi/fulcrum-videos-api-openapi.yml
- filename: fulcrum-webhooks-api-openapi.yml
  format: yaml
  label: Fulcrum Webhooks API
  slug: fulcrum-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fulcrum/openapi/fulcrum-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: CPA-certified external auditors
    period: on a yearly basis
    report_access: unstated
    scope: design and operational effectiveness of internal controls
    text: Fulcrum is audited on a yearly basis by CPA-certified external auditors who issue a SOC 2 report regarding the design and operational effectiveness of internal controls.
    type: SOC 2 report
  - framework: ISO27001
    issuer: null
    period: cycle start date of October 14, 2026, and an expiration date of October 13, 2029
    report_access: unstated
    scope: Fulcrum application
    text: Fulcrum officially achieved its ISO/IEC 27001:2022 certification with a cycle start date of October 14, 2026, and an expiration date of October 13, 2029.
    type: ISO/IEC 27001:2022 certification
  trust_center:
    url: https://www.fulcrumapp.com/security/
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Fulcrum
provenance_date: '2026-11-09'
provider_name: Fulcrum
provider_slug: fulcrum
slug: fulcrum-compliance
source_date: '2026-11-09'
source_filename: fulcrum-compliance.yml
source_heading: Compliance
source_page: https://www.fulcrumapp.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Fulcrum\naid: fulcrum\nurl: https://www.fulcrumapp.com/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/fulcrum-trust-center.yml\ntrust_center:\n  url: https://www.fulcrumapp.com/security/\nattestations:\n- framework: SOC2\n  type: SOC 2 report\n  scope: design and operational effectiveness of internal controls\n  period: on a yearly basis\n  issuer: CPA-certified external auditors\n  report_access: unstated\n  text: Fulcrum is audited on a yearly basis by CPA-certified external auditors who issue a SOC 2 report regarding\n    the design and operational effectiveness of internal controls.\n\
  - framework: ISO27001\n  type: ISO/IEC 27001:2022 certification\n  scope: Fulcrum application\n  period: cycle start date of October 14, 2026, and an expiration date of October 13, 2029\n  issuer: null\n  report_access: unstated\n  text: Fulcrum officially achieved its ISO/IEC 27001:2022 certification with a cycle start date of October 14,\n    2026, and an expiration date of October 13, 2029.\n"
source_yaml_url: https://artifacts.apis.io/fulcrum/compliance/fulcrum-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Fulcrum's own page on 2026-11-09.
synthetic: false
tags:
- Data Collection
- Field Data
- Geospatial
- Process Management
- Mobile
---
