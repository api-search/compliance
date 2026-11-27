---
api_specs:
- filename: leadspace-authorization-api-openapi.yml
  format: yaml
  label: Leadspace Authorization API
  slug: leadspace-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadspace/openapi/leadspace-authorization-api-openapi.yml
- filename: leadspace-discovery-api-openapi.yml
  format: yaml
  label: Leadspace Discovery API
  slug: leadspace-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadspace/openapi/leadspace-discovery-api-openapi.yml
- filename: leadspace-enrichment-api-openapi.yml
  format: yaml
  label: Leadspace Enrichment API
  slug: leadspace-enrichment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadspace/openapi/leadspace-enrichment-api-openapi.yml
- filename: leadspace-intent-api-openapi.yml
  format: yaml
  label: Leadspace Intent API
  slug: leadspace-intent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadspace/openapi/leadspace-intent-api-openapi.yml
- filename: leadspace-results-api-openapi.yml
  format: yaml
  label: Leadspace Results API
  slug: leadspace-results-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadspace/openapi/leadspace-results-api-openapi.yml
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
    text: CCPA
    type: null
  trust_center:
    url: https://www.leadspace.com/platform/security-and-compliance
frameworks:
- CCPA
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Leadspace
provenance_date: '2026-11-09'
provider_name: Leadspace
provider_slug: leadspace
slug: leadspace-compliance
source_date: '2026-11-09'
source_filename: leadspace-compliance.yml
source_heading: Compliance
source_page: https://www.leadspace.com/platform/security-and-compliance
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Leadspace\naid: leadspace\nurl: https://www.leadspace.com/platform/security-and-compliance\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.leadspace.com/platform/security-and-compliance\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: CCPA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA\n"
source_yaml_url: https://artifacts.apis.io/leadspace/compliance/leadspace-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Leadspace's own page on 2026-11-09.
synthetic: false
tags:
- MCP
- AI Agents
- B2B Data
- Customer Data Platform
- Data Enrichment
- Intent Data
- Sales Intelligence
- Account Based Marketing
- Identity Resolution
- Firmographics
- Lead Scoring
- Company
---
