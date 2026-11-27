---
api_specs:
- filename: submittable-assignments-api-openapi.yml
  format: yaml
  label: Submittable Assignments API
  slug: submittable-assignments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/submittable/openapi/submittable-assignments-api-openapi.yml
- filename: submittable-entries-api-openapi.yml
  format: yaml
  label: Submittable Entries API
  slug: submittable-entries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/submittable/openapi/submittable-entries-api-openapi.yml
- filename: submittable-funds-api-openapi.yml
  format: yaml
  label: Submittable Funds API
  slug: submittable-funds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/submittable/openapi/submittable-funds-api-openapi.yml
- filename: submittable-labels-api-openapi.yml
  format: yaml
  label: Submittable Labels API
  slug: submittable-labels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/submittable/openapi/submittable-labels-api-openapi.yml
- filename: submittable-messaging-api-openapi.yml
  format: yaml
  label: Submittable Messaging API
  slug: submittable-messaging-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/submittable/openapi/submittable-messaging-api-openapi.yml
- filename: submittable-payments-api-openapi.yml
  format: yaml
  label: Submittable Payments API
  slug: submittable-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/submittable/openapi/submittable-payments-api-openapi.yml
- filename: submittable-projects-api-openapi.yml
  format: yaml
  label: Submittable Projects API
  slug: submittable-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/submittable/openapi/submittable-projects-api-openapi.yml
- filename: submittable-submissions-api-openapi.yml
  format: yaml
  label: Submittable Submissions API
  slug: submittable-submissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/submittable/openapi/submittable-submissions-api-openapi.yml
- filename: submittable-teams-api-openapi.yml
  format: yaml
  label: Submittable Teams API
  slug: submittable-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/submittable/openapi/submittable-teams-api-openapi.yml
- filename: submittable-users-api-openapi.yml
  format: yaml
  label: Submittable Users API
  slug: submittable-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/submittable/openapi/submittable-users-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: third party
    period: every year
    report_access: unstated
    scope: customer data security
    text: Submittable completes a third party SOC 2 Type 2 compliance audit every year.
    type: SOC 2 Type 2 audit
  - framework: HIPAA
    issuer: third party
    period: every year
    report_access: unstated
    scope: null
    text: Submittable completes a third party audit every year to assure that we are HIPAA compliant.
    type: third party audit
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Submittable has implemented tools and processes to ensure our compliance with the latest requirements under the GDPR and to help our customers comply as well.
    type: compliance program
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: student education records
    text: Submittable complies with FERPA to protect the privacy of student education records.
    type: FERPA compliance statement
  trust_center:
    url: https://www.submittable.com/security
frameworks:
- GDPR
- HIPAA
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Submittable
provenance_date: '2026-11-10'
provider_name: Submittable
provider_slug: submittable
slug: submittable-compliance
source_date: '2026-11-10'
source_filename: submittable-compliance.yml
source_heading: Compliance
source_page: https://www.submittable.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Submittable\naid: submittable\nurl: https://www.submittable.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/submittable-trust-center.yml\ntrust_center:\n  url: https://www.submittable.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 audit\n  scope: customer data security\n  period: every year\n  issuer: third party\n  report_access: unstated\n  text: Submittable completes a third party SOC 2 Type 2 compliance audit every year.\n- framework: HIPAA\n  type: third party audit\n  scope: null\n  period: every year\n  issuer: third party\n  report_access: unstated\n  text:\
  \ Submittable completes a third party audit every year to assure that we are HIPAA compliant.\n- framework: GDPR\n  type: compliance program\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Submittable has implemented tools and processes to ensure our compliance with the latest requirements under\n    the GDPR and to help our customers comply as well.\n- framework: other\n  type: FERPA compliance statement\n  scope: student education records\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Submittable complies with FERPA to protect the privacy of student education records.\n"
source_yaml_url: https://artifacts.apis.io/submittable/compliance/submittable-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Submittable's own page on 2026-11-10.
synthetic: false
tags:
- Submission Management
- Grants Management
- Application
- Forms
- Non-Profit
- Corporate Social Responsibility
- Workflows
---
