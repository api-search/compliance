---
api_specs:
- filename: swoogo-authentication-api-openapi.yml
  format: yaml
  label: Swoogo Authentication API
  slug: swoogo-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/swoogo/openapi/swoogo-authentication-api-openapi.yml
- filename: swoogo-contacts-api-openapi.yml
  format: yaml
  label: Swoogo Contacts API
  slug: swoogo-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/swoogo/openapi/swoogo-contacts-api-openapi.yml
- filename: swoogo-events-api-openapi.yml
  format: yaml
  label: Swoogo Events API
  slug: swoogo-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/swoogo/openapi/swoogo-events-api-openapi.yml
- filename: swoogo-registrants-api-openapi.yml
  format: yaml
  label: Swoogo Registrants API
  slug: swoogo-registrants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/swoogo/openapi/swoogo-registrants-api-openapi.yml
- filename: swoogo-sessions-api-openapi.yml
  format: yaml
  label: Swoogo Sessions API
  slug: swoogo-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/swoogo/openapi/swoogo-sessions-api-openapi.yml
- filename: swoogo-speakers-api-openapi.yml
  format: yaml
  label: Swoogo Speakers API
  slug: swoogo-speakers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/swoogo/openapi/swoogo-speakers-api-openapi.yml
claim_count: 8
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Certified
    type: certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001 Certified
    type: certification
  - framework: ISO27701
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27701 Certified
    type: certification
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PCI-DSS Level 1 Certified
    type: certification
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: DPF Certified
    type: certification (DPF)
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: TX-RAMP Certified
    type: certification (TX-RAMP)
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR Compliant
    type: compliance claim
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Level AA 508 Compliant
    type: compliance claim (Section 508 accessibility)
  trust_center:
    url: https://swoogo.events/security-compliance/
frameworks:
- GDPR
- ISO27001
- ISO27701
- PCI-DSS
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Swoogo
provenance_date: '2026-11-10'
provider_name: Swoogo
provider_slug: swoogo
slug: swoogo-compliance
source_date: '2026-11-10'
source_filename: swoogo-compliance.yml
source_heading: Compliance
source_page: https://swoogo.events/security-compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Swoogo\naid: swoogo\nurl: https://swoogo.events/security-compliance/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/swoogo-trust-center.yml\ntrust_center:\n  url: https://swoogo.events/security-compliance/\nattestations:\n- framework: SOC2\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Certified\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001 Certified\n- framework: ISO27701\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n\
  \  report_access: unstated\n  text: ISO 27701 Certified\n- framework: PCI-DSS\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI-DSS Level 1 Certified\n- framework: other\n  type: certification (DPF)\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: DPF Certified\n- framework: other\n  type: certification (TX-RAMP)\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: TX-RAMP Certified\n- framework: GDPR\n  type: compliance claim\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR Compliant\n- framework: other\n  type: compliance claim (Section 508 accessibility)\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Level AA 508 Compliant\n"
source_yaml_url: https://artifacts.apis.io/swoogo/compliance/swoogo-compliance.yml
stated_fields:
- attestations
summary_line: 8 quoted statements, read from Swoogo's own page on 2026-11-10.
synthetic: false
tags:
- Event Management
- Event Registration
- Event
- Sessions
- Speakers
- Attendees
- Software-as-a-Service
---
