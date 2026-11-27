---
api_specs:
- filename: leaseaccelerator-documents-api-openapi.yml
  format: yaml
  label: LeaseAccelerator Documents API
  slug: leaseaccelerator-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leaseaccelerator/openapi/leaseaccelerator-documents-api-openapi.yml
- filename: leaseaccelerator-events-api-openapi.yml
  format: yaml
  label: LeaseAccelerator Events API
  slug: leaseaccelerator-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leaseaccelerator/openapi/leaseaccelerator-events-api-openapi.yml
- filename: leaseaccelerator-financials-api-openapi.yml
  format: yaml
  label: LeaseAccelerator Financials API
  slug: leaseaccelerator-financials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leaseaccelerator/openapi/leaseaccelerator-financials-api-openapi.yml
- filename: leaseaccelerator-portfolio-api-openapi.yml
  format: yaml
  label: LeaseAccelerator Portfolio API
  slug: leaseaccelerator-portfolio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leaseaccelerator/openapi/leaseaccelerator-portfolio-api-openapi.yml
- filename: leaseaccelerator-process-status-api-openapi.yml
  format: yaml
  label: LeaseAccelerator Process Status API
  slug: leaseaccelerator-process-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leaseaccelerator/openapi/leaseaccelerator-process-status-api-openapi.yml
- filename: leaseaccelerator-reference-data-api-openapi.yml
  format: yaml
  label: LeaseAccelerator Reference Data API
  slug: leaseaccelerator-reference-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leaseaccelerator/openapi/leaseaccelerator-reference-data-api-openapi.yml
- filename: leaseaccelerator-reporting-api-openapi.yml
  format: yaml
  label: LeaseAccelerator Reporting API
  slug: leaseaccelerator-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leaseaccelerator/openapi/leaseaccelerator-reporting-api-openapi.yml
- filename: leaseaccelerator-search-api-openapi.yml
  format: yaml
  label: LeaseAccelerator Search API
  slug: leaseaccelerator-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leaseaccelerator/openapi/leaseaccelerator-search-api-openapi.yml
- filename: leaseaccelerator-user-provisioning-api-openapi.yml
  format: yaml
  label: LeaseAccelerator User Provisioning API
  slug: leaseaccelerator-user-provisioning-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leaseaccelerator/openapi/leaseaccelerator-user-provisioning-api-openapi.yml
claim_count: 7
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: '2026'
    report_access: unstated
    scope: insightsoftware
    text: ISO 27001-2022 Certificate_2026
    type: certificate
  - framework: ISO42001
    issuer: null
    period: '2023'
    report_access: unstated
    scope: insightsoftware
    text: ISO 42001-2023 Certificate_2026
    type: certificate
  - framework: ISO9001
    issuer: null
    period: '2026'
    report_access: unstated
    scope: insightsoftware
    text: ISO 9001-2015 Surveillance 1 certificate 2026
    type: certificate
  - framework: SOC1
    issuer: null
    period: April 2025
    report_access: unstated
    scope: LeaseAccelerator
    text: LeaseAccelerator - SOC 1 Type 2 Audit Report April 2025
    type: Type 2 audit report
  - framework: SOC2
    issuer: null
    period: '2026'
    report_access: unstated
    scope: LeaseAccelerator Lease Accounting Manager
    text: LeaseAccelerator Lease Accounting Manager - SOC 2 Type 2 - Audit Report 2026
    type: Type 2 audit report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: insightsoftware
    text: GDPR
    type: badge
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: insightsoftware
    text: CCPA
    type: badge
  trust_center:
    url: https://trust.insightsoftware.com/,%20https://insightsoftware.com/trust/
frameworks:
- CCPA
- GDPR
- ISO27001
- ISO42001
- ISO9001
- SOC1
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: LeaseAccelerator
provenance_date: '2026-11-09'
provider_name: LeaseAccelerator
provider_slug: leaseaccelerator
slug: leaseaccelerator-compliance
source_date: '2026-11-09'
source_filename: leaseaccelerator-compliance.yml
source_heading: Compliance
source_page: https://trust.insightsoftware.com/,%20https://insightsoftware.com/trust/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: LeaseAccelerator\naid: leaseaccelerator\nurl: https://trust.insightsoftware.com/,%20https://insightsoftware.com/trust/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/leaseaccelerator-trust-center.yml\ntrust_center:\n  url: https://trust.insightsoftware.com/,%20https://insightsoftware.com/trust/\nattestations:\n- framework: ISO27001\n  type: certificate\n  scope: insightsoftware\n  period: '2026'\n  issuer: null\n  report_access: unstated\n  text: ISO 27001-2022 Certificate_2026\n- framework: ISO42001\n  type: certificate\n  scope: insightsoftware\n  period: '2023'\n  issuer: null\n  report_access:\
  \ unstated\n  text: ISO 42001-2023 Certificate_2026\n- framework: ISO9001\n  type: certificate\n  scope: insightsoftware\n  period: '2026'\n  issuer: null\n  report_access: unstated\n  text: ISO 9001-2015 Surveillance 1 certificate 2026\n- framework: SOC1\n  type: Type 2 audit report\n  scope: LeaseAccelerator\n  period: April 2025\n  issuer: null\n  report_access: unstated\n  text: LeaseAccelerator - SOC 1 Type 2 Audit Report April 2025\n- framework: SOC2\n  type: Type 2 audit report\n  scope: LeaseAccelerator Lease Accounting Manager\n  period: '2026'\n  issuer: null\n  report_access: unstated\n  text: LeaseAccelerator Lease Accounting Manager - SOC 2 Type 2 - Audit Report 2026\n- framework: GDPR\n  type: badge\n  scope: insightsoftware\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: CCPA\n  type: badge\n  scope: insightsoftware\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA\n"
source_yaml_url: https://artifacts.apis.io/leaseaccelerator/compliance/leaseaccelerator-compliance.yml
stated_fields:
- attestations
summary_line: 7 quoted statements, read from LeaseAccelerator's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Lease Accounting
- Lease Administration
- Financial Reporting
- Enterprise Software
- Accounting
- Real Estate
- Asset Management
- ERP Integration
- Compliance
---
