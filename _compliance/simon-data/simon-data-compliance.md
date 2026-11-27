---
api_specs:
- filename: simon-data-contacts-api-openapi.yml
  format: yaml
  label: Simon Data Contacts API
  slug: simon-data-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simon-data/openapi/simon-data-contacts-api-openapi.yml
- filename: simon-data-events-api-openapi.yml
  format: yaml
  label: Simon Data Events API
  slug: simon-data-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simon-data/openapi/simon-data-events-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: Simon Platform
    text: Our SOC 2 Type 2 report and bridge letter can be shared with any prospects or customers that are under NDA.
    type: SOC 2 Type 2 report and bridge letter
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: Simon Data
    text: Simon Data is SOC 2 certified, and continuously monitors all associated controls to ensure we remain in compliance at all times.
    type: SOC 2 certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Simon Data as data processor
    text: We are also compliant with GDPR and CCPA privacy standards.
    type: compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: Simon Data
    text: We are also compliant with GDPR and CCPA privacy standards.
    type: compliance
  trust_center:
    url: https://www.simon.ai/terms/security
frameworks:
- CCPA
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Simon Data
provenance_date: '2026-11-10'
provider_name: Simon Data
provider_slug: simon-data
slug: simon-data-compliance
source_date: '2026-11-10'
source_filename: simon-data-compliance.yml
source_heading: Compliance
source_page: https://www.simon.ai/terms/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Simon Data\naid: simon-data\nurl: https://www.simon.ai/terms/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.simon.ai/terms/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 report and bridge letter\n  scope: Simon Platform\n  period: null\n  issuer: null\n  report_access: nda\n  text: Our SOC 2 Type 2 report and bridge letter can be shared with any prospects or customers that are under NDA.\n- framework: SOC2\n  type: SOC 2 certification\n  scope: Simon Data\n  period: null\n  issuer: null\n  report_access: nda\n  text: Simon Data is SOC 2 certified, and continuously monitors\
  \ all associated controls to ensure we remain in\n    compliance at all times.\n- framework: GDPR\n  type: compliance\n  scope: Simon Data as data processor\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We are also compliant with GDPR and CCPA privacy standards.\n- framework: CCPA\n  type: compliance\n  scope: Simon Data\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We are also compliant with GDPR and CCPA privacy standards.\n"
source_yaml_url: https://artifacts.apis.io/simon-data/compliance/simon-data-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Simon Data's own page on 2026-11-10.
synthetic: false
tags:
- Customer Data Platform
- CDP
- Marketing Automation
- Audience Segmentation
- Event Tracking
- Data Ingestion
- Personalization
- Marketing Technology
- Identity Resolution
- Customer Profiles
- Journey Orchestration
- Snowflake
---
