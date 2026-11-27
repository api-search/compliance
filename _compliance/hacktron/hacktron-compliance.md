---
api_specs:
- filename: hacktron-rest-api-cost-estimations-api-openapi.yml
  format: yaml
  label: Hacktron REST API - Cost Estimations API
  slug: hacktron-rest-api-cost-estimations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hacktron/openapi/hacktron-rest-api-cost-estimations-api-openapi.yml
- filename: hacktron-rest-api-findings-api-openapi.yml
  format: yaml
  label: Hacktron REST API - Findings API
  slug: hacktron-rest-api-findings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hacktron/openapi/hacktron-rest-api-findings-api-openapi.yml
- filename: hacktron-rest-api-hfw-api-openapi.yml
  format: yaml
  label: Hacktron REST API - HFW API
  slug: hacktron-rest-api-hfw-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hacktron/openapi/hacktron-rest-api-hfw-api-openapi.yml
- filename: hacktron-rest-api-repos-api-openapi.yml
  format: yaml
  label: Hacktron REST API - Repos API
  slug: hacktron-rest-api-repos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hacktron/openapi/hacktron-rest-api-repos-api-openapi.yml
- filename: hacktron-rest-api-scans-api-openapi.yml
  format: yaml
  label: Hacktron REST API - Scans API
  slug: hacktron-rest-api-scans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hacktron/openapi/hacktron-rest-api-scans-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type 1 Report
    type: Type 1 report
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type 2 Report
    type: Type 2 report
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Cyber Trust Mark Tier 3 Report
    type: Cyber Trust Mark Tier 3 report
  trust_center:
    url: https://trust.hacktron.ai/
frameworks:
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Hacktron
provenance_date: '2026-11-09'
provider_name: Hacktron
provider_slug: hacktron
slug: hacktron-compliance
source_date: '2026-11-09'
source_filename: hacktron-compliance.yml
source_heading: Compliance
source_page: https://trust.hacktron.ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Hacktron\naid: hacktron\nurl: https://trust.hacktron.ai/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.hacktron.ai/\nattestations:\n- framework: SOC2\n  type: Type 1 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 1 Report\n- framework: SOC2\n  type: Type 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2 Report\n- framework: other\n  type: Cyber Trust Mark Tier 3 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Cyber Trust Mark Tier 3 Report\n"
source_yaml_url: https://artifacts.apis.io/hacktron/compliance/hacktron-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Hacktron's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Automation
- Integration
- IoT
- Enterprise
---
