---
api_specs:
- filename: unbounce-accounts-api-openapi.yml
  format: yaml
  label: Unbounce Accounts API
  slug: unbounce-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unbounce/openapi/unbounce-accounts-api-openapi.yml
- filename: unbounce-domains-api-openapi.yml
  format: yaml
  label: Unbounce Domains API
  slug: unbounce-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unbounce/openapi/unbounce-domains-api-openapi.yml
- filename: unbounce-leads-api-openapi.yml
  format: yaml
  label: Unbounce Leads API
  slug: unbounce-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unbounce/openapi/unbounce-leads-api-openapi.yml
- filename: unbounce-meta-api-openapi.yml
  format: yaml
  label: Unbounce Meta API
  slug: unbounce-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unbounce/openapi/unbounce-meta-api-openapi.yml
- filename: unbounce-pagegroups-api-openapi.yml
  format: yaml
  label: Unbounce PageGroups API
  slug: unbounce-pagegroups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unbounce/openapi/unbounce-pagegroups-api-openapi.yml
- filename: unbounce-pages-api-openapi.yml
  format: yaml
  label: Unbounce Pages API
  slug: unbounce-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unbounce/openapi/unbounce-pages-api-openapi.yml
- filename: unbounce-users-api-openapi.yml
  format: yaml
  label: Unbounce Users API
  slug: unbounce-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unbounce/openapi/unbounce-users-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: credit card processing via third-party payment processor
    text: Unbounce is a PCI Level 4 Merchant and has successfully completed all SAQ A-EP requirements.
    type: self-assessment (SAQ A-EP)
  trust_center:
    url: https://unbounce.com/security/
frameworks:
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Unbounce
provenance_date: '2026-11-10'
provider_name: Unbounce
provider_slug: unbounce
slug: unbounce-compliance
source_date: '2026-11-10'
source_filename: unbounce-compliance.yml
source_heading: Compliance
source_page: https://unbounce.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Unbounce\naid: unbounce\nurl: https://unbounce.com/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://unbounce.com/security/\nattestations:\n- framework: PCI-DSS\n  type: self-assessment (SAQ A-EP)\n  scope: credit card processing via third-party payment processor\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Unbounce is a PCI Level 4 Merchant and has successfully completed all SAQ A-EP requirements.\n"
source_yaml_url: https://artifacts.apis.io/unbounce/compliance/unbounce-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Unbounce's own page on 2026-11-10.
synthetic: false
tags:
- Landing Pages
- Conversion Rate Optimization
- Marketing
- A/B Testing
- Lead Generation
- Marketing Automation
---
