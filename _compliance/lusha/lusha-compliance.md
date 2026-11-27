---
api_specs:
- filename: lusha-search-api-openapi.yml
  format: yaml
  label: Lusha Search API
  slug: lusha-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-search-api-openapi.yml
- filename: lusha-enrich-api-openapi.yml
  format: yaml
  label: Lusha Enrich API
  slug: lusha-enrich-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-enrich-api-openapi.yml
- filename: lusha-search-enrich-api-openapi.yml
  format: yaml
  label: Lusha Search & Enrich API
  slug: lusha-search-enrich-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-search-enrich-api-openapi.yml
- filename: lusha-prospecting-api-openapi.yml
  format: yaml
  label: Lusha Prospecting API
  slug: lusha-prospecting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-prospecting-api-openapi.yml
- filename: lusha-lookalikes-api-openapi.yml
  format: yaml
  label: Lusha Lookalikes API
  slug: lusha-lookalike-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-lookalikes-api-openapi.yml
- filename: lusha-buying-group-api-openapi.yml
  format: yaml
  label: Lusha Buying Group API
  slug: lusha-buying-group-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-buying-group-api-openapi.yml
- filename: lusha-signals-api-openapi.yml
  format: yaml
  label: Lusha Signals API
  slug: lusha-signals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-signals-api-openapi.yml
- filename: lusha-website-visits-api-openapi.yml
  format: yaml
  label: Lusha Website Visitors API
  slug: lusha-website-visits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-website-visits-api-openapi.yml
- filename: lusha-filters-api-openapi.yml
  format: yaml
  label: Lusha Filters API
  slug: lusha-filters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-filters-api-openapi.yml
- filename: lusha-contacts-tables-api-openapi.yml
  format: yaml
  label: Lusha Contacts Tables API
  slug: lusha-contacts-tables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-contacts-tables-api-openapi.yml
- filename: lusha-companies-tables-api-openapi.yml
  format: yaml
  label: Lusha Companies Tables API
  slug: lusha-companies-tables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-companies-tables-api-openapi.yml
- filename: lusha-webhooks-api-openapi.yml
  format: yaml
  label: Lusha Webhooks API
  slug: lusha-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-webhooks-api-openapi.yml
- filename: lusha-account-api-openapi.yml
  format: yaml
  label: Lusha Account API
  slug: lusha-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-account-api-openapi.yml
- filename: lusha-account-management-api-openapi.yml
  format: yaml
  label: Lusha Account Management API
  slug: lusha-account-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-account-management-api-openapi.yml
- filename: lusha-company-filters-api-openapi.yml
  format: yaml
  label: Lusha Company Filters API
  slug: lusha-company-filters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-company-filters-api-openapi.yml
- filename: lusha-contact-filters-api-openapi.yml
  format: yaml
  label: Lusha Contact Filters API
  slug: lusha-contact-filters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-contact-filters-api-openapi.yml
- filename: lusha-enrichment-api-openapi.yml
  format: yaml
  label: Lusha Enrichment API
  slug: lusha-enrichment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-enrichment-api-openapi.yml
- filename: lusha-prospecting-search-enrich-api-openapi.yml
  format: yaml
  label: Lusha Prospecting - Search & Enrich API
  slug: lusha-prospecting-search-enrich-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-prospecting-search-enrich-api-openapi.yml
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
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: 5 ISO Certifications
    type: ISO certifications (standards not named)
  trust_center:
    url: https://www.lusha.com/trust-center/
frameworks:
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Lusha
provenance_date: '2026-11-10'
provider_name: Lusha
provider_slug: lusha
slug: lusha-compliance
source_date: '2026-11-10'
source_filename: lusha-compliance.yml
source_heading: Compliance
source_page: https://www.lusha.com/trust-center/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Lusha\naid: lusha\nurl: https://www.lusha.com/trust-center/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.lusha.com/trust-center/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II Certified\n- framework: other\n  type: ISO certifications (standards not named)\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 5 ISO Certifications\n"
source_yaml_url: https://artifacts.apis.io/lusha/compliance/lusha-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Lusha's own page on 2026-11-10.
synthetic: false
tags:
- Sales Intelligence
- B2B
- Data Enrichment
- Contact Data
- Prospecting
- Intents
- Signals
- Lookalikes
- Webhook
- MCP
---
