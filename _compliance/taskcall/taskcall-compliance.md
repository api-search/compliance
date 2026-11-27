---
api_specs:
- filename: taskcall-components-api-openapi.yml
  format: yaml
  label: TaskCall Components API
  slug: taskcall-components-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/taskcall/openapi/taskcall-components-api-openapi.yml
- filename: taskcall-incidents-api-openapi.yml
  format: yaml
  label: TaskCall Incidents API
  slug: taskcall-incidents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/taskcall/openapi/taskcall-incidents-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: third-party auditor
    period: null
    report_access: on_request
    scope: Security, Availability, Processing Integrity, Confidentiality, and Privacy Trust Services Criteria
    text: TaskCall has achieved SOC 2 Type II certification, independently verified by a third-party auditor.
    type: SOC 2 Type II certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Handling of Protected Health Information (PHI)
    text: TaskCall is designed and operated in compliance with the Health Insurance Portability and Accountability Act (HIPAA).
    type: HIPAA compliance program
  trust_center:
    url: https://taskcallapp.com/security
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: TaskCall
provenance_date: '2026-11-10'
provider_name: TaskCall
provider_slug: taskcall
slug: taskcall-compliance
source_date: '2026-11-10'
source_filename: taskcall-compliance.yml
source_heading: Compliance
source_page: https://taskcallapp.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: TaskCall\naid: taskcall\nurl: https://taskcallapp.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/taskcall-trust-center.yml\ntrust_center:\n  url: https://taskcallapp.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II certification\n  scope: Security, Availability, Processing Integrity, Confidentiality, and Privacy Trust Services Criteria\n  period: null\n  issuer: third-party auditor\n  report_access: on_request\n  text: TaskCall has achieved SOC 2 Type II certification, independently verified by a third-party auditor.\n- framework: HIPAA\n  type: HIPAA compliance program\n\
  \  scope: Handling of Protected Health Information (PHI)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: TaskCall is designed and operated in compliance with the Health Insurance Portability and Accountability\n    Act (HIPAA).\n"
source_yaml_url: https://artifacts.apis.io/taskcall/compliance/taskcall-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from TaskCall's own page on 2026-11-10.
synthetic: false
tags:
- Incident Management
- On-Call
- Alerting
- DevOps
- SRE
- ITSM
---
