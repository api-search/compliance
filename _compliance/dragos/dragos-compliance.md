---
api_specs:
- filename: dragos-indicators-api-openapi.yml
  format: yaml
  label: Dragos Indicators API
  slug: dragos-indicators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dragos/openapi/dragos-indicators-api-openapi.yml
- filename: dragos-products-api-openapi.yml
  format: yaml
  label: Dragos Products API
  slug: dragos-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dragos/openapi/dragos-products-api-openapi.yml
- filename: dragos-tags-api-openapi.yml
  format: yaml
  label: Dragos Tags API
  slug: dragos-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dragos/openapi/dragos-tags-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: Dragos security program
    text: Dragos will provide an independent SOC 2 Type II annually upon execution of NDA.
    type: SOC 2 Type 2 Report
  - framework: NIST-CSF
    issuer: null
    period: null
    report_access: unstated
    scope: Dragos products
    text: Dragos’s products align with NIST CSF, ISO 27001 and SOC 2 Type 2 standards.
    type: aligned with standard
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Dragos products
    text: Dragos’s products align with NIST CSF, ISO 27001 and SOC 2 Type 2 standards.
    type: aligned with standard
  trust_center:
    url: https://www.dragos.com/security-program/
frameworks:
- ISO27001
- NIST-CSF
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Dragos
provenance_date: '2026-11-09'
provider_name: Dragos
provider_slug: dragos
slug: dragos-compliance
source_date: '2026-11-09'
source_filename: dragos-compliance.yml
source_heading: Compliance
source_page: https://www.dragos.com/security-program/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Dragos\naid: dragos\nurl: https://www.dragos.com/security-program/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.dragos.com/security-program/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 Report\n  scope: Dragos security program\n  period: null\n  issuer: null\n  report_access: nda\n  text: Dragos will provide an independent SOC 2 Type II annually upon execution of NDA.\n- framework: NIST-CSF\n  type: aligned with standard\n  scope: Dragos products\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Dragos’s products align with NIST CSF, ISO 27001 and SOC 2 Type 2 standards.\n\
  - framework: ISO27001\n  type: aligned with standard\n  scope: Dragos products\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Dragos’s products align with NIST CSF, ISO 27001 and SOC 2 Type 2 standards.\n"
source_yaml_url: https://artifacts.apis.io/dragos/compliance/dragos-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Dragos's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- OT Security
- ICS
- Threat Intelligence
- Industrial Control Systems
- Indicators of Compromise
- STIX
- Vulnerability Management
- Security
---
