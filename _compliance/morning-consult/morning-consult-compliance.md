---
api_specs:
- filename: morning-consult-ai-api-openapi.yml
  format: yaml
  label: Morning Consult AI API
  slug: morning-consult-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/morning-consult/openapi/morning-consult-ai-api-openapi.yml
- filename: morning-consult-authentication-api-openapi.yml
  format: yaml
  label: Morning Consult Authentication API
  slug: morning-consult-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/morning-consult/openapi/morning-consult-authentication-api-openapi.yml
- filename: morning-consult-data-api-openapi.yml
  format: yaml
  label: Morning Consult Data API
  slug: morning-consult-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/morning-consult/openapi/morning-consult-data-api-openapi.yml
- filename: morning-consult-lookup-api-openapi.yml
  format: yaml
  label: Morning Consult Lookup API
  slug: morning-consult-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/morning-consult/openapi/morning-consult-lookup-api-openapi.yml
claim_count: 6
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: annual
    report_access: unstated
    scope: 'all five Trust Services Criteria: Security, Confidentiality, Availability, Processing Integrity and Privacy'
    text: 'we undergo annual SOC 2 Type II audits covering all five Trust Services Criteria: Security, Confidentiality, Availability, Processing Integrity and Privacy.'
    type: SOC 2 Type II audit
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: relevant privacy regulations including GDPR
    text: Morning Consult complies with relevant privacy regulations including GDPR and CCPA
    type: privacy regulation compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: relevant privacy regulations including CCPA
    text: Morning Consult complies with relevant privacy regulations including GDPR and CCPA
    type: privacy regulation compliance
  - framework: SOC2
    issuer: null
    period: '2024'
    report_access: unstated
    scope: null
    source: https://trust.morningconsult.com/
    text: SOC 2 Type II - 2024
    type: SOC 2 Type II
  - framework: SOC2
    issuer: null
    period: '2025'
    report_access: unstated
    scope: null
    source: https://trust.morningconsult.com/
    text: SOC 2 Type II - 2025
    type: SOC 2 Type II
  - framework: SOC2
    issuer: null
    period: '2023'
    report_access: unstated
    scope: null
    source: https://trust.morningconsult.com/
    text: SOC 2 Type I - 2023
    type: SOC 2 Type I
  trust_center:
    url: https://morningconsult.com/legal/security
frameworks:
- CCPA
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Morning Consult
provenance_date: '2026-11-10'
provider_name: Morning Consult
provider_slug: morning-consult
slug: morning-consult-compliance
source_date: '2026-11-10'
source_filename: morning-consult-compliance.yml
source_heading: Compliance
source_page: https://morningconsult.com/legal/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Morning Consult\naid: morning-consult\nurl: https://morningconsult.com/legal/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/morning-consult-trust-center.yml\n  sources:\n  - https://morningconsult.com/legal/security\n  - https://trust.morningconsult.com/\ntrust_center:\n  url: https://morningconsult.com/legal/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II audit\n  scope: 'all five Trust Services Criteria: Security, Confidentiality, Availability, Processing Integrity and Privacy'\n  period: annual\n  issuer: null\n  report_access: unstated\n  text: 'we undergo annual SOC\
  \ 2 Type II audits covering all five Trust Services Criteria: Security, Confidentiality,\n    Availability, Processing Integrity and Privacy.'\n- framework: GDPR\n  type: privacy regulation compliance\n  scope: relevant privacy regulations including GDPR\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Morning Consult complies with relevant privacy regulations including GDPR and CCPA\n- framework: CCPA\n  type: privacy regulation compliance\n  scope: relevant privacy regulations including CCPA\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Morning Consult complies with relevant privacy regulations including GDPR and CCPA\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: '2024'\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II - 2024\n  source: https://trust.morningconsult.com/\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: '2025'\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type\
  \ II - 2025\n  source: https://trust.morningconsult.com/\n- framework: SOC2\n  type: SOC 2 Type I\n  scope: null\n  period: '2023'\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type I - 2023\n  source: https://trust.morningconsult.com/\n"
source_yaml_url: https://artifacts.apis.io/morning-consult/compliance/morning-consult-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from Morning Consult's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Market Research
- Survey Data
- Consumer Intelligence
- Brand Tracking
- Decision Intelligence
- Public Opinion
- Analytics
- Data
- Artificial Intelligence
---
