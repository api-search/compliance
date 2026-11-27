---
api_specs:
- filename: quo-calls-api-openapi.yml
  format: yaml
  label: Quo Calls API
  slug: quo-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quo/openapi/quo-calls-api-openapi.yml
- filename: quo-contact-custom-fields-api-openapi.yml
  format: yaml
  label: Quo Contact Custom Fields API
  slug: quo-contact-custom-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quo/openapi/quo-contact-custom-fields-api-openapi.yml
- filename: quo-contacts-api-openapi.yml
  format: yaml
  label: Quo Contacts API
  slug: quo-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quo/openapi/quo-contacts-api-openapi.yml
- filename: quo-conversations-api-openapi.yml
  format: yaml
  label: Quo Conversations API
  slug: quo-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quo/openapi/quo-conversations-api-openapi.yml
- filename: quo-messages-api-openapi.yml
  format: yaml
  label: Quo Messages API
  slug: quo-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quo/openapi/quo-messages-api-openapi.yml
- filename: quo-phone-numbers-api-openapi.yml
  format: yaml
  label: Quo Phone Numbers API
  slug: quo-phone-numbers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quo/openapi/quo-phone-numbers-api-openapi.yml
- filename: quo-tasks-api-openapi.yml
  format: yaml
  label: Quo Tasks API
  slug: quo-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quo/openapi/quo-tasks-api-openapi.yml
- filename: quo-users-api-openapi.yml
  format: yaml
  label: Quo Users API
  slug: quo-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quo/openapi/quo-users-api-openapi.yml
- filename: quo-webhooks-api-openapi.yml
  format: yaml
  label: Quo Webhooks API
  slug: quo-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quo/openapi/quo-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent auditors
    period: null
    report_access: on_request
    scope: security controls
    text: Our SOC 2 Type II certification means independent auditors have verified our security controls, not just once, but continuously.
    type: SOC 2 Type II certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: use of Quo to communicate protected health information
    text: Our HIPAA compliance means you can confidently use Quo to communicate protected health information.
    type: HIPAA compliance
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: we stay current with privacy regulations including GDPR and CCPA.
    type: privacy regulation compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: we stay current with privacy regulations including GDPR and CCPA.
    type: privacy regulation compliance
  trust_center:
    url: https://www.quo.com/security
frameworks:
- CCPA
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Quo
provenance_date: '2026-11-10'
provider_name: Quo
provider_slug: quo
slug: quo-compliance
source_date: '2026-11-10'
source_filename: quo-compliance.yml
source_heading: Compliance
source_page: https://www.quo.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Quo\naid: quo\nurl: https://www.quo.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/quo-trust-center.yml\ntrust_center:\n  url: https://www.quo.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II certification\n  scope: security controls\n  period: null\n  issuer: independent auditors\n  report_access: on_request\n  text: Our SOC 2 Type II certification means independent auditors have verified our security controls, not just\n    once, but continuously.\n- framework: HIPAA\n  type: HIPAA compliance\n  scope: use of Quo to communicate protected health information\n  period:\
  \ null\n  issuer: null\n  report_access: unstated\n  text: Our HIPAA compliance means you can confidently use Quo to communicate protected health information.\n- framework: GDPR\n  type: privacy regulation compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: we stay current with privacy regulations including GDPR and CCPA.\n- framework: CCPA\n  type: privacy regulation compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: we stay current with privacy regulations including GDPR and CCPA.\n"
source_yaml_url: https://artifacts.apis.io/quo/compliance/quo-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Quo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Communications
- Messaging
- SMS
- Voice
- Contacts
- Webhook
- Telephony
- Business Phone
- CPaaS
- Contact Center
- Phone System
- Shared Numbers
- AI Agents
- Small Business
- Integration
- CRM
- Call Routing
---
