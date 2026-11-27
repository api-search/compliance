---
api_specs:
- filename: sendoso-marketplace-api-openapi.yml
  format: yaml
  label: Sendoso Marketplace and SmartSend API
  slug: sendoso-marketplace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendoso/openapi/sendoso-marketplace-api-openapi.yml
- filename: sendoso-webhooks-asyncapi.yml
  format: yaml
  label: Sendoso Webhooks
  slug: sendoso-webhooks
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/sendoso/asyncapi/sendoso-webhooks-asyncapi.yml
- filename: sendoso-campaigns-api-openapi.yml
  format: yaml
  label: Sendoso Campaigns API
  slug: sendoso-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendoso/openapi/sendoso-campaigns-api-openapi.yml
- filename: sendoso-sends-api-openapi.yml
  format: yaml
  label: Sendoso Sends API
  slug: sendoso-sends-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendoso/openapi/sendoso-sends-api-openapi.yml
- filename: sendoso-smartsend-api-openapi.yml
  format: yaml
  label: Sendoso Smart Send API
  slug: sendoso-smartsend-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendoso/openapi/sendoso-smartsend-api-openapi.yml
- filename: sendoso-teams-api-openapi.yml
  format: yaml
  label: Sendoso Teams API
  slug: sendoso-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendoso/openapi/sendoso-teams-api-openapi.yml
- filename: sendoso-users-api-openapi.yml
  format: yaml
  label: Sendoso Users API
  slug: sendoso-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendoso/openapi/sendoso-users-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: Barr Advisory, P.A.
    period: null
    report_access: unstated
    scope: Trust Services Criteria of Security, Availability, and Confidentiality
    text: Sendoso SOC 2 Type 2 Report for Trust Services Criteria of Security, Availability, and Confidentiality. Issued by Barr Advisory, P.A. on 15-Jun-2026.
    type: SOC 2 Type 2 report
  - framework: SOC3
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Sendoso's 2025 SOC 2 Type 2 and SOC 3 Reports have now been posted to the Trust Center
    type: SOC 3 report
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Sendoso 2024 PCI 4.0 SAQ-A Attestation of Compliance (AOC)
    type: Attestation of Compliance (SAQ-A)
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA COMPLIANT
    type: compliance
  trust_center:
    url: https://security.sendoso.com/
frameworks:
- CCPA
- GDPR
- PCI-DSS
- SOC2
- SOC3
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Sendoso
provenance_date: '2026-11-10'
provider_name: Sendoso
provider_slug: sendoso
slug: sendoso-compliance
source_date: '2026-11-10'
source_filename: sendoso-compliance.yml
source_heading: Compliance
source_page: https://security.sendoso.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Sendoso\naid: sendoso\nurl: https://security.sendoso.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/sendoso-trust-center.yml\ntrust_center:\n  url: https://security.sendoso.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: Trust Services Criteria of Security, Availability, and Confidentiality\n  period: null\n  issuer: Barr Advisory, P.A.\n  report_access: unstated\n  text: Sendoso SOC 2 Type 2 Report for Trust Services Criteria of Security, Availability, and Confidentiality.\n    Issued by Barr Advisory, P.A. on 15-Jun-2026.\n- framework: SOC3\n  type: SOC 3 report\n\
  \  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Sendoso's 2025 SOC 2 Type 2 and SOC 3 Reports have now been posted to the Trust Center\n- framework: PCI-DSS\n  type: Attestation of Compliance (SAQ-A)\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Sendoso 2024 PCI 4.0 SAQ-A Attestation of Compliance (AOC)\n- framework: GDPR\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: CCPA\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA COMPLIANT\n"
source_yaml_url: https://artifacts.apis.io/sendoso/compliance/sendoso-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Sendoso's own page on 2026-11-10.
synthetic: false
tags:
- Corporate Gifting
- Direct Mail
- Sales Engagement
- Marketing Automation
- CRM Integration
- eGifts
- Swag and Merchandise
- Fulfillment
- Employee Recognition
- Account Based Marketing
- SCIM Provisioning
- Webhook
- A2A
---
