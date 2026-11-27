---
api_specs:
- filename: tracebit-alerts-api-openapi.yml
  format: yaml
  label: Tracebit Alerts API
  slug: tracebit-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tracebit/openapi/tracebit-alerts-api-openapi.yml
- filename: tracebit-canary-credentials-api-openapi.yml
  format: yaml
  label: Tracebit Canary Credentials API
  slug: tracebit-canary-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tracebit/openapi/tracebit-canary-credentials-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Tracebit has attained our SOC 2 Type 2 Attestation
    type: SOC 2 Type 2 attestation
  - framework: CyberEssentials
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: UK Cyber Essentials
    type: UK Cyber Essentials
  trust_center:
    url: https://trust.tracebit.com/
frameworks:
- CyberEssentials
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Tracebit
provenance_date: '2026-11-10'
provider_name: Tracebit
provider_slug: tracebit
slug: tracebit-compliance
source_date: '2026-11-10'
source_filename: tracebit-compliance.yml
source_heading: Compliance
source_page: https://trust.tracebit.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Tracebit\naid: tracebit\nurl: https://trust.tracebit.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/tracebit-trust-center.yml\ntrust_center:\n  url: https://trust.tracebit.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 attestation\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Tracebit has attained our SOC 2 Type 2 Attestation\n- framework: CyberEssentials\n  type: UK Cyber Essentials\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: UK Cyber Essentials\n"
source_yaml_url: https://artifacts.apis.io/tracebit/compliance/tracebit-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Tracebit's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cloud Saas
- Security
- Deception
- Canary Tokens
- Threat Detection
- Cloud Security
- Incident Response
---
