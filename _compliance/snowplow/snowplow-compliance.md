---
api_specs:
- filename: snowplow-authentication-api-openapi.yml
  format: yaml
  label: Snowplow Authentication API
  slug: snowplow-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snowplow/openapi/snowplow-authentication-api-openapi.yml
- filename: snowplow-data-products-api-openapi.yml
  format: yaml
  label: Snowplow Data Products API
  slug: snowplow-data-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snowplow/openapi/snowplow-data-products-api-openapi.yml
- filename: snowplow-data-structures-api-openapi.yml
  format: yaml
  label: Snowplow Data Structures API
  slug: snowplow-data-structures-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snowplow/openapi/snowplow-data-structures-api-openapi.yml
claim_count: 6
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent third-party audit
    period: null
    report_access: unstated
    scope: Security, Availability, and Confidentiality
    text: Snowplow has achieved SOC 2 Type 2 certification for Security, Availability, and Confidentiality, demonstrating our commitment to the highest standards through independent third-party audit.
    type: SOC 2 Type 2 certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: security processes
    text: Snowplow has achieved ISO 27001 certification through extensive documentation and external review of our security processes.
    type: ISO 27001 certification
  - framework: ISO42001
    issuer: null
    period: null
    report_access: unstated
    scope: delivery, management, and customization of Snowplow's customer data infrastructure
    text: Snowplow is certified to ISO/IEC 42001:2023, the international standard for AI management systems.
    type: ISO/IEC 42001:2023 certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: data collection
    text: Snowplow enables GDPR & CCPA-compliance with full control over data collection
    type: compliance-ready claim
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: data collection
    text: Snowplow enables GDPR & CCPA-compliance with full control over data collection
    type: compliance-ready claim
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: PHI data hosted in Private Managed Cloud deployment
    text: our HIPAA-eligible platform offers a standard Business Associate Addendum (BAA)
    type: HIPAA-eligible platform with standard Business Associate Addendum
  trust_center:
    url: https://snowplow.io/security
frameworks:
- CCPA
- GDPR
- HIPAA
- ISO27001
- ISO42001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Snowplow
provenance_date: '2026-11-10'
provider_name: Snowplow
provider_slug: snowplow
slug: snowplow-compliance
source_date: '2026-11-10'
source_filename: snowplow-compliance.yml
source_heading: Compliance
source_page: https://snowplow.io/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Snowplow\naid: snowplow\nurl: https://snowplow.io/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/snowplow-trust-center.yml\ntrust_center:\n  url: https://snowplow.io/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 certification\n  scope: Security, Availability, and Confidentiality\n  period: null\n  issuer: independent third-party audit\n  report_access: unstated\n  text: Snowplow has achieved SOC 2 Type 2 certification for Security, Availability, and Confidentiality, demonstrating\n    our commitment to the highest standards through independent third-party audit.\n- framework:\
  \ ISO27001\n  type: ISO 27001 certification\n  scope: security processes\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Snowplow has achieved ISO 27001 certification through extensive documentation and external review of our\n    security processes.\n- framework: ISO42001\n  type: ISO/IEC 42001:2023 certification\n  scope: delivery, management, and customization of Snowplow's customer data infrastructure\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Snowplow is certified to ISO/IEC 42001:2023, the international standard for AI management systems.\n- framework: GDPR\n  type: compliance-ready claim\n  scope: data collection\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Snowplow enables GDPR & CCPA-compliance with full control over data collection\n- framework: CCPA\n  type: compliance-ready claim\n  scope: data collection\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Snowplow enables GDPR & CCPA-compliance\
  \ with full control over data collection\n- framework: HIPAA\n  type: HIPAA-eligible platform with standard Business Associate Addendum\n  scope: PHI data hosted in Private Managed Cloud deployment\n  period: null\n  issuer: null\n  report_access: unstated\n  text: our HIPAA-eligible platform offers a standard Business Associate Addendum (BAA)\n"
source_yaml_url: https://artifacts.apis.io/snowplow/compliance/snowplow-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from Snowplow's own page on 2026-11-10.
synthetic: false
tags:
- Analytics Platform
- Behavioral Data
- Data Collection
- Data Engineering
- Data Pipeline
- Event Tracking
- Open Source
---
