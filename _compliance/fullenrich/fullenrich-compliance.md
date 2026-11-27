---
api_specs:
- filename: fullenrich-account-api-openapi.yml
  format: yaml
  label: FullEnrich Account API
  slug: fullenrich-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fullenrich/openapi/fullenrich-account-api-openapi.yml
- filename: fullenrich-company-api-openapi.yml
  format: yaml
  label: FullEnrich Company API
  slug: fullenrich-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fullenrich/openapi/fullenrich-company-api-openapi.yml
- filename: fullenrich-contact-api-openapi.yml
  format: yaml
  label: FullEnrich Contact API
  slug: fullenrich-contact-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fullenrich/openapi/fullenrich-contact-api-openapi.yml
- filename: fullenrich-people-api-openapi.yml
  format: yaml
  label: FullEnrich People API
  slug: fullenrich-people-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fullenrich/openapi/fullenrich-people-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: FullEnrich services and company
    text: Yes, FullEnrich complies with GDPR and CCPA and takes them into account to provide its services and run its company.
    type: compliance statement
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: FullEnrich services and company
    text: Yes, FullEnrich complies with GDPR and CCPA and takes them into account to provide its services and run its company.
    type: compliance statement
  trust_center:
    url: https://fullenrich.com/trust
frameworks:
- CCPA
- GDPR
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: FullEnrich
provenance_date: '2026-11-09'
provider_name: FullEnrich
provider_slug: fullenrich
slug: fullenrich-compliance
source_date: '2026-11-09'
source_filename: fullenrich-compliance.yml
source_heading: Compliance
source_page: https://fullenrich.com/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: FullEnrich\naid: fullenrich\nurl: https://fullenrich.com/trust\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://fullenrich.com/trust\nattestations:\n- framework: GDPR\n  type: compliance statement\n  scope: FullEnrich services and company\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Yes, FullEnrich complies with GDPR and CCPA and takes them into account to provide its services and run\n    its company.\n- framework: CCPA\n  type: compliance statement\n  scope: FullEnrich services and company\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Yes, FullEnrich complies\
  \ with GDPR and CCPA and takes them into account to provide its services and run\n    its company.\n"
source_yaml_url: https://artifacts.apis.io/fullenrich/compliance/fullenrich-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from FullEnrich's own page on 2026-11-09.
synthetic: false
tags:
- B2B Data
- Contact Enrichment
- Email Finder
- Phone Finder
- Waterfall Enrichment
- Sales Intelligence
- People Search
- Company Search
- Reverse Email Lookup
- A2A
- Data Enrichment
---
