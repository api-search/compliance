---
api_specs:
- filename: anysphere-agents-api-openapi.yml
  format: yaml
  label: Anysphere Agents API
  slug: anysphere-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anysphere/openapi/anysphere-agents-api-openapi.yml
- filename: anysphere-me-api-openapi.yml
  format: yaml
  label: Anysphere Me API
  slug: anysphere-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anysphere/openapi/anysphere-me-api-openapi.yml
- filename: anysphere-models-api-openapi.yml
  format: yaml
  label: Anysphere Models API
  slug: anysphere-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anysphere/openapi/anysphere-models-api-openapi.yml
- filename: anysphere-repositories-api-openapi.yml
  format: yaml
  label: Anysphere Repositories API
  slug: anysphere-repositories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anysphere/openapi/anysphere-repositories-api-openapi.yml
- filename: anysphere-sub-tokens-api-openapi.yml
  format: yaml
  label: Anysphere Sub Tokens API
  slug: anysphere-sub-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anysphere/openapi/anysphere-sub-tokens-api-openapi.yml
claim_count: 7
description: ''
doc:
  attestations:
  - framework: other
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Cursor holds AIUC-1, ISO/IEC 27001:2022, and ISO/IEC 42001:2023 certifications, along with a SOC 2 Type II attestation.
    type: certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Cursor holds AIUC-1, ISO/IEC 27001:2022, and ISO/IEC 42001:2023 certifications, along with a SOC 2 Type II attestation.
    type: certification
  - framework: ISO42001
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Cursor holds AIUC-1, ISO/IEC 27001:2022, and ISO/IEC 42001:2023 certifications, along with a SOC 2 Type II attestation.
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Cursor holds AIUC-1, ISO/IEC 27001:2022, and ISO/IEC 42001:2023 certifications, along with a SOC 2 Type II attestation.
    type: attestation
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.cursor.com/
    text: SOC 2 Type 2 - Attestation Report
    type: SOC 2 Type 2
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.cursor.com/
    text: ISO 27001 Certificate.pdf
    type: ISO 27001:2022 certificate
  - framework: ISO42001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.cursor.com/
    text: ISO/IEC 42001:2023
    type: ISO/IEC 42001:2023 certificate
  trust_center:
    url: https://cursor.com/security
frameworks:
- ISO27001
- ISO42001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Anysphere
provenance_date: '2026-11-09'
provider_name: Anysphere
provider_slug: anysphere
slug: anysphere-compliance
source_date: '2026-11-09'
source_filename: anysphere-compliance.yml
source_heading: Compliance
source_page: https://cursor.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Anysphere\naid: anysphere\nurl: https://cursor.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/anysphere-trust-center.yml\n  sources:\n  - https://cursor.com/security\n  - https://trust.cursor.com/\ntrust_center:\n  url: https://cursor.com/security\nattestations:\n- framework: other\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Cursor holds AIUC-1, ISO/IEC 27001:2022, and ISO/IEC 42001:2023 certifications, along with a SOC 2 Type\n    II attestation.\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n\
  \  issuer: null\n  report_access: on_request\n  text: Cursor holds AIUC-1, ISO/IEC 27001:2022, and ISO/IEC 42001:2023 certifications, along with a SOC 2 Type\n    II attestation.\n- framework: ISO42001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Cursor holds AIUC-1, ISO/IEC 27001:2022, and ISO/IEC 42001:2023 certifications, along with a SOC 2 Type\n    II attestation.\n- framework: SOC2\n  type: attestation\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Cursor holds AIUC-1, ISO/IEC 27001:2022, and ISO/IEC 42001:2023 certifications, along with a SOC 2 Type\n    II attestation.\n- framework: SOC2\n  type: SOC 2 Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2 - Attestation Report\n  source: https://trust.cursor.com/\n- framework: ISO27001\n  type: ISO 27001:2022 certificate\n  scope: null\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: ISO 27001 Certificate.pdf\n  source: https://trust.cursor.com/\n- framework: ISO42001\n  type: ISO/IEC 42001:2023 certificate\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO/IEC 42001:2023\n  source: https://trust.cursor.com/\n"
source_yaml_url: https://artifacts.apis.io/anysphere/compliance/anysphere-compliance.yml
stated_fields:
- attestations
summary_line: 7 quoted statements, read from Anysphere's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Developer Tools
- Artificial Intelligence
- Code Editor
- Coding Agents
- Cloud Agents
- Developer Productivity
- IDE
---
