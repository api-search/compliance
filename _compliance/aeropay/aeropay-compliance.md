---
api_specs:
- filename: aeropay-authentication-api-openapi.yml
  format: yaml
  label: Aeropay Authentication API
  slug: aeropay-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aeropay/openapi/aeropay-authentication-api-openapi.yml
- filename: aeropay-bank-connection-api-openapi.yml
  format: yaml
  label: Aeropay Bank Connection API
  slug: aeropay-bank-connection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aeropay/openapi/aeropay-bank-connection-api-openapi.yml
- filename: aeropay-create-manage-transactions-api-openapi.yml
  format: yaml
  label: Aeropay Create & Manage Transactions API
  slug: aeropay-create-manage-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aeropay/openapi/aeropay-create-manage-transactions-api-openapi.yml
- filename: aeropay-merchant-management-api-openapi.yml
  format: yaml
  label: Aeropay Merchant Management API
  slug: aeropay-merchant-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aeropay/openapi/aeropay-merchant-management-api-openapi.yml
- filename: aeropay-reports-api-openapi.yml
  format: yaml
  label: Aeropay Reports API
  slug: aeropay-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aeropay/openapi/aeropay-reports-api-openapi.yml
- filename: aeropay-user-management-api-openapi.yml
  format: yaml
  label: Aeropay User Management API
  slug: aeropay-user-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aeropay/openapi/aeropay-user-management-api-openapi.yml
- filename: aeropay-webhooks-api-openapi.yml
  format: yaml
  label: Aeropay Webhooks API
  slug: aeropay-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aeropay/openapi/aeropay-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: infrastructure and security, availability, confidentiality controls
    text: Aeropay's infrastructure is SOC 2 Type II certified.
    type: SOC 2 Type II certification
  - framework: other
    issuer: null
    period: annual independent audits
    report_access: unstated
    scope: ACH operations in compliance with NACHA standards
    text: We handle ACH operations in strict compliance with NACHA standards, and undergo annual independent audits of our ACH processes.
    type: NACHA-aligned ACH operations audit
  trust_center:
    url: https://www.aeropay.com/trust-center
frameworks:
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Aeropay
provenance_date: '2026-11-09'
provider_name: Aeropay
provider_slug: aeropay
slug: aeropay-compliance
source_date: '2026-11-09'
source_filename: aeropay-compliance.yml
source_heading: Compliance
source_page: https://www.aeropay.com/trust-center
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Aeropay\naid: aeropay\nurl: https://www.aeropay.com/trust-center\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.aeropay.com/trust-center\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II certification\n  scope: infrastructure and security, availability, confidentiality controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Aeropay's infrastructure is SOC 2 Type II certified.\n- framework: other\n  type: NACHA-aligned ACH operations audit\n  scope: ACH operations in compliance with NACHA standards\n  period: annual independent audits\n  issuer: null\n  report_access:\
  \ unstated\n  text: We handle ACH operations in strict compliance with NACHA standards, and undergo annual independent audits\n    of our ACH processes.\n"
source_yaml_url: https://artifacts.apis.io/aeropay/compliance/aeropay-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Aeropay's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- Pay by Bank
- ACH
- Open Banking
- Fintech
- Bank linking
- Financial Services
- Real-Time Payments
- Webhook
- Payouts
- MCP
- Risk & fraud
---
