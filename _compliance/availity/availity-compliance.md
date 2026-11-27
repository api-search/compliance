---
api_specs:
- filename: availity-auth-attachments-api-openapi.yml
  format: yaml
  label: availity Auth Attachments API
  slug: availity-auth-attachments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/availity/openapi/availity-auth-attachments-api-openapi.yml
- filename: availity-claim-attachments-api-openapi.yml
  format: yaml
  label: availity Claim Attachments API
  slug: availity-claim-attachments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/availity/openapi/availity-claim-attachments-api-openapi.yml
- filename: availity-claim-status-api-openapi.yml
  format: yaml
  label: availity Claim Status API
  slug: availity-claim-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/availity/openapi/availity-claim-status-api-openapi.yml
- filename: availity-eligibility-api-openapi.yml
  format: yaml
  label: availity Eligibility API
  slug: availity-eligibility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/availity/openapi/availity-eligibility-api-openapi.yml
- filename: availity-enhanced-claim-status-api-openapi.yml
  format: yaml
  label: availity Enhanced Claim Status API
  slug: availity-enhanced-claim-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/availity/openapi/availity-enhanced-claim-status-api-openapi.yml
- filename: availity-is-auth-required-api-openapi.yml
  format: yaml
  label: availity Is Auth Required API
  slug: availity-is-auth-required-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/availity/openapi/availity-is-auth-required-api-openapi.yml
- filename: availity-service-reviews-api-openapi.yml
  format: yaml
  label: availity Service Reviews API
  slug: availity-service-reviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/availity/openapi/availity-service-reviews-api-openapi.yml
- filename: availity-availity-payer-list-api-openapi.yml
  format: yaml
  label: Availity Availity Payer List API
  slug: availity-availity-payer-list-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/availity/openapi/availity-availity-payer-list-api-openapi.yml
- filename: availity-claim-statuses-api-openapi.yml
  format: yaml
  label: Availity Claim Statuses API
  slug: availity-claim-statuses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/availity/openapi/availity-claim-statuses-api-openapi.yml
- filename: availity-configurations-api-openapi.yml
  format: yaml
  label: Availity Configurations API
  slug: availity-configurations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/availity/openapi/availity-configurations-api-openapi.yml
- filename: availity-coverages-api-openapi.yml
  format: yaml
  label: Availity Coverages API
  slug: availity-coverages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/availity/openapi/availity-coverages-api-openapi.yml
- filename: availity-dental-claims-api-openapi.yml
  format: yaml
  label: Availity Dental Claims API
  slug: availity-dental-claims-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/availity/openapi/availity-dental-claims-api-openapi.yml
- filename: availity-dfs-api-openapi.yml
  format: yaml
  label: Availity Dfs API
  slug: availity-dfs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/availity/openapi/availity-dfs-api-openapi.yml
- filename: availity-institutional-claims-api-openapi.yml
  format: yaml
  label: Availity Institutional Claims API
  slug: availity-institutional-claims-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/availity/openapi/availity-institutional-claims-api-openapi.yml
- filename: availity-patient-cost-estimator-2-0-0-professional-api-openapi.yml
  format: yaml
  label: Availity Patient Cost Estimator 2.0.0 Professional API
  slug: availity-patient-cost-estimator-2-0-0-professional-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/availity/openapi/availity-patient-cost-estimator-2-0-0-professional-api-openapi.yml
- filename: availity-professional-claims-api-openapi.yml
  format: yaml
  label: Availity Professional Claims API
  slug: availity-professional-claims-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/availity/openapi/availity-professional-claims-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: HITRUST
    issuer: null
    period: null
    report_access: unstated
    scope: risks associated with industry including HIPAA Privacy and Security
    text: Availity follows requirements and standards established by CMS, EHNAC, and HITRUST for risks associated with our industry
    type: standards followed
  trust_center:
    url: https://www.availity.com/regulatory-compliance/
frameworks:
- HITRUST
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Availity
provenance_date: '2026-11-09'
provider_name: Availity
provider_slug: availity
slug: availity-compliance
source_date: '2026-11-09'
source_filename: availity-compliance.yml
source_heading: Compliance
source_page: https://www.availity.com/regulatory-compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Availity\naid: availity\nurl: https://www.availity.com/regulatory-compliance/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.availity.com/regulatory-compliance/\nattestations:\n- framework: HITRUST\n  type: standards followed\n  scope: risks associated with industry including HIPAA Privacy and Security\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Availity follows requirements and standards established by CMS, EHNAC, and HITRUST for risks associated\n    with our industry\n"
source_yaml_url: https://artifacts.apis.io/availity/compliance/availity-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Availity's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Clearinghouse
- HIPAA
- X12 EDI
- Eligibility
- Claims
- Prior Authorization
- Revenue Cycle Management
- Payers
- Price Transparency
- Health Insurance
---
