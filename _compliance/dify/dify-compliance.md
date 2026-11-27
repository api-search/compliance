---
api_specs:
- filename: dify-conversations-api-openapi.yml
  format: yaml
  label: Dify Conversations API
  slug: dify-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dify/openapi/dify-conversations-api-openapi.yml
- filename: dify-files-api-openapi.yml
  format: yaml
  label: Dify Files API
  slug: dify-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dify/openapi/dify-files-api-openapi.yml
- filename: dify-applications-api-openapi.yml
  format: yaml
  label: Dify Applications API
  slug: dify-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dify/openapi/dify-applications-api-openapi.yml
- filename: dify-annotations-api-openapi.yml
  format: yaml
  label: Dify Annotations API
  slug: dify-annotations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dify/openapi/dify-annotations-api-openapi.yml
- filename: dify-audio-api-openapi.yml
  format: yaml
  label: Dify Audio API
  slug: dify-audio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dify/openapi/dify-audio-api-openapi.yml
- filename: dify-feedback-api-openapi.yml
  format: yaml
  label: Dify Feedback API
  slug: dify-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dify/openapi/dify-feedback-api-openapi.yml
- filename: dify-end-users-api-openapi.yml
  format: yaml
  label: Dify End Users API
  slug: dify-end-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dify/openapi/dify-end-users-api-openapi.yml
- filename: dify-human-input-api-openapi.yml
  format: yaml
  label: Dify Human Input API
  slug: dify-human-input-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dify/openapi/dify-human-input-api-openapi.yml
- filename: dify-documents-api-openapi.yml
  format: yaml
  label: Dify Documents API
  slug: dify-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dify/openapi/dify-documents-api-openapi.yml
- filename: dify-chunks-api-openapi.yml
  format: yaml
  label: Dify Chunks API
  slug: dify-chunks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dify/openapi/dify-chunks-api-openapi.yml
- filename: dify-tags-api-openapi.yml
  format: yaml
  label: Dify Knowledge Tags API
  slug: dify-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dify/openapi/dify-tags-api-openapi.yml
- filename: dify-metadata-api-openapi.yml
  format: yaml
  label: Dify Metadata API
  slug: dify-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dify/openapi/dify-metadata-api-openapi.yml
- filename: dify-models-api-openapi.yml
  format: yaml
  label: Dify Models API
  slug: dify-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dify/openapi/dify-models-api-openapi.yml
- filename: dify-knowledge-pipeline-api-openapi.yml
  format: yaml
  label: Dify Knowledge Pipeline API
  slug: dify-knowledge-pipeline-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dify/openapi/dify-knowledge-pipeline-api-openapi.yml
- filename: dify-chat-messages-api-openapi.yml
  format: yaml
  label: Dify Chat Messages API
  slug: dify-chat-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dify/openapi/dify-chat-messages-api-openapi.yml
- filename: dify-completion-messages-api-openapi.yml
  format: yaml
  label: Dify Completion Messages API
  slug: dify-completion-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dify/openapi/dify-completion-messages-api-openapi.yml
- filename: dify-knowledge-bases-api-openapi.yml
  format: yaml
  label: Dify Knowledge Bases API
  slug: dify-knowledge-bases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dify/openapi/dify-knowledge-bases-api-openapi.yml
- filename: dify-workflow-runs-api-openapi.yml
  format: yaml
  label: Dify Workflow Runs API
  slug: dify-workflow-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dify/openapi/dify-workflow-runs-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: As a paid plan customer, you can acquire our compliance report and safety report, e.g. SOC 2 Type 1 Report, Pen Test report through our security email below.
    type: SOC 2 Type 1 Report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001:2022
    type: ISO 27001:2022
  trust_center:
    url: https://security.dify.ai/
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Dify
provenance_date: '2026-11-09'
provider_name: Dify
provider_slug: dify
slug: dify-compliance
source_date: '2026-11-09'
source_filename: dify-compliance.yml
source_heading: Compliance
source_page: https://security.dify.ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Dify\naid: dify\nurl: https://security.dify.ai/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/dify-trust-center.yml\ntrust_center:\n  url: https://security.dify.ai/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 1 Report\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: As a paid plan customer, you can acquire our compliance report and safety report, e.g. SOC 2 Type 1 Report,\n    Pen Test report through our security email below.\n- framework: ISO27001\n  type: ISO 27001:2022\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text:\
  \ ISO 27001:2022\n"
source_yaml_url: https://artifacts.apis.io/dify/compliance/dify-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Dify's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- LLMOps
- Backend-as-a-Service
- Agents
- Workflows
- Knowledge Management
- RAG
- MCP
- Low-Code
- Open Source
- A2A
---
