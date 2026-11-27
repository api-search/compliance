---
api_specs:
- filename: deployxa-deployments-api-openapi.yml
  format: yaml
  label: Deployxa Deployments API
  slug: deployxa-deployments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deployxa/openapi/deployxa-deployments-api-openapi.yml
- filename: deployxa-projects-api-openapi.yml
  format: yaml
  label: Deployxa Projects API
  slug: deployxa-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deployxa/openapi/deployxa-projects-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: How we meet GDPR obligations.
    type: policy link
  trust_center:
    url: https://deployxa.com/trust
frameworks:
- GDPR
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Deployxa
provenance_date: '2026-11-09'
provider_name: Deployxa
provider_slug: deployxa
slug: deployxa-compliance
source_date: '2026-11-09'
source_filename: deployxa-compliance.yml
source_heading: Compliance
source_page: https://deployxa.com/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Deployxa\naid: deployxa\nurl: https://deployxa.com/trust\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/deployxa-trust-center.yml\ntrust_center:\n  url: https://deployxa.com/trust\nattestations:\n- framework: GDPR\n  type: policy link\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: How we meet GDPR obligations.\n"
source_yaml_url: https://artifacts.apis.io/deployxa/compliance/deployxa-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Deployxa's own page on 2026-11-09.
synthetic: false
tags:
- Platform-as-a-Service
- Cloud Deployment
- DevOps
- CI/CD
- containers-docker
- edge-hosting
- Managed Database
- AIOps
- Developer Tools
- A2A
---
