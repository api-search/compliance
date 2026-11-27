---
api_specs:
- filename: pigment-blocksapi-api-openapi.yml
  format: yaml
  label: Pigment BlocksApi API
  slug: pigment-blocksapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pigment/openapi/pigment-blocksapi-api-openapi.yml
- filename: pigment-export-api-openapi.yml
  format: yaml
  label: Pigment Export API
  slug: pigment-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pigment/openapi/pigment-export-api-openapi.yml
- filename: pigment-exportv1-api-openapi.yml
  format: yaml
  label: Pigment ExportV1 API
  slug: pigment-exportv1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pigment/openapi/pigment-exportv1-api-openapi.yml
- filename: pigment-importconfigurationapi-api-openapi.yml
  format: yaml
  label: Pigment ImportConfigurationApi API
  slug: pigment-importconfigurationapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pigment/openapi/pigment-importconfigurationapi-api-openapi.yml
- filename: pigment-importv1-api-openapi.yml
  format: yaml
  label: Pigment ImportV1 API
  slug: pigment-importv1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pigment/openapi/pigment-importv1-api-openapi.yml
- filename: pigment-viewapi-api-openapi.yml
  format: yaml
  label: Pigment ViewApi API
  slug: pigment-viewapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pigment/openapi/pigment-viewapi-api-openapi.yml
- filename: pigment-application-api-api-openapi.yml
  format: yaml
  label: Pigment Application API
  slug: pigment-application-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pigment/openapi/pigment-application-api-api-openapi.yml
- filename: pigment-import-api-api-openapi.yml
  format: yaml
  label: Pigment Import API
  slug: pigment-import-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pigment/openapi/pigment-import-api-api-openapi.yml
claim_count: 9
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Pigment holds SOC 2 Type 2 and ISO 27001 certifications, independently audited on an annual basis.
    type: SOC 2 Type 2 certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Pigment holds SOC 2 Type 2 and ISO 27001 certifications, independently audited on an annual basis.
    type: ISO 27001 certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Our compliance program covers GDPR and CCPA/CPRA, with formal policies reviewed at least yearly across all security domains.
    type: compliance program coverage
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Our compliance program covers GDPR and CCPA/CPRA, with formal policies reviewed at least yearly across all security domains.
    type: compliance program coverage
  - framework: SOC1
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Certified SOC 1 & SOC 2 Type 2
    type: SOC 1 & SOC 2 Type 2 certification badge
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Certified SOC 1 & SOC 2 Type 2
    type: SOC 1 & SOC 2 Type 2 certification badge
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC2 Type 2 Certified Data Safety
    type: SOC 2 Type 2 certification (page header)
  - framework: SOC1
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Certified SOC 1 & SOC 2 Type 2
    type: SOC 1 badge
  - framework: SOC1
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Certified SOC 1 & SOC 2 Type 2
    type: SOC 1 badge
  trust_center:
    url: https://www.pigment.com/security
frameworks:
- CCPA
- GDPR
- ISO27001
- SOC1
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Pigment
provenance_date: '2026-11-10'
provider_name: Pigment
provider_slug: pigment
slug: pigment-compliance
source_date: '2026-11-10'
source_filename: pigment-compliance.yml
source_heading: Compliance
source_page: https://www.pigment.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Pigment\naid: pigment\nurl: https://www.pigment.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.pigment.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Pigment holds SOC 2 Type 2 and ISO 27001 certifications, independently audited on an annual basis.\n- framework: ISO27001\n  type: ISO 27001 certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Pigment holds SOC 2 Type 2 and ISO 27001 certifications, independently audited on\
  \ an annual basis.\n- framework: GDPR\n  type: compliance program coverage\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our compliance program covers GDPR and CCPA/CPRA, with formal policies reviewed at least yearly across all\n    security domains.\n- framework: CCPA\n  type: compliance program coverage\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our compliance program covers GDPR and CCPA/CPRA, with formal policies reviewed at least yearly across all\n    security domains.\n- framework: SOC1\n  type: SOC 1 & SOC 2 Type 2 certification badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Certified SOC 1 & SOC 2 Type 2\n- framework: SOC2\n  type: SOC 1 & SOC 2 Type 2 certification badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Certified SOC 1 & SOC 2 Type 2\n- framework: SOC2\n  type: SOC 2 Type 2 certification (page header)\n  scope:\
  \ null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC2 Type 2 Certified Data Safety\n- framework: SOC1\n  type: SOC 1 badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Certified SOC 1 & SOC 2 Type 2\n- framework: SOC1\n  type: SOC 1 badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Certified SOC 1 & SOC 2 Type 2\n"
source_yaml_url: https://artifacts.apis.io/pigment/compliance/pigment-compliance.yml
stated_fields:
- attestations
summary_line: 9 quoted statements, read from Pigment's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise Software
- Business Planning
- Financial Planning
- FP&A
- Analytics
- EPM
- Data Integration
- MCP
- SCIM
- Data Platform
- Visualization
- Collaboration
---
