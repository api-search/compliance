---
api_specs:
- filename: marginedge-categories-api-openapi.yml
  format: yaml
  label: MarginEdge Categories API
  slug: marginedge-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marginedge/openapi/marginedge-categories-api-openapi.yml
- filename: marginedge-orders-api-openapi.yml
  format: yaml
  label: MarginEdge Orders API
  slug: marginedge-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marginedge/openapi/marginedge-orders-api-openapi.yml
- filename: marginedge-products-api-openapi.yml
  format: yaml
  label: MarginEdge Products API
  slug: marginedge-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marginedge/openapi/marginedge-products-api-openapi.yml
- filename: marginedge-restaurant-units-api-openapi.yml
  format: yaml
  label: MarginEdge Restaurant Units API
  slug: marginedge-restaurant-units-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marginedge/openapi/marginedge-restaurant-units-api-openapi.yml
- filename: marginedge-vendors-api-openapi.yml
  format: yaml
  label: MarginEdge Vendors API
  slug: marginedge-vendors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marginedge/openapi/marginedge-vendors-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Our cybersecurity program aligns with SOC2 security standards.
    type: null
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: MarginEdge maintains PCI DSS compliance.
    type: null
  trust_center:
    url: https://www.marginedge.com/security
frameworks:
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: MarginEdge
provenance_date: '2026-11-10'
provider_name: MarginEdge
provider_slug: marginedge
slug: marginedge-compliance
source_date: '2026-11-10'
source_filename: marginedge-compliance.yml
source_heading: Compliance
source_page: https://www.marginedge.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: MarginEdge\naid: marginedge\nurl: https://www.marginedge.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/marginedge-trust-center.yml\ntrust_center:\n  url: https://www.marginedge.com/security\nattestations:\n- framework: SOC2\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Our cybersecurity program aligns with SOC2 security standards.\n- framework: PCI-DSS\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: MarginEdge maintains PCI DSS compliance.\n"
source_yaml_url: https://artifacts.apis.io/marginedge/compliance/marginedge-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from MarginEdge's own page on 2026-11-10.
synthetic: false
tags:
- Restaurant
- Back Office
- Invoices
- Inventory
- Accounting
- Reporting
---
