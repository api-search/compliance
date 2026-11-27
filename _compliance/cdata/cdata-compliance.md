---
api_specs:
- filename: cdata-mcp-api-openapi.yml
  format: yaml
  label: CData Connect AI MCP Server
  slug: mcp
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdata/openapi/cdata-mcp-api-openapi.yml
- filename: cdata-account-api-openapi.yml
  format: yaml
  label: CData Account API
  slug: cdata-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdata/openapi/cdata-account-api-openapi.yml
- filename: cdata-cache-api-openapi.yml
  format: yaml
  label: CData Cache API
  slug: cdata-cache-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdata/openapi/cdata-cache-api-openapi.yml
- filename: cdata-connection-api-openapi.yml
  format: yaml
  label: CData Connection API
  slug: cdata-connection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdata/openapi/cdata-connection-api-openapi.yml
- filename: cdata-data-explorer-api-openapi.yml
  format: yaml
  label: CData Data Explorer API
  slug: cdata-data-explorer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdata/openapi/cdata-data-explorer-api-openapi.yml
- filename: cdata-job-api-openapi.yml
  format: yaml
  label: CData Job API
  slug: cdata-job-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdata/openapi/cdata-job-api-openapi.yml
- filename: cdata-jobs-api-openapi.yml
  format: yaml
  label: CData Jobs API
  slug: cdata-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdata/openapi/cdata-jobs-api-openapi.yml
- filename: cdata-log-api-openapi.yml
  format: yaml
  label: CData Log API
  slug: cdata-log-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdata/openapi/cdata-log-api-openapi.yml
- filename: cdata-metadata-api-openapi.yml
  format: yaml
  label: CData Metadata API
  slug: cdata-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdata/openapi/cdata-metadata-api-openapi.yml
- filename: cdata-query-api-openapi.yml
  format: yaml
  label: CData Query API
  slug: cdata-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdata/openapi/cdata-query-api-openapi.yml
- filename: cdata-service-accounts-api-openapi.yml
  format: yaml
  label: CData Service Accounts API
  slug: cdata-service-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdata/openapi/cdata-service-accounts-api-openapi.yml
- filename: cdata-users-api-openapi.yml
  format: yaml
  label: CData Users API
  slug: cdata-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdata/openapi/cdata-users-api-openapi.yml
- filename: cdata-odata-api-openapi.yml
  format: yaml
  label: CData O Data API
  slug: cdata-odata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdata/openapi/cdata-odata-api-openapi.yml
- filename: cdata-open-api-api-openapi.yml
  format: yaml
  label: CData Open API
  slug: cdata-open-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdata/openapi/cdata-open-api-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent auditor
    period: null
    report_access: on_request
    scope: product, infrastructure, and policies
    text: CData has completed third-party SOC 2 Type II and ISO/IEC 27001:2022 compliance audits
    type: SOC 2 Type II audit
  - framework: ISO27001
    issuer: independent auditor
    period: null
    report_access: on_request
    scope: product, infrastructure, and policies
    text: To obtain CData updated SOC 2 Type II Attestations and ISO Certificates, see the Customer Kit link at the bottom of the page.
    type: ISO/IEC 27001:2022 compliance audit
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: customer and partner data
    text: CData is compliant with US and international consumer data privacy regulations like GDPR and CCPA
    type: compliance with regulation
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: customer and partner data
    text: CData is compliant with US and international consumer data privacy regulations like GDPR and CCPA
    type: compliance with regulation
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: CData Connect AI, CData Sync (On-Prem), and CData Arc (On-Prem)
    text: CData operates as a business associate and offers a Business Associate Agreement (BAA) for eligible use cases.
    type: business associate agreement offered for eligible use cases
  trust_center:
    url: https://www.cdata.com/security/
frameworks:
- CCPA
- GDPR
- HIPAA
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: CData
provenance_date: '2026-11-09'
provider_name: CData
provider_slug: cdata
slug: cdata-compliance
source_date: '2026-11-09'
source_filename: cdata-compliance.yml
source_heading: Compliance
source_page: https://www.cdata.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: CData\naid: cdata\nurl: https://www.cdata.com/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.cdata.com/security/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II audit\n  scope: product, infrastructure, and policies\n  period: null\n  issuer: independent auditor\n  report_access: on_request\n  text: CData has completed third-party SOC 2 Type II and ISO/IEC 27001:2022 compliance audits\n- framework: ISO27001\n  type: ISO/IEC 27001:2022 compliance audit\n  scope: product, infrastructure, and policies\n  period: null\n  issuer: independent auditor\n  report_access: on_request\n  text:\
  \ To obtain CData updated SOC 2 Type II Attestations and ISO Certificates, see the Customer Kit link at the\n    bottom of the page.\n- framework: GDPR\n  type: compliance with regulation\n  scope: customer and partner data\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CData is compliant with US and international consumer data privacy regulations like GDPR and CCPA\n- framework: CCPA\n  type: compliance with regulation\n  scope: customer and partner data\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CData is compliant with US and international consumer data privacy regulations like GDPR and CCPA\n- framework: HIPAA\n  type: business associate agreement offered for eligible use cases\n  scope: CData Connect AI, CData Sync (On-Prem), and CData Arc (On-Prem)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CData operates as a business associate and offers a Business Associate Agreement (BAA) for eligible use\n    cases.\n"
source_yaml_url: https://artifacts.apis.io/cdata/compliance/cdata-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from CData's own page on 2026-11-09.
synthetic: false
tags:
- Data
- Data Access
- Data Connectivity
- Database
- NoSQL
- SQL
- A2A
---
