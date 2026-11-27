---
api_specs:
- filename: algolia-search-api-openapi.yml
  format: yaml
  label: Algolia Search API
  slug: algolia-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algolia/openapi/algolia-search-api-openapi.yml
- filename: algolia-insights-api-openapi.yml
  format: yaml
  label: Algolia Insights API
  slug: algolia-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algolia/openapi/algolia-insights-api-openapi.yml
- filename: algolia-recommend-api-openapi.yml
  format: yaml
  label: Algolia Recommend API
  slug: algolia-recommend-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algolia/openapi/algolia-recommend-api-openapi.yml
- filename: algolia-analytics-api-openapi.yml
  format: yaml
  label: Algolia Analytics API
  slug: algolia-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algolia/openapi/algolia-analytics-api-openapi.yml
- filename: algolia-abtesting-v3-api-openapi.yml
  format: yaml
  label: Algolia A/B Testing API
  slug: algolia-a-b-testing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algolia/openapi/algolia-abtesting-v3-api-openapi.yml
- filename: algolia-personalization-api-openapi.yml
  format: yaml
  label: Algolia Personalization API
  slug: algolia-personalization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algolia/openapi/algolia-personalization-api-openapi.yml
- filename: algolia-advanced-personalization-api-openapi.yml
  format: yaml
  label: Algolia Advanced Personalization API
  slug: algolia-advanced-personalization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algolia/openapi/algolia-advanced-personalization-api-openapi.yml
- filename: algolia-crawler-api-openapi.yml
  format: yaml
  label: Algolia Crawler API
  slug: algolia-crawler-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algolia/openapi/algolia-crawler-api-openapi.yml
- filename: algolia-ingestion-api-openapi.yml
  format: yaml
  label: Algolia Ingestion API
  slug: algolia-ingestion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algolia/openapi/algolia-ingestion-api-openapi.yml
- filename: algolia-query-suggestions-api-openapi.yml
  format: yaml
  label: Algolia Query Suggestions API
  slug: algolia-query-suggestions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algolia/openapi/algolia-query-suggestions-api-openapi.yml
- filename: algolia-composition-api-openapi.yml
  format: yaml
  label: Algolia Composition API
  slug: algolia-composition-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algolia/openapi/algolia-composition-api-openapi.yml
- filename: algolia-agent-studio-api-openapi.yml
  format: yaml
  label: Algolia Agent Studio API
  slug: algolia-agent-studio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algolia/openapi/algolia-agent-studio-api-openapi.yml
- filename: algolia-monitoring-api-openapi.yml
  format: yaml
  label: Algolia Monitoring API
  slug: algolia-monitoring-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algolia/openapi/algolia-monitoring-api-openapi.yml
- filename: algolia-ab-testing-api-openapi.yml
  format: yaml
  label: Algolia Ab Testing API
  slug: algolia-ab-testing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algolia/openapi/algolia-ab-testing-api-openapi.yml
claim_count: 7
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: The report covers the period from January 1, 2025, to January 31, 2026.
    report_access: unstated
    scope: null
    text: The report covers the period from January 1, 2025, to January 31, 2026.
    type: SOC 2 Type II report
  - framework: SOC3
    issuer: null
    period: null
    report_access: public
    scope: null
    text: Algolia SOC 3 Final Report 2026.05.12.pdf
    type: SOC 3 report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001:2022
    type: ISO 27001:2022 certification
  - framework: ISO27017
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27017
    type: ISO 27017 certification
  - framework: C5
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Algolia C5 Type 2 Final Report 2026.05.12.pdf
    type: C5 Type 2 report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: GDPR compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA COMPLIANT
    type: CCPA compliance
  trust_center:
    url: https://trust.algolia.com/
frameworks:
- C5
- CCPA
- GDPR
- ISO27001
- ISO27017
- SOC2
- SOC3
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Algolia
provenance_date: '2026-11-09'
provider_name: Algolia
provider_slug: algolia
slug: algolia-compliance
source_date: '2026-11-09'
source_filename: algolia-compliance.yml
source_heading: Compliance
source_page: https://trust.algolia.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Algolia\naid: algolia\nurl: https://trust.algolia.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/algolia-trust-center.yml\ntrust_center:\n  url: https://trust.algolia.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: null\n  period: The report covers the period from January 1, 2025, to January 31, 2026.\n  issuer: null\n  report_access: unstated\n  text: The report covers the period from January 1, 2025, to January 31, 2026.\n- framework: SOC3\n  type: SOC 3 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: public\n  text: Algolia SOC 3 Final\
  \ Report 2026.05.12.pdf\n- framework: ISO27001\n  type: ISO 27001:2022 certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022\n- framework: ISO27017\n  type: ISO 27017 certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27017\n- framework: C5\n  type: C5 Type 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Algolia C5 Type 2 Final Report 2026.05.12.pdf\n- framework: GDPR\n  type: GDPR compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: CCPA\n  type: CCPA compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA COMPLIANT\n"
source_yaml_url: https://artifacts.apis.io/algolia/compliance/algolia-compliance.yml
stated_fields:
- attestations
summary_line: 7 quoted statements, read from Algolia's own page on 2026-11-09.
synthetic: false
tags:
- Search
- Discovery
- Recommendations
- Personalization
- Analytics
- E-Commerce
---
