---
api_specs:
- filename: aclaimant-answers-api-openapi.yml
  format: yaml
  label: Aclaimant Answers API
  slug: aclaimant-answers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aclaimant/openapi/aclaimant-answers-api-openapi.yml
- filename: aclaimant-bulk-api-openapi.yml
  format: yaml
  label: Aclaimant Bulk API
  slug: aclaimant-bulk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aclaimant/openapi/aclaimant-bulk-api-openapi.yml
- filename: aclaimant-companies-api-openapi.yml
  format: yaml
  label: Aclaimant Companies API
  slug: aclaimant-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aclaimant/openapi/aclaimant-companies-api-openapi.yml
- filename: aclaimant-exposures-api-openapi.yml
  format: yaml
  label: Aclaimant Exposures API
  slug: aclaimant-exposures-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aclaimant/openapi/aclaimant-exposures-api-openapi.yml
- filename: aclaimant-incidents-api-openapi.yml
  format: yaml
  label: Aclaimant Incidents API
  slug: aclaimant-incidents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aclaimant/openapi/aclaimant-incidents-api-openapi.yml
- filename: aclaimant-policies-api-openapi.yml
  format: yaml
  label: Aclaimant Policies API
  slug: aclaimant-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aclaimant/openapi/aclaimant-policies-api-openapi.yml
- filename: aclaimant-policy-programs-api-openapi.yml
  format: yaml
  label: Aclaimant Policy Programs API
  slug: aclaimant-policy-programs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aclaimant/openapi/aclaimant-policy-programs-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II
    type: Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: null
  trust_center:
    url: https://trust.aclaimant.com/
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Aclaimant
provenance_date: '2026-11-09'
provider_name: Aclaimant
provider_slug: aclaimant
slug: aclaimant-compliance
source_date: '2026-11-09'
source_filename: aclaimant-compliance.yml
source_heading: Compliance
source_page: https://trust.aclaimant.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Aclaimant\naid: aclaimant\nurl: https://trust.aclaimant.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.aclaimant.com/\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n"
source_yaml_url: https://artifacts.apis.io/aclaimant/compliance/aclaimant-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Aclaimant's own page on 2026-11-09.
synthetic: false
tags:
- Risk Management
- Insurance
- Claims Management
- Incident Management
- Safety
- RMIS
- Workers Compensation
- OSHA
- Enterprise Risk Management
- Insurtech
---
