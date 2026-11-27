---
api_specs:
- filename: ravelin-3d-secure-api-openapi.yml
  format: yaml
  label: Ravelin 3D Secure API
  slug: ravelin-3d-secure-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ravelin/openapi/ravelin-3d-secure-api-openapi.yml
- filename: ravelin-authentication-api-openapi.yml
  format: yaml
  label: Ravelin Authentication API
  slug: ravelin-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ravelin/openapi/ravelin-authentication-api-openapi.yml
- filename: ravelin-checkout-api-openapi.yml
  format: yaml
  label: Ravelin Checkout API
  slug: ravelin-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ravelin/openapi/ravelin-checkout-api-openapi.yml
- filename: ravelin-connect-api-openapi.yml
  format: yaml
  label: Ravelin Connect API
  slug: ravelin-connect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ravelin/openapi/ravelin-connect-api-openapi.yml
- filename: ravelin-customer-api-openapi.yml
  format: yaml
  label: Ravelin Customer API
  slug: ravelin-customer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ravelin/openapi/ravelin-customer-api-openapi.yml
- filename: ravelin-disputes-api-openapi.yml
  format: yaml
  label: Ravelin Disputes API
  slug: ravelin-disputes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ravelin/openapi/ravelin-disputes-api-openapi.yml
- filename: ravelin-payouts-api-openapi.yml
  format: yaml
  label: Ravelin Payouts API
  slug: ravelin-payouts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ravelin/openapi/ravelin-payouts-api-openapi.yml
- filename: ravelin-refunds-api-openapi.yml
  format: yaml
  label: Ravelin Refunds API
  slug: ravelin-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ravelin/openapi/ravelin-refunds-api-openapi.yml
- filename: ravelin-supplier-api-openapi.yml
  format: yaml
  label: Ravelin Supplier API
  slug: ravelin-supplier-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ravelin/openapi/ravelin-supplier-api-openapi.yml
- filename: ravelin-transactions-api-openapi.yml
  format: yaml
  label: Ravelin Transactions API
  slug: ravelin-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ravelin/openapi/ravelin-transactions-api-openapi.yml
- filename: ravelin-vouchers-api-openapi.yml
  format: yaml
  label: Ravelin Vouchers API
  slug: ravelin-vouchers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ravelin/openapi/ravelin-vouchers-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: 3DS Server, Access Control Server, and Directory Server functions
    text: Ravelin is certified as Payment Card Industry 3D Secure compliant.
    type: certification
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: sensitive payment card information handling
    text: Ravelin is certified as Payment Card Industry Data Security Standard compliant, which ensures that we handle sensitive payment card information securely.
    type: certification
  - framework: ISO27001
    issuer: British Assessment Bureau
    period: null
    report_access: unstated
    scope: null
    text: Ravelin has been assessed by British Assessment Bureau and deemed to comply with the requirements of ISO 27001:2022.
    type: assessment
  trust_center:
    url: https://www.ravelin.com/
frameworks:
- ISO27001
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Ravelin
provenance_date: '2026-11-10'
provider_name: Ravelin
provider_slug: ravelin
slug: ravelin-compliance
source_date: '2026-11-10'
source_filename: ravelin-compliance.yml
source_heading: Compliance
source_page: https://www.ravelin.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Ravelin\naid: ravelin\nurl: https://www.ravelin.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.ravelin.com/\nattestations:\n- framework: PCI-DSS\n  type: certification\n  scope: 3DS Server, Access Control Server, and Directory Server functions\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Ravelin is certified as Payment Card Industry 3D Secure compliant.\n- framework: PCI-DSS\n  type: certification\n  scope: sensitive payment card information handling\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Ravelin is certified as Payment Card Industry Data\
  \ Security Standard compliant, which ensures that we handle\n    sensitive payment card information securely.\n- framework: ISO27001\n  type: assessment\n  scope: null\n  period: null\n  issuer: British Assessment Bureau\n  report_access: unstated\n  text: Ravelin has been assessed by British Assessment Bureau and deemed to comply with the requirements of ISO\n    27001:2022.\n"
source_yaml_url: https://artifacts.apis.io/ravelin/compliance/ravelin-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Ravelin's own page on 2026-11-10.
synthetic: false
tags:
- Fraud Prevention
- Chargeback Prevention
- Account Takeover
- 3D Secure
- Risk Scoring
- Payments
- Machine Learning
---
