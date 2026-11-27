---
api_specs:
- filename: cloudtalk-agents-api-openapi.yml
  format: yaml
  label: CloudTalk Agents API
  slug: cloudtalk-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudtalk/openapi/cloudtalk-agents-api-openapi.yml
- filename: cloudtalk-bulks-api-openapi.yml
  format: yaml
  label: CloudTalk Bulks API
  slug: cloudtalk-bulks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudtalk/openapi/cloudtalk-bulks-api-openapi.yml
- filename: cloudtalk-calls-api-openapi.yml
  format: yaml
  label: CloudTalk Calls API
  slug: cloudtalk-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudtalk/openapi/cloudtalk-calls-api-openapi.yml
- filename: cloudtalk-campaigns-api-openapi.yml
  format: yaml
  label: CloudTalk Campaigns API
  slug: cloudtalk-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudtalk/openapi/cloudtalk-campaigns-api-openapi.yml
- filename: cloudtalk-contacts-api-openapi.yml
  format: yaml
  label: CloudTalk Contacts API
  slug: cloudtalk-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudtalk/openapi/cloudtalk-contacts-api-openapi.yml
- filename: cloudtalk-conversation-intelligence-api-openapi.yml
  format: yaml
  label: CloudTalk Conversation Intelligence API
  slug: cloudtalk-conversation-intelligence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudtalk/openapi/cloudtalk-conversation-intelligence-api-openapi.yml
- filename: cloudtalk-cuecard-api-openapi.yml
  format: yaml
  label: CloudTalk CueCard API
  slug: cloudtalk-cuecard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudtalk/openapi/cloudtalk-cuecard-api-openapi.yml
- filename: cloudtalk-groups-api-openapi.yml
  format: yaml
  label: CloudTalk Groups API
  slug: cloudtalk-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudtalk/openapi/cloudtalk-groups-api-openapi.yml
- filename: cloudtalk-numbers-api-openapi.yml
  format: yaml
  label: CloudTalk Numbers API
  slug: cloudtalk-numbers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudtalk/openapi/cloudtalk-numbers-api-openapi.yml
- filename: cloudtalk-sms-api-openapi.yml
  format: yaml
  label: CloudTalk Sms API
  slug: cloudtalk-sms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudtalk/openapi/cloudtalk-sms-api-openapi.yml
- filename: cloudtalk-voiceagent-api-openapi.yml
  format: yaml
  label: CloudTalk VoiceAgent API
  slug: cloudtalk-voiceagent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudtalk/openapi/cloudtalk-voiceagent-api-openapi.yml
- filename: cloudtalk-contact-tags-api-openapi.yml
  format: yaml
  label: CloudTalk Contact tags API
  slug: cloudtalk-contact-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudtalk/openapi/cloudtalk-contact-tags-api-openapi.yml
- filename: cloudtalk-dialer-api-openapi.yml
  format: yaml
  label: CloudTalk Dialer API
  slug: cloudtalk-dialer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudtalk/openapi/cloudtalk-dialer-api-openapi.yml
- filename: cloudtalk-utilities-api-openapi.yml
  format: yaml
  label: CloudTalk Utilities API
  slug: cloudtalk-utilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudtalk/openapi/cloudtalk-utilities-api-openapi.yml
- filename: cloudtalk-webhooks-api-openapi.yml
  format: yaml
  label: CloudTalk Webhooks API
  slug: cloudtalk-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudtalk/openapi/cloudtalk-webhooks-api-openapi.yml
claim_count: 7
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: ISO 27001:2022
    type: certification badge
  - framework: SOC2
    issuer: independent auditors
    period: null
    report_access: on_request
    scope: null
    text: CloudTalk has successfully completed a SOC 2 Type II audit, conducted by independent auditors.
    type: Type II audit
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: PCI DSS SAQ A 4.0 pdf
    type: SAQ A 4.0 document
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: badge
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA
    type: badge
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA
    type: badge
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: CAIQv4.0.3_STAR-CloudTalk_2025_06
    type: CAIQ v4.0.3 document
  trust_center:
    url: https://trust.cloudtalk.io/
frameworks:
- CCPA
- CSA-STAR
- GDPR
- HIPAA
- ISO27001
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: CloudTalk
provenance_date: '2026-11-09'
provider_name: CloudTalk
provider_slug: cloudtalk
slug: cloudtalk-compliance
source_date: '2026-11-09'
source_filename: cloudtalk-compliance.yml
source_heading: Compliance
source_page: https://trust.cloudtalk.io/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: CloudTalk\naid: cloudtalk\nurl: https://trust.cloudtalk.io/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.cloudtalk.io/\nattestations:\n- framework: ISO27001\n  type: certification badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: ISO 27001:2022\n- framework: SOC2\n  type: Type II audit\n  scope: null\n  period: null\n  issuer: independent auditors\n  report_access: on_request\n  text: CloudTalk has successfully completed a SOC 2 Type II audit, conducted by independent auditors.\n- framework: PCI-DSS\n  type: SAQ A 4.0 document\n  scope: null\n  period:\
  \ null\n  issuer: null\n  report_access: on_request\n  text: PCI DSS SAQ A 4.0 pdf\n- framework: GDPR\n  type: badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: CCPA\n  type: badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA\n- framework: HIPAA\n  type: badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA\n- framework: CSA-STAR\n  type: CAIQ v4.0.3 document\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: CAIQv4.0.3_STAR-CloudTalk_2025_06\n"
source_yaml_url: https://artifacts.apis.io/cloudtalk/compliance/cloudtalk-compliance.yml
stated_fields:
- attestations
summary_line: 7 quoted statements, read from CloudTalk's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Communications
- Voice
- VoIP
- Call Center
- Contact Center
- CCaaS
- Telephony
- SMS
- Conversation Intelligence
---
