---
api_specs:
- filename: echorelay-openapi-generated.yml
  format: yaml
  label: EchoRelay API
  slug: echorelay-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/echorelay/openapi/_ae-authored/echorelay-openapi-generated.yml
- filename: echorelay-keys-api-openapi.yml
  format: yaml
  label: EchoRelay Keys API
  slug: echorelay-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/echorelay/openapi/echorelay-keys-api-openapi.yml
- filename: echorelay-projects-api-openapi.yml
  format: yaml
  label: EchoRelay Projects API
  slug: echorelay-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/echorelay/openapi/echorelay-projects-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Common Criteria, Availability, Processing Integrity, Confidentiality and Privacy
    text: No auditor has checked them yet, and we don’t claim certification.
    type: Self-mapped alignment to Trust Services Criteria; no auditor check; not certified
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: unstated
    scope: Cloud Controls Matrix
    text: A self-assessment against the Cloud Controls Matrix, to be published in the public STAR registry.
    type: Self-assessment against Cloud Controls Matrix, in progress
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: EU-primary data residency, Data Processing Agreement, data-subject-request process
    text: EU-primary data residency, a signed Data Processing Agreement , and a documented data-subject-request process.
    type: Stated compliance in place
  trust_center:
    url: https://echorelay.dev/trust
frameworks:
- CSA-STAR
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: EchoRelay
provenance_date: '2026-11-09'
provider_name: EchoRelay
provider_slug: echorelay
slug: echorelay-compliance
source_date: '2026-11-09'
source_filename: echorelay-compliance.yml
source_heading: Compliance
source_page: https://echorelay.dev/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: EchoRelay\naid: echorelay\nurl: https://echorelay.dev/trust\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://echorelay.dev/trust\nattestations:\n- framework: SOC2\n  type: Self-mapped alignment to Trust Services Criteria; no auditor check; not certified\n  scope: Common Criteria, Availability, Processing Integrity, Confidentiality and Privacy\n  period: null\n  issuer: null\n  report_access: unstated\n  text: No auditor has checked them yet, and we don’t claim certification.\n- framework: CSA-STAR\n  type: Self-assessment against Cloud Controls Matrix, in progress\n  scope: Cloud Controls Matrix\n  period:\
  \ null\n  issuer: null\n  report_access: unstated\n  text: A self-assessment against the Cloud Controls Matrix, to be published in the public STAR registry.\n- framework: GDPR\n  type: Stated compliance in place\n  scope: EU-primary data residency, Data Processing Agreement, data-subject-request process\n  period: null\n  issuer: null\n  report_access: unstated\n  text: EU-primary data residency, a signed Data Processing Agreement , and a documented data-subject-request process.\n"
source_yaml_url: https://artifacts.apis.io/echorelay/compliance/echorelay-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from EchoRelay's own page on 2026-11-09.
synthetic: false
tags:
- Integration
- Platform
- Automation
- No-Code
- Company
---
