---
api_specs:
- filename: crowdin-files-api-openapi.yml
  format: yaml
  label: Crowdin Files API
  slug: crowdin-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crowdin/openapi/crowdin-files-api-openapi.yml
- filename: crowdin-glossaries-api-openapi.yml
  format: yaml
  label: Crowdin Glossaries API
  slug: crowdin-glossaries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crowdin/openapi/crowdin-glossaries-api-openapi.yml
- filename: crowdin-projects-api-openapi.yml
  format: yaml
  label: Crowdin Projects API
  slug: crowdin-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crowdin/openapi/crowdin-projects-api-openapi.yml
- filename: crowdin-screenshots-api-openapi.yml
  format: yaml
  label: Crowdin Screenshots API
  slug: crowdin-screenshots-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crowdin/openapi/crowdin-screenshots-api-openapi.yml
- filename: crowdin-sourcestrings-api-openapi.yml
  format: yaml
  label: Crowdin SourceStrings API
  slug: crowdin-sourcestrings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crowdin/openapi/crowdin-sourcestrings-api-openapi.yml
- filename: crowdin-stringtranslations-api-openapi.yml
  format: yaml
  label: Crowdin StringTranslations API
  slug: crowdin-stringtranslations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crowdin/openapi/crowdin-stringtranslations-api-openapi.yml
- filename: crowdin-webhooks-api-openapi.yml
  format: yaml
  label: Crowdin Webhooks API
  slug: crowdin-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crowdin/openapi/crowdin-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Crowdin's Information Security Management System
    text: Crowdin's Information Security Management System is certified under ISO/IEC 27001
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: personal data of EU residents
    text: Crowdin complies with GDPR, protecting personal data of EU residents in line with European privacy standards.
    type: compliance statement
  trust_center:
    url: https://crowdin.com/security
frameworks:
- GDPR
- ISO27001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Crowdin
provenance_date: '2026-11-09'
provider_name: Crowdin
provider_slug: crowdin
slug: crowdin-compliance
source_date: '2026-11-09'
source_filename: crowdin-compliance.yml
source_heading: Compliance
source_page: https://crowdin.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Crowdin\naid: crowdin\nurl: https://crowdin.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/crowdin-trust-center.yml\ntrust_center:\n  url: https://crowdin.com/security\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: Crowdin's Information Security Management System\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Crowdin's Information Security Management System is certified under ISO/IEC 27001\n- framework: GDPR\n  type: compliance statement\n  scope: personal data of EU residents\n  period: null\n  issuer: null\n  report_access: unstated\n  text:\
  \ Crowdin complies with GDPR, protecting personal data of EU residents in line with European privacy standards.\n"
source_yaml_url: https://artifacts.apis.io/crowdin/compliance/crowdin-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Crowdin's own page on 2026-11-09.
synthetic: false
tags:
- Localization
- Translation
- TMS
- REST
- GraphQL
- Developer Tools
- Enterprise
---
