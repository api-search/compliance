---
api_specs:
- filename: ibanfirst-accounts-api-openapi.yml
  format: yaml
  label: iBanFirst Accounts API
  slug: ibanfirst-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ibanfirst/openapi/ibanfirst-accounts-api-openapi.yml
- filename: ibanfirst-beneficiaries-api-openapi.yml
  format: yaml
  label: iBanFirst Beneficiaries API
  slug: ibanfirst-beneficiaries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ibanfirst/openapi/ibanfirst-beneficiaries-api-openapi.yml
- filename: ibanfirst-documents-api-openapi.yml
  format: yaml
  label: iBanFirst Documents API
  slug: ibanfirst-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ibanfirst/openapi/ibanfirst-documents-api-openapi.yml
- filename: ibanfirst-financial-movements-api-openapi.yml
  format: yaml
  label: iBanFirst Financial movements API
  slug: ibanfirst-financial-movements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ibanfirst/openapi/ibanfirst-financial-movements-api-openapi.yml
- filename: ibanfirst-fixed-forward-payment-contract-api-openapi.yml
  format: yaml
  label: iBanFirst Fixed forward payment contract API
  slug: ibanfirst-fixed-forward-payment-contract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ibanfirst/openapi/ibanfirst-fixed-forward-payment-contract-api-openapi.yml
- filename: ibanfirst-logs-api-openapi.yml
  format: yaml
  label: iBanFirst Logs API
  slug: ibanfirst-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ibanfirst/openapi/ibanfirst-logs-api-openapi.yml
- filename: ibanfirst-payments-api-openapi.yml
  format: yaml
  label: iBanFirst Payments API
  slug: ibanfirst-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ibanfirst/openapi/ibanfirst-payments-api-openapi.yml
- filename: ibanfirst-spot-trades-api-openapi.yml
  format: yaml
  label: iBanFirst Spot trades API
  slug: ibanfirst-spot-trades-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ibanfirst/openapi/ibanfirst-spot-trades-api-openapi.yml
- filename: ibanfirst-webhook-subscriptions-api-openapi.yml
  format: yaml
  label: iBanFirst Webhook subscriptions API
  slug: ibanfirst-webhook-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ibanfirst/openapi/ibanfirst-webhook-subscriptions-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: iBanFirst PSD2 API
    text: Our API is certified and iBanFirst is exempted from any fallback mechanism in the context of PSD2.
    type: API certification
  - framework: other
    issuer: National Bank of Belgium
    period: null
    report_access: unstated
    scope: iBanFirst S.A. payment institution
    text: iBanFirst S.A. is duly authorised and regulated by the National Bank of Belgium (under company number 0849.872.824) as a payment institution.
    type: payment institution authorisation
  trust_center:
    url: https://ibanfirst.com/psd2-api
frameworks:
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: iBanFirst
provenance_date: '2026-11-09'
provider_name: iBanFirst
provider_slug: ibanfirst
slug: ibanfirst-compliance
source_date: '2026-11-09'
source_filename: ibanfirst-compliance.yml
source_heading: Compliance
source_page: https://ibanfirst.com/psd2-api
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: iBanFirst\naid: ibanfirst\nurl: https://ibanfirst.com/psd2-api\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://ibanfirst.com/psd2-api\nattestations:\n- framework: other\n  type: API certification\n  scope: iBanFirst PSD2 API\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our API is certified and iBanFirst is exempted from any fallback mechanism in the context of PSD2.\n- framework: other\n  type: payment institution authorisation\n  scope: iBanFirst S.A. payment institution\n  period: null\n  issuer: National Bank of Belgium\n  report_access: unstated\n  text: iBanFirst S.A. is duly\
  \ authorised and regulated by the National Bank of Belgium (under company number 0849.872.824)\n    as a payment institution.\n"
source_yaml_url: https://artifacts.apis.io/ibanfirst/compliance/ibanfirst-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from iBanFirst's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech Insurtech
- Cross-Border Payments
- Foreign Exchange
- B2B Payments
- Treasury
- Multi‑Currency Accounts
- SEPA
- PSD2
- Open Banking
- currency-risk-management
- Webhook
- MCP
- Belgium
- Europe
- SWIFT
---
