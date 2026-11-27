---
api_specs:
- filename: fullcontact-address-api-openapi.yml
  format: yaml
  label: FullContact Address API
  slug: fullcontact-address-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fullcontact/openapi/fullcontact-address-api-openapi.yml
- filename: fullcontact-audience-api-openapi.yml
  format: yaml
  label: FullContact Audience API
  slug: fullcontact-audience-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fullcontact/openapi/fullcontact-audience-api-openapi.yml
- filename: fullcontact-enrich-api-openapi.yml
  format: yaml
  label: FullContact Enrich API
  slug: fullcontact-enrich-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fullcontact/openapi/fullcontact-enrich-api-openapi.yml
- filename: fullcontact-identity-api-openapi.yml
  format: yaml
  label: FullContact Identity API
  slug: fullcontact-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fullcontact/openapi/fullcontact-identity-api-openapi.yml
- filename: fullcontact-permission-api-openapi.yml
  format: yaml
  label: FullContact Permission API
  slug: fullcontact-permission-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fullcontact/openapi/fullcontact-permission-api-openapi.yml
- filename: fullcontact-tags-api-openapi.yml
  format: yaml
  label: FullContact Tags API
  slug: fullcontact-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fullcontact/openapi/fullcontact-tags-api-openapi.yml
claim_count: 3
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
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA COMPLIANT
    type: null
  trust_center:
    url: https://trust.fullcontact.com/
frameworks:
- CCPA
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: FullContact
provenance_date: '2026-11-09'
provider_name: FullContact
provider_slug: fullcontact
slug: fullcontact-compliance
source_date: '2026-11-09'
source_filename: fullcontact-compliance.yml
source_heading: Compliance
source_page: https://trust.fullcontact.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: FullContact\naid: fullcontact\nurl: https://trust.fullcontact.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.fullcontact.com/\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: CCPA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA COMPLIANT\n"
source_yaml_url: https://artifacts.apis.io/fullcontact/compliance/fullcontact-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from FullContact's own page on 2026-11-09.
synthetic: false
tags:
- Identity Resolution
- Customer Data
- Data Enrichment
- Person API
- Company API
- Privacy-Safe Identity
- Customer Recognition
---
