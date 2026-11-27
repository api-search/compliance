---
api_specs:
- filename: daily-co-domain-api-openapi.yml
  format: yaml
  label: Daily Domain API
  slug: daily-co-domain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/daily-co/openapi/daily-co-domain-api-openapi.yml
- filename: daily-co-meetings-api-openapi.yml
  format: yaml
  label: Daily Meetings API
  slug: daily-co-meetings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/daily-co/openapi/daily-co-meetings-api-openapi.yml
- filename: daily-co-presence-api-openapi.yml
  format: yaml
  label: Daily Presence API
  slug: daily-co-presence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/daily-co/openapi/daily-co-presence-api-openapi.yml
- filename: daily-co-recordings-api-openapi.yml
  format: yaml
  label: Daily Recordings API
  slug: daily-co-recordings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/daily-co/openapi/daily-co-recordings-api-openapi.yml
- filename: daily-co-rooms-api-openapi.yml
  format: yaml
  label: Daily Rooms API
  slug: daily-co-rooms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/daily-co/openapi/daily-co-rooms-api-openapi.yml
- filename: daily-co-webhooks-api-openapi.yml
  format: yaml
  label: Daily Webhooks API
  slug: daily-co-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/daily-co/openapi/daily-co-webhooks-api-openapi.yml
- filename: daily-co-meeting-tokens-api-openapi.yml
  format: yaml
  label: Daily Meeting Tokens API
  slug: daily-co-meeting-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/daily-co/openapi/daily-co-meeting-tokens-api-openapi.yml
- filename: daily-co-phone-numbers-api-openapi.yml
  format: yaml
  label: Daily Phone Numbers API
  slug: daily-co-phone-numbers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/daily-co/openapi/daily-co-phone-numbers-api-openapi.yml
- filename: daily-co-batch-rooms-api-openapi.yml
  format: yaml
  label: Daily Batch/rooms API
  slug: daily-co-batch-rooms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/daily-co/openapi/daily-co-batch-rooms-api-openapi.yml
- filename: daily-co-domain-dialin-config-api-openapi.yml
  format: yaml
  label: Daily Domain Dialin Config API
  slug: daily-co-domain-dialin-config-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/daily-co/openapi/daily-co-domain-dialin-config-api-openapi.yml
- filename: daily-co-logs-api-openapi.yml
  format: yaml
  label: Daily Logs API
  slug: daily-co-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/daily-co/openapi/daily-co-logs-api-openapi.yml
- filename: daily-co-transcript-api-openapi.yml
  format: yaml
  label: Daily Transcript API
  slug: daily-co-transcript-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/daily-co/openapi/daily-co-transcript-api-openapi.yml
- filename: daily-co-dial-in-api-openapi.yml
  format: yaml
  label: Daily Dial In API
  slug: daily-co-dial-in-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/daily-co/openapi/daily-co-dial-in-api-openapi.yml
claim_count: 6
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Security and Confidentiality Trust Service Criteria
    text: Daily is SOC 2 Type 2 certified, covering the Security and Confidentiality Trust Service Criteria.
    type: SOC 2 Type 2 report
  - framework: SOC1
    issuer: null
    period: null
    report_access: unstated
    scope: Data centers hosting Daily's services
    text: Data centers are SOC 1, SOC 2, and ISO 27001 certified with 24/7 operations and enterprise-grade security.
    type: certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Data centers hosting Daily's services
    text: Data centers are SOC 1, SOC 2, and ISO 27001 certified with 24/7 operations and enterprise-grade security.
    type: certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Customers who have added the Healthcare Add-on
    text: HIPAA-compliant video chat for customers who have added our Healthcare Add-on. We will sign a BAA.
    type: compliance with BAA
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Data policies
    text: With GDPR-compliant data policies, we only collect and store data needed to deliver high-quality video calls.
    type: compliant data policies
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Daily
    text: Daily is certified under the EU-US and Swiss-US Data Privacy Framework Program.
    type: Data Privacy Framework certification (EU-US and Swiss-US)
  trust_center:
    url: https://www.daily.co/products/security-at-daily/
frameworks:
- GDPR
- HIPAA
- ISO27001
- SOC1
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Daily
provenance_date: '2026-11-09'
provider_name: Daily
provider_slug: daily-co
slug: daily-co-compliance
source_date: '2026-11-09'
source_filename: daily-co-compliance.yml
source_heading: Compliance
source_page: https://www.daily.co/products/security-at-daily/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Daily\naid: daily-co\nurl: https://www.daily.co/products/security-at-daily/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/daily-co-trust-center.yml\ntrust_center:\n  url: https://www.daily.co/products/security-at-daily/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: Security and Confidentiality Trust Service Criteria\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Daily is SOC 2 Type 2 certified, covering the Security and Confidentiality Trust Service Criteria.\n- framework: SOC1\n  type: certification\n  scope: Data centers hosting Daily's services\n\
  \  period: null\n  issuer: null\n  report_access: unstated\n  text: Data centers are SOC 1, SOC 2, and ISO 27001 certified with 24/7 operations and enterprise-grade security.\n- framework: ISO27001\n  type: certification\n  scope: Data centers hosting Daily's services\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Data centers are SOC 1, SOC 2, and ISO 27001 certified with 24/7 operations and enterprise-grade security.\n- framework: HIPAA\n  type: compliance with BAA\n  scope: Customers who have added the Healthcare Add-on\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA-compliant video chat for customers who have added our Healthcare Add-on. We will sign a BAA.\n- framework: GDPR\n  type: compliant data policies\n  scope: Data policies\n  period: null\n  issuer: null\n  report_access: unstated\n  text: With GDPR-compliant data policies, we only collect and store data needed to deliver high-quality video calls.\n- framework: other\n  type:\
  \ Data Privacy Framework certification (EU-US and Swiss-US)\n  scope: Daily\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Daily is certified under the EU-US and Swiss-US Data Privacy Framework Program.\n"
source_yaml_url: https://artifacts.apis.io/daily-co/compliance/daily-co-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from Daily's own page on 2026-11-09.
synthetic: false
tags:
- Daily
- Real-Time
- WebRTC
- Video
- Audio
- SDK
- Voice AI
- Recording
- Transcription
- Voice
---
