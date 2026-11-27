---
api_specs:
- filename: wompi-merchants-api-openapi.yml
  format: yaml
  label: Wompi Merchants API
  slug: wompi-merchants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wompi/openapi/wompi-merchants-api-openapi.yml
- filename: wompi-payment-links-api-openapi.yml
  format: yaml
  label: Wompi Payment Links API
  slug: wompi-payment-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wompi/openapi/wompi-payment-links-api-openapi.yml
- filename: wompi-payment-sources-api-openapi.yml
  format: yaml
  label: Wompi Payment Sources API
  slug: wompi-payment-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wompi/openapi/wompi-payment-sources-api-openapi.yml
- filename: wompi-pse-api-openapi.yml
  format: yaml
  label: Wompi PSE API
  slug: wompi-pse-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wompi/openapi/wompi-pse-api-openapi.yml
- filename: wompi-tokenization-api-openapi.yml
  format: yaml
  label: Wompi Tokenization API
  slug: wompi-tokenization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wompi/openapi/wompi-tokenization-api-openapi.yml
- filename: wompi-transactions-api-openapi.yml
  format: yaml
  label: Wompi Transactions API
  slug: wompi-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wompi/openapi/wompi-transactions-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: payment gateway (pasarela)
    text: Nuestra pasarela cuenta con certificación PCI DSS para la seguridad de las transacciones en línea con tarjetas de crédito y la protección de los datos de los tarjetahabientes.
    type: certification
  trust_center:
    url: https://wompi.com/es/co/
frameworks:
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Wompi
provenance_date: '2026-11-10'
provider_name: Wompi
provider_slug: wompi
slug: wompi-compliance
source_date: '2026-11-10'
source_filename: wompi-compliance.yml
source_heading: Compliance
source_page: https://wompi.com/es/co/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Wompi\naid: wompi\nurl: https://wompi.com/es/co/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/wompi-trust-center.yml\ntrust_center:\n  url: https://wompi.com/es/co/\nattestations:\n- framework: PCI-DSS\n  type: certification\n  scope: payment gateway (pasarela)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Nuestra pasarela cuenta con certificación PCI DSS para la seguridad de las transacciones en línea con tarjetas\n    de crédito y la protección de los datos de los tarjetahabientes.\n"
source_yaml_url: https://artifacts.apis.io/wompi/compliance/wompi-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Wompi's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- Fintech
- Colombia
- Latin America
- Payment Gateway
- PSE
- Nequi
---
