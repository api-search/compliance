---
api_specs:
- filename: millimetric-identity-api-openapi.yml
  format: yaml
  label: Millimetric Identity API
  slug: millimetric-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/millimetric/openapi/millimetric-identity-api-openapi.yml
- filename: millimetric-ingest-api-openapi.yml
  format: yaml
  label: Millimetric Ingest API
  slug: millimetric-ingest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/millimetric/openapi/millimetric-ingest-api-openapi.yml
- filename: millimetric-read-api-openapi.yml
  format: yaml
  label: Millimetric Read API
  slug: millimetric-read-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/millimetric/openapi/millimetric-read-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Service
    text: GDPR · UK-GDPR · CCPA ready
    type: compliance statement (footer claim)
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: Service
    text: GDPR · UK-GDPR · CCPA ready
    type: compliance statement (footer claim)
  trust_center:
    url: https://www.millimetric.ai/legal/dpa
frameworks:
- CCPA
- GDPR
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Millimetric
provenance_date: '2026-11-10'
provider_name: Millimetric
provider_slug: millimetric
slug: millimetric-compliance
source_date: '2026-11-10'
source_filename: millimetric-compliance.yml
source_heading: Compliance
source_page: https://www.millimetric.ai/legal/dpa
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Millimetric\naid: millimetric\nurl: https://www.millimetric.ai/legal/dpa\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.millimetric.ai/legal/dpa\nattestations:\n- framework: GDPR\n  type: compliance statement (footer claim)\n  scope: Service\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR · UK-GDPR · CCPA ready\n- framework: CCPA\n  type: compliance statement (footer claim)\n  scope: Service\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR · UK-GDPR · CCPA ready\n"
source_yaml_url: https://artifacts.apis.io/millimetric/compliance/millimetric-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Millimetric's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Analytics
- Web Analytics
- Product Analytics
- Attribution
- Privacy
- MCP
- AI Agents
- Event
- Developer Tools
---
