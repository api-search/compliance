---
api_specs:
- filename: b-well-users-api-openapi.yml
  format: yaml
  label: b.well Users API
  slug: b-well-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/b-well/openapi/b-well-users-api-openapi.yml
- filename: b-well-webhook-api-openapi.yml
  format: yaml
  label: b.well Webhook API
  slug: b-well-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/b-well/openapi/b-well-webhook-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: HITRUST
    issuer: external auditors
    period: annual security reviews
    report_access: unstated
    scope: systems
    text: Our systems are subject to annual security reviews and have achieved HITRUST and US NIST cybersecurity framework (CSF) certification, which require independent verification of our security-related policies, procedures, and implemented controls by external auditors on at least a biennial (2 year) basis.
    type: certification
  - framework: NIST-CSF
    issuer: external auditors
    period: annual security reviews
    report_access: unstated
    scope: systems
    text: Our systems are subject to annual security reviews and have achieved HITRUST and US NIST cybersecurity framework (CSF) certification, which require independent verification of our security-related policies, procedures, and implemented controls by external auditors on at least a biennial (2 year) basis.
    type: certification
  trust_center:
    url: https://www.icanbwell.com/health-data-security-for-consumers/
frameworks:
- HITRUST
- NIST-CSF
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: b.well
provenance_date: '2026-11-09'
provider_name: b.well
provider_slug: b-well
slug: b-well-compliance
source_date: '2026-11-09'
source_filename: b-well-compliance.yml
source_heading: Compliance
source_page: https://www.icanbwell.com/health-data-security-for-consumers/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: b.well\naid: b-well\nurl: https://www.icanbwell.com/health-data-security-for-consumers/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/b-well-trust-center.yml\ntrust_center:\n  url: https://www.icanbwell.com/health-data-security-for-consumers/\nattestations:\n- framework: HITRUST\n  type: certification\n  scope: systems\n  period: annual security reviews\n  issuer: external auditors\n  report_access: unstated\n  text: Our systems are subject to annual security reviews and have achieved HITRUST and US NIST cybersecurity framework\n    (CSF) certification, which require independent verification of our\
  \ security-related policies, procedures, and\n    implemented controls by external auditors on at least a biennial (2 year) basis.\n- framework: NIST-CSF\n  type: certification\n  scope: systems\n  period: annual security reviews\n  issuer: external auditors\n  report_access: unstated\n  text: Our systems are subject to annual security reviews and have achieved HITRUST and US NIST cybersecurity framework\n    (CSF) certification, which require independent verification of our security-related policies, procedures, and\n    implemented controls by external auditors on at least a biennial (2 year) basis.\n"
source_yaml_url: https://artifacts.apis.io/b-well/compliance/b-well-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from b.well's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Digital Health
- FHIR
- Health Data
- Interoperability
- Patient Access
- Health Records
- MCP
---
