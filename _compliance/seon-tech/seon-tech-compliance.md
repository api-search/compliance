---
api_specs:
- filename: seon-tech-aml-api-openapi.yml
  format: yaml
  label: SEON AML API
  slug: seon-tech-aml-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seon-tech/openapi/seon-tech-aml-api-openapi.yml
- filename: seon-tech-bin-api-openapi.yml
  format: yaml
  label: SEON BIN API
  slug: seon-tech-bin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seon-tech/openapi/seon-tech-bin-api-openapi.yml
- filename: seon-tech-email-api-openapi.yml
  format: yaml
  label: SEON Email API
  slug: seon-tech-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seon-tech/openapi/seon-tech-email-api-openapi.yml
- filename: seon-tech-fraud-api-openapi.yml
  format: yaml
  label: SEON Fraud API
  slug: seon-tech-fraud-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seon-tech/openapi/seon-tech-fraud-api-openapi.yml
- filename: seon-tech-ip-api-openapi.yml
  format: yaml
  label: SEON IP API
  slug: seon-tech-ip-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seon-tech/openapi/seon-tech-ip-api-openapi.yml
- filename: seon-tech-phone-api-openapi.yml
  format: yaml
  label: SEON Phone API
  slug: seon-tech-phone-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seon-tech/openapi/seon-tech-phone-api-openapi.yml
- filename: seon-tech-labels-api-openapi.yml
  format: yaml
  label: SEON Labels API
  slug: seon-tech-labels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seon-tech/openapi/seon-tech-labels-api-openapi.yml
claim_count: 6
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: ISO/IEC 27001:2022; 27017:2015 certificate
    type: ISO/IEC 27001:2022 certification
  - framework: ISO27017
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: ISO/IEC 27001:2022; 27017:2015 certificate
    type: ISO/IEC 27017:2015 certification
  - framework: SOC2
    issuer: null
    period: August 1, 2025 to July 31, 2026
    report_access: on_request
    scope: null
    text: SEON Technologies has completed its annual SOC 2 Type II examination, covering the period August 1, 2025 to July 31, 2026. To request a copy, use the "Request access" option on this Trust Center.
    type: SOC 2 Type II report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR compliance
    type: GDPR compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA
    type: CCPA compliance
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: SEON PCI-DSS SAQ A-EP and Attestation of Compliance
    type: PCI DSS SAQ A-EP attestation of compliance
  trust_center:
    url: https://trust.seon.io/
frameworks:
- CCPA
- GDPR
- ISO27001
- ISO27017
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: SEON
provenance_date: '2026-11-10'
provider_name: SEON
provider_slug: seon-tech
slug: seon-tech-compliance
source_date: '2026-11-10'
source_filename: seon-tech-compliance.yml
source_heading: Compliance
source_page: https://trust.seon.io/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: SEON\naid: seon-tech\nurl: https://trust.seon.io/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/seon-tech-trust-center.yml\ntrust_center:\n  url: https://trust.seon.io/\nattestations:\n- framework: ISO27001\n  type: ISO/IEC 27001:2022 certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: ISO/IEC 27001:2022; 27017:2015 certificate\n- framework: ISO27017\n  type: ISO/IEC 27017:2015 certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: ISO/IEC 27001:2022; 27017:2015 certificate\n- framework: SOC2\n  type: SOC 2\
  \ Type II report\n  scope: null\n  period: August 1, 2025 to July 31, 2026\n  issuer: null\n  report_access: on_request\n  text: SEON Technologies has completed its annual SOC 2 Type II examination, covering the period August 1, 2025\n    to July 31, 2026. To request a copy, use the \"Request access\" option on this Trust Center.\n- framework: GDPR\n  type: GDPR compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR compliance\n- framework: CCPA\n  type: CCPA compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA\n- framework: PCI-DSS\n  type: PCI DSS SAQ A-EP attestation of compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SEON PCI-DSS SAQ A-EP and Attestation of Compliance\n"
source_yaml_url: https://artifacts.apis.io/seon-tech/compliance/seon-tech-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from SEON's own page on 2026-11-10.
synthetic: false
tags:
- AML Compliance
- Device Intelligence
- Digital Footprint
- Fraud Prevention
- Identity Verification
- Risk Scoring
---
