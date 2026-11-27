---
api_specs:
- filename: orkes-authentication-api-openapi.yml
  format: yaml
  label: Orkes Authentication API
  slug: orkes-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orkes/openapi/orkes-authentication-api-openapi.yml
- filename: orkes-human-tasks-api-openapi.yml
  format: yaml
  label: Orkes Human Tasks API
  slug: orkes-human-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orkes/openapi/orkes-human-tasks-api-openapi.yml
- filename: orkes-schedules-api-openapi.yml
  format: yaml
  label: Orkes Schedules API
  slug: orkes-schedules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orkes/openapi/orkes-schedules-api-openapi.yml
- filename: orkes-secrets-api-openapi.yml
  format: yaml
  label: Orkes Secrets API
  slug: orkes-secrets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orkes/openapi/orkes-secrets-api-openapi.yml
- filename: orkes-task-metadata-api-openapi.yml
  format: yaml
  label: Orkes Task Metadata API
  slug: orkes-task-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orkes/openapi/orkes-task-metadata-api-openapi.yml
- filename: orkes-tasks-api-openapi.yml
  format: yaml
  label: Orkes Tasks API
  slug: orkes-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orkes/openapi/orkes-tasks-api-openapi.yml
- filename: orkes-workflow-execution-api-openapi.yml
  format: yaml
  label: Orkes Workflow Execution API
  slug: orkes-workflow-execution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orkes/openapi/orkes-workflow-execution-api-openapi.yml
- filename: orkes-workflow-metadata-api-openapi.yml
  format: yaml
  label: Orkes Workflow Metadata API
  slug: orkes-workflow-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orkes/openapi/orkes-workflow-metadata-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Orkes Cloud
    text: Orkes Cloud is SOC 2 Type 2 compliant .
    type: SOC 2 Type 2
  trust_center:
    url: https://orkes.io/security
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Orkes
provenance_date: '2026-11-10'
provider_name: Orkes
provider_slug: orkes
slug: orkes-compliance
source_date: '2026-11-10'
source_filename: orkes-compliance.yml
source_heading: Compliance
source_page: https://orkes.io/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Orkes\naid: orkes\nurl: https://orkes.io/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/orkes-trust-center.yml\ntrust_center:\n  url: https://orkes.io/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2\n  scope: Orkes Cloud\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Orkes Cloud is SOC 2 Type 2 compliant .\n"
source_yaml_url: https://artifacts.apis.io/orkes/compliance/orkes-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Orkes's own page on 2026-11-10.
synthetic: false
tags:
- Microservices
---
