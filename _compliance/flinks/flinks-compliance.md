---
api_specs:
- filename: flinks-connect-api-openapi.yml
  format: yaml
  label: Flinks Connect API
  slug: flinks-connect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flinks/openapi/flinks-connect-api-openapi.yml
- filename: flinks-enrich-api-openapi.yml
  format: yaml
  label: Flinks Enrich API
  slug: flinks-enrich-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flinks/openapi/flinks-enrich-api-openapi.yml
- filename: flinks-authorization-api-openapi.yml
  format: yaml
  label: Flinks Authorization API
  slug: flinks-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flinks/openapi/flinks-authorization-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Request our SOC2 report
    type: SOC 2 Trust Services Principles
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: PCI-DSS & SOC2 compliant providers hosting (Microsoft Azure, Google Cloud Platform)
    text: PCI-DSS & SOC2 compliant providers hosting (Microsoft Azure, Google Cloud Platform)
    type: null
  trust_center:
    url: https://www.flinks.com/security
frameworks:
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Flinks
provenance_date: '2026-11-09'
provider_name: Flinks
provider_slug: flinks
slug: flinks-compliance
source_date: '2026-11-09'
source_filename: flinks-compliance.yml
source_heading: Compliance
source_page: https://www.flinks.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Flinks\naid: flinks\nurl: https://www.flinks.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/flinks-trust-center.yml\ntrust_center:\n  url: https://www.flinks.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Trust Services Principles\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Request our SOC2 report\n- framework: PCI-DSS\n  type: null\n  scope: PCI-DSS & SOC2 compliant providers hosting (Microsoft Azure, Google Cloud Platform)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI-DSS & SOC2 compliant providers hosting\
  \ (Microsoft Azure, Google Cloud Platform)\n"
source_yaml_url: https://artifacts.apis.io/flinks/compliance/flinks-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Flinks's own page on 2026-11-09.
synthetic: false
tags:
- Financial Data
- Open Banking
- Bank Aggregation
- Fintech
- Canada
---
