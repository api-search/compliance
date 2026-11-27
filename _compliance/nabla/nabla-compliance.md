---
api_specs:
- filename: nabla-authentication-api-openapi.yml
  format: yaml
  label: Nabla Authentication API
  slug: nabla-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nabla/openapi/nabla-authentication-api-openapi.yml
- filename: nabla-transcription-api-openapi.yml
  format: yaml
  label: Nabla Transcription API
  slug: nabla-transcription-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nabla/openapi/nabla-transcription-api-openapi.yml
claim_count: 6
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: November 2024 to October 2025
    report_access: on_request
    scope: null
    text: SOC 2 Type II Report November 2024 to October 2025 Request
    type: SOC 2 Type II report
  - framework: ISO27001
    issuer: null
    period: September 2026
    report_access: on_request
    scope: null
    text: Request ISO/IEC 27001 September 2026 Request
    type: ISO/IEC 27001 certificate
  - framework: other
    issuer: null
    period: January 2026
    report_access: on_request
    scope: null
    text: Request TX-RAMP Certificate Level 2 January 2026 Request
    type: TX-RAMP Certificate Level 2
  - framework: HIPAA
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Request HIPAA Request CCPA
    type: HIPAA compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Request HIPAA Request CCPA
    type: CCPA compliance
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Nabla follows HIPAA, GDPR, SOC2, ISO27001 and NIST Cybersecurity standards for security and privacy.
    type: GDPR compliance
  trust_center:
    url: https://trust.nabla.com/
frameworks:
- CCPA
- GDPR
- HIPAA
- ISO27001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Nabla
provenance_date: '2026-11-10'
provider_name: Nabla
provider_slug: nabla
slug: nabla-compliance
source_date: '2026-11-10'
source_filename: nabla-compliance.yml
source_heading: Compliance
source_page: https://trust.nabla.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Nabla\naid: nabla\nurl: https://trust.nabla.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/nabla-trust-center.yml\ntrust_center:\n  url: https://trust.nabla.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: null\n  period: November 2024 to October 2025\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Type II Report November 2024 to October 2025 Request\n- framework: ISO27001\n  type: ISO/IEC 27001 certificate\n  scope: null\n  period: September 2026\n  issuer: null\n  report_access: on_request\n  text: Request ISO/IEC 27001 September 2026 Request\n- framework:\
  \ other\n  type: TX-RAMP Certificate Level 2\n  scope: null\n  period: January 2026\n  issuer: null\n  report_access: on_request\n  text: Request TX-RAMP Certificate Level 2 January 2026 Request\n- framework: HIPAA\n  type: HIPAA compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Request HIPAA Request CCPA\n- framework: CCPA\n  type: CCPA compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Request HIPAA Request CCPA\n- framework: GDPR\n  type: GDPR compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Nabla follows HIPAA, GDPR, SOC2, ISO27001 and NIST Cybersecurity standards for security and privacy.\n"
source_yaml_url: https://artifacts.apis.io/nabla/compliance/nabla-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from Nabla's own page on 2026-11-10.
synthetic: false
tags:
- Healthcare
- Ambient AI
- Clinical Documentation
- Medical Transcription
- Speech Recognition
- FHIR
- SOAP Notes
- Voice
- EHR Integration
---
