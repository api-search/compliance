---
api_specs:
- filename: cursor-audit-logs-api-openapi.yml
  format: yaml
  label: Cursor Audit Logs API
  slug: cursor-audit-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cursor/openapi/cursor-audit-logs-api-openapi.yml
- filename: cursor-groups-api-openapi.yml
  format: yaml
  label: Cursor Groups API
  slug: cursor-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cursor/openapi/cursor-groups-api-openapi.yml
- filename: cursor-members-api-openapi.yml
  format: yaml
  label: Cursor Members API
  slug: cursor-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cursor/openapi/cursor-members-api-openapi.yml
- filename: cursor-repo-blocklists-api-openapi.yml
  format: yaml
  label: Cursor Repo Blocklists API
  slug: cursor-repo-blocklists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cursor/openapi/cursor-repo-blocklists-api-openapi.yml
- filename: cursor-spend-api-openapi.yml
  format: yaml
  label: Cursor Spend API
  slug: cursor-spend-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cursor/openapi/cursor-spend-api-openapi.yml
- filename: cursor-usage-api-openapi.yml
  format: yaml
  label: Cursor Usage API
  slug: cursor-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cursor/openapi/cursor-usage-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: Cursor
    text: Cursor holds AIUC-1, ISO/IEC 27001:2022, and ISO/IEC 42001:2023 certifications, along with a SOC 2 Type II attestation.
    type: certification
  - framework: ISO42001
    issuer: null
    period: null
    report_access: on_request
    scope: Cursor
    text: Cursor holds AIUC-1, ISO/IEC 27001:2022, and ISO/IEC 42001:2023 certifications, along with a SOC 2 Type II attestation.
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Cursor
    text: along with a SOC 2 Type II attestation.
    type: attestation (Type II)
  - framework: other
    issuer: null
    period: null
    report_access: on_request
    scope: Cursor
    text: Cursor holds AIUC-1, ISO/IEC 27001:2022, and ISO/IEC 42001:2023 certifications, along with a SOC 2 Type II attestation.
    type: certification (AIUC-1)
  trust_center:
    url: https://cursor.com/security
frameworks:
- ISO27001
- ISO42001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Cursor
provenance_date: '2026-11-09'
provider_name: Cursor
provider_slug: cursor
slug: cursor-compliance
source_date: '2026-11-09'
source_filename: cursor-compliance.yml
source_heading: Compliance
source_page: https://cursor.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Cursor\naid: cursor\nurl: https://cursor.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://cursor.com/security\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: Cursor\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Cursor holds AIUC-1, ISO/IEC 27001:2022, and ISO/IEC 42001:2023 certifications, along with a SOC 2 Type\n    II attestation.\n- framework: ISO42001\n  type: certification\n  scope: Cursor\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Cursor holds AIUC-1, ISO/IEC 27001:2022, and ISO/IEC 42001:2023 certifications,\
  \ along with a SOC 2 Type\n    II attestation.\n- framework: SOC2\n  type: attestation (Type II)\n  scope: Cursor\n  period: null\n  issuer: null\n  report_access: on_request\n  text: along with a SOC 2 Type II attestation.\n- framework: other\n  type: certification (AIUC-1)\n  scope: Cursor\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Cursor holds AIUC-1, ISO/IEC 27001:2022, and ISO/IEC 42001:2023 certifications, along with a SOC 2 Type\n    II attestation.\n"
source_yaml_url: https://artifacts.apis.io/cursor/compliance/cursor-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Cursor's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Developer Tools
- Code Editor
- Agents
- IDE
- Cloud Agents
---
