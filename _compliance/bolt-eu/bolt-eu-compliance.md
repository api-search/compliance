---
api_specs:
- filename: bolt-eu-genericclient-api-openapi.yml
  format: yaml
  label: Bolt GenericClient API
  slug: bolt-eu-genericclient-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bolt-eu/openapi/bolt-eu-genericclient-api-openapi.yml
- filename: bolt-eu-pim-api-openapi.yml
  format: yaml
  label: Bolt Pim API
  slug: bolt-eu-pim-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bolt-eu/openapi/bolt-eu-pim-api-openapi.yml
- filename: bolt-eu-validateloyaltycard-api-openapi.yml
  format: yaml
  label: Bolt ValidateLoyaltyCard API
  slug: bolt-eu-validateloyaltycard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bolt-eu/openapi/bolt-eu-validateloyaltycard-api-openapi.yml
- filename: bolt-eu-bolt-delivery-api-api-openapi.yml
  format: yaml
  label: Bolt Delivery API
  slug: bolt-eu-bolt-delivery-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bolt-eu/openapi/bolt-eu-bolt-delivery-api-api-openapi.yml
- filename: bolt-eu-bolt-food-api-api-openapi.yml
  format: yaml
  label: Bolt Food API
  slug: bolt-eu-bolt-food-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bolt-eu/openapi/bolt-eu-bolt-food-api-api-openapi.yml
- filename: bolt-eu-bolt-stores-api-api-openapi.yml
  format: yaml
  label: Bolt Stores API
  slug: bolt-eu-bolt-stores-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bolt-eu/openapi/bolt-eu-bolt-stores-api-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Bolt is certified and complies with the requirements of PCI DSS and ISO 27001.
    type: certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Bolt is certified and complies with the requirements of PCI DSS and ISO 27001.
    type: certification
  trust_center:
    url: https://bolt.eu/en/security/
frameworks:
- ISO27001
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Bolt
provenance_date: '2026-11-09'
provider_name: Bolt
provider_slug: bolt-eu
slug: bolt-eu-compliance
source_date: '2026-11-09'
source_filename: bolt-eu-compliance.yml
source_heading: Compliance
source_page: https://bolt.eu/en/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Bolt\naid: bolt-eu\nurl: https://bolt.eu/en/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/bolt-eu-trust-center.yml\ntrust_center:\n  url: https://bolt.eu/en/security/\nattestations:\n- framework: PCI-DSS\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Bolt is certified and complies with the requirements of PCI DSS and ISO 27001.\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Bolt is certified and complies with the requirements of PCI DSS and ISO 27001.\n"
source_yaml_url: https://artifacts.apis.io/bolt-eu/compliance/bolt-eu-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Bolt's own page on 2026-11-09.
synthetic: false
tags:
- Ride Booking
- Ride Hailing
- Mobility
- Transportation
- Food Delivery
- Micromobility
- Delivery
- Super App
---
