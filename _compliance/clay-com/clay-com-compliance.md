---
api_specs:
- filename: clay-com-me-api-openapi.yml
  format: yaml
  label: Clay Me API
  slug: clay-com-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clay-com/openapi/clay-com-me-api-openapi.yml
- filename: clay-com-routines-api-openapi.yml
  format: yaml
  label: Clay Routines API
  slug: clay-com-routines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clay-com/openapi/clay-com-routines-api-openapi.yml
- filename: clay-com-search-api-openapi.yml
  format: yaml
  label: Clay Search API
  slug: clay-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clay-com/openapi/clay-com-search-api-openapi.yml
- filename: clay-com-tables-api-openapi.yml
  format: yaml
  label: Clay Tables API
  slug: clay-com-tables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clay-com/openapi/clay-com-tables-api-openapi.yml
- filename: clay-com-credits-api-openapi.yml
  format: yaml
  label: Clay Credits API
  slug: clay-com-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clay-com/openapi/clay-com-credits-api-openapi.yml
- filename: clay-com-workflowsruns-api-openapi.yml
  format: yaml
  label: Clay Workflows Runs API
  slug: clay-com-workflowsruns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clay-com/openapi/clay-com-workflowsruns-api-openapi.yml
claim_count: 9
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type 2
    type: SOC 2 Type 2
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
    text: CCPA COMPLIANT CCPA
    type: null
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001:2022
    type: ISO 27001:2022
  - framework: ISO42001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 42001:2023
    type: ISO 42001:2023
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: unstated
    source: https://www.clay.com/enterprise
    text: We are SOC 2 Type II compliant. Request our SOC 2 in our Trust Center.
    type: SOC 2 Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: unstated
    source: https://www.clay.com/enterprise
    text: GDPR Go to market anywhere in the world — let us handle compliance with local laws.
    type: compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: unstated
    source: https://www.clay.com/enterprise
    text: CCPA Support your customer base with opt out and DNC support.
    type: compliance
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: unstated
    source: https://www.clay.com/enterprise
    text: ISO 27001 Securely connect your CRM and other systems.
    type: certification
  trust_center:
    url: https://trust.clay.com/
frameworks:
- CCPA
- GDPR
- ISO27001
- ISO42001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Clay
provenance_date: '2026-11-09'
provider_name: Clay
provider_slug: clay-com
slug: clay-com-compliance
source_date: '2026-11-09'
source_filename: clay-com-compliance.yml
source_heading: Compliance
source_page: https://trust.clay.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Clay\naid: clay-com\nurl: https://trust.clay.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://trust.clay.com/\n  - https://www.clay.com/enterprise\ntrust_center:\n  url: https://trust.clay.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: CCPA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA COMPLIANT CCPA\n- framework:\
  \ ISO27001\n  type: ISO 27001:2022\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022\n- framework: ISO42001\n  type: ISO 42001:2023\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 42001:2023\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: unstated\n  period: null\n  issuer: null\n  report_access: on_request\n  text: We are SOC 2 Type II compliant. Request our SOC 2 in our Trust Center.\n  source: https://www.clay.com/enterprise\n- framework: GDPR\n  type: compliance\n  scope: unstated\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR Go to market anywhere in the world — let us handle compliance with local laws.\n  source: https://www.clay.com/enterprise\n- framework: CCPA\n  type: compliance\n  scope: unstated\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA Support your customer base with opt out and DNC support.\n  source: https://www.clay.com/enterprise\n\
  - framework: ISO27001\n  type: certification\n  scope: unstated\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001 Securely connect your CRM and other systems.\n  source: https://www.clay.com/enterprise\n"
source_yaml_url: https://artifacts.apis.io/clay-com/compliance/clay-com-compliance.yml
stated_fields:
- attestations
summary_line: 9 quoted statements, read from Clay's own page on 2026-11-09.
synthetic: false
tags:
- Prospecting
- Go-To-Market
- Sales
- Data Enrichment
- Automation
- Artificial Intelligence
- Webhook
- A2A
---
