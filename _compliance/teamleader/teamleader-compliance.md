---
api_specs:
- filename: teamleader-contacts-api-openapi.yml
  format: yaml
  label: Teamleader Contacts API
  slug: teamleader-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teamleader/openapi/teamleader-contacts-api-openapi.yml
- filename: teamleader-daysoff-api-openapi.yml
  format: yaml
  label: Teamleader Daysoff API
  slug: teamleader-daysoff-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teamleader/openapi/teamleader-daysoff-api-openapi.yml
- filename: teamleader-deals-api-openapi.yml
  format: yaml
  label: Teamleader Deals API
  slug: teamleader-deals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teamleader/openapi/teamleader-deals-api-openapi.yml
- filename: teamleader-expenses-api-openapi.yml
  format: yaml
  label: Teamleader Expenses API
  slug: teamleader-expenses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teamleader/openapi/teamleader-expenses-api-openapi.yml
- filename: teamleader-files-api-openapi.yml
  format: yaml
  label: Teamleader Files API
  slug: teamleader-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teamleader/openapi/teamleader-files-api-openapi.yml
- filename: teamleader-invoices-api-openapi.yml
  format: yaml
  label: Teamleader Invoices API
  slug: teamleader-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teamleader/openapi/teamleader-invoices-api-openapi.yml
- filename: teamleader-leveltwoareas-api-openapi.yml
  format: yaml
  label: Teamleader Leveltwoareas API
  slug: teamleader-leveltwoareas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teamleader/openapi/teamleader-leveltwoareas-api-openapi.yml
- filename: teamleader-lostreasons-api-openapi.yml
  format: yaml
  label: Teamleader Lostreasons API
  slug: teamleader-lostreasons-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teamleader/openapi/teamleader-lostreasons-api-openapi.yml
- filename: teamleader-tasks-api-openapi.yml
  format: yaml
  label: Teamleader Tasks API
  slug: teamleader-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teamleader/openapi/teamleader-tasks-api-openapi.yml
- filename: teamleader-tickets-api-openapi.yml
  format: yaml
  label: Teamleader Tickets API
  slug: teamleader-tickets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teamleader/openapi/teamleader-tickets-api-openapi.yml
- filename: teamleader-ticketstatus-api-openapi.yml
  format: yaml
  label: Teamleader Ticketstatus API
  slug: teamleader-ticketstatus-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teamleader/openapi/teamleader-ticketstatus-api-openapi.yml
- filename: teamleader-timers-api-openapi.yml
  format: yaml
  label: Teamleader Timers API
  slug: teamleader-timers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teamleader/openapi/teamleader-timers-api-openapi.yml
- filename: teamleader-useravailability-api-openapi.yml
  format: yaml
  label: Teamleader Useravailability API
  slug: teamleader-useravailability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teamleader/openapi/teamleader-useravailability-api-openapi.yml
- filename: teamleader-payment-methods-api-openapi.yml
  format: yaml
  label: Teamleader Payment Methods API
  slug: teamleader-payment-methods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teamleader/openapi/teamleader-payment-methods-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: AWS infrastructure used to store user data
    text: 'By using AWS as our data center, our infrastructure is accredited by: ISO 27001'
    type: accreditation of AWS data center infrastructure
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: AWS infrastructure used to store user data
    text: SOC 1 and SOC 2/SSAE 16/ISAE 3402 (Previously SAS 70 Type II)
    type: accreditation of AWS data center infrastructure
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: AWS infrastructure used to store user data
    text: PCI Level 1
    type: accreditation of AWS data center infrastructure
  - framework: C5
    issuer: null
    period: null
    report_access: unstated
    scope: AWS infrastructure used to store user data
    text: C5 Operational Security
    type: accreditation of AWS data center infrastructure
  trust_center:
    url: https://www.teamleader.eu/legal/security-teamleader-focus
frameworks:
- C5
- ISO27001
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Teamleader
provenance_date: '2026-11-10'
provider_name: Teamleader
provider_slug: teamleader
slug: teamleader-compliance
source_date: '2026-11-10'
source_filename: teamleader-compliance.yml
source_heading: Compliance
source_page: https://www.teamleader.eu/legal/security-teamleader-focus
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Teamleader\naid: teamleader\nurl: https://www.teamleader.eu/legal/security-teamleader-focus\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.teamleader.eu/legal/security-teamleader-focus\nattestations:\n- framework: ISO27001\n  type: accreditation of AWS data center infrastructure\n  scope: AWS infrastructure used to store user data\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'By using AWS as our data center, our infrastructure is accredited by: ISO 27001'\n- framework: SOC2\n  type: accreditation of AWS data center infrastructure\n  scope: AWS infrastructure used to store\
  \ user data\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 1 and SOC 2/SSAE 16/ISAE 3402 (Previously SAS 70 Type II)\n- framework: PCI-DSS\n  type: accreditation of AWS data center infrastructure\n  scope: AWS infrastructure used to store user data\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI Level 1\n- framework: C5\n  type: accreditation of AWS data center infrastructure\n  scope: AWS infrastructure used to store user data\n  period: null\n  issuer: null\n  report_access: unstated\n  text: C5 Operational Security\n"
source_yaml_url: https://artifacts.apis.io/teamleader/compliance/teamleader-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Teamleader's own page on 2026-11-10.
synthetic: false
tags:
- CRM
- Invoicing
- Project Management
- Software-as-a-Service
- Small Business
---
