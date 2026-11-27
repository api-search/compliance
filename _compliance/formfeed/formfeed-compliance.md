---
api_specs:
- filename: formfeed-account-api-openapi.yml
  format: yaml
  label: Formfeed Account API
  slug: formfeed-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/formfeed/openapi/formfeed-account-api-openapi.yml
- filename: formfeed-brand-api-openapi.yml
  format: yaml
  label: Formfeed Brand API
  slug: formfeed-brand-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/formfeed/openapi/formfeed-brand-api-openapi.yml
- filename: formfeed-compat-api-openapi.yml
  format: yaml
  label: Formfeed Compat API
  slug: formfeed-compat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/formfeed/openapi/formfeed-compat-api-openapi.yml
- filename: formfeed-files-api-openapi.yml
  format: yaml
  label: Formfeed Files API
  slug: formfeed-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/formfeed/openapi/formfeed-files-api-openapi.yml
- filename: formfeed-partials-api-openapi.yml
  format: yaml
  label: Formfeed Partials API
  slug: formfeed-partials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/formfeed/openapi/formfeed-partials-api-openapi.yml
- filename: formfeed-pdf-tools-api-openapi.yml
  format: yaml
  label: Formfeed PDF tools API
  slug: formfeed-pdf-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/formfeed/openapi/formfeed-pdf-tools-api-openapi.yml
- filename: formfeed-renders-api-openapi.yml
  format: yaml
  label: Formfeed Renders API
  slug: formfeed-renders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/formfeed/openapi/formfeed-renders-api-openapi.yml
- filename: formfeed-templates-api-openapi.yml
  format: yaml
  label: Formfeed Templates API
  slug: formfeed-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/formfeed/openapi/formfeed-templates-api-openapi.yml
- filename: formfeed-webhooks-api-openapi.yml
  format: yaml
  label: Formfeed Webhooks API
  slug: formfeed-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/formfeed/openapi/formfeed-webhooks-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: every paid plan (Free workspaces can request it by email)
    text: 'GDPR: a data processing agreement under Art. 28 is part of the terms of every paid plan'
    type: data processing agreement
  trust_center:
    url: https://formfeed.dev/security
frameworks:
- GDPR
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Formfeed
provenance_date: '2026-11-09'
provider_name: Formfeed
provider_slug: formfeed
slug: formfeed-compliance
source_date: '2026-11-09'
source_filename: formfeed-compliance.yml
source_heading: Compliance
source_page: https://formfeed.dev/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Formfeed\naid: formfeed\nurl: https://formfeed.dev/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://formfeed.dev/security\nattestations:\n- framework: GDPR\n  type: data processing agreement\n  scope: every paid plan (Free workspaces can request it by email)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'GDPR: a data processing agreement under Art. 28 is part of the terms of every paid plan'\n"
source_yaml_url: https://artifacts.apis.io/formfeed/compliance/formfeed-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Formfeed's own page on 2026-11-09.
synthetic: false
tags:
- PDF
- Image Generation
- Templates
- Developer Tools
- Software-as-a-Service
---
