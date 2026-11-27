---
api_specs:
- filename: survicate-personal-data-api-openapi.yml
  format: yaml
  label: Survicate Personal Data API
  slug: survicate-personal-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/survicate/openapi/survicate-personal-data-api-openapi.yml
- filename: survicate-respondents-api-openapi.yml
  format: yaml
  label: Survicate Respondents API
  slug: survicate-respondents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/survicate/openapi/survicate-respondents-api-openapi.yml
- filename: survicate-responses-api-openapi.yml
  format: yaml
  label: Survicate Responses API
  slug: survicate-responses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/survicate/openapi/survicate-responses-api-openapi.yml
- filename: survicate-surveys-api-openapi.yml
  format: yaml
  label: Survicate Surveys API
  slug: survicate-surveys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/survicate/openapi/survicate-surveys-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: whole platform and AWS
    text: ISO/IEC 27001:2022 certified
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR compliant
    type: compliance statement
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA/CPRA compliant
    type: compliance statement
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: infrastructure
    text: PCI DSS and HIPAA compliant infrastructure available.
    type: compliant infrastructure
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: infrastructure
    text: PCI DSS and HIPAA compliant infrastructure available.
    type: compliant infrastructure
  trust_center:
    url: https://survicate.com/security/
frameworks:
- CCPA
- GDPR
- HIPAA
- ISO27001
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Survicate
provenance_date: '2026-11-10'
provider_name: Survicate
provider_slug: survicate
slug: survicate-compliance
source_date: '2026-11-10'
source_filename: survicate-compliance.yml
source_heading: Compliance
source_page: https://survicate.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Survicate\naid: survicate\nurl: https://survicate.com/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/survicate-trust-center.yml\ntrust_center:\n  url: https://survicate.com/security/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: whole platform and AWS\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO/IEC 27001:2022 certified\n- framework: GDPR\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR compliant\n- framework: CCPA\n  type: compliance statement\n  scope: null\n  period:\
  \ null\n  issuer: null\n  report_access: unstated\n  text: CCPA/CPRA compliant\n- framework: PCI-DSS\n  type: compliant infrastructure\n  scope: infrastructure\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI DSS and HIPAA compliant infrastructure available.\n- framework: HIPAA\n  type: compliant infrastructure\n  scope: infrastructure\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI DSS and HIPAA compliant infrastructure available.\n"
source_yaml_url: https://artifacts.apis.io/survicate/compliance/survicate-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Survicate's own page on 2026-11-10.
synthetic: false
tags:
- Surveys
- Customer Feedback
- NPS
- User Research
- Feedback Analytics
- CRM Integration
- Customer Experience
---
