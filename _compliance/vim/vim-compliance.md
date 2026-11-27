---
api_specs:
- filename: vim-access-token-retrieval-api-openapi.yml
  format: yaml
  label: Vim Access Token Retrieval API
  slug: vim-access-token-retrieval-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vim/openapi/vim-access-token-retrieval-api-openapi.yml
- filename: vim-applications-api-openapi.yml
  format: yaml
  label: Vim Applications API
  slug: vim-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vim/openapi/vim-applications-api-openapi.yml
- filename: vim-appointments-api-openapi.yml
  format: yaml
  label: Vim Appointments API
  slug: vim-appointments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vim/openapi/vim-appointments-api-openapi.yml
- filename: vim-authentication-api-openapi.yml
  format: yaml
  label: Vim Authentication API
  slug: vim-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vim/openapi/vim-authentication-api-openapi.yml
- filename: vim-chart-retrieval-api-openapi.yml
  format: yaml
  label: Vim Chart Retrieval API
  slug: vim-chart-retrieval-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vim/openapi/vim-chart-retrieval-api-openapi.yml
- filename: vim-get-patient-care-insights-api-openapi.yml
  format: yaml
  label: Vim Get Patient Care Insights API
  slug: vim-get-patient-care-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vim/openapi/vim-get-patient-care-insights-api-openapi.yml
- filename: vim-invitations-api-openapi.yml
  format: yaml
  label: Vim Invitations API
  slug: vim-invitations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vim/openapi/vim-invitations-api-openapi.yml
- filename: vim-patient-care-insights-feedback-api-openapi.yml
  format: yaml
  label: Vim Patient Care Insights Feedback API
  slug: vim-patient-care-insights-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vim/openapi/vim-patient-care-insights-feedback-api-openapi.yml
- filename: vim-patient-identification-api-openapi.yml
  format: yaml
  label: Vim Patient Identification API
  slug: vim-patient-identification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vim/openapi/vim-patient-identification-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: HITRUST
    issuer: null
    period: null
    report_access: nda
    scope: HITRUST CSF
    text: Vim has successfully passed the rigorous external audit of HITRUST CSF and SOC 2 Type II
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: null
    text: SOC 2 Type II report, HITRUST CSF certification, penetration test summary, network architecture diagram, and security questionnaire are available on request to qualified customers and partners under NDA.
    type: audit (Type II)
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: acts in compliance with the HIPAA Breach Notification Rule
    type: compliance
  trust_center:
    url: https://www.getvim.ai/trust-center
frameworks:
- HIPAA
- HITRUST
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Vim
provenance_date: '2026-11-10'
provider_name: Vim
provider_slug: vim
slug: vim-compliance
source_date: '2026-11-10'
source_filename: vim-compliance.yml
source_heading: Compliance
source_page: https://www.getvim.ai/trust-center
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Vim\naid: vim\nurl: https://www.getvim.ai/trust-center\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.getvim.ai/trust-center\nattestations:\n- framework: HITRUST\n  type: certification\n  scope: HITRUST CSF\n  period: null\n  issuer: null\n  report_access: nda\n  text: Vim has successfully passed the rigorous external audit of HITRUST CSF and SOC 2 Type II\n- framework: SOC2\n  type: audit (Type II)\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: SOC 2 Type II report, HITRUST CSF certification, penetration test summary, network architecture diagram,\n    and security\
  \ questionnaire are available on request to qualified customers and partners under NDA.\n- framework: HIPAA\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: acts in compliance with the HIPAA Breach Notification Rule\n"
source_yaml_url: https://artifacts.apis.io/vim/compliance/vim-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Vim's own page on 2026-11-10.
synthetic: false
tags:
- Healthcare
- United States
- Clinical AI
- EHR Integration
- Point of Care
- Interoperability
- Value-Based Care
- Care Gaps
- OAuth
- Authentication
---
