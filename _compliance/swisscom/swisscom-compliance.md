---
api_specs:
- filename: swisscom-process-create-api-openapi.yml
  format: yaml
  label: 'Swisscom Process: create API'
  slug: swisscom-process-create-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/swisscom/openapi/swisscom-process-create-api-openapi.yml
- filename: swisscom-process-read-api-openapi.yml
  format: yaml
  label: 'Swisscom Process: read API'
  slug: swisscom-process-read-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/swisscom/openapi/swisscom-process-read-api-openapi.yml
- filename: swisscom-signatures-api-openapi.yml
  format: yaml
  label: Swisscom Signatures API
  slug: swisscom-signatures-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/swisscom/openapi/swisscom-signatures-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Swiss ZertES electronic signature services
    text: Certificate confirming as a qualified certification service provider (ZertES)
    type: Qualified certification service provider certificate
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: EU eIDAS qualified electronic signature services
    text: Certificate confirming as a qualified trust service provider (eIDAS)
    type: Qualified trust service provider certificate
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Remote signature under ZertES
    text: Certificate confirming the issuance of remote signature in accordance with ZertES
    type: Certificate confirming remote signature issuance
  trust_center:
    url: https://trustservices.swisscom.com/en/esignature-hub/downloads-and-documents
frameworks:
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Swisscom
provenance_date: '2026-11-10'
provider_name: Swisscom
provider_slug: swisscom
slug: swisscom-compliance
source_date: '2026-11-10'
source_filename: swisscom-compliance.yml
source_heading: Compliance
source_page: https://trustservices.swisscom.com/en/esignature-hub/downloads-and-documents
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Swisscom\naid: swisscom\nurl: https://trustservices.swisscom.com/en/esignature-hub/downloads-and-documents\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trustservices.swisscom.com/en/esignature-hub/downloads-and-documents\nattestations:\n- framework: other\n  type: Qualified certification service provider certificate\n  scope: Swiss ZertES electronic signature services\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Certificate confirming as a qualified certification service provider (ZertES)\n- framework: other\n  type: Qualified trust service provider certificate\n  scope: EU\
  \ eIDAS qualified electronic signature services\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Certificate confirming as a qualified trust service provider (eIDAS)\n- framework: other\n  type: Certificate confirming remote signature issuance\n  scope: Remote signature under ZertES\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Certificate confirming the issuance of remote signature in accordance with ZertES\n"
source_yaml_url: https://artifacts.apis.io/swisscom/compliance/swisscom-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Swisscom's own page on 2026-11-10.
synthetic: false
tags:
- Telecommunications
- Switzerland
- Mobile Network Operator
- Broadband
- Network APIs
- Open Gateway
- Messaging
- SMS
- Voice
- Identity Verification
- Mobility Data
- Digital Signature
- eSIM
- Artificial Intelligence
---
