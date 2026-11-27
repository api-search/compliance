---
api_specs:
- filename: clicksend-account-api-openapi.yml
  format: yaml
  label: ClickSend Account API
  slug: clicksend-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clicksend/openapi/clicksend-account-api-openapi.yml
- filename: clicksend-contact-api-openapi.yml
  format: yaml
  label: ClickSend Contact API
  slug: clicksend-contact-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clicksend/openapi/clicksend-contact-api-openapi.yml
- filename: clicksend-email-api-openapi.yml
  format: yaml
  label: ClickSend Email API
  slug: clicksend-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clicksend/openapi/clicksend-email-api-openapi.yml
- filename: clicksend-mms-api-openapi.yml
  format: yaml
  label: ClickSend MMS API
  slug: clicksend-mms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clicksend/openapi/clicksend-mms-api-openapi.yml
- filename: clicksend-post-letter-api-openapi.yml
  format: yaml
  label: ClickSend Post Letter API
  slug: clicksend-post-letter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clicksend/openapi/clicksend-post-letter-api-openapi.yml
- filename: clicksend-post-postcard-api-openapi.yml
  format: yaml
  label: ClickSend Post Postcard API
  slug: clicksend-post-postcard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clicksend/openapi/clicksend-post-postcard-api-openapi.yml
- filename: clicksend-receipts-api-openapi.yml
  format: yaml
  label: ClickSend Receipts API
  slug: clicksend-receipts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clicksend/openapi/clicksend-receipts-api-openapi.yml
- filename: clicksend-sms-api-openapi.yml
  format: yaml
  label: ClickSend SMS API
  slug: clicksend-sms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clicksend/openapi/clicksend-sms-api-openapi.yml
- filename: clicksend-voice-api-openapi.yml
  format: yaml
  label: ClickSend Voice API
  slug: clicksend-voice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clicksend/openapi/clicksend-voice-api-openapi.yml
- filename: clicksend-contact-list-api-openapi.yml
  format: yaml
  label: ClickSend Contact List API
  slug: clicksend-contact-list-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clicksend/openapi/clicksend-contact-list-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Sinch Trust Center badge, not stated as ClickSend-specific
    text: ISO 27001:2022
    type: badge
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Sinch Messaging API - SMS, Sinch Messaging API - MAD, Nobill, Rialto services
    text: SOC2 Type II for Sinch Messaging API - SMS, Sinch Messaging API - MAD, Nobill, Rialto services
    type: SOC 2 Type II report
  - framework: DORA
    issuer: null
    period: null
    report_access: unstated
    scope: Sinch agreements with customers, third parties and sub-contractors
    text: Sinch has written agreements with customers, third parties and sub-contractors that meet or exceed the requirements set forth by DORA.
    type: contractual alignment
  trust_center:
    url: https://trust.sinch.com:443/?product=clicksend
frameworks:
- DORA
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: ClickSend
provenance_date: '2026-11-09'
provider_name: ClickSend
provider_slug: clicksend
slug: clicksend-compliance
source_date: '2026-11-09'
source_filename: clicksend-compliance.yml
source_heading: Compliance
source_page: https://trust.sinch.com:443/?product=clicksend
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: ClickSend\naid: clicksend\nurl: https://trust.sinch.com:443/?product=clicksend\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/clicksend-trust-center.yml\ntrust_center:\n  url: https://trust.sinch.com:443/?product=clicksend\nattestations:\n- framework: ISO27001\n  type: badge\n  scope: Sinch Trust Center badge, not stated as ClickSend-specific\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: Sinch Messaging API - SMS, Sinch Messaging API - MAD, Nobill, Rialto services\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: SOC2 Type II for Sinch Messaging API - SMS, Sinch Messaging API - MAD, Nobill, Rialto services\n- framework: DORA\n  type: contractual alignment\n  scope: Sinch agreements with customers, third parties and sub-contractors\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Sinch has written agreements with customers, third parties and sub-contractors that meet or exceed the requirements\n    set forth by DORA.\n"
source_yaml_url: https://artifacts.apis.io/clicksend/compliance/clicksend-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from ClickSend's own page on 2026-11-09.
synthetic: false
tags:
- Communications
- SMS
- MMS
- Voice
- Email
- Messaging
- CPaaS
- Fax
- Direct Mail
---
