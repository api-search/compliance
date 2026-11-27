---
api_specs:
- filename: chaossearch-bulkexport-api-openapi.yml
  format: yaml
  label: ChaosSearch Bulkexport API
  slug: chaossearch-bulkexport-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chaossearch/openapi/chaossearch-bulkexport-api-openapi.yml
- filename: chaossearch-chaossearch-api-api-openapi.yml
  format: yaml
  label: ChaosSearch ChaosSearch API
  slug: chaossearch-chaossearch-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chaossearch/openapi/chaossearch-chaossearch-api-api-openapi.yml
- filename: chaossearch-user-api-openapi.yml
  format: yaml
  label: ChaosSearch User API
  slug: chaossearch-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chaossearch/openapi/chaossearch-user-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ChaosSearch has designed its control environment to satisfy the requirements of the Security Rule of the Health Information Portability and Accountability Act (HIPAA).
    type: null
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ChaosSearch is committed to complying with the EU General Data Protection Regulation (GDPR)
    type: null
  trust_center:
    url: https://www.chaossearch.io/security
frameworks:
- GDPR
- HIPAA
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: ChaosSearch
provenance_date: '2026-11-09'
provider_name: ChaosSearch
provider_slug: chaossearch
slug: chaossearch-compliance
source_date: '2026-11-09'
source_filename: chaossearch-compliance.yml
source_heading: Compliance
source_page: https://www.chaossearch.io/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: ChaosSearch\naid: chaossearch\nurl: https://www.chaossearch.io/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.chaossearch.io/security\nattestations:\n- framework: HIPAA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ChaosSearch has designed its control environment to satisfy the requirements of the Security Rule of the\n    Health Information Portability and Accountability Act (HIPAA).\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ChaosSearch is committed to complying\
  \ with the EU General Data Protection Regulation (GDPR)\n"
source_yaml_url: https://artifacts.apis.io/chaossearch/compliance/chaossearch-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from ChaosSearch's own page on 2026-11-09.
synthetic: false
tags:
- Analytics
- Observability
- Security
- Data Lake
- Cloud Storage
- ELK
---
