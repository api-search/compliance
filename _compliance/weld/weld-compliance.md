---
api_specs:
- filename: weld-connection-bridge-api-openapi.yml
  format: yaml
  label: Weld Connection Bridge API
  slug: weld-connection-bridge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weld/openapi/weld-connection-bridge-api-openapi.yml
- filename: weld-connections-api-openapi.yml
  format: yaml
  label: Weld Connections API
  slug: weld-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weld/openapi/weld-connections-api-openapi.yml
- filename: weld-custom-reports-api-openapi.yml
  format: yaml
  label: Weld Custom Reports API
  slug: weld-custom-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weld/openapi/weld-custom-reports-api-openapi.yml
- filename: weld-elt-stream-runs-api-openapi.yml
  format: yaml
  label: Weld ELT Stream Runs API
  slug: weld-elt-stream-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weld/openapi/weld-elt-stream-runs-api-openapi.yml
- filename: weld-elt-streams-api-openapi.yml
  format: yaml
  label: Weld ELT Streams API
  slug: weld-elt-streams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weld/openapi/weld-elt-streams-api-openapi.yml
- filename: weld-elt-syncs-api-openapi.yml
  format: yaml
  label: Weld ELT Syncs API
  slug: weld-elt-syncs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weld/openapi/weld-elt-syncs-api-openapi.yml
- filename: weld-integrations-api-openapi.yml
  format: yaml
  label: Weld Integrations API
  slug: weld-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weld/openapi/weld-integrations-api-openapi.yml
- filename: weld-orchestration-runs-api-openapi.yml
  format: yaml
  label: Weld Orchestration Runs API
  slug: weld-orchestration-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weld/openapi/weld-orchestration-runs-api-openapi.yml
- filename: weld-orchestrations-api-openapi.yml
  format: yaml
  label: Weld Orchestrations API
  slug: weld-orchestrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weld/openapi/weld-orchestrations-api-openapi.yml
- filename: weld-reverse-etl-failed-records-api-openapi.yml
  format: yaml
  label: Weld Reverse ETL Failed Records API
  slug: weld-reverse-etl-failed-records-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weld/openapi/weld-reverse-etl-failed-records-api-openapi.yml
- filename: weld-reverse-etl-sync-runs-api-openapi.yml
  format: yaml
  label: Weld Reverse ETL Sync Runs API
  slug: weld-reverse-etl-sync-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weld/openapi/weld-reverse-etl-sync-runs-api-openapi.yml
- filename: weld-reverse-etl-syncs-api-openapi.yml
  format: yaml
  label: Weld Reverse ETL Syncs API
  slug: weld-reverse-etl-syncs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weld/openapi/weld-reverse-etl-syncs-api-openapi.yml
- filename: weld-transforms-api-openapi.yml
  format: yaml
  label: Weld Transforms API
  slug: weld-transforms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weld/openapi/weld-transforms-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent auditor
    period: null
    report_access: nda
    scope: Weld controls
    text: The SOC 2 Type II report is available under NDA, and the SOC 3 report on request.
    type: SOC 2 Type II audit
  - framework: SOC3
    issuer: independent auditor
    period: null
    report_access: on_request
    scope: Weld controls
    text: the SOC 3 report on request
    type: SOC 3 report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: data centres used by Weld hosting providers
    text: These data centres are certified to SOC 2 and ISO 27001.
    type: data centre certification
  trust_center:
    url: https://weld.app/security
frameworks:
- ISO27001
- SOC2
- SOC3
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Weld
provenance_date: '2026-11-10'
provider_name: Weld
provider_slug: weld
slug: weld-compliance
source_date: '2026-11-10'
source_filename: weld-compliance.yml
source_heading: Compliance
source_page: https://weld.app/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Weld\naid: weld\nurl: https://weld.app/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://weld.app/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II audit\n  scope: Weld controls\n  period: null\n  issuer: independent auditor\n  report_access: nda\n  text: The SOC 2 Type II report is available under NDA, and the SOC 3 report on request.\n- framework: SOC3\n  type: SOC 3 report\n  scope: Weld controls\n  period: null\n  issuer: independent auditor\n  report_access: on_request\n  text: the SOC 3 report on request\n- framework: ISO27001\n  type: data centre certification\n  scope:\
  \ data centres used by Weld hosting providers\n  period: null\n  issuer: null\n  report_access: unstated\n  text: These data centres are certified to SOC 2 and ISO 27001.\n"
source_yaml_url: https://artifacts.apis.io/weld/compliance/weld-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Weld's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data
- ETL
- ELT
- Reverse ETL
- Data Pipeline
- Data Integration
- Change Data Capture
- Transformation
- Analytics
- MCP
- AI Agents
---
