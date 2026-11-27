---
api_specs:
- filename: warpstream-api-keys-api-openapi.yml
  format: yaml
  label: WarpStream API Keys API
  slug: warpstream-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/warpstream/openapi/warpstream-api-keys-api-openapi.yml
- filename: warpstream-monitoring-api-openapi.yml
  format: yaml
  label: WarpStream Monitoring API
  slug: warpstream-monitoring-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/warpstream/openapi/warpstream-monitoring-api-openapi.yml
- filename: warpstream-pipelines-api-openapi.yml
  format: yaml
  label: WarpStream Pipelines API
  slug: warpstream-pipelines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/warpstream/openapi/warpstream-pipelines-api-openapi.yml
- filename: warpstream-topics-api-openapi.yml
  format: yaml
  label: WarpStream Topics API
  slug: warpstream-topics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/warpstream/openapi/warpstream-topics-api-openapi.yml
- filename: warpstream-virtual-cluster-credentials-api-openapi.yml
  format: yaml
  label: WarpStream Virtual Cluster Credentials API
  slug: warpstream-virtual-cluster-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/warpstream/openapi/warpstream-virtual-cluster-credentials-api-openapi.yml
- filename: warpstream-virtual-clusters-api-openapi.yml
  format: yaml
  label: WarpStream Virtual Clusters API
  slug: warpstream-virtual-clusters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/warpstream/openapi/warpstream-virtual-clusters-api-openapi.yml
- filename: warpstream-workspaces-api-openapi.yml
  format: yaml
  label: WarpStream Workspaces API
  slug: warpstream-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/warpstream/openapi/warpstream-workspaces-api-openapi.yml
- filename: warpstream-acls-api-openapi.yml
  format: yaml
  label: WarpStream AC Ls API
  slug: warpstream-acls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/warpstream/openapi/warpstream-acls-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type 2
    type: SOC 2 Type 2
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO/IEC 27001 SoA
    type: ISO/IEC 27001
  - framework: ISO27017
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO/IEC 27017:2015
    type: ISO/IEC 27017:2015
  - framework: C5
    issuer: null
    period: null
    report_access: on_request
    scope: Confluent Cloud
    text: The BSI C5 report is available now on the Trust Center .
    type: BSI Cloud Computing Compliance Criteria Catalogue (C5)
  - framework: other
    issuer: null
    period: null
    report_access: on_request
    scope: Confluent Cloud Services
    text: The full report is available now on the Trust Center to customers and prospects on request.
    type: OSPAR (Outsourced Service Provider's Audit Report)
  trust_center:
    url: https://confluent.safebase.us/?product=bring-your-own-cloud-warpstream
frameworks:
- C5
- ISO27001
- ISO27017
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: WarpStream
provenance_date: '2026-11-10'
provider_name: WarpStream
provider_slug: warpstream
slug: warpstream-compliance
source_date: '2026-11-10'
source_filename: warpstream-compliance.yml
source_heading: Compliance
source_page: https://confluent.safebase.us/?product=bring-your-own-cloud-warpstream
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: WarpStream\naid: warpstream\nurl: https://confluent.safebase.us/?product=bring-your-own-cloud-warpstream\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/warpstream-trust-center.yml\ntrust_center:\n  url: https://confluent.safebase.us/?product=bring-your-own-cloud-warpstream\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2\n- framework: ISO27001\n  type: ISO/IEC 27001\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO/IEC 27001 SoA\n- framework: ISO27017\n  type:\
  \ ISO/IEC 27017:2015\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO/IEC 27017:2015\n- framework: C5\n  type: BSI Cloud Computing Compliance Criteria Catalogue (C5)\n  scope: Confluent Cloud\n  period: null\n  issuer: null\n  report_access: on_request\n  text: The BSI C5 report is available now on the Trust Center .\n- framework: other\n  type: OSPAR (Outsourced Service Provider's Audit Report)\n  scope: Confluent Cloud Services\n  period: null\n  issuer: null\n  report_access: on_request\n  text: The full report is available now on the Trust Center to customers and prospects on request.\n"
source_yaml_url: https://artifacts.apis.io/warpstream/compliance/warpstream-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from WarpStream's own page on 2026-11-10.
synthetic: false
tags:
- Kafka
- Streaming
- Serverless
- Object Storage
- BYOC
- Data Streaming
- Apache Kafka
- Message Queue
- Event Streaming
---
