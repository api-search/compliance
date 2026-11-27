---
api_specs:
- filename: gusto-asyncapi.yml
  format: yaml
  label: Gusto Embedded Payroll API
  slug: embedded-payroll-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/gusto/openapi/gusto-asyncapi.yml
- filename: gusto-companies-api-openapi.yml
  format: yaml
  label: Gusto Companies API
  slug: gusto-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gusto/openapi/gusto-companies-api-openapi.yml
- filename: gusto-contractors-api-openapi.yml
  format: yaml
  label: Gusto Contractors API
  slug: gusto-contractors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gusto/openapi/gusto-contractors-api-openapi.yml
- filename: gusto-employees-api-openapi.yml
  format: yaml
  label: Gusto Employees API
  slug: gusto-employees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gusto/openapi/gusto-employees-api-openapi.yml
- filename: gusto-flows-api-openapi.yml
  format: yaml
  label: Gusto Flows API
  slug: gusto-flows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gusto/openapi/gusto-flows-api-openapi.yml
- filename: gusto-payrolls-api-openapi.yml
  format: yaml
  label: Gusto Payrolls API
  slug: gusto-payrolls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gusto/openapi/gusto-payrolls-api-openapi.yml
- filename: gusto-reports-api-openapi.yml
  format: yaml
  label: Gusto Reports API
  slug: gusto-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gusto/openapi/gusto-reports-api-openapi.yml
- filename: gusto-webhooks-api-openapi.yml
  format: yaml
  label: Gusto Webhooks API
  slug: gusto-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gusto/openapi/gusto-webhooks-api-openapi.yml
- filename: gusto-bank-accounts-api-openapi.yml
  format: yaml
  label: Gusto Bank Accounts API
  slug: gusto-bank-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gusto/openapi/gusto-bank-accounts-api-openapi.yml
- filename: gusto-contractor-payments-api-openapi.yml
  format: yaml
  label: Gusto Contractor Payments API
  slug: gusto-contractor-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gusto/openapi/gusto-contractor-payments-api-openapi.yml
- filename: gusto-pay-schedules-api-openapi.yml
  format: yaml
  label: Gusto Pay Schedules API
  slug: gusto-pay-schedules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gusto/openapi/gusto-pay-schedules-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC1
    issuer: null
    period: null
    report_access: nda
    scope: null
    text: Gusto maintains SOC 1 and SOC 2 reports, which are updated annually.
    type: SOC 1 report
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: null
    text: Customers can access these reports via our Trust Center after filling out a nondisclosure agreement.
    type: SOC 2 report
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: protected health information (PHI)
    text: We follow HIPAA guidelines to safeguard our customers’ protected health information (PHI).
    type: HIPAA guidelines adherence
  trust_center:
    url: https://gusto.com/security
frameworks:
- HIPAA
- SOC1
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Gusto
provenance_date: '2026-11-09'
provider_name: Gusto
provider_slug: gusto
slug: gusto-compliance
source_date: '2026-11-09'
source_filename: gusto-compliance.yml
source_heading: Compliance
source_page: https://gusto.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Gusto\naid: gusto\nurl: https://gusto.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/gusto-trust-center.yml\ntrust_center:\n  url: https://gusto.com/security\nattestations:\n- framework: SOC1\n  type: SOC 1 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: Gusto maintains SOC 1 and SOC 2 reports, which are updated annually.\n- framework: SOC2\n  type: SOC 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: Customers can access these reports via our Trust Center after filling out a nondisclosure agreement.\n- framework:\
  \ HIPAA\n  type: HIPAA guidelines adherence\n  scope: protected health information (PHI)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We follow HIPAA guidelines to safeguard our customers’ protected health information (PHI).\n"
source_yaml_url: https://artifacts.apis.io/gusto/compliance/gusto-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Gusto's own page on 2026-11-09.
synthetic: false
tags:
- Human Resources
- Payroll
- Benefits
- Enterprise Software
- Embedded Finance
- Employee Benefits
---
