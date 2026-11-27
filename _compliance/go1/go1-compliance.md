---
api_specs:
- filename: go1-enrollments-api-openapi.yml
  format: yaml
  label: Go1 Enrollments API
  slug: go1-enrollments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/go1/openapi/go1-enrollments-api-openapi.yml
- filename: go1-learning-objects-api-openapi.yml
  format: yaml
  label: Go1 Learning objects API
  slug: go1-learning-objects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/go1/openapi/go1-learning-objects-api-openapi.yml
- filename: go1-portals-api-openapi.yml
  format: yaml
  label: Go1 Portals API
  slug: go1-portals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/go1/openapi/go1-portals-api-openapi.yml
- filename: go1-webhooks-api-openapi.yml
  format: yaml
  label: Go1 Webhooks API
  slug: go1-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/go1/openapi/go1-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: Go1
    text: Go1 ISO/IEC 27001:2022 Certificate - 2026
    type: certification
  - framework: SOC2
    issuer: null
    period: '2026'
    report_access: on_request
    scope: Go1
    text: Go1 SOC 2 Type II Report 2026
    type: Type II report
  trust_center:
    url: https://trust.go1.com/
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Go1
provenance_date: '2026-11-09'
provider_name: Go1
provider_slug: go1
slug: go1-compliance
source_date: '2026-11-09'
source_filename: go1-compliance.yml
source_heading: Compliance
source_page: https://trust.go1.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Go1\naid: go1\nurl: https://trust.go1.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/go1-trust-center.yml\ntrust_center:\n  url: https://trust.go1.com/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: Go1\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Go1 ISO/IEC 27001:2022 Certificate - 2026\n- framework: SOC2\n  type: Type II report\n  scope: Go1\n  period: '2026'\n  issuer: null\n  report_access: on_request\n  text: Go1 SOC 2 Type II Report 2026\n"
source_yaml_url: https://artifacts.apis.io/go1/compliance/go1-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Go1's own page on 2026-11-09.
synthetic: false
tags:
- Company
- EdTech
- Learning
- E-Learning
- Corporate Training
- Content
- LMS
- Education
- Webhook
---
