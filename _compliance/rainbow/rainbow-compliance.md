---
api_specs:
- filename: rainbow-applications-api-openapi.yml
  format: yaml
  label: Rainbow Applications API
  slug: rainbow-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rainbow/openapi/rainbow-applications-api-openapi.yml
- filename: rainbow-authentication-api-openapi.yml
  format: yaml
  label: Rainbow Authentication API
  slug: rainbow-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rainbow/openapi/rainbow-authentication-api-openapi.yml
- filename: rainbow-bubbles-api-openapi.yml
  format: yaml
  label: Rainbow Bubbles API
  slug: rainbow-bubbles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rainbow/openapi/rainbow-bubbles-api-openapi.yml
- filename: rainbow-contacts-api-openapi.yml
  format: yaml
  label: Rainbow Contacts API
  slug: rainbow-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rainbow/openapi/rainbow-contacts-api-openapi.yml
- filename: rainbow-conversations-api-openapi.yml
  format: yaml
  label: Rainbow Conversations API
  slug: rainbow-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rainbow/openapi/rainbow-conversations-api-openapi.yml
- filename: rainbow-messages-api-openapi.yml
  format: yaml
  label: Rainbow Messages API
  slug: rainbow-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rainbow/openapi/rainbow-messages-api-openapi.yml
- filename: rainbow-users-api-openapi.yml
  format: yaml
  label: Rainbow Users API
  slug: rainbow-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rainbow/openapi/rainbow-users-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: other
    issuer: ANSSI
    period: null
    report_access: unstated
    scope: Rainbow
    text: Rainbow™ by Alcatel-Lucent Enterprise, has been awarded the Certification de Sécurité de Premier Niveau (CSPN) issued by the Agence Nationale de la Sécurité des Systèmes d'Information (ANSSI).
    type: ANSSI CSPN certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Rainbow services
    text: Rainbow services are designed to comply with the European Data Protection Directive, which strengthens privacy and data protection.
    type: GDPR compliance design
  trust_center:
    url: https://www.openrainbow.com/app/en/security-certifications
frameworks:
- GDPR
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Rainbow
provenance_date: '2026-11-10'
provider_name: Rainbow
provider_slug: rainbow
slug: rainbow-compliance
source_date: '2026-11-10'
source_filename: rainbow-compliance.yml
source_heading: Compliance
source_page: https://www.openrainbow.com/app/en/security-certifications
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Rainbow\naid: rainbow\nurl: https://www.openrainbow.com/app/en/security-certifications\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/rainbow-trust-center.yml\ntrust_center:\n  url: https://www.openrainbow.com/app/en/security-certifications\nattestations:\n- framework: other\n  type: ANSSI CSPN certification\n  scope: Rainbow\n  period: null\n  issuer: ANSSI\n  report_access: unstated\n  text: Rainbow™ by Alcatel-Lucent Enterprise, has been awarded the Certification de Sécurité de Premier Niveau\n    (CSPN) issued by the Agence Nationale de la Sécurité des Systèmes d'Information (ANSSI).\n- framework:\
  \ GDPR\n  type: GDPR compliance design\n  scope: Rainbow services\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Rainbow services are designed to comply with the European Data Protection Directive, which strengthens privacy\n    and data protection.\n"
source_yaml_url: https://artifacts.apis.io/rainbow/compliance/rainbow-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Rainbow's own page on 2026-11-10.
synthetic: false
tags:
- Communications
- CPaaS
- Chat
- Voice
- Video
- Telephony
- Messaging
- Collaboration
- Unified Communications
---
