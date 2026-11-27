---
api_specs:
- filename: boundaryai-ai-openapi-generated.yml
  format: yaml
  label: BoundaryAI API
  slug: boundaryai-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/boundaryai-ai/openapi/_ae-authored/boundaryai-ai-openapi-generated.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: Annual audit
    report_access: nda
    scope: null
    text: SOC 2 Type II Annual audit. Report available under NDA.
    type: Type II
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Enterprise
    text: HIPAA / BAA Available on Enterprise.
    type: BAA
  trust_center:
    url: https://boundaryai.ai/security
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: BoundaryAI
provenance_date: '2026-11-09'
provider_name: BoundaryAI
provider_slug: boundaryai-ai
slug: boundaryai-ai-compliance
source_date: '2026-11-09'
source_filename: boundaryai-ai-compliance.yml
source_heading: Compliance
source_page: https://boundaryai.ai/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: BoundaryAI\naid: boundaryai-ai\nurl: https://boundaryai.ai/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://boundaryai.ai/security\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: Annual audit\n  issuer: null\n  report_access: nda\n  text: SOC 2 Type II Annual audit. Report available under NDA.\n- framework: HIPAA\n  type: BAA\n  scope: Enterprise\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA / BAA Available on Enterprise.\n"
source_yaml_url: https://artifacts.apis.io/boundaryai-ai/compliance/boundaryai-ai-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from BoundaryAI's own page on 2026-11-09.
synthetic: false
tags:
- AI Governance
- Action enforcement
- Policy compliance
- Security
- Developer Tools
---
