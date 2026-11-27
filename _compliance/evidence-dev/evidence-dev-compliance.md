---
api_specs:
- filename: evidence-dev-openapi.yml
  format: yaml
  label: Evidence Framework (SQL + Markdown)
  slug: evidence-framework
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evidence-dev/openapi/_original/evidence-dev-openapi.yml
- filename: evidence-dev-openapi.yml
  format: yaml
  label: Evidence USQL / Query Layer
  slug: usql-query-layer
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evidence-dev/openapi/_original/evidence-dev-openapi.yml
- filename: evidence-dev-openapi.yml
  format: yaml
  label: Evidence Cloud
  slug: evidence-cloud
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evidence-dev/openapi/_original/evidence-dev-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Compliant
    type: null
  trust_center:
    url: https://security.evidence.dev/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Evidence
provenance_date: '2026-11-09'
provider_name: Evidence
provider_slug: evidence-dev
slug: evidence-dev-compliance
source_date: '2026-11-09'
source_filename: evidence-dev-compliance.yml
source_heading: Compliance
source_page: https://security.evidence.dev/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Evidence\naid: evidence-dev\nurl: https://security.evidence.dev/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/evidence-dev-trust-center.yml\ntrust_center:\n  url: https://security.evidence.dev/\nattestations:\n- framework: SOC2\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Compliant\n"
source_yaml_url: https://artifacts.apis.io/evidence-dev/compliance/evidence-dev-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Evidence's own page on 2026-11-09.
synthetic: false
tags:
- Business Intelligence
- BI-as-Code
- SQL
- Markdown
- Data Apps
- Open Source
---
