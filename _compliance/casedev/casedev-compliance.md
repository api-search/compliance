---
api_specs:
- filename: casedev-api-openapi.json
  format: json
  label: Case.dev API API
  slug: case-dev-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/casedev/openapi/_original/casedev-api-openapi.json
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II Independently audited controls
    type: SOC 2 Type II
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Healthcare-adjacent legal workflows
    text: HIPAA + BAA Healthcare-adjacent legal workflows
    type: HIPAA with BAA
  trust_center:
    url: https://case.dev/
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Case.dev
provenance_date: '2026-11-09'
provider_name: Case.dev
provider_slug: casedev
slug: casedev-compliance
source_date: '2026-11-09'
source_filename: casedev-compliance.yml
source_heading: Compliance
source_page: https://case.dev/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Case.dev\naid: casedev\nurl: https://case.dev/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://case.dev/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II Independently audited controls\n- framework: HIPAA\n  type: HIPAA with BAA\n  scope: Healthcare-adjacent legal workflows\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA + BAA Healthcare-adjacent legal workflows\n"
source_yaml_url: https://artifacts.apis.io/casedev/compliance/casedev-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Case.dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal Tech
- Artificial Intelligence
- Platform
- Automation
---
