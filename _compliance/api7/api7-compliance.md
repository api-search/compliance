---
api_specs:
- filename: api7-a2a-api-openapi.yml
  format: yaml
  label: API7.ai A2A API
  slug: api7-a2a-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/api7/openapi/api7-a2a-api-openapi.yml
- filename: api7-anything-api-openapi.yml
  format: yaml
  label: API7.ai Anything API
  slug: api7-anything-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/api7/openapi/api7-anything-api-openapi.yml
- filename: api7-api7-ai-api-api-openapi.yml
  format: yaml
  label: API7.ai API7.ai API
  slug: api7-api7-ai-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/api7/openapi/api7-api7-ai-api-api-openapi.yml
- filename: api7-apisix-api-openapi.yml
  format: yaml
  label: API7.ai Apisix API
  slug: api7-apisix-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/api7/openapi/api7-apisix-api-openapi.yml
- filename: api7-audio-api-openapi.yml
  format: yaml
  label: API7.ai Audio API
  slug: api7-audio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/api7/openapi/api7-audio-api-openapi.yml
- filename: api7-debug-api-openapi.yml
  format: yaml
  label: API7.ai Debug API
  slug: api7-debug-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/api7/openapi/api7-debug-api-openapi.yml
- filename: api7-fine-tuning-api-openapi.yml
  format: yaml
  label: API7.ai Fine Tuning API
  slug: api7-fine-tuning-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/api7/openapi/api7-fine-tuning-api-openapi.yml
- filename: api7-get-api-openapi.yml
  format: yaml
  label: API7.ai Get API
  slug: api7-get-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/api7/openapi/api7-get-api-openapi.yml
- filename: api7-images-api-openapi.yml
  format: yaml
  label: API7.ai Images API
  slug: api7-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/api7/openapi/api7-images-api-openapi.yml
- filename: api7-livez-api-openapi.yml
  format: yaml
  label: API7.ai Livez API
  slug: api7-livez-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/api7/openapi/api7-livez-api-openapi.yml
- filename: api7-messages-api-openapi.yml
  format: yaml
  label: API7.ai Messages API
  slug: api7-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/api7/openapi/api7-messages-api-openapi.yml
- filename: api7-metrics-api-openapi.yml
  format: yaml
  label: API7.ai Metrics API
  slug: api7-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/api7/openapi/api7-metrics-api-openapi.yml
- filename: api7-readyz-api-openapi.yml
  format: yaml
  label: API7.ai Readyz API
  slug: api7-readyz-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/api7/openapi/api7-readyz-api-openapi.yml
- filename: api7-status-api-openapi.yml
  format: yaml
  label: API7.ai Status API
  slug: api7-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/api7/openapi/api7-status-api-openapi.yml
- filename: api7-videos-api-openapi.yml
  format: yaml
  label: API7.ai Videos API
  slug: api7-videos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/api7/openapi/api7-videos-api-openapi.yml
- filename: api7-chat-completions-api-openapi.yml
  format: yaml
  label: API7.ai Chat Completions API
  slug: api7-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/api7/openapi/api7-chat-completions-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: null
    text: Our SOC 2 report is available under NDA
    type: SOC 2 Type II
  - framework: ISO27001
    issuer: null
    period: null
    report_access: public
    scope: null
    text: ISO/IEC 27001:2022 Certificate
    type: ISO/IEC 27001:2022 certificate
  - framework: HIPAA
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: HIPAA Compliance Documentation Request Access
    type: HIPAA compliance
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: API7.ai is committed to GDPR compliance.
    type: GDPR compliance
  - framework: other
    issuer: null
    period: null
    report_access: nda
    scope: null
    text: The results are available under NDA
    type: Penetration test report (third-party)
  trust_center:
    url: https://api7.ai/trust
frameworks:
- GDPR
- HIPAA
- ISO27001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: API7.ai
provenance_date: '2026-11-09'
provider_name: API7.ai
provider_slug: api7
slug: api7-compliance
source_date: '2026-11-09'
source_filename: api7-compliance.yml
source_heading: Compliance
source_page: https://api7.ai/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: API7.ai\naid: api7\nurl: https://api7.ai/trust\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://api7.ai/trust\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: Our SOC 2 report is available under NDA\n- framework: ISO27001\n  type: ISO/IEC 27001:2022 certificate\n  scope: null\n  period: null\n  issuer: null\n  report_access: public\n  text: ISO/IEC 27001:2022 Certificate\n- framework: HIPAA\n  type: HIPAA compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: HIPAA Compliance\
  \ Documentation Request Access\n- framework: GDPR\n  type: GDPR compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: API7.ai is committed to GDPR compliance.\n- framework: other\n  type: Penetration test report (third-party)\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: The results are available under NDA\n"
source_yaml_url: https://artifacts.apis.io/api7/compliance/api7-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from API7.ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- API Gateway
- AI Gateway
- Open Source
- Cloud
---
