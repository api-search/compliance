---
api_specs:
- filename: athelas-auth-api-openapi.yml
  format: yaml
  label: Athelas Auth API
  slug: athelas-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/athelas/openapi/athelas-auth-api-openapi.yml
- filename: athelas-patients-api-openapi.yml
  format: yaml
  label: Athelas Patients API
  slug: athelas-patients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/athelas/openapi/athelas-patients-api-openapi.yml
- filename: athelas-prescribers-api-openapi.yml
  format: yaml
  label: Athelas Prescribers API
  slug: athelas-prescribers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/athelas/openapi/athelas-prescribers-api-openapi.yml
- filename: athelas-sites-api-openapi.yml
  format: yaml
  label: Athelas Sites API
  slug: athelas-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/athelas/openapi/athelas-sites-api-openapi.yml
- filename: athelas-test-types-api-openapi.yml
  format: yaml
  label: Athelas Test Types API
  slug: athelas-test-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/athelas/openapi/athelas-test-types-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: other
    issuer: Drummond Group (ONC-ACB)
    period: null
    report_access: unstated
    scope: Air Health IT Module, CHPL ID 15.04.04.3268.Air1.01.00.1.260617
    text: This Health IT Module is compliant with the ONC Certification Criteria for Health IT and has been certified by an ONC-ACB in accordance with the applicable certification criteria adopted by the Secretary of Health and Human Services.
    type: ONC Health IT Certification Program certification
  trust_center:
    url: https://docs.athelas.com/air_developer/onc_certification/mandatory_disclosure
frameworks:
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Athelas
provenance_date: '2026-11-09'
provider_name: Athelas
provider_slug: athelas
slug: athelas-compliance
source_date: '2026-11-09'
source_filename: athelas-compliance.yml
source_heading: Compliance
source_page: https://docs.athelas.com/air_developer/onc_certification/mandatory_disclosure
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Athelas\naid: athelas\nurl: https://docs.athelas.com/air_developer/onc_certification/mandatory_disclosure\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://docs.athelas.com/air_developer/onc_certification/mandatory_disclosure\nattestations:\n- framework: other\n  type: ONC Health IT Certification Program certification\n  scope: Air Health IT Module, CHPL ID 15.04.04.3268.Air1.01.00.1.260617\n  period: null\n  issuer: Drummond Group (ONC-ACB)\n  report_access: unstated\n  text: This Health IT Module is compliant with the ONC Certification Criteria for Health IT and has been certified\n    by an ONC-ACB\
  \ in accordance with the applicable certification criteria adopted by the Secretary of Health and\n    Human Services.\n"
source_yaml_url: https://artifacts.apis.io/athelas/compliance/athelas-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Athelas's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Remote Patient Monitoring
- Electronic Health Records
- FHIR
- Revenue Cycle Management
- Medical Devices
- SMART on FHIR
- Interoperability
- Artificial Intelligence
---
