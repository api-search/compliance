---
api_specs:
- filename: datavant-configuration-api-openapi.yml
  format: yaml
  label: Datavant Configuration API
  slug: datavant-configuration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datavant/openapi/datavant-configuration-api-openapi.yml
- filename: datavant-documents-api-openapi.yml
  format: yaml
  label: Datavant Documents API
  slug: datavant-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datavant/openapi/datavant-documents-api-openapi.yml
- filename: datavant-order-queries-api-openapi.yml
  format: yaml
  label: Datavant Order Queries API
  slug: datavant-order-queries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datavant/openapi/datavant-order-queries-api-openapi.yml
- filename: datavant-orders-api-openapi.yml
  format: yaml
  label: Datavant Orders API
  slug: datavant-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datavant/openapi/datavant-orders-api-openapi.yml
- filename: datavant-prematch-api-openapi.yml
  format: yaml
  label: Datavant Prematch API
  slug: datavant-prematch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datavant/openapi/datavant-prematch-api-openapi.yml
- filename: datavant-projects-api-openapi.yml
  format: yaml
  label: Datavant Projects API
  slug: datavant-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datavant/openapi/datavant-projects-api-openapi.yml
- filename: datavant-visits-api-openapi.yml
  format: yaml
  label: Datavant Visits API
  slug: datavant-visits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datavant/openapi/datavant-visits-api-openapi.yml
- filename: datavant-oauth2-api-openapi.yml
  format: yaml
  label: Datavant Oauth2 API
  slug: datavant-oauth2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datavant/openapi/datavant-oauth2-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: accredited independent certification body
    period: null
    report_access: on_request
    scope: Information Security Management System (ISMS)
    text: Datavant maintains ISO/IEC 27001:2022 certification for our Information Security Management System (ISMS), issued by an accredited independent certification body.
    type: ISO/IEC 27001:2022 certification
  - framework: other
    issuer: AHIMA and HCCA
    period: null
    report_access: unstated
    scope: Privacy and Compliance team credentials
    source: https://www.datavant.com/about/privacy-compliance
    text: We hold a myriad of credentials, including, but not limited to, RHIAs, RHITs, CHPS (AHIMA Certified Credentials), CHPC, and CHRC (HCCA Certified Credentials).
    type: staff professional credentials (RHIA, RHIT, CHPS, CHPC, CHRC)
  trust_center:
    url: https://trust.datavant.com/home
frameworks:
- ISO27001
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Datavant
provenance_date: '2026-11-09'
provider_name: Datavant
provider_slug: datavant
slug: datavant-compliance
source_date: '2026-11-09'
source_filename: datavant-compliance.yml
source_heading: Compliance
source_page: https://trust.datavant.com/home
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Datavant\naid: datavant\nurl: https://trust.datavant.com/home\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://trust.datavant.com/home\n  - https://www.datavant.com/about/privacy-compliance\ntrust_center:\n  url: https://trust.datavant.com/home\nattestations:\n- framework: ISO27001\n  type: ISO/IEC 27001:2022 certification\n  scope: Information Security Management System (ISMS)\n  period: null\n  issuer: accredited independent certification body\n  report_access: on_request\n  text: Datavant maintains ISO/IEC 27001:2022 certification for our Information Security Management System (ISMS),\n    issued by an accredited\
  \ independent certification body.\n- framework: other\n  type: staff professional credentials (RHIA, RHIT, CHPS, CHPC, CHRC)\n  scope: Privacy and Compliance team credentials\n  period: null\n  issuer: AHIMA and HCCA\n  report_access: unstated\n  text: We hold a myriad of credentials, including, but not limited to, RHIAs, RHITs, CHPS (AHIMA Certified Credentials),\n    CHPC, and CHRC (HCCA Certified Credentials).\n  source: https://www.datavant.com/about/privacy-compliance\n"
source_yaml_url: https://artifacts.apis.io/datavant/compliance/datavant-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Datavant's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- United States
- Interoperability
- Health Data
- De-Identification
- Tokenization
- Real-World Data
- Record Retrieval
- Data Connectivity
- Life Sciences
- HIPAA
- Medical Records
- Release of Information
- Privacy
- OAuth
- Health Information Exchange
- Authentication
---
