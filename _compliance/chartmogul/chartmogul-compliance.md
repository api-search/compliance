---
api_specs:
- filename: chartmogul-asyncapi.yml
  format: yaml
  label: ChartMogul Webhooks
  slug: webhooks
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/chartmogul/openapi/chartmogul-asyncapi.yml
- filename: chartmogul-account-api-openapi.yml
  format: yaml
  label: ChartMogul Account API
  slug: chartmogul-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chartmogul/openapi/chartmogul-account-api-openapi.yml
- filename: chartmogul-customers-api-openapi.yml
  format: yaml
  label: ChartMogul Customers API
  slug: chartmogul-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chartmogul/openapi/chartmogul-customers-api-openapi.yml
- filename: chartmogul-invoices-api-openapi.yml
  format: yaml
  label: ChartMogul Invoices API
  slug: chartmogul-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chartmogul/openapi/chartmogul-invoices-api-openapi.yml
- filename: chartmogul-metrics-api-openapi.yml
  format: yaml
  label: ChartMogul Metrics API
  slug: chartmogul-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chartmogul/openapi/chartmogul-metrics-api-openapi.yml
- filename: chartmogul-plans-api-openapi.yml
  format: yaml
  label: ChartMogul Plans API
  slug: chartmogul-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chartmogul/openapi/chartmogul-plans-api-openapi.yml
- filename: chartmogul-subscriptions-api-openapi.yml
  format: yaml
  label: ChartMogul Subscriptions API
  slug: chartmogul-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chartmogul/openapi/chartmogul-subscriptions-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: null
    text: We have our SOC 2 Type 2 report and regularly submit to external audits to demonstrate continued compliance.
    type: SOC 2 Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ChartMogul and all our third-party providers comply with the EU’s General Data Protection Regulation.
    type: null
  trust_center:
    url: https://chartmogul.com/security/
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: ChartMogul
provenance_date: '2026-11-09'
provider_name: ChartMogul
provider_slug: chartmogul
slug: chartmogul-compliance
source_date: '2026-11-09'
source_filename: chartmogul-compliance.yml
source_heading: Compliance
source_page: https://chartmogul.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: ChartMogul\naid: chartmogul\nurl: https://chartmogul.com/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/chartmogul-trust-center.yml\ntrust_center:\n  url: https://chartmogul.com/security/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: We have our SOC 2 Type 2 report and regularly submit to external audits to demonstrate continued compliance.\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ChartMogul and all our third-party providers comply\
  \ with the EU’s General Data Protection Regulation.\n"
source_yaml_url: https://artifacts.apis.io/chartmogul/compliance/chartmogul-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from ChartMogul's own page on 2026-11-09.
synthetic: false
tags:
- Subscription Analytics
- SaaS Metrics
- Revenue Analytics
- MRR
- Churn
- Cohorts
- Billing
---
