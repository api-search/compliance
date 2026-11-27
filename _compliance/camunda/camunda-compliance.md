---
api_specs:
- filename: camunda-cluster-api-openapi.yml
  format: yaml
  label: Camunda Cluster API
  slug: camunda-cluster-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/camunda/openapi/camunda-cluster-api-openapi.yml
- filename: camunda-decisions-api-openapi.yml
  format: yaml
  label: Camunda Decisions API
  slug: camunda-decisions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/camunda/openapi/camunda-decisions-api-openapi.yml
- filename: camunda-deployments-api-openapi.yml
  format: yaml
  label: Camunda Deployments API
  slug: camunda-deployments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/camunda/openapi/camunda-deployments-api-openapi.yml
- filename: camunda-incidents-api-openapi.yml
  format: yaml
  label: Camunda Incidents API
  slug: camunda-incidents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/camunda/openapi/camunda-incidents-api-openapi.yml
- filename: camunda-jobs-api-openapi.yml
  format: yaml
  label: Camunda Jobs API
  slug: camunda-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/camunda/openapi/camunda-jobs-api-openapi.yml
- filename: camunda-messages-api-openapi.yml
  format: yaml
  label: Camunda Messages API
  slug: camunda-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/camunda/openapi/camunda-messages-api-openapi.yml
- filename: camunda-process-definitions-api-openapi.yml
  format: yaml
  label: Camunda Process Definitions API
  slug: camunda-process-definitions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/camunda/openapi/camunda-process-definitions-api-openapi.yml
- filename: camunda-process-instances-api-openapi.yml
  format: yaml
  label: Camunda Process Instances API
  slug: camunda-process-instances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/camunda/openapi/camunda-process-instances-api-openapi.yml
- filename: camunda-signals-api-openapi.yml
  format: yaml
  label: Camunda Signals API
  slug: camunda-signals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/camunda/openapi/camunda-signals-api-openapi.yml
- filename: camunda-user-tasks-api-openapi.yml
  format: yaml
  label: Camunda User Tasks API
  slug: camunda-user-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/camunda/openapi/camunda-user-tasks-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: TISAX
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: TISAX
    type: certification
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Cloud Security Alliance
    type: Cloud Security Alliance listing
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: regulatory compliance
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II
    type: SOC 2 Type II report
  trust_center:
    url: https://trust.camunda.com/
frameworks:
- GDPR
- ISO27001
- SOC2
- TISAX
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Camunda
provenance_date: '2026-11-09'
provider_name: Camunda
provider_slug: camunda
slug: camunda-compliance
source_date: '2026-11-09'
source_filename: camunda-compliance.yml
source_heading: Compliance
source_page: https://trust.camunda.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Camunda\naid: camunda\nurl: https://trust.camunda.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/camunda-trust-center.yml\ntrust_center:\n  url: https://trust.camunda.com/\nattestations:\n- framework: TISAX\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: TISAX\n- framework: other\n  type: Cloud Security Alliance listing\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Cloud Security Alliance\n- framework: GDPR\n  type: regulatory compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: GDPR\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II\n"
source_yaml_url: https://artifacts.apis.io/camunda/compliance/camunda-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Camunda's own page on 2026-11-09.
synthetic: false
tags:
- BPMN
- Business Process Management
- Process Automation
- Workflows
- Workflow Automation
---
