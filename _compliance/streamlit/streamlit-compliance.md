---
api_specs:
- filename: streamlit-apps-api-openapi.yml
  format: yaml
  label: Streamlit Apps API
  slug: streamlit-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/streamlit/openapi/streamlit-apps-api-openapi.yml
- filename: streamlit-secrets-api-openapi.yml
  format: yaml
  label: Streamlit Secrets API
  slug: streamlit-secrets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/streamlit/openapi/streamlit-secrets-api-openapi.yml
- filename: streamlit-workspaces-api-openapi.yml
  format: yaml
  label: Streamlit Workspaces API
  slug: streamlit-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/streamlit/openapi/streamlit-workspaces-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: are SOC2 readiness certified
    type: readiness certification
  trust_center:
    url: https://streamlit.io/security
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Streamlit
provenance_date: '2026-11-10'
provider_name: Streamlit
provider_slug: streamlit
slug: streamlit-compliance
source_date: '2026-11-10'
source_filename: streamlit-compliance.yml
source_heading: Compliance
source_page: https://streamlit.io/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Streamlit\naid: streamlit\nurl: https://streamlit.io/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/streamlit-trust-center.yml\ntrust_center:\n  url: https://streamlit.io/security\nattestations:\n- framework: SOC2\n  type: readiness certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: are SOC2 readiness certified\n"
source_yaml_url: https://artifacts.apis.io/streamlit/compliance/streamlit-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Streamlit's own page on 2026-11-10.
synthetic: false
tags:
- Data Science
- Machine Learning
- Open Source
- Python
- Web Applications
---
