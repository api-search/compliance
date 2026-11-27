---
api_specs:
- filename: API_catalog.html
  format: yaml
  label: Windchill REST Services
  slug: windchill-rest-services
  spec_type: OpenAPI
  url: https://support.ptc.com/help/windchill_rest_services/r1.6/en/windchill_rest_services/API_catalog.html
- filename: index.html
  format: yaml
  label: Arena PLM REST API
  slug: arena-plm-rest-api
  spec_type: OpenAPI
  url: https://api.arenasolutions.com/v1/swagger-ui/index.html
- filename: ptc-openapi-generated.yml
  format: yaml
  label: PTC API
  slug: ptc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ptc/openapi/_ae-authored/ptc-openapi-generated.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II Attestation Reports
    type: SOC 2 Type II Attestation Reports
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: PTC Cloud
    text: PTC Cloud FedRAMP
    type: FedRAMP
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PTC Inc. ISO 27001
    type: ISO 27001
  - framework: ISO9001
    issuer: null
    period: null
    report_access: unstated
    scope: Codebeamer and Tech Support
    text: Codebeamer ISO 9001
    type: ISO 9001
  - framework: TISAX
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PTC Inc. TISAX
    type: TISAX
  trust_center:
    url: https://www.ptc.com/en/about/trust-center/
frameworks:
- FedRAMP
- ISO27001
- ISO9001
- SOC2
- TISAX
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: PTC
provenance_date: '2026-11-10'
provider_name: PTC
provider_slug: ptc
slug: ptc-compliance
source_date: '2026-11-10'
source_filename: ptc-compliance.yml
source_heading: Compliance
source_page: https://www.ptc.com/en/about/trust-center/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: PTC\naid: ptc\nurl: https://www.ptc.com/en/about/trust-center/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/ptc-trust-center.yml\ntrust_center:\n  url: https://www.ptc.com/en/about/trust-center/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II Attestation Reports\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II Attestation Reports\n- framework: FedRAMP\n  type: FedRAMP\n  scope: PTC Cloud\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PTC Cloud FedRAMP\n- framework: ISO27001\n  type: ISO 27001\n  scope: null\n  period:\
  \ null\n  issuer: null\n  report_access: unstated\n  text: PTC Inc. ISO 27001\n- framework: ISO9001\n  type: ISO 9001\n  scope: Codebeamer and Tech Support\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Codebeamer ISO 9001\n- framework: TISAX\n  type: TISAX\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PTC Inc. TISAX\n"
source_yaml_url: https://artifacts.apis.io/ptc/compliance/ptc-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from PTC's own page on 2026-11-10.
synthetic: false
tags:
- Industrial IoT
- PLM
- Augmented Reality
- Field Service Management
- Manufacturing
- CAD
- Digital Transformation
- Industrial
---
