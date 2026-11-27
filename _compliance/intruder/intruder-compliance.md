---
api_specs:
- filename: intruder-health-api-openapi.yml
  format: yaml
  label: Intruder Health API
  slug: intruder-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intruder/openapi/intruder-health-api-openapi.yml
- filename: intruder-issues-api-openapi.yml
  format: yaml
  label: Intruder Issues API
  slug: intruder-issues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intruder/openapi/intruder-issues-api-openapi.yml
- filename: intruder-licenses-api-openapi.yml
  format: yaml
  label: Intruder Licenses API
  slug: intruder-licenses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intruder/openapi/intruder-licenses-api-openapi.yml
- filename: intruder-occurrences-api-openapi.yml
  format: yaml
  label: Intruder Occurrences API
  slug: intruder-occurrences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intruder/openapi/intruder-occurrences-api-openapi.yml
- filename: intruder-scans-api-openapi.yml
  format: yaml
  label: Intruder Scans API
  slug: intruder-scans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intruder/openapi/intruder-scans-api-openapi.yml
- filename: intruder-tags-api-openapi.yml
  format: yaml
  label: Intruder Tags API
  slug: intruder-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intruder/openapi/intruder-tags-api-openapi.yml
- filename: intruder-targets-api-openapi.yml
  format: yaml
  label: Intruder Targets API
  slug: intruder-targets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intruder/openapi/intruder-targets-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: AICPA Service Organization Control (SOC) 2 Type 2 audit
    period: null
    report_access: unstated
    scope: Intruder Systems Ltd information security practices, policies, procedures, and operations
    text: Intruder Systems Ltd successfully completed the AICPA Service Organization Control (SOC) 2 Type 2 audit.
    type: SOC 2 Type 2 audit
  trust_center:
    url: https://www.intruder.io/security
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Intruder
provenance_date: '2026-11-09'
provider_name: Intruder
provider_slug: intruder
slug: intruder-compliance
source_date: '2026-11-09'
source_filename: intruder-compliance.yml
source_heading: Compliance
source_page: https://www.intruder.io/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Intruder\naid: intruder\nurl: https://www.intruder.io/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.intruder.io/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 audit\n  scope: Intruder Systems Ltd information security practices, policies, procedures, and operations\n  period: null\n  issuer: AICPA Service Organization Control (SOC) 2 Type 2 audit\n  report_access: unstated\n  text: Intruder Systems Ltd successfully completed the AICPA Service Organization Control (SOC) 2 Type 2 audit.\n"
source_yaml_url: https://artifacts.apis.io/intruder/compliance/intruder-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Intruder's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Cloud
- Artificial Intelligence
- Platform
---
