---
api_specs:
- filename: unionai-domains-api-openapi.yml
  format: yaml
  label: Union.ai Domains API
  slug: unionai-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unionai/openapi/unionai-domains-api-openapi.yml
- filename: unionai-executions-api-openapi.yml
  format: yaml
  label: Union.ai Executions API
  slug: unionai-executions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unionai/openapi/unionai-executions-api-openapi.yml
- filename: unionai-launch-plans-api-openapi.yml
  format: yaml
  label: Union.ai Launch Plans API
  slug: unionai-launch-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unionai/openapi/unionai-launch-plans-api-openapi.yml
- filename: unionai-node-executions-api-openapi.yml
  format: yaml
  label: Union.ai Node Executions API
  slug: unionai-node-executions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unionai/openapi/unionai-node-executions-api-openapi.yml
- filename: unionai-projects-api-openapi.yml
  format: yaml
  label: Union.ai Projects API
  slug: unionai-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unionai/openapi/unionai-projects-api-openapi.yml
- filename: unionai-tasks-api-openapi.yml
  format: yaml
  label: Union.ai Tasks API
  slug: unionai-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unionai/openapi/unionai-tasks-api-openapi.yml
- filename: unionai-version-api-openapi.yml
  format: yaml
  label: Union.ai Version API
  slug: unionai-version-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unionai/openapi/unionai-version-api-openapi.yml
- filename: unionai-workflows-api-openapi.yml
  format: yaml
  label: Union.ai Workflows API
  slug: unionai-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unionai/openapi/unionai-workflows-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II
    type: SOC 2 Type II
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type I
    type: SOC 2 Type I
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA
    type: HIPAA
  trust_center:
    url: https://www.union.ai/security
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Union.ai
provenance_date: '2026-11-10'
provider_name: Union.ai
provider_slug: unionai
slug: unionai-compliance
source_date: '2026-11-10'
source_filename: unionai-compliance.yml
source_heading: Compliance
source_page: https://www.union.ai/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Union.ai\naid: unionai\nurl: https://www.union.ai/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/unionai-trust-center.yml\ntrust_center:\n  url: https://www.union.ai/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II\n- framework: SOC2\n  type: SOC 2 Type I\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type I\n- framework: HIPAA\n  type: HIPAA\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA\n"
source_yaml_url: https://artifacts.apis.io/unionai/compliance/unionai-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Union.ai's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Machine Learning
- Orchestration
- Workflows
- MLOps
- Flyte
- Serverless
---
