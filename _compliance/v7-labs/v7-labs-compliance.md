---
api_specs:
- filename: v7-labs-annotations-api-openapi.yml
  format: yaml
  label: V7 Annotations API
  slug: v7-labs-annotations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/v7-labs/openapi/v7-labs-annotations-api-openapi.yml
- filename: v7-labs-classes-api-openapi.yml
  format: yaml
  label: V7 Classes API
  slug: v7-labs-classes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/v7-labs/openapi/v7-labs-classes-api-openapi.yml
- filename: v7-labs-datasets-api-openapi.yml
  format: yaml
  label: V7 Datasets API
  slug: v7-labs-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/v7-labs/openapi/v7-labs-datasets-api-openapi.yml
- filename: v7-labs-exports-api-openapi.yml
  format: yaml
  label: V7 Exports API
  slug: v7-labs-exports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/v7-labs/openapi/v7-labs-exports-api-openapi.yml
- filename: v7-labs-items-api-openapi.yml
  format: yaml
  label: V7 Items API
  slug: v7-labs-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/v7-labs/openapi/v7-labs-items-api-openapi.yml
- filename: v7-labs-workflows-api-openapi.yml
  format: yaml
  label: V7 Workflows API
  slug: v7-labs-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/v7-labs/openapi/v7-labs-workflows-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: SOC 2 Type 2 Report 2026 Request
    type: SOC 2 Type 2
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: ISO 27001:2022 Certificate 2026 Request
    type: ISO 27001 certificate
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: ISO 27001 Audit Report 2026 Request
    type: ISO 27001 audit report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR HIPAA
    type: GDPR
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR HIPAA
    type: HIPAA
  trust_center:
    url: https://trust.v7labs.com/
frameworks:
- GDPR
- HIPAA
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: V7
provenance_date: '2026-11-10'
provider_name: V7
provider_slug: v7-labs
slug: v7-labs-compliance
source_date: '2026-11-10'
source_filename: v7-labs-compliance.yml
source_heading: Compliance
source_page: https://trust.v7labs.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: V7\naid: v7-labs\nurl: https://trust.v7labs.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/v7-labs-trust-center.yml\ntrust_center:\n  url: https://trust.v7labs.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Type 2 Report 2026 Request\n- framework: ISO27001\n  type: ISO 27001 certificate\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: ISO 27001:2022 Certificate 2026 Request\n- framework: ISO27001\n  type: ISO 27001 audit report\n  scope: null\n  period:\
  \ null\n  issuer: null\n  report_access: on_request\n  text: ISO 27001 Audit Report 2026 Request\n- framework: GDPR\n  type: GDPR\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR HIPAA\n- framework: HIPAA\n  type: HIPAA\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR HIPAA\n"
source_yaml_url: https://artifacts.apis.io/v7-labs/compliance/v7-labs-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from V7's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Training Data
- Data Labeling
- Annotation
- Document AI
- Computer Vision
---
