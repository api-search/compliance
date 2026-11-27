---
api_specs:
- filename: splitit-authentication-api-openapi.yml
  format: yaml
  label: Splitit Authentication API
  slug: splitit-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/splitit/openapi/splitit-authentication-api-openapi.yml
- filename: splitit-eligibility-api-openapi.yml
  format: yaml
  label: Splitit Eligibility API
  slug: splitit-eligibility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/splitit/openapi/splitit-eligibility-api-openapi.yml
- filename: splitit-installment-plans-api-openapi.yml
  format: yaml
  label: Splitit Installment Plans API
  slug: splitit-installment-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/splitit/openapi/splitit-installment-plans-api-openapi.yml
- filename: splitit-merchant-management-api-openapi.yml
  format: yaml
  label: Splitit Merchant Management API
  slug: splitit-merchant-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/splitit/openapi/splitit-merchant-management-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PCI-DSS 4.0
    type: PCI DSS certificate and report
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II
    type: SOC 2 Type II report
  trust_center:
    url: https://trust.splitit.com/
frameworks:
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Splitit
provenance_date: '2026-11-10'
provider_name: Splitit
provider_slug: splitit
slug: splitit-compliance
source_date: '2026-11-10'
source_filename: splitit-compliance.yml
source_heading: Compliance
source_page: https://trust.splitit.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Splitit\naid: splitit\nurl: https://trust.splitit.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.splitit.com/\nattestations:\n- framework: PCI-DSS\n  type: PCI DSS certificate and report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI-DSS 4.0\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II\n"
source_yaml_url: https://artifacts.apis.io/splitit/compliance/splitit-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Splitit's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- Installments
- Buy Now Pay Later
- Credit Cards
- Fintech
- E-Commerce
---
