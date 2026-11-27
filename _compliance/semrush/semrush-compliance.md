---
api_specs:
- filename: semrush-hermes-partner-api-api-openapi.yml
  format: yaml
  label: Semrush Hermes Partner API
  slug: semrush-hermes-partner-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/semrush/openapi/semrush-hermes-partner-api-api-openapi.yml
- filename: semrush-jwt-issuer-api-openapi.yml
  format: yaml
  label: Semrush JWT Issuer API
  slug: semrush-jwt-issuer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/semrush/openapi/semrush-jwt-issuer-api-openapi.yml
- filename: semrush-partner-service-api-openapi.yml
  format: yaml
  label: Semrush Partner Service API
  slug: semrush-partner-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/semrush/openapi/semrush-partner-service-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: independent QSA audit
    period: null
    report_access: unstated
    scope: company
    text: As a result, we have achieved a PCI DSS Level 1 certificate.
    type: PCI DSS Level 1 certificate
  - framework: GDPR
    issuer: null
    period: effective May 25, 2018
    report_access: unstated
    scope: Semrush products
    text: Semrush’s products adhere to GDPR requirements effective May 25, 2018.
    type: GDPR adherence statement
  trust_center:
    url: https://www.semrush.com/company/security/
frameworks:
- GDPR
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Semrush
provenance_date: '2026-11-10'
provider_name: Semrush
provider_slug: semrush
slug: semrush-compliance
source_date: '2026-11-10'
source_filename: semrush-compliance.yml
source_heading: Compliance
source_page: https://www.semrush.com/company/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Semrush\naid: semrush\nurl: https://www.semrush.com/company/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/semrush-trust-center.yml\ntrust_center:\n  url: https://www.semrush.com/company/security/\nattestations:\n- framework: PCI-DSS\n  type: PCI DSS Level 1 certificate\n  scope: company\n  period: null\n  issuer: independent QSA audit\n  report_access: unstated\n  text: As a result, we have achieved a PCI DSS Level 1 certificate.\n- framework: GDPR\n  type: GDPR adherence statement\n  scope: Semrush products\n  period: effective May 25, 2018\n  issuer: null\n  report_access: unstated\n\
  \  text: Semrush’s products adhere to GDPR requirements effective May 25, 2018.\n"
source_yaml_url: https://artifacts.apis.io/semrush/compliance/semrush-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Semrush's own page on 2026-11-10.
synthetic: false
tags:
- Data
- Search Engines
- SEO
- Marketing
- Marketing Intelligence
- Content Marketing
- Advertising
- Competitive Intelligence
- Keyword Research
- Backlinks
- Rank Tracking
- AI Search Visibility
- Local SEO
- MCP
---
