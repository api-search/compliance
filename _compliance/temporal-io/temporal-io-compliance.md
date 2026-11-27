---
api_specs:
- filename: temporal-io-cluster-api-openapi.yml
  format: yaml
  label: Temporal Cluster API
  slug: temporal-io-cluster-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/temporal-io/openapi/temporal-io-cluster-api-openapi.yml
- filename: temporal-io-namespaces-api-openapi.yml
  format: yaml
  label: Temporal Namespaces API
  slug: temporal-io-namespaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/temporal-io/openapi/temporal-io-namespaces-api-openapi.yml
- filename: temporal-io-workflow-lifecycle-api-openapi.yml
  format: yaml
  label: Temporal Workflow Lifecycle API
  slug: temporal-io-workflow-lifecycle-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/temporal-io/openapi/temporal-io-workflow-lifecycle-api-openapi.yml
- filename: temporal-io-workflow-messaging-api-openapi.yml
  format: yaml
  label: Temporal Workflow Messaging API
  slug: temporal-io-workflow-messaging-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/temporal-io/openapi/temporal-io-workflow-messaging-api-openapi.yml
- filename: temporal-io-workflows-api-openapi.yml
  format: yaml
  label: Temporal Workflows API
  slug: temporal-io-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/temporal-io/openapi/temporal-io-workflows-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II GDPR HIPAA CCPA
    type: Type II
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Temporal Cloud
    text: 'Certifications: SOC 2 Type 2 , HIPAA'
    type: null
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II GDPR HIPAA CCPA
    type: null
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II GDPR HIPAA CCPA
    type: null
  trust_center:
    url: https://trust.temporal.io/
frameworks:
- CCPA
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Temporal
provenance_date: '2026-11-10'
provider_name: Temporal
provider_slug: temporal-io
slug: temporal-io-compliance
source_date: '2026-11-10'
source_filename: temporal-io-compliance.yml
source_heading: Compliance
source_page: https://trust.temporal.io/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Temporal\naid: temporal-io\nurl: https://trust.temporal.io/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/temporal-io-trust-center.yml\ntrust_center:\n  url: https://trust.temporal.io/\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II GDPR HIPAA CCPA\n- framework: HIPAA\n  type: null\n  scope: Temporal Cloud\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'Certifications: SOC 2 Type 2 , HIPAA'\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: SOC 2 Type II GDPR HIPAA CCPA\n- framework: CCPA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II GDPR HIPAA CCPA\n"
source_yaml_url: https://artifacts.apis.io/temporal-io/compliance/temporal-io-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Temporal's own page on 2026-11-10.
synthetic: false
tags:
- Durable Execution
- Workflow Orchestration
- gRPC
- Workflows
- Open Source
- Temporal Cloud
- Workflow Automation
---
