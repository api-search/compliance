---
api_specs:
- filename: seven-bridges-action-api-openapi.yml
  format: yaml
  label: Seven Bridges Action API
  slug: seven-bridges-action-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-bridges/openapi/seven-bridges-action-api-openapi.yml
- filename: seven-bridges-api-settings-api-openapi.yml
  format: yaml
  label: Seven Bridges API Settings API
  slug: seven-bridges-api-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-bridges/openapi/seven-bridges-api-settings-api-openapi.yml
- filename: seven-bridges-apps-api-openapi.yml
  format: yaml
  label: Seven Bridges Apps API
  slug: seven-bridges-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-bridges/openapi/seven-bridges-apps-api-openapi.yml
- filename: seven-bridges-billing-api-openapi.yml
  format: yaml
  label: Seven Bridges Billing API
  slug: seven-bridges-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-bridges/openapi/seven-bridges-billing-api-openapi.yml
- filename: seven-bridges-bulk-api-openapi.yml
  format: yaml
  label: Seven Bridges Bulk API
  slug: seven-bridges-bulk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-bridges/openapi/seven-bridges-bulk-api-openapi.yml
- filename: seven-bridges-files-api-openapi.yml
  format: yaml
  label: Seven Bridges Files API
  slug: seven-bridges-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-bridges/openapi/seven-bridges-files-api-openapi.yml
- filename: seven-bridges-https-api-openapi.yml
  format: yaml
  label: 'Seven Bridges Https: API'
  slug: seven-bridges-https-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-bridges/openapi/seven-bridges-https-api-openapi.yml
- filename: seven-bridges-projects-api-openapi.yml
  format: yaml
  label: Seven Bridges Projects API
  slug: seven-bridges-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-bridges/openapi/seven-bridges-projects-api-openapi.yml
- filename: seven-bridges-rate-limit-api-openapi.yml
  format: yaml
  label: Seven Bridges Rate Limit API
  slug: seven-bridges-rate-limit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-bridges/openapi/seven-bridges-rate-limit-api-openapi.yml
- filename: seven-bridges-search-api-openapi.yml
  format: yaml
  label: Seven Bridges Search API
  slug: seven-bridges-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-bridges/openapi/seven-bridges-search-api-openapi.yml
- filename: seven-bridges-seven-bridges-platform-api-openapi.yml
  format: yaml
  label: Seven Bridges Seven Bridges Platform API
  slug: seven-bridges-seven-bridges-platform-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-bridges/openapi/seven-bridges-seven-bridges-platform-api-openapi.yml
- filename: seven-bridges-storage-api-openapi.yml
  format: yaml
  label: Seven Bridges Storage API
  slug: seven-bridges-storage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-bridges/openapi/seven-bridges-storage-api-openapi.yml
- filename: seven-bridges-tasks-api-openapi.yml
  format: yaml
  label: Seven Bridges Tasks API
  slug: seven-bridges-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-bridges/openapi/seven-bridges-tasks-api-openapi.yml
- filename: seven-bridges-upload-api-openapi.yml
  format: yaml
  label: Seven Bridges Upload API
  slug: seven-bridges-upload-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-bridges/openapi/seven-bridges-upload-api-openapi.yml
- filename: seven-bridges-user-api-openapi.yml
  format: yaml
  label: Seven Bridges User API
  slug: seven-bridges-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-bridges/openapi/seven-bridges-user-api-openapi.yml
- filename: seven-bridges-users-api-openapi.yml
  format: yaml
  label: Seven Bridges Users API
  slug: seven-bridges-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-bridges/openapi/seven-bridges-users-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: third-party accredited certification body (Schellman)
    period: null
    report_access: public
    scope: ISMS supporting cloud-based environments and related information systems owned or operated by Seven Bridges
    text: Our ISO certificate is publicly available on the website of our third-party accredited certification body
    type: certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: on_request
    scope: Seven Bridges Platform; treats all clients as HIPAA-regulated
    text: Seven Bridges has entered into a Business Associate Agreement with Amazon Web Services
    type: compliance posture (Business Associate)
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: processing of EU personal data
    text: Seven Bridges operates as both a Data Processor and a Data Controller.
    type: compliance posture (data processor and controller)
  - framework: other
    issuer: U.S. Department of Commerce (International Trade Administration)
    period: since 2016
    report_access: public
    scope: data transfers from the EEA to the United States
    text: We have also self-validated as a requirement of the EU-U.S. Privacy Shield since 2016 for data transfers from the EEA to the United States.
    type: EU-U.S. Privacy Shield self-validation
  trust_center:
    url: https://www.sevenbridges.com/library/white-papers/compliance/
frameworks:
- GDPR
- HIPAA
- ISO27001
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Seven Bridges
provenance_date: '2026-11-10'
provider_name: Seven Bridges
provider_slug: seven-bridges
slug: seven-bridges-compliance
source_date: '2026-11-10'
source_filename: seven-bridges-compliance.yml
source_heading: Compliance
source_page: https://www.sevenbridges.com/library/white-papers/compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Seven Bridges\naid: seven-bridges\nurl: https://www.sevenbridges.com/library/white-papers/compliance/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/seven-bridges-trust-center.yml\ntrust_center:\n  url: https://www.sevenbridges.com/library/white-papers/compliance/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: ISMS supporting cloud-based environments and related information systems owned or operated by Seven Bridges\n  period: null\n  issuer: third-party accredited certification body (Schellman)\n  report_access: public\n  text: Our ISO certificate is publicly available on\
  \ the website of our third-party accredited certification body\n- framework: HIPAA\n  type: compliance posture (Business Associate)\n  scope: Seven Bridges Platform; treats all clients as HIPAA-regulated\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Seven Bridges has entered into a Business Associate Agreement with Amazon Web Services\n- framework: GDPR\n  type: compliance posture (data processor and controller)\n  scope: processing of EU personal data\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Seven Bridges operates as both a Data Processor and a Data Controller.\n- framework: other\n  type: EU-U.S. Privacy Shield self-validation\n  scope: data transfers from the EEA to the United States\n  period: since 2016\n  issuer: U.S. Department of Commerce (International Trade Administration)\n  report_access: public\n  text: We have also self-validated as a requirement of the EU-U.S. Privacy Shield since 2016 for data transfers\n    from the EEA\
  \ to the United States.\n"
source_yaml_url: https://artifacts.apis.io/seven-bridges/compliance/seven-bridges-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Seven Bridges's own page on 2026-11-10.
synthetic: false
tags:
- Genomics
- Bioinformatics
- Life Sciences
- Healthcare
- Cloud Computing
- Data Analysis
- Workflow Automation
- Research
- Precision Medicine
- Common Workflow Language
- File Storage
- Company
---
