---
api_specs:
- filename: factory-automations-api-openapi.yml
  format: yaml
  label: Factory Automations API
  slug: factory-automations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/factory/openapi/factory-automations-api-openapi.yml
- filename: factory-computers-api-openapi.yml
  format: yaml
  label: Factory Computers API
  slug: factory-computers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/factory/openapi/factory-computers-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Factory has achieved the SOC 2 Type I certification
    type: Type I certification
  - framework: ISO42001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Factory is among the first organizations worldwide to adopt ISO 42001
    type: standard adoption
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 GPDR ISO 42001 CCPA
    type: compliance listed
  trust_center:
    url: https://factory.com/security
frameworks:
- CCPA
- ISO42001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Factory
provenance_date: '2026-11-09'
provider_name: Factory
provider_slug: factory
slug: factory-compliance
source_date: '2026-11-09'
source_filename: factory-compliance.yml
source_heading: Compliance
source_page: https://factory.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Factory\naid: factory\nurl: https://factory.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://factory.com/security\nattestations:\n- framework: SOC2\n  type: Type I certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Factory has achieved the SOC 2 Type I certification\n- framework: ISO42001\n  type: standard adoption\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Factory is among the first organizations worldwide to adopt ISO 42001\n- framework: CCPA\n  type: compliance listed\n  scope: null\n  period: null\n\
  \  issuer: null\n  report_access: unstated\n  text: SOC 2 GPDR ISO 42001 CCPA\n"
source_yaml_url: https://artifacts.apis.io/factory/compliance/factory-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Factory's own page on 2026-11-09.
synthetic: false
tags:
- Manufacturing
- Software-as-a-Service
- Cloud
- Automation
- Supply Chain
- Company
---
