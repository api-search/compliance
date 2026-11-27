---
api_specs:
- filename: postscript-subscribers-api-openapi.yml
  format: yaml
  label: Postscript Subscribers API
  slug: postscript-subscribers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postscript/openapi/postscript-subscribers-api-openapi.yml
- filename: postscript-events-api-openapi.yml
  format: yaml
  label: Postscript Events API
  slug: postscript-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postscript/openapi/postscript-events-api-openapi.yml
- filename: postscript-keywords-api-openapi.yml
  format: yaml
  label: Postscript Keywords API
  slug: postscript-keywords-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postscript/openapi/postscript-keywords-api-openapi.yml
- filename: postscript-messages-api-openapi.yml
  format: yaml
  label: Postscript Messages API
  slug: postscript-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postscript/openapi/postscript-messages-api-openapi.yml
- filename: postscript-webhooks-api-openapi.yml
  format: yaml
  label: Postscript Webhooks API
  slug: postscript-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postscript/openapi/postscript-webhooks-api-openapi.yml
- filename: postscript-compliance-api-openapi.yml
  format: yaml
  label: Postscript Compliance API
  slug: postscript-compliance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postscript/openapi/postscript-compliance-api-openapi.yml
- filename: postscript-identity-api-openapi.yml
  format: yaml
  label: Postscript Identity API
  slug: postscript-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postscript/openapi/postscript-identity-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CPRA (formerly CCPA) Compliant
    type: self-stated compliance
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR Compliant
    type: self-stated compliance
  trust_center:
    url: https://trust.postscript.io/
frameworks:
- CCPA
- GDPR
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Postscript
provenance_date: '2026-11-10'
provider_name: Postscript
provider_slug: postscript
slug: postscript-compliance
source_date: '2026-11-10'
source_filename: postscript-compliance.yml
source_heading: Compliance
source_page: https://trust.postscript.io/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Postscript\naid: postscript\nurl: https://trust.postscript.io/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/postscript-trust-center.yml\ntrust_center:\n  url: https://trust.postscript.io/\nattestations:\n- framework: CCPA\n  type: self-stated compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CPRA (formerly CCPA) Compliant\n- framework: GDPR\n  type: self-stated compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR Compliant\n"
source_yaml_url: https://artifacts.apis.io/postscript/compliance/postscript-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Postscript's own page on 2026-11-10.
synthetic: false
tags:
- SMS
- Marketing
- Messaging
- E-Commerce
- Shopify
- RCS
- Subscribers
- Webhook
- Compliance
---
