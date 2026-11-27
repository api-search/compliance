---
api_specs:
- filename: smsapi-blacklist-api-openapi.yml
  format: yaml
  label: SMSAPI Blacklist API
  slug: smsapi-blacklist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smsapi/openapi/smsapi-blacklist-api-openapi.yml
- filename: smsapi-contacts-api-openapi.yml
  format: yaml
  label: SMSAPI Contacts API
  slug: smsapi-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smsapi/openapi/smsapi-contacts-api-openapi.yml
- filename: smsapi-hlr-api-openapi.yml
  format: yaml
  label: SMSAPI HLR API
  slug: smsapi-hlr-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smsapi/openapi/smsapi-hlr-api-openapi.yml
- filename: smsapi-mms-api-openapi.yml
  format: yaml
  label: SMSAPI MMS API
  slug: smsapi-mms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smsapi/openapi/smsapi-mms-api-openapi.yml
- filename: smsapi-profile-api-openapi.yml
  format: yaml
  label: SMSAPI Profile API
  slug: smsapi-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smsapi/openapi/smsapi-profile-api-openapi.yml
- filename: smsapi-sender-names-api-openapi.yml
  format: yaml
  label: SMSAPI Sender Names API
  slug: smsapi-sender-names-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smsapi/openapi/smsapi-sender-names-api-openapi.yml
- filename: smsapi-short-urls-api-openapi.yml
  format: yaml
  label: SMSAPI Short URLs API
  slug: smsapi-short-urls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smsapi/openapi/smsapi-short-urls-api-openapi.yml
- filename: smsapi-sms-api-openapi.yml
  format: yaml
  label: SMSAPI SMS API
  slug: smsapi-sms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smsapi/openapi/smsapi-sms-api-openapi.yml
- filename: smsapi-subusers-api-openapi.yml
  format: yaml
  label: SMSAPI Subusers API
  slug: smsapi-subusers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smsapi/openapi/smsapi-subusers-api-openapi.yml
- filename: smsapi-vms-api-openapi.yml
  format: yaml
  label: SMSAPI VMS API
  slug: smsapi-vms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smsapi/openapi/smsapi-vms-api-openapi.yml
- filename: smsapi-2-fa-api-openapi.yml
  format: yaml
  label: SMSAPI 2 FA API
  slug: smsapi-2-fa-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smsapi/openapi/smsapi-2-fa-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We hold an ISO 27001 security certificate.
    type: security certificate
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SMSAPI is fully compliant with the GDPR.
    type: compliance statement
  trust_center:
    url: https://www.smsapi.com/en
frameworks:
- GDPR
- ISO27001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: SMSAPI
provenance_date: '2026-11-10'
provider_name: SMSAPI
provider_slug: smsapi
slug: smsapi-compliance
source_date: '2026-11-10'
source_filename: smsapi-compliance.yml
source_heading: Compliance
source_page: https://www.smsapi.com/en
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: SMSAPI\naid: smsapi\nurl: https://www.smsapi.com/en\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/smsapi-trust-center.yml\ntrust_center:\n  url: https://www.smsapi.com/en\nattestations:\n- framework: ISO27001\n  type: security certificate\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We hold an ISO 27001 security certificate.\n- framework: GDPR\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SMSAPI is fully compliant with the GDPR.\n"
source_yaml_url: https://artifacts.apis.io/smsapi/compliance/smsapi-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from SMSAPI's own page on 2026-11-10.
synthetic: false
tags:
- Messaging
- SMS
- MMS
- Voice
- 2FA
- Bulk Messaging
- Communications
- CPaaS
---
