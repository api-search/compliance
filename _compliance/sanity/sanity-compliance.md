---
api_specs:
- filename: sanity-assets-api-openapi.yml
  format: yaml
  label: Sanity Assets API
  slug: sanity-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sanity/openapi/sanity-assets-api-openapi.yml
- filename: sanity-listen-api-openapi.yml
  format: yaml
  label: Sanity Listen API
  slug: sanity-listen-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sanity/openapi/sanity-listen-api-openapi.yml
- filename: sanity-mutations-api-openapi.yml
  format: yaml
  label: Sanity Mutations API
  slug: sanity-mutations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sanity/openapi/sanity-mutations-api-openapi.yml
- filename: sanity-projects-api-openapi.yml
  format: yaml
  label: Sanity Projects API
  slug: sanity-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sanity/openapi/sanity-projects-api-openapi.yml
- filename: sanity-query-api-openapi.yml
  format: yaml
  label: Sanity Query API
  slug: sanity-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sanity/openapi/sanity-query-api-openapi.yml
- filename: sanity-webhooks-api-openapi.yml
  format: yaml
  label: Sanity Webhooks API
  slug: sanity-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sanity/openapi/sanity-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Security principle in the Trust Services Criteria
    text: Sanity.io is a SOC 2 Type 2 certified provider. Our SOC 2 examination covers the Security principle in the Trust Services Criteria.
    type: SOC 2 Type 2 certified
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Sanity.io personal data handling
    text: Sanity.io is fully GDPR-compliant, and we handle our customers' personal data with great care and respect
    type: compliance statement
  trust_center:
    url: https://www.sanity.io/security
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Sanity
provenance_date: '2026-11-10'
provider_name: Sanity
provider_slug: sanity
slug: sanity-compliance
source_date: '2026-11-10'
source_filename: sanity-compliance.yml
source_heading: Compliance
source_page: https://www.sanity.io/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Sanity\naid: sanity\nurl: https://www.sanity.io/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/sanity-trust-center.yml\ntrust_center:\n  url: https://www.sanity.io/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 certified\n  scope: Security principle in the Trust Services Criteria\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Sanity.io is a SOC 2 Type 2 certified provider. Our SOC 2 examination covers the Security principle in the\n    Trust Services Criteria.\n- framework: GDPR\n  type: compliance statement\n  scope: Sanity.io personal data handling\n\
  \  period: null\n  issuer: null\n  report_access: unstated\n  text: Sanity.io is fully GDPR-compliant, and we handle our customers' personal data with great care and respect\n"
source_yaml_url: https://artifacts.apis.io/sanity/compliance/sanity-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Sanity's own page on 2026-11-10.
synthetic: false
tags:
- Headless CMS
- Content Management
- GROQ
- Real-Time
- Structured Content
- Developer Platform
---
