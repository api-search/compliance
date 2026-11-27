---
api_specs:
- filename: humaans-io-audit-events-api-openapi.yml
  format: yaml
  label: Humaans Audit Events API
  slug: humaans-io-audit-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/humaans-io/openapi/humaans-io-audit-events-api-openapi.yml
- filename: humaans-io-bank-accounts-api-openapi.yml
  format: yaml
  label: Humaans Bank Accounts API
  slug: humaans-io-bank-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/humaans-io/openapi/humaans-io-bank-accounts-api-openapi.yml
- filename: humaans-io-companies-api-openapi.yml
  format: yaml
  label: Humaans Companies API
  slug: humaans-io-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/humaans-io/openapi/humaans-io-companies-api-openapi.yml
- filename: humaans-io-compensations-api-openapi.yml
  format: yaml
  label: Humaans Compensations API
  slug: humaans-io-compensations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/humaans-io/openapi/humaans-io-compensations-api-openapi.yml
- filename: humaans-io-custom-fields-api-openapi.yml
  format: yaml
  label: Humaans Custom Fields API
  slug: humaans-io-custom-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/humaans-io/openapi/humaans-io-custom-fields-api-openapi.yml
- filename: humaans-io-documents-api-openapi.yml
  format: yaml
  label: Humaans Documents API
  slug: humaans-io-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/humaans-io/openapi/humaans-io-documents-api-openapi.yml
- filename: humaans-io-equipment-api-openapi.yml
  format: yaml
  label: Humaans Equipment API
  slug: humaans-io-equipment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/humaans-io/openapi/humaans-io-equipment-api-openapi.yml
- filename: humaans-io-job-roles-api-openapi.yml
  format: yaml
  label: Humaans Job Roles API
  slug: humaans-io-job-roles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/humaans-io/openapi/humaans-io-job-roles-api-openapi.yml
- filename: humaans-io-locations-api-openapi.yml
  format: yaml
  label: Humaans Locations API
  slug: humaans-io-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/humaans-io/openapi/humaans-io-locations-api-openapi.yml
- filename: humaans-io-people-api-openapi.yml
  format: yaml
  label: Humaans People API
  slug: humaans-io-people-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/humaans-io/openapi/humaans-io-people-api-openapi.yml
- filename: humaans-io-performance-api-openapi.yml
  format: yaml
  label: Humaans Performance API
  slug: humaans-io-performance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/humaans-io/openapi/humaans-io-performance-api-openapi.yml
- filename: humaans-io-time-away-api-openapi.yml
  format: yaml
  label: Humaans Time Away API
  slug: humaans-io-time-away-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/humaans-io/openapi/humaans-io-time-away-api-openapi.yml
- filename: humaans-io-timesheet-api-openapi.yml
  format: yaml
  label: Humaans Timesheet API
  slug: humaans-io-timesheet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/humaans-io/openapi/humaans-io-timesheet-api-openapi.yml
- filename: humaans-io-webhooks-api-openapi.yml
  format: yaml
  label: Humaans Webhooks API
  slug: humaans-io-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/humaans-io/openapi/humaans-io-webhooks-api-openapi.yml
- filename: humaans-io-working-patterns-api-openapi.yml
  format: yaml
  label: Humaans Working Patterns API
  slug: humaans-io-working-patterns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/humaans-io/openapi/humaans-io-working-patterns-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Humaans platform
    text: Our SOC2 Type 2 report is available for download in our Trust Center.
    type: SOC 2 Type 2 report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: Humaans
    text: You can download our ISO27001 certification in our Trust Center.
    type: ISO/IEC 27001:2022 certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Humaans
    text: Humaans is fully committed to compliance with the General Data Protection Regulation (GDPR) and the UK Data Protection Act 2018.
    type: GDPR compliance commitment
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: Credit card processing via Stripe
    text: with PCI Service Provider Level 1 standards in the storage and handling of credit card information.
    type: PCI Service Provider Level 1 (via Stripe)
  trust_center:
    url: https://humaans.io/security
frameworks:
- GDPR
- ISO27001
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Humaans
provenance_date: '2026-11-09'
provider_name: Humaans
provider_slug: humaans-io
slug: humaans-io-compliance
source_date: '2026-11-09'
source_filename: humaans-io-compliance.yml
source_heading: Compliance
source_page: https://humaans.io/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Humaans\naid: humaans-io\nurl: https://humaans.io/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/humaans-io-trust-center.yml\ntrust_center:\n  url: https://humaans.io/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: Humaans platform\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Our SOC2 Type 2 report is available for download in our Trust Center.\n- framework: ISO27001\n  type: ISO/IEC 27001:2022 certification\n  scope: Humaans\n  period: null\n  issuer: null\n  report_access: on_request\n  text: You can download our ISO27001 certification\
  \ in our Trust Center.\n- framework: GDPR\n  type: GDPR compliance commitment\n  scope: Humaans\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Humaans is fully committed to compliance with the General Data Protection Regulation (GDPR) and the UK Data\n    Protection Act 2018.\n- framework: PCI-DSS\n  type: PCI Service Provider Level 1 (via Stripe)\n  scope: Credit card processing via Stripe\n  period: null\n  issuer: null\n  report_access: unstated\n  text: with PCI Service Provider Level 1 standards in the storage and handling of credit card information.\n"
source_yaml_url: https://artifacts.apis.io/humaans-io/compliance/humaans-io-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Humaans's own page on 2026-11-09.
synthetic: false
tags:
- Human Resources
- HRIS
- People Operations
- People Analytics
- Onboarding
- Offboarding
- Performance Management
- Time Off
- Compensation
- Workflow Automation
- AI Companion
- AI Agents
- United Kingdom
- London
---
