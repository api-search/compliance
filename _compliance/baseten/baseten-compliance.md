---
api_specs:
- filename: baseten-chat-completions-api-openapi.yml
  format: yaml
  label: Baseten Chat Completions API
  slug: baseten-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/baseten/openapi/baseten-chat-completions-api-openapi.yml
- filename: baseten-messages-api-openapi.yml
  format: yaml
  label: Baseten Messages API
  slug: baseten-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/baseten/openapi/baseten-messages-api-openapi.yml
claim_count: 6
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type 2 Report 5.31.26.pdf
    type: SOC 2 Type 2 report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001:2022
    type: ISO 27001:2022 certificate
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Baseten Labs, Inc. HIPAA Report 5.31.26.pdf
    type: HIPAA report
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PCI DSS - SAQ D
    type: PCI DSS SAQ D attestation of compliance
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: GDPR compliance badge
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA COMPLIANT
    type: CCPA compliance badge
  trust_center:
    url: https://trust.baseten.co/
frameworks:
- CCPA
- GDPR
- HIPAA
- ISO27001
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Baseten
provenance_date: '2026-11-09'
provider_name: Baseten
provider_slug: baseten
slug: baseten-compliance
source_date: '2026-11-09'
source_filename: baseten-compliance.yml
source_heading: Compliance
source_page: https://trust.baseten.co/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Baseten\naid: baseten\nurl: https://trust.baseten.co/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/baseten-trust-center.yml\ntrust_center:\n  url: https://trust.baseten.co/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2 Report 5.31.26.pdf\n- framework: ISO27001\n  type: ISO 27001:2022 certificate\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022\n- framework: HIPAA\n  type: HIPAA report\n  scope: null\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: Baseten Labs, Inc. HIPAA Report 5.31.26.pdf\n- framework: PCI-DSS\n  type: PCI DSS SAQ D attestation of compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI DSS - SAQ D\n- framework: GDPR\n  type: GDPR compliance badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: CCPA\n  type: CCPA compliance badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA COMPLIANT\n"
source_yaml_url: https://artifacts.apis.io/baseten/compliance/baseten-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from Baseten's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Machine Learning
- Inference
- Deployment
- MLOps
- OpenAI-Compatible
- Anthropic Compatible
- Truss
---
