---
api_specs:
- filename: coviu-auth-api-openapi.yml
  format: yaml
  label: Coviu Auth API
  slug: coviu-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coviu/openapi/coviu-auth-api-openapi.yml
- filename: coviu-collections-api-openapi.yml
  format: yaml
  label: Coviu Collections API
  slug: coviu-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coviu/openapi/coviu-collections-api-openapi.yml
- filename: coviu-participants-api-openapi.yml
  format: yaml
  label: Coviu Participants API
  slug: coviu-participants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coviu/openapi/coviu-participants-api-openapi.yml
- filename: coviu-sessions-api-openapi.yml
  format: yaml
  label: Coviu Sessions API
  slug: coviu-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coviu/openapi/coviu-sessions-api-openapi.yml
- filename: coviu-waiting-area-api-openapi.yml
  format: yaml
  label: Coviu Waiting Area API
  slug: coviu-waiting-area-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coviu/openapi/coviu-waiting-area-api-openapi.yml
- filename: coviu-webhook-requests-api-openapi.yml
  format: yaml
  label: Coviu Webhook Requests API
  slug: coviu-webhook-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coviu/openapi/coviu-webhook-requests-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: electronic protected health information (ePHI) safeguards
    text: HIPAA-Aligned by Design Our safeguards are structured to protect electronic protected health information (ePHI) across infrastructure, access controls, and operational workflows.
    type: HIPAA-aligned safeguards
  trust_center:
    url: https://www.coviu.com/en-us/compliance-and-security
frameworks:
- HIPAA
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Coviu
provenance_date: '2026-11-09'
provider_name: Coviu
provider_slug: coviu
slug: coviu-compliance
source_date: '2026-11-09'
source_filename: coviu-compliance.yml
source_heading: Compliance
source_page: https://www.coviu.com/en-us/compliance-and-security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Coviu\naid: coviu\nurl: https://www.coviu.com/en-us/compliance-and-security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.coviu.com/en-us/compliance-and-security\nattestations:\n- framework: HIPAA\n  type: HIPAA-aligned safeguards\n  scope: electronic protected health information (ePHI) safeguards\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA-Aligned by Design Our safeguards are structured to protect electronic protected health information\n    (ePHI) across infrastructure, access controls, and operational workflows.\n"
source_yaml_url: https://artifacts.apis.io/coviu/compliance/coviu-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Coviu's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Telehealth
- Australia
- Virtual Care
- Video
- WebRTC
- Appointments
- Remote Monitoring
- REST
---
