---
api_specs:
- filename: e2b-dev-events-api-openapi.yml
  format: yaml
  label: E2B Events API
  slug: e2b-dev-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/e2b-dev/openapi/e2b-dev-events-api-openapi.yml
- filename: e2b-dev-sandboxes-api-openapi.yml
  format: yaml
  label: E2B Sandboxes API
  slug: e2b-dev-sandboxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/e2b-dev/openapi/e2b-dev-sandboxes-api-openapi.yml
- filename: e2b-dev-tags-api-openapi.yml
  format: yaml
  label: E2B Tags API
  slug: e2b-dev-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/e2b-dev/openapi/e2b-dev-tags-api-openapi.yml
- filename: e2b-dev-templates-api-openapi.yml
  format: yaml
  label: E2B Templates API
  slug: e2b-dev-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/e2b-dev/openapi/e2b-dev-templates-api-openapi.yml
- filename: e2b-dev-volumes-api-openapi.yml
  format: yaml
  label: E2B Volumes API
  slug: e2b-dev-volumes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/e2b-dev/openapi/e2b-dev-volumes-api-openapi.yml
- filename: e2b-dev-webhooks-api-openapi.yml
  format: yaml
  label: E2B Webhooks API
  slug: e2b-dev-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/e2b-dev/openapi/e2b-dev-webhooks-api-openapi.yml
- filename: e2b-dev-e2b-sandbox-events-and-webhooks-api-api-openapi.yml
  format: yaml
  label: E2B Sandbox Events And Webhooks API
  slug: e2b-dev-e2b-sandbox-events-and-webhooks-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/e2b-dev/openapi/e2b-dev-e2b-sandbox-events-and-webhooks-api-api-openapi.yml
- filename: e2b-dev-envd-api-openapi.yml
  format: yaml
  label: E2B Envd API
  slug: e2b-dev-envd-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/e2b-dev/openapi/e2b-dev-envd-api-openapi.yml
- filename: e2b-dev-filesystem-api-openapi.yml
  format: yaml
  label: E2B Filesystem API
  slug: e2b-dev-filesystem-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/e2b-dev/openapi/e2b-dev-filesystem-api-openapi.yml
- filename: e2b-dev-process-api-openapi.yml
  format: yaml
  label: E2B Process API
  slug: e2b-dev-process-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/e2b-dev/openapi/e2b-dev-process-api-openapi.yml
- filename: e2b-dev-secrets-api-openapi.yml
  format: yaml
  label: E2B Secrets API
  slug: e2b-dev-secrets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/e2b-dev/openapi/e2b-dev-secrets-api-openapi.yml
- filename: e2b-dev-teams-api-openapi.yml
  format: yaml
  label: E2B Teams API
  slug: e2b-dev-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/e2b-dev/openapi/e2b-dev-teams-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent auditor
    period: null
    report_access: nda
    scope: E2B software and control plane
    text: SOC 2 Type II Report under NDA, bridge letter available, in the Trust Center.
    type: SOC 2 Type II
  - framework: HIPAA
    issuer: E2B
    period: null
    report_access: on_request
    scope: Enterprise plans
    text: HIPAA Business Associate Agreements signed on Enterprise plans.
    type: Business Associate Agreement
  - framework: GDPR
    issuer: E2B
    period: null
    report_access: on_request
    scope: E2B services
    text: For GDPR, a Data Processing Addendum is available; request the template from the Trust Center, or email trust@e2b.dev for a signed copy.
    type: Data Processing Addendum
  trust_center:
    url: https://e2b.dev/security
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: E2B
provenance_date: '2026-11-09'
provider_name: E2B
provider_slug: e2b-dev
slug: e2b-dev-compliance
source_date: '2026-11-09'
source_filename: e2b-dev-compliance.yml
source_heading: Compliance
source_page: https://e2b.dev/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: E2B\naid: e2b-dev\nurl: https://e2b.dev/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://e2b.dev/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: E2B software and control plane\n  period: null\n  issuer: independent auditor\n  report_access: nda\n  text: SOC 2 Type II Report under NDA, bridge letter available, in the Trust Center.\n- framework: HIPAA\n  type: Business Associate Agreement\n  scope: Enterprise plans\n  period: null\n  issuer: E2B\n  report_access: on_request\n  text: HIPAA Business Associate Agreements signed on Enterprise plans.\n- framework: GDPR\n\
  \  type: Data Processing Addendum\n  scope: E2B services\n  period: null\n  issuer: E2B\n  report_access: on_request\n  text: For GDPR, a Data Processing Addendum is available; request the template from the Trust Center, or email\n    trust@e2b.dev for a signed copy.\n"
source_yaml_url: https://artifacts.apis.io/e2b-dev/compliance/e2b-dev-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from E2B's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Agents
- Code Execution
- Code Interpreter
- Sandbox
- Firecracker
- MicroVM
- Computer Use
- Desktop Sandbox
- Templates
- MCP
- Open Source
---
