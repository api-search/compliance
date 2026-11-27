---
api_specs:
- filename: trigger-dev-batches-api-openapi.yml
  format: yaml
  label: Trigger.dev Batches API
  slug: trigger-dev-batches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trigger-dev/openapi/trigger-dev-batches-api-openapi.yml
- filename: trigger-dev-deployments-api-openapi.yml
  format: yaml
  label: Trigger.dev Deployments API
  slug: trigger-dev-deployments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trigger-dev/openapi/trigger-dev-deployments-api-openapi.yml
- filename: trigger-dev-environment-variables-api-openapi.yml
  format: yaml
  label: Trigger.dev Environment Variables API
  slug: trigger-dev-environment-variables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trigger-dev/openapi/trigger-dev-environment-variables-api-openapi.yml
- filename: trigger-dev-query-api-openapi.yml
  format: yaml
  label: Trigger.dev Query API
  slug: trigger-dev-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trigger-dev/openapi/trigger-dev-query-api-openapi.yml
- filename: trigger-dev-queues-api-openapi.yml
  format: yaml
  label: Trigger.dev Queues API
  slug: trigger-dev-queues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trigger-dev/openapi/trigger-dev-queues-api-openapi.yml
- filename: trigger-dev-runs-api-openapi.yml
  format: yaml
  label: Trigger.dev Runs API
  slug: trigger-dev-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trigger-dev/openapi/trigger-dev-runs-api-openapi.yml
- filename: trigger-dev-schedules-api-openapi.yml
  format: yaml
  label: Trigger.dev Schedules API
  slug: trigger-dev-schedules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trigger-dev/openapi/trigger-dev-schedules-api-openapi.yml
- filename: trigger-dev-tasks-api-openapi.yml
  format: yaml
  label: Trigger.dev Tasks API
  slug: trigger-dev-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trigger-dev/openapi/trigger-dev-tasks-api-openapi.yml
- filename: trigger-dev-waitpoints-api-openapi.yml
  format: yaml
  label: Trigger.dev Waitpoints API
  slug: trigger-dev-waitpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trigger-dev/openapi/trigger-dev-waitpoints-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Yes, Trigger.dev is SOC 2 Type II compliant.
    type: SOC 2 Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Yes, Trigger.dev is GDPR compliant.
    type: compliance
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Trigger.dev Cloud tasks processing PHI requires a signed BAA
    text: Yes. Trigger.dev meets HIPAA Business Associate requirements.
    type: Business Associate requirements
  trust_center:
    url: https://trigger.dev/security
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Trigger.dev
provenance_date: '2026-11-10'
provider_name: Trigger.dev
provider_slug: trigger-dev
slug: trigger-dev-compliance
source_date: '2026-11-10'
source_filename: trigger-dev-compliance.yml
source_heading: Compliance
source_page: https://trigger.dev/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Trigger.dev\naid: trigger-dev\nurl: https://trigger.dev/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/trigger-dev-trust-center.yml\ntrust_center:\n  url: https://trigger.dev/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Yes, Trigger.dev is SOC 2 Type II compliant.\n- framework: GDPR\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Yes, Trigger.dev is GDPR compliant.\n- framework: HIPAA\n  type: Business Associate requirements\n  scope:\
  \ Trigger.dev Cloud tasks processing PHI requires a signed BAA\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Yes. Trigger.dev meets HIPAA Business Associate requirements.\n"
source_yaml_url: https://artifacts.apis.io/trigger-dev/compliance/trigger-dev-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Trigger.dev's own page on 2026-11-10.
synthetic: false
tags:
- Workflow Automation
- Background Jobs
- Durable Execution
- TypeScript
- AI Agents
- Real-Time
- Open Source
---
