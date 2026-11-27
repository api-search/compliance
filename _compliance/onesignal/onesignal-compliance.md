---
api_specs:
- filename: onesignal-apps-api-openapi.yml
  format: yaml
  label: OneSignal Apps API
  slug: onesignal-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/onesignal/openapi/onesignal-apps-api-openapi.yml
- filename: onesignal-notifications-api-openapi.yml
  format: yaml
  label: OneSignal Notifications API
  slug: onesignal-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/onesignal/openapi/onesignal-notifications-api-openapi.yml
- filename: onesignal-players-api-openapi.yml
  format: yaml
  label: OneSignal Players API
  slug: onesignal-players-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/onesignal/openapi/onesignal-players-api-openapi.yml
- filename: onesignal-templates-api-openapi.yml
  format: yaml
  label: OneSignal Templates API
  slug: onesignal-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/onesignal/openapi/onesignal-templates-api-openapi.yml
- filename: onesignal-organizations-api-openapi.yml
  format: yaml
  label: OneSignal Organizations API
  slug: onesignal-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/onesignal/openapi/onesignal-organizations-api-openapi.yml
claim_count: 7
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: OneSignal platform controls
    text: 'OneSignal maintains the following independent security certifications: SOC 2 Type II'
    type: SOC 2 Type II certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: OneSignal internal controls and privacy management
    text: ISO 27001 & ISO 27701
    type: ISO 27001 certification
  - framework: ISO27701
    issuer: null
    period: null
    report_access: unstated
    scope: privacy management systems
    text: ISO 27001 & ISO 27701
    type: ISO 27701 certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: customers who manage protected health information
    text: OneSignal complies with HIPAA requirements for customers who manage protected health information (PHI).
    type: HIPAA compliance
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: customers' GDPR responsibilities
    text: OneSignal complies with the EU General Data Protection Regulation (GDPR)
    type: GDPR compliance
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: lawful data transfers between the EU and the U.S.
    text: OneSignal is certified under the EU–U.S. Data Privacy Framework for lawful data transfers between the EU and the U.S.
    type: EU-U.S. Data Privacy Framework certification
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: COPPA-related program
    text: OneSignal is certified under the Families Ads Program (as of January 10, 2022).
    type: Families Ads Program certification
  trust_center:
    url: https://documentation.onesignal.com/docs/en/data-questions
frameworks:
- GDPR
- HIPAA
- ISO27001
- ISO27701
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: OneSignal
provenance_date: '2026-11-10'
provider_name: OneSignal
provider_slug: onesignal
slug: onesignal-compliance
source_date: '2026-11-10'
source_filename: onesignal-compliance.yml
source_heading: Compliance
source_page: https://documentation.onesignal.com/docs/en/data-questions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: OneSignal\naid: onesignal\nurl: https://documentation.onesignal.com/docs/en/data-questions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/onesignal-trust-center.yml\ntrust_center:\n  url: https://documentation.onesignal.com/docs/en/data-questions\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II certification\n  scope: OneSignal platform controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'OneSignal maintains the following independent security certifications: SOC 2 Type II'\n- framework: ISO27001\n  type: ISO 27001 certification\n  scope: OneSignal internal controls\
  \ and privacy management\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001 & ISO 27701\n- framework: ISO27701\n  type: ISO 27701 certification\n  scope: privacy management systems\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001 & ISO 27701\n- framework: HIPAA\n  type: HIPAA compliance\n  scope: customers who manage protected health information\n  period: null\n  issuer: null\n  report_access: unstated\n  text: OneSignal complies with HIPAA requirements for customers who manage protected health information (PHI).\n- framework: GDPR\n  type: GDPR compliance\n  scope: customers' GDPR responsibilities\n  period: null\n  issuer: null\n  report_access: unstated\n  text: OneSignal complies with the EU General Data Protection Regulation (GDPR)\n- framework: other\n  type: EU-U.S. Data Privacy Framework certification\n  scope: lawful data transfers between the EU and the U.S.\n  period: null\n  issuer: null\n  report_access: unstated\n \
  \ text: OneSignal is certified under the EU–U.S. Data Privacy Framework for lawful data transfers between the EU\n    and the U.S.\n- framework: other\n  type: Families Ads Program certification\n  scope: COPPA-related program\n  period: null\n  issuer: null\n  report_access: unstated\n  text: OneSignal is certified under the Families Ads Program (as of January 10, 2022).\n"
source_yaml_url: https://artifacts.apis.io/onesignal/compliance/onesignal-compliance.yml
stated_fields:
- attestations
summary_line: 7 quoted statements, read from OneSignal's own page on 2026-11-10.
synthetic: false
tags:
- Notification
- Push
- Email
- SMS
- Mobile
- Push Notifications
- Web Push
- Customer Engagement
- Marketing Automation
- Live Activities
- RCS
- In-App Messaging
- Journeys
- Lifecycle Marketing
- MCP
- A2A
---
