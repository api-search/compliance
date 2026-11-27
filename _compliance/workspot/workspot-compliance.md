---
api_specs:
- filename: workspot-apis-api-openapi.yml
  format: yaml
  label: Workspot APIs API
  slug: workspot-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workspot/openapi/workspot-apis-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: external leading audit firm
    period: annually
    report_access: on_request
    scope: Information security and privacy policies and controls
    text: Workspot’s Information security and privacy policies and controls are assessed annually by an external leading audit firm to ensure Workspot meets the requirements of Service Organization Control (SOC) 2 Type 2 and General Data Protection Regulation (GDPR).
    type: SOC 2 Type 2 assessment
  - framework: GDPR
    issuer: external leading audit firm
    period: null
    report_access: on_request
    scope: Information security and privacy policies and controls; Data Processing Addendum
    text: Workspot provides its customers with a GDPR compliant Data Processing Addendum with the recent Standard Contractual Clauses (SCC) 2021.
    type: GDPR compliance assessment and DPA
  - framework: other
    issuer: external security lab
    period: annually
    report_access: on_request
    scope: Latest assessment and penetration testing reports
    text: Workspot provides its customers access to the latest assessment and penetration testing reports annually upon request.
    type: penetration testing reports
  trust_center:
    url: https://www.workspot.com/resources/trust-center/
frameworks:
- GDPR
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Workspot
provenance_date: '2026-11-10'
provider_name: Workspot
provider_slug: workspot
slug: workspot-compliance
source_date: '2026-11-10'
source_filename: workspot-compliance.yml
source_heading: Compliance
source_page: https://www.workspot.com/resources/trust-center/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Workspot\naid: workspot\nurl: https://www.workspot.com/resources/trust-center/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.workspot.com/resources/trust-center/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 assessment\n  scope: Information security and privacy policies and controls\n  period: annually\n  issuer: external leading audit firm\n  report_access: on_request\n  text: Workspot’s Information security and privacy policies and controls are assessed annually by an external leading\n    audit firm to ensure Workspot meets the requirements of Service Organization Control (SOC) 2 Type\
  \ 2 and General\n    Data Protection Regulation (GDPR).\n- framework: GDPR\n  type: GDPR compliance assessment and DPA\n  scope: Information security and privacy policies and controls; Data Processing Addendum\n  period: null\n  issuer: external leading audit firm\n  report_access: on_request\n  text: Workspot provides its customers with a GDPR compliant Data Processing Addendum with the recent Standard\n    Contractual Clauses (SCC) 2021.\n- framework: other\n  type: penetration testing reports\n  scope: Latest assessment and penetration testing reports\n  period: annually\n  issuer: external security lab\n  report_access: on_request\n  text: Workspot provides its customers access to the latest assessment and penetration testing reports annually\n    upon request.\n"
source_yaml_url: https://artifacts.apis.io/workspot/compliance/workspot-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Workspot's own page on 2026-11-10.
synthetic: false
tags:
- Virtual Desktop Infrastructure
- Desktop as a Service
- Cloud PC
- End User Computing
- Cloud Infrastructure
- Enterprise IT
- Workspace Management
- Software-as-a-Service
---
