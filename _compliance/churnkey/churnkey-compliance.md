---
api_specs:
- filename: churnkey-billing-contacts-api-openapi.yml
  format: yaml
  label: Churnkey Billing Contacts API
  slug: churnkey-billing-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/churnkey/openapi/churnkey-billing-contacts-api-openapi.yml
- filename: churnkey-customers-api-openapi.yml
  format: yaml
  label: Churnkey Customers API
  slug: churnkey-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/churnkey/openapi/churnkey-customers-api-openapi.yml
- filename: churnkey-data-subject-requests-api-openapi.yml
  format: yaml
  label: Churnkey Data Subject Requests API
  slug: churnkey-data-subject-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/churnkey/openapi/churnkey-data-subject-requests-api-openapi.yml
- filename: churnkey-events-api-openapi.yml
  format: yaml
  label: Churnkey Events API
  slug: churnkey-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/churnkey/openapi/churnkey-events-api-openapi.yml
- filename: churnkey-sessions-api-openapi.yml
  format: yaml
  label: Churnkey Sessions API
  slug: churnkey-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/churnkey/openapi/churnkey-sessions-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: In addition to our SOC 2 Type II audit, we also ensure GDPR compliance
    type: SOC 2 Type II audit
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: we also ensure GDPR compliance, conduct regular penetration tests
    type: GDPR compliance
  trust_center:
    url: https://churnkey.co/security
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Churnkey
provenance_date: '2026-11-09'
provider_name: Churnkey
provider_slug: churnkey
slug: churnkey-compliance
source_date: '2026-11-09'
source_filename: churnkey-compliance.yml
source_heading: Compliance
source_page: https://churnkey.co/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Churnkey\naid: churnkey\nurl: https://churnkey.co/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/churnkey-trust-center.yml\ntrust_center:\n  url: https://churnkey.co/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II audit\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: In addition to our SOC 2 Type II audit, we also ensure GDPR compliance\n- framework: GDPR\n  type: GDPR compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: we also ensure GDPR compliance, conduct regular penetration tests\n"
source_yaml_url: https://artifacts.apis.io/churnkey/compliance/churnkey-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Churnkey's own page on 2026-11-09.
synthetic: false
tags:
- Churn Prevention
- Retention
- Cancellation Flows
- Failed Payment Recovery
- Dunning
- Reactivation
- Subscription
- Software-as-a-Service
---
