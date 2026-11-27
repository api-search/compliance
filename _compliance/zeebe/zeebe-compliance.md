---
api_specs:
- filename: zeebe-cluster-api-openapi.yml
  format: yaml
  label: Zeebe Cluster API
  slug: zeebe-cluster-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zeebe/openapi/zeebe-cluster-api-openapi.yml
- filename: zeebe-deployments-api-openapi.yml
  format: yaml
  label: Zeebe Deployments API
  slug: zeebe-deployments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zeebe/openapi/zeebe-deployments-api-openapi.yml
- filename: zeebe-incidents-api-openapi.yml
  format: yaml
  label: Zeebe Incidents API
  slug: zeebe-incidents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zeebe/openapi/zeebe-incidents-api-openapi.yml
- filename: zeebe-jobs-api-openapi.yml
  format: yaml
  label: Zeebe Jobs API
  slug: zeebe-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zeebe/openapi/zeebe-jobs-api-openapi.yml
- filename: zeebe-messages-api-openapi.yml
  format: yaml
  label: Zeebe Messages API
  slug: zeebe-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zeebe/openapi/zeebe-messages-api-openapi.yml
- filename: zeebe-process-instances-api-openapi.yml
  format: yaml
  label: Zeebe Process Instances API
  slug: zeebe-process-instances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zeebe/openapi/zeebe-process-instances-api-openapi.yml
- filename: zeebe-resources-api-openapi.yml
  format: yaml
  label: Zeebe Resources API
  slug: zeebe-resources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zeebe/openapi/zeebe-resources-api-openapi.yml
- filename: zeebe-signals-api-openapi.yml
  format: yaml
  label: Zeebe Signals API
  slug: zeebe-signals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zeebe/openapi/zeebe-signals-api-openapi.yml
- filename: zeebe-user-tasks-api-openapi.yml
  format: yaml
  label: Zeebe User Tasks API
  slug: zeebe-user-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zeebe/openapi/zeebe-user-tasks-api-openapi.yml
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
    type: Cloud Security Alliance
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: regulation compliance
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
    type: Type II report
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
name: Zeebe
provenance_date: '2026-11-10'
provider_name: Zeebe
provider_slug: zeebe
slug: zeebe-compliance
source_date: '2026-11-10'
source_filename: zeebe-compliance.yml
source_heading: Compliance
source_page: https://trust.camunda.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Zeebe\naid: zeebe\nurl: https://trust.camunda.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/zeebe-trust-center.yml\ntrust_center:\n  url: https://trust.camunda.com/\nattestations:\n- framework: TISAX\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: TISAX\n- framework: other\n  type: Cloud Security Alliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Cloud Security Alliance\n- framework: GDPR\n  type: regulation compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: GDPR\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001\n- framework: SOC2\n  type: Type II report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II\n"
source_yaml_url: https://artifacts.apis.io/zeebe/compliance/zeebe-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Zeebe's own page on 2026-11-10.
synthetic: false
tags:
- BPMN
- Camunda
- Cloud-Native
- Distributed Systems
- Java
- Microservices
- Process Automation
- Workflow Orchestration
---
