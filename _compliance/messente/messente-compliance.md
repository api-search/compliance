---
api_specs:
- filename: messente-account-balance-api-openapi.yml
  format: yaml
  label: Messente Account Balance API
  slug: messente-account-balance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/messente/openapi/messente-account-balance-api-openapi.yml
- filename: messente-blacklist-api-openapi.yml
  format: yaml
  label: Messente Blacklist API
  slug: messente-blacklist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/messente/openapi/messente-blacklist-api-openapi.yml
- filename: messente-bulk-messaging-api-openapi.yml
  format: yaml
  label: Messente Bulk Messaging API
  slug: messente-bulk-messaging-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/messente/openapi/messente-bulk-messaging-api-openapi.yml
- filename: messente-contacts-api-openapi.yml
  format: yaml
  label: Messente Contacts API
  slug: messente-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/messente/openapi/messente-contacts-api-openapi.yml
- filename: messente-delivery-report-api-openapi.yml
  format: yaml
  label: Messente Delivery Report API
  slug: messente-delivery-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/messente/openapi/messente-delivery-report-api-openapi.yml
- filename: messente-groups-api-openapi.yml
  format: yaml
  label: Messente Groups API
  slug: messente-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/messente/openapi/messente-groups-api-openapi.yml
- filename: messente-number-lookup-api-openapi.yml
  format: yaml
  label: Messente Number Lookup API
  slug: messente-number-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/messente/openapi/messente-number-lookup-api-openapi.yml
- filename: messente-number-verification-api-openapi.yml
  format: yaml
  label: Messente Number Verification API
  slug: messente-number-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/messente/openapi/messente-number-verification-api-openapi.yml
- filename: messente-omnimessage-api-openapi.yml
  format: yaml
  label: Messente Omnimessage API
  slug: messente-omnimessage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/messente/openapi/messente-omnimessage-api-openapi.yml
- filename: messente-pricing-api-openapi.yml
  format: yaml
  label: Messente Pricing API
  slug: messente-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/messente/openapi/messente-pricing-api-openapi.yml
- filename: messente-statistics-api-openapi.yml
  format: yaml
  label: Messente Statistics API
  slug: messente-statistics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/messente/openapi/messente-statistics-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We are GDPR compliant
    type: compliance claim
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: regularly audited for ISO 27001:2022 security framework
    type: audit claim
  - framework: DORA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Messente is compliant with GDPR, ISO 27001:2022, and DORA
    type: compliance claim
  trust_center:
    url: https://messente.com/compliance
frameworks:
- DORA
- GDPR
- ISO27001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Messente
provenance_date: '2026-11-10'
provider_name: Messente
provider_slug: messente
slug: messente-compliance
source_date: '2026-11-10'
source_filename: messente-compliance.yml
source_heading: Compliance
source_page: https://messente.com/compliance
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Messente\naid: messente\nurl: https://messente.com/compliance\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/messente-trust-center.yml\ntrust_center:\n  url: https://messente.com/compliance\nattestations:\n- framework: GDPR\n  type: compliance claim\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We are GDPR compliant\n- framework: ISO27001\n  type: audit claim\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: regularly audited for ISO 27001:2022 security framework\n- framework: DORA\n  type: compliance claim\n  scope: null\n  period:\
  \ null\n  issuer: null\n  report_access: unstated\n  text: Messente is compliant with GDPR, ISO 27001:2022, and DORA\n"
source_yaml_url: https://artifacts.apis.io/messente/compliance/messente-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Messente's own page on 2026-11-10.
synthetic: false
tags:
- CPaaS
- Messaging
- SMS
- Viber
- WhatsApp
- Verification
- 2FA
---
