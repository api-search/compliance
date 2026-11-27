---
api_specs:
- filename: contensis-content-types-api-openapi.yml
  format: yaml
  label: Contensis Content Types API
  slug: contensis-content-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contensis/openapi/contensis-content-types-api-openapi.yml
- filename: contensis-entries-api-openapi.yml
  format: yaml
  label: Contensis Entries API
  slug: contensis-entries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contensis/openapi/contensis-entries-api-openapi.yml
- filename: contensis-projects-api-openapi.yml
  format: yaml
  label: Contensis Projects API
  slug: contensis-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contensis/openapi/contensis-projects-api-openapi.yml
- filename: contensis-taxonomy-api-openapi.yml
  format: yaml
  label: Contensis Taxonomy API
  slug: contensis-taxonomy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contensis/openapi/contensis-taxonomy-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Zengenti, the company behind Contensis, is certified to ISO/IEC 27001
    type: certification
  - framework: ISO9001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Zengenti Ltd is an ISO 9001:2015 and ISO 27001:2022 registered company.
    type: registration
  trust_center:
    url: https://www.contensis.com/security
frameworks:
- ISO27001
- ISO9001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Contensis
provenance_date: '2026-11-09'
provider_name: Contensis
provider_slug: contensis
slug: contensis-compliance
source_date: '2026-11-09'
source_filename: contensis-compliance.yml
source_heading: Compliance
source_page: https://www.contensis.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Contensis\naid: contensis\nurl: https://www.contensis.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/contensis-trust-center.yml\ntrust_center:\n  url: https://www.contensis.com/security\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Zengenti, the company behind Contensis, is certified to ISO/IEC 27001\n- framework: ISO9001\n  type: registration\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Zengenti Ltd is an ISO 9001:2015 and ISO 27001:2022 registered company.\n"
source_yaml_url: https://artifacts.apis.io/contensis/compliance/contensis-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Contensis's own page on 2026-11-09.
synthetic: false
tags:
- CMS
- Content
- Headless CMS
- Content Management
- Digital Experience Platform
- Content Delivery
- Webhook
- Higher Education
---
