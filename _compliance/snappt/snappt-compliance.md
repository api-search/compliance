---
api_specs:
- filename: snappt-account-api-openapi.yml
  format: yaml
  label: Snappt Account API
  slug: snappt-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snappt/openapi/snappt-account-api-openapi.yml
- filename: snappt-applicant-sessions-api-openapi.yml
  format: yaml
  label: Snappt Applicant Sessions API
  slug: snappt-applicant-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snappt/openapi/snappt-applicant-sessions-api-openapi.yml
- filename: snappt-applicants-api-openapi.yml
  format: yaml
  label: Snappt Applicants API
  slug: snappt-applicants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snappt/openapi/snappt-applicants-api-openapi.yml
- filename: snappt-id-verification-api-openapi.yml
  format: yaml
  label: Snappt ID Verification API
  slug: snappt-id-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snappt/openapi/snappt-id-verification-api-openapi.yml
- filename: snappt-internal-idv-api-openapi.yml
  format: yaml
  label: Snappt Internal IDV API
  slug: snappt-internal-idv-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snappt/openapi/snappt-internal-idv-api-openapi.yml
- filename: snappt-properties-api-openapi.yml
  format: yaml
  label: Snappt Properties API
  slug: snappt-properties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snappt/openapi/snappt-properties-api-openapi.yml
- filename: snappt-webhooks-api-openapi.yml
  format: yaml
  label: Snappt Webhooks API
  slug: snappt-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snappt/openapi/snappt-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent auditors
    period: null
    report_access: on_request
    scope: Snappt platform
    text: SOC 2 Type II compliant.
    type: SOC 2 Type II
  - framework: SOC2
    issuer: null
    period: July 1 2025 through June 30 2026
    report_access: on_request
    scope: Snappt Inc.
    source: https://trust.snappt.com/
    text: Snappt Inc. SOC 2 Type II | July 1 2025 through June 30 2026
    type: SOC 2 Type II
  trust_center:
    url: https://snappt.com/security
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Snappt
provenance_date: '2026-11-10'
provider_name: Snappt
provider_slug: snappt
slug: snappt-compliance
source_date: '2026-11-10'
source_filename: snappt-compliance.yml
source_heading: Compliance
source_page: https://snappt.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Snappt\naid: snappt\nurl: https://snappt.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/snappt-trust-center.yml\n  sources:\n  - https://snappt.com/security\n  - https://trust.snappt.com/\ntrust_center:\n  url: https://snappt.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: Snappt platform\n  period: null\n  issuer: independent auditors\n  report_access: on_request\n  text: SOC 2 Type II compliant.\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: Snappt Inc.\n  period: July 1 2025 through June 30 2026\n  issuer: null\n  report_access: on_request\n  text:\
  \ Snappt Inc. SOC 2 Type II | July 1 2025 through June 30 2026\n  source: https://trust.snappt.com/\n"
source_yaml_url: https://artifacts.apis.io/snappt/compliance/snappt-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Snappt's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fraud Prevention
- Document Verification
- Identity Verification
- Income Verification
- Property Management
- Multifamily
- Real Estate
- PropTech
- Tenant Screening
- Rental Applications
- Webhook
---
