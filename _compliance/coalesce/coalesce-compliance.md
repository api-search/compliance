---
api_specs:
- filename: coalesce-environments-api-openapi.yml
  format: yaml
  label: Coalesce Environments API
  slug: coalesce-environments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coalesce/openapi/coalesce-environments-api-openapi.yml
- filename: coalesce-git-accounts-api-openapi.yml
  format: yaml
  label: Coalesce Git Accounts API
  slug: coalesce-git-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coalesce/openapi/coalesce-git-accounts-api-openapi.yml
- filename: coalesce-nodes-api-openapi.yml
  format: yaml
  label: Coalesce Nodes API
  slug: coalesce-nodes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coalesce/openapi/coalesce-nodes-api-openapi.yml
- filename: coalesce-projects-api-openapi.yml
  format: yaml
  label: Coalesce Projects API
  slug: coalesce-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coalesce/openapi/coalesce-projects-api-openapi.yml
- filename: coalesce-runs-api-openapi.yml
  format: yaml
  label: Coalesce Runs API
  slug: coalesce-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coalesce/openapi/coalesce-runs-api-openapi.yml
- filename: coalesce-users-api-openapi.yml
  format: yaml
  label: Coalesce Users API
  slug: coalesce-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coalesce/openapi/coalesce-users-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: '2024'
    report_access: unstated
    scope: null
    text: SOC 2 Type II (2024)
    type: SOC 2 Type II
  - framework: ISO27001
    issuer: null
    period: '2024'
    report_access: unstated
    scope: null
    text: ISO/IEC 27001:2022 (2024)
    type: ISO/IEC 27001:2022 certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Coalesce proudly upholds SOC 2, ISO 27001:2022, and GDPR compliance, reflecting our ongoing commitment to transparency, cybersecurity, and trust.
    type: null
  trust_center:
    url: https://trust.coalesce.io/
frameworks:
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Coalesce
provenance_date: '2026-11-09'
provider_name: Coalesce
provider_slug: coalesce
slug: coalesce-compliance
source_date: '2026-11-09'
source_filename: coalesce-compliance.yml
source_heading: Compliance
source_page: https://trust.coalesce.io/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Coalesce\naid: coalesce\nurl: https://trust.coalesce.io/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/coalesce-trust-center.yml\ntrust_center:\n  url: https://trust.coalesce.io/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: '2024'\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II (2024)\n- framework: ISO27001\n  type: ISO/IEC 27001:2022 certification\n  scope: null\n  period: '2024'\n  issuer: null\n  report_access: unstated\n  text: ISO/IEC 27001:2022 (2024)\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: Coalesce proudly upholds SOC 2, ISO 27001:2022, and GDPR compliance, reflecting our ongoing commitment to\n    transparency, cybersecurity, and trust.\n"
source_yaml_url: https://artifacts.apis.io/coalesce/compliance/coalesce-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Coalesce's own page on 2026-11-09.
synthetic: false
tags:
- Data Transformation
- Snowflake
- Data Pipeline
- Data Catalog
- Data Quality
- Analytics
- Artificial Intelligence
---
