---
api_specs:
- filename: trade-desk-advertiser-api-openapi.yml
  format: yaml
  label: The Trade Desk Advertiser API
  slug: trade-desk-advertiser-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trade-desk/openapi/trade-desk-advertiser-api-openapi.yml
- filename: trade-desk-deletionoptout-api-openapi.yml
  format: yaml
  label: The Trade Desk DeletionOptOut API
  slug: trade-desk-deletionoptout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trade-desk/openapi/trade-desk-deletionoptout-api-openapi.yml
- filename: trade-desk-offlineconversion-api-openapi.yml
  format: yaml
  label: The Trade Desk OfflineConversion API
  slug: trade-desk-offlineconversion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trade-desk/openapi/trade-desk-offlineconversion-api-openapi.yml
- filename: trade-desk-ip-address-api-openapi.yml
  format: yaml
  label: The Trade Desk IP Address API
  slug: trade-desk-ip-address-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trade-desk/openapi/trade-desk-ip-address-api-openapi.yml
- filename: trade-desk-third-party-api-openapi.yml
  format: yaml
  label: The Trade Desk Third Party API
  slug: trade-desk-third-party-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trade-desk/openapi/trade-desk-third-party-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent auditing firm
    period: null
    report_access: unstated
    scope: Security Trust Services Criteria within the Platform
    text: The Trade Desk is annually audited against AICPA’s SSAE18 SOC 2 standard by an independent auditing firm resulting in a SOC 2 Type 2 report covering the Security Trust Services Criteria implementation within their Platform.
    type: SOC 2 Type 2 report
  - framework: SOC1
    issuer: independent auditor
    period: null
    report_access: unstated
    scope: internal controls over financial reporting
    text: The Trade Desk is annually audited against the AICPA’s SSAE18 SOC1 and Sarbanes-Oxley (SOX) Section 404 standards to ensure effective internal controls over financial reporting (ICFR’s).
    type: SSAE18 SOC 1 audit
  - framework: PCI-DSS
    issuer: self-attested
    period: null
    report_access: unstated
    scope: credit card acceptance via merchant services provider
    text: The Trade Desk attests to the applicable requirements in the PCI-DSS Self Attestation Questionnaire (SAQ) Version A.
    type: Self Attestation Questionnaire (SAQ) Version A
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Information Security Program
    text: The Trade Desk’s Information Security Program is based on ISO/IEC 27001 and includes multiple information-security policies, updated annually
    type: information security program basis
  trust_center:
    url: https://www.thetradedesk.com/trust/security
frameworks:
- ISO27001
- PCI-DSS
- SOC1
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: The Trade Desk
provenance_date: '2026-11-10'
provider_name: The Trade Desk
provider_slug: trade-desk
slug: trade-desk-compliance
source_date: '2026-11-10'
source_filename: trade-desk-compliance.yml
source_heading: Compliance
source_page: https://www.thetradedesk.com/trust/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: The Trade Desk\naid: trade-desk\nurl: https://www.thetradedesk.com/trust/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.thetradedesk.com/trust/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: Security Trust Services Criteria within the Platform\n  period: null\n  issuer: independent auditing firm\n  report_access: unstated\n  text: The Trade Desk is annually audited against AICPA’s SSAE18 SOC 2 standard by an independent auditing firm\n    resulting in a SOC 2 Type 2 report covering the Security Trust Services Criteria implementation within their\n    Platform.\n\
  - framework: SOC1\n  type: SSAE18 SOC 1 audit\n  scope: internal controls over financial reporting\n  period: null\n  issuer: independent auditor\n  report_access: unstated\n  text: The Trade Desk is annually audited against the AICPA’s SSAE18 SOC1 and Sarbanes-Oxley (SOX) Section 404\n    standards to ensure effective internal controls over financial reporting (ICFR’s).\n- framework: PCI-DSS\n  type: Self Attestation Questionnaire (SAQ) Version A\n  scope: credit card acceptance via merchant services provider\n  period: null\n  issuer: self-attested\n  report_access: unstated\n  text: The Trade Desk attests to the applicable requirements in the PCI-DSS Self Attestation Questionnaire (SAQ)\n    Version A.\n- framework: ISO27001\n  type: information security program basis\n  scope: Information Security Program\n  period: null\n  issuer: null\n  report_access: unstated\n  text: The Trade Desk’s Information Security Program is based on ISO/IEC 27001 and includes multiple information-security\n\
  \    policies, updated annually\n"
source_yaml_url: https://artifacts.apis.io/trade-desk/compliance/trade-desk-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from The Trade Desk's own page on 2026-11-10.
synthetic: false
tags:
- Advertising
- Programmatic Advertising
- DSP
- AdTech
- Connected TV
- CTV
- Identity
- Unified ID 2.0
- UID2
- OpenPath
- Kokai
- Koa AI
- Galileo
- Sincera
- Open Internet
- Real-Time Bidding
- Open Measurement
---
