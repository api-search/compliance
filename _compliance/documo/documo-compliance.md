---
api_specs:
- filename: documo-account-api-openapi.yml
  format: yaml
  label: Documo Account API
  slug: documo-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/documo/openapi/documo-account-api-openapi.yml
- filename: documo-fax-api-openapi.yml
  format: yaml
  label: Documo Fax API
  slug: documo-fax-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/documo/openapi/documo-fax-api-openapi.yml
- filename: documo-numbers-api-openapi.yml
  format: yaml
  label: Documo Numbers API
  slug: documo-numbers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/documo/openapi/documo-numbers-api-openapi.yml
- filename: documo-webhooks-api-openapi.yml
  format: yaml
  label: Documo Webhooks API
  slug: documo-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/documo/openapi/documo-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II Certified
    type: SOC 2 Type II certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Cloud fax and related solutions
    text: Our secure cloud fax includes a Business Associate Agreement (BAA) and detailed policies and procedures
    type: HIPAA compliance
  trust_center:
    url: https://www.documo.com/our-solution/
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Documo
provenance_date: '2026-11-09'
provider_name: Documo
provider_slug: documo
slug: documo-compliance
source_date: '2026-11-09'
source_filename: documo-compliance.yml
source_heading: Compliance
source_page: https://www.documo.com/our-solution/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Documo\naid: documo\nurl: https://www.documo.com/our-solution/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/documo-trust-center.yml\ntrust_center:\n  url: https://www.documo.com/our-solution/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II Certified\n- framework: HIPAA\n  type: HIPAA compliance\n  scope: Cloud fax and related solutions\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our secure cloud fax includes a Business Associate Agreement (BAA) and detailed\
  \ policies and procedures\n"
source_yaml_url: https://artifacts.apis.io/documo/compliance/documo-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Documo's own page on 2026-11-09.
synthetic: false
tags:
- Fax
- Cloud Fax
- Document Delivery
- HIPAA
- Communications
---
