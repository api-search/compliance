---
api_specs:
- filename: meilisearch-documents-api-openapi.yml
  format: yaml
  label: Meilisearch Documents API
  slug: meilisearch-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/meilisearch/openapi/meilisearch-documents-api-openapi.yml
- filename: meilisearch-health-api-openapi.yml
  format: yaml
  label: Meilisearch Health API
  slug: meilisearch-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/meilisearch/openapi/meilisearch-health-api-openapi.yml
- filename: meilisearch-indexes-api-openapi.yml
  format: yaml
  label: Meilisearch Indexes API
  slug: meilisearch-indexes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/meilisearch/openapi/meilisearch-indexes-api-openapi.yml
- filename: meilisearch-keys-api-openapi.yml
  format: yaml
  label: Meilisearch Keys API
  slug: meilisearch-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/meilisearch/openapi/meilisearch-keys-api-openapi.yml
- filename: meilisearch-search-api-openapi.yml
  format: yaml
  label: Meilisearch Search API
  slug: meilisearch-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/meilisearch/openapi/meilisearch-search-api-openapi.yml
- filename: meilisearch-settings-api-openapi.yml
  format: yaml
  label: Meilisearch Settings API
  slug: meilisearch-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/meilisearch/openapi/meilisearch-settings-api-openapi.yml
- filename: meilisearch-tasks-api-openapi.yml
  format: yaml
  label: Meilisearch Tasks API
  slug: meilisearch-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/meilisearch/openapi/meilisearch-tasks-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC2 type 2 report
    type: type 2 report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: strict compliance with regulations like GDPR
    type: null
  trust_center:
    url: https://trust.meilisearch.com/
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Meilisearch
provenance_date: '2026-11-10'
provider_name: Meilisearch
provider_slug: meilisearch
slug: meilisearch-compliance
source_date: '2026-11-10'
source_filename: meilisearch-compliance.yml
source_heading: Compliance
source_page: https://trust.meilisearch.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Meilisearch\naid: meilisearch\nurl: https://trust.meilisearch.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/meilisearch-trust-center.yml\ntrust_center:\n  url: https://trust.meilisearch.com/\nattestations:\n- framework: SOC2\n  type: type 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC2 type 2 report\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: strict compliance with regulations like GDPR\n"
source_yaml_url: https://artifacts.apis.io/meilisearch/compliance/meilisearch-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Meilisearch's own page on 2026-11-10.
synthetic: false
tags:
- AI Search
- Full-Text Search
- Hybrid Search
- Open Source
- Search
---
