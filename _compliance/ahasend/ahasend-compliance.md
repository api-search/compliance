---
api_specs:
- filename: ahasend-accounts-api-openapi.yml
  format: yaml
  label: AhaSend Accounts API
  slug: ahasend-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-accounts-api-openapi.yml
- filename: ahasend-api-keys-api-openapi.yml
  format: yaml
  label: AhaSend API Keys API
  slug: ahasend-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-api-keys-api-openapi.yml
- filename: ahasend-domains-api-openapi.yml
  format: yaml
  label: AhaSend Domains API
  slug: ahasend-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-domains-api-openapi.yml
- filename: ahasend-email-api-openapi.yml
  format: yaml
  label: AhaSend Email API
  slug: ahasend-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-email-api-openapi.yml
- filename: ahasend-messages-api-openapi.yml
  format: yaml
  label: AhaSend Messages API
  slug: ahasend-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-messages-api-openapi.yml
- filename: ahasend-routes-api-openapi.yml
  format: yaml
  label: AhaSend Routes API
  slug: ahasend-routes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-routes-api-openapi.yml
- filename: ahasend-smtp-credentials-api-openapi.yml
  format: yaml
  label: AhaSend SMTP Credentials API
  slug: ahasend-smtp-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-smtp-credentials-api-openapi.yml
- filename: ahasend-statistics-api-openapi.yml
  format: yaml
  label: AhaSend Statistics API
  slug: ahasend-statistics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-statistics-api-openapi.yml
- filename: ahasend-suppressions-api-openapi.yml
  format: yaml
  label: AhaSend Suppressions API
  slug: ahasend-suppressions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-suppressions-api-openapi.yml
- filename: ahasend-utility-api-openapi.yml
  format: yaml
  label: AhaSend Utility API
  slug: ahasend-utility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-utility-api-openapi.yml
- filename: ahasend-webhooks-api-openapi.yml
  format: yaml
  label: AhaSend Webhooks API
  slug: ahasend-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-webhooks-api-openapi.yml
- filename: ahasend-campaign-templates-api-openapi.yml
  format: yaml
  label: AhaSend Campaign Templates API
  slug: ahasend-campaign-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-campaign-templates-api-openapi.yml
- filename: ahasend-campaigns-api-openapi.yml
  format: yaml
  label: AhaSend Campaigns API
  slug: ahasend-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-campaigns-api-openapi.yml
- filename: ahasend-contacts-api-openapi.yml
  format: yaml
  label: AhaSend Contacts API
  slug: ahasend-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-contacts-api-openapi.yml
- filename: ahasend-lists-api-openapi.yml
  format: yaml
  label: AhaSend Lists API
  slug: ahasend-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-lists-api-openapi.yml
- filename: ahasend-templates-api-openapi.yml
  format: yaml
  label: AhaSend Templates API
  slug: ahasend-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-templates-api-openapi.yml
- filename: ahasend-subaccounts-api-openapi.yml
  format: yaml
  label: AhaSend Subaccounts API
  slug: ahasend-subaccounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-subaccounts-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: public
    scope: AhaSend
    text: AhaSend is certified against ISO 27001. The certificate, our controls and their current status are published in our Trust Center.
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: AhaSend
    text: GDPR compliant
    type: compliance claim
  trust_center:
    url: https://ahasend.com/security
frameworks:
- GDPR
- ISO27001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: AhaSend
provenance_date: '2026-11-09'
provider_name: AhaSend
provider_slug: ahasend
slug: ahasend-compliance
source_date: '2026-11-09'
source_filename: ahasend-compliance.yml
source_heading: Compliance
source_page: https://ahasend.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: AhaSend\naid: ahasend\nurl: https://ahasend.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/ahasend-trust-center.yml\ntrust_center:\n  url: https://ahasend.com/security\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: AhaSend\n  period: null\n  issuer: null\n  report_access: public\n  text: AhaSend is certified against ISO 27001. The certificate, our controls and their current status are published\n    in our Trust Center.\n- framework: GDPR\n  type: compliance claim\n  scope: AhaSend\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR compliant\n"
source_yaml_url: https://artifacts.apis.io/ahasend/compliance/ahasend-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from AhaSend's own page on 2026-11-09.
synthetic: false
tags:
- Email
- Transactional Email
- Developer Tools
- SMTP
- Webhook
---
