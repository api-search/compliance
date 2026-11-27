---
api_specs:
- filename: taxjar-categories-api-openapi.yml
  format: yaml
  label: TaxJar Categories API
  slug: taxjar-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/taxjar/openapi/taxjar-categories-api-openapi.yml
- filename: taxjar-customers-api-openapi.yml
  format: yaml
  label: TaxJar Customers API
  slug: taxjar-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/taxjar/openapi/taxjar-customers-api-openapi.yml
- filename: taxjar-nexus-api-openapi.yml
  format: yaml
  label: TaxJar Nexus API
  slug: taxjar-nexus-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/taxjar/openapi/taxjar-nexus-api-openapi.yml
- filename: taxjar-rates-api-openapi.yml
  format: yaml
  label: TaxJar Rates API
  slug: taxjar-rates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/taxjar/openapi/taxjar-rates-api-openapi.yml
- filename: taxjar-summary-rates-api-openapi.yml
  format: yaml
  label: TaxJar Summary Rates API
  slug: taxjar-summary-rates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/taxjar/openapi/taxjar-summary-rates-api-openapi.yml
- filename: taxjar-taxes-api-openapi.yml
  format: yaml
  label: TaxJar Taxes API
  slug: taxjar-taxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/taxjar/openapi/taxjar-taxes-api-openapi.yml
- filename: taxjar-transactions-orders-api-openapi.yml
  format: yaml
  label: TaxJar Transactions - Orders API
  slug: taxjar-transactions-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/taxjar/openapi/taxjar-transactions-orders-api-openapi.yml
- filename: taxjar-transactions-refunds-api-openapi.yml
  format: yaml
  label: TaxJar Transactions - Refunds API
  slug: taxjar-transactions-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/taxjar/openapi/taxjar-transactions-refunds-api-openapi.yml
- filename: taxjar-validations-api-openapi.yml
  format: yaml
  label: TaxJar Validations API
  slug: taxjar-validations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/taxjar/openapi/taxjar-validations-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent audit
    period: null
    report_access: unstated
    scope: null
    text: TaxJar has achieved SOC 2, Type 2 compliance through an independent audit.
    type: SOC 2 Type II report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR Compliant
    type: compliance
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Cloud Security Alliance
    type: Cloud Security Alliance listing
  trust_center:
    url: https://www.taxjar.com/security
frameworks:
- CSA-STAR
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: TaxJar
provenance_date: '2026-11-10'
provider_name: TaxJar
provider_slug: taxjar
slug: taxjar-compliance
source_date: '2026-11-10'
source_filename: taxjar-compliance.yml
source_heading: Compliance
source_page: https://www.taxjar.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: TaxJar\naid: taxjar\nurl: https://www.taxjar.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/taxjar-trust-center.yml\ntrust_center:\n  url: https://www.taxjar.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: null\n  period: null\n  issuer: independent audit\n  report_access: unstated\n  text: TaxJar has achieved SOC 2, Type 2 compliance through an independent audit.\n- framework: GDPR\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR Compliant\n- framework: CSA-STAR\n  type: Cloud Security Alliance\
  \ listing\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Cloud Security Alliance\n"
source_yaml_url: https://artifacts.apis.io/taxjar/compliance/taxjar-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from TaxJar's own page on 2026-11-10.
synthetic: false
tags:
- Sales Tax
- Tax Compliance
- E-Commerce
- Tax Calculation
- Tax Automation
- Stripe
- Fintech
- Tax
---
