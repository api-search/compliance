---
api_specs:
- filename: ozonetel-agent-api-openapi.yml
  format: yaml
  label: Ozonetel Agent API
  slug: ozonetel-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ozonetel/openapi/ozonetel-agent-api-openapi.yml
- filename: ozonetel-aht-api-openapi.yml
  format: yaml
  label: Ozonetel AHT API
  slug: ozonetel-aht-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ozonetel/openapi/ozonetel-aht-api-openapi.yml
- filename: ozonetel-campaign-api-openapi.yml
  format: yaml
  label: Ozonetel Campaign API
  slug: ozonetel-campaign-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ozonetel/openapi/ozonetel-campaign-api-openapi.yml
- filename: ozonetel-campaign-reports-api-openapi.yml
  format: yaml
  label: Ozonetel Campaign Reports API
  slug: ozonetel-campaign-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ozonetel/openapi/ozonetel-campaign-reports-api-openapi.yml
- filename: ozonetel-chat-campaign-api-openapi.yml
  format: yaml
  label: Ozonetel Chat Campaign API
  slug: ozonetel-chat-campaign-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ozonetel/openapi/ozonetel-chat-campaign-api-openapi.yml
- filename: ozonetel-default-api-openapi.yml
  format: yaml
  label: Ozonetel Default API
  slug: ozonetel-default-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ozonetel/openapi/ozonetel-default-api-openapi.yml
- filename: ozonetel-disposition-api-openapi.yml
  format: yaml
  label: Ozonetel Disposition API
  slug: ozonetel-disposition-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ozonetel/openapi/ozonetel-disposition-api-openapi.yml
- filename: ozonetel-reports-api-openapi.yml
  format: yaml
  label: Ozonetel Reports API
  slug: ozonetel-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ozonetel/openapi/ozonetel-reports-api-openapi.yml
- filename: ozonetel-sms-api-openapi.yml
  format: yaml
  label: Ozonetel SMS API
  slug: ozonetel-sms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ozonetel/openapi/ozonetel-sms-api-openapi.yml
claim_count: 7
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Information security and IT service management
    text: ISO 27001 & ISO 20000-1 Information security and IT service management.
    type: standard supported
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: IT service management (ISO 20000-1)
    text: ISO 27001 & ISO 20000-1 Information security and IT service management.
    type: standard supported
  - framework: ISO27701
    issuer: null
    period: null
    report_access: unstated
    scope: Privacy information management and data protection
    text: ISO 27701 Privacy information management and data protection.
    type: standard supported
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Controls for security, availability and payment-related data
    text: SOC 2 & PCI DSS Controls for security, availability and payment-related data.
    type: standard supported
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: Controls for payment-related data
    text: SOC 2 & PCI DSS Controls for security, availability and payment-related data.
    type: standard supported
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Healthcare data protection
    text: HIPAA & ISO/IEC 42001 Healthcare data protection and responsible AI management.
    type: standard supported
  - framework: ISO42001
    issuer: null
    period: null
    report_access: unstated
    scope: Responsible AI management
    text: HIPAA & ISO/IEC 42001 Healthcare data protection and responsible AI management.
    type: standard supported
  trust_center:
    url: https://ozonetel.com/trust/
frameworks:
- HIPAA
- ISO27001
- ISO27701
- ISO42001
- PCI-DSS
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Ozonetel
provenance_date: '2026-11-10'
provider_name: Ozonetel
provider_slug: ozonetel
slug: ozonetel-compliance
source_date: '2026-11-10'
source_filename: ozonetel-compliance.yml
source_heading: Compliance
source_page: https://ozonetel.com/trust/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Ozonetel\naid: ozonetel\nurl: https://ozonetel.com/trust/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://ozonetel.com/trust/\nattestations:\n- framework: ISO27001\n  type: standard supported\n  scope: Information security and IT service management\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001 & ISO 20000-1 Information security and IT service management.\n- framework: other\n  type: standard supported\n  scope: IT service management (ISO 20000-1)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001 & ISO 20000-1 Information security and IT service\
  \ management.\n- framework: ISO27701\n  type: standard supported\n  scope: Privacy information management and data protection\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27701 Privacy information management and data protection.\n- framework: SOC2\n  type: standard supported\n  scope: Controls for security, availability and payment-related data\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 & PCI DSS Controls for security, availability and payment-related data.\n- framework: PCI-DSS\n  type: standard supported\n  scope: Controls for payment-related data\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 & PCI DSS Controls for security, availability and payment-related data.\n- framework: HIPAA\n  type: standard supported\n  scope: Healthcare data protection\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA & ISO/IEC 42001 Healthcare data protection and responsible AI management.\n- framework:\
  \ ISO42001\n  type: standard supported\n  scope: Responsible AI management\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA & ISO/IEC 42001 Healthcare data protection and responsible AI management.\n"
source_yaml_url: https://artifacts.apis.io/ozonetel/compliance/ozonetel-compliance.yml
stated_fields:
- attestations
summary_line: 7 quoted statements, read from Ozonetel's own page on 2026-11-10.
synthetic: false
tags:
- Company
- CX Platform
- Cloud Communications
- Contact Center
---
