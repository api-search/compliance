---
api_specs:
- filename: evervault-core-api-openapi.yml
  format: yaml
  label: Evervault Core API
  slug: evervault-core-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evervault/openapi/evervault-core-api-openapi.yml
- filename: evervault-payments-api-openapi.yml
  format: yaml
  label: Evervault Payments API
  slug: evervault-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evervault/openapi/evervault-payments-api-openapi.yml
- filename: evervault-webhooks-api-openapi.yml
  format: yaml
  label: Evervault Webhooks API
  slug: evervault-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evervault/openapi/evervault-webhooks-api-openapi.yml
- filename: evervault-evervault-api-api-openapi.yml
  format: yaml
  label: Evervault API
  slug: evervault-evervault-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evervault/openapi/evervault-evervault-api-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: Card Collection UI components served from Evervault infrastructure
    text: retrieved directly from Evervault’s PCI-compliant infrastructure
    type: stated PCI-compliant infrastructure
  trust_center:
    url: https://docs.evervault.com/compliance/pci-compliance
frameworks:
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Evervault
provenance_date: '2026-11-09'
provider_name: Evervault
provider_slug: evervault
slug: evervault-compliance
source_date: '2026-11-09'
source_filename: evervault-compliance.yml
source_heading: Compliance
source_page: https://docs.evervault.com/compliance/pci-compliance
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Evervault\naid: evervault\nurl: https://docs.evervault.com/compliance/pci-compliance\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://docs.evervault.com/compliance/pci-compliance\nattestations:\n- framework: PCI-DSS\n  type: stated PCI-compliant infrastructure\n  scope: Card Collection UI components served from Evervault infrastructure\n  period: null\n  issuer: null\n  report_access: unstated\n  text: retrieved directly from Evervault’s PCI-compliant infrastructure\n"
source_yaml_url: https://artifacts.apis.io/evervault/compliance/evervault-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Evervault's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- Security
- Encryption
- Payments
- PCI Compliance
- Tokenization
- Cards
- Developer Tools
---
