---
api_specs:
- filename: guidewire-integration-gateway-asyncapi.yml
  format: yaml
  label: Guidewire Integration Gateway API
  slug: guidewire-integration-gateway-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/guidewire/asyncapi/guidewire-integration-gateway-asyncapi.yml
- filename: guidewire-accounts-api-openapi.yml
  format: yaml
  label: Guidewire Accounts API
  slug: guidewire-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/guidewire/openapi/guidewire-accounts-api-openapi.yml
- filename: guidewire-claims-api-openapi.yml
  format: yaml
  label: Guidewire Claims API
  slug: guidewire-claims-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/guidewire/openapi/guidewire-claims-api-openapi.yml
- filename: guidewire-exposures-api-openapi.yml
  format: yaml
  label: Guidewire Exposures API
  slug: guidewire-exposures-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/guidewire/openapi/guidewire-exposures-api-openapi.yml
- filename: guidewire-fnol-api-openapi.yml
  format: yaml
  label: Guidewire FNOL API
  slug: guidewire-fnol-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/guidewire/openapi/guidewire-fnol-api-openapi.yml
- filename: guidewire-payments-api-openapi.yml
  format: yaml
  label: Guidewire Payments API
  slug: guidewire-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/guidewire/openapi/guidewire-payments-api-openapi.yml
- filename: guidewire-policies-api-openapi.yml
  format: yaml
  label: Guidewire Policies API
  slug: guidewire-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/guidewire/openapi/guidewire-policies-api-openapi.yml
- filename: guidewire-quotes-api-openapi.yml
  format: yaml
  label: Guidewire Quotes API
  slug: guidewire-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/guidewire/openapi/guidewire-quotes-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Guidewire Cloud services
    text: SOC1 & SOC2 Type 2 Reports
    type: SOC 2 Type 2 report
  - framework: SOC1
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC1 & SOC2 Type 2 Reports
    type: SOC 1 report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001 Certification
    type: ISO/IEC 27001 certification
  - framework: ISO27701
    issuer: null
    period: null
    report_access: unstated
    scope: Privacy Information Management System as data processor
    text: ISO 27701 Certification
    type: ISO/IEC 27701 certification
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PCI DSS
    type: PCI DSS
  trust_center:
    url: https://www.guidewire.com/resources/help-and-support/trust-and-security
frameworks:
- ISO27001
- ISO27701
- PCI-DSS
- SOC1
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Guidewire
provenance_date: '2026-11-09'
provider_name: Guidewire
provider_slug: guidewire
slug: guidewire-compliance
source_date: '2026-11-09'
source_filename: guidewire-compliance.yml
source_heading: Compliance
source_page: https://www.guidewire.com/resources/help-and-support/trust-and-security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Guidewire\naid: guidewire\nurl: https://www.guidewire.com/resources/help-and-support/trust-and-security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/guidewire-trust-center.yml\ntrust_center:\n  url: https://www.guidewire.com/resources/help-and-support/trust-and-security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: Guidewire Cloud services\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC1 & SOC2 Type 2 Reports\n- framework: SOC1\n  type: SOC 1 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC1 & SOC2 Type\
  \ 2 Reports\n- framework: ISO27001\n  type: ISO/IEC 27001 certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001 Certification\n- framework: ISO27701\n  type: ISO/IEC 27701 certification\n  scope: Privacy Information Management System as data processor\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27701 Certification\n- framework: PCI-DSS\n  type: PCI DSS\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI DSS\n"
source_yaml_url: https://artifacts.apis.io/guidewire/compliance/guidewire-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Guidewire's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Policy
- Claims
- Billing
- Property and Casualty
---
