---
api_specs:
- filename: arkestro-webhooks-api-openapi.yml
  format: yaml
  label: Arkestro Webhooks API
  slug: arkestro-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkestro/openapi/arkestro-webhooks-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: annually
    report_access: unstated
    scope: platform
    text: SOC 2 Type II examined annually, with reports and bridge letters available through the Trust Center.
    type: SOC 2 Type II examination
  trust_center:
    url: https://arkestro.com/security-compliance/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Arkestro
provenance_date: '2026-11-09'
provider_name: Arkestro
provider_slug: arkestro
slug: arkestro-compliance
source_date: '2026-11-09'
source_filename: arkestro-compliance.yml
source_heading: Compliance
source_page: https://arkestro.com/security-compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Arkestro\naid: arkestro\nurl: https://arkestro.com/security-compliance/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://arkestro.com/security-compliance/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II examination\n  scope: platform\n  period: annually\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II examined annually, with reports and bridge letters available through the Trust Center.\n"
source_yaml_url: https://artifacts.apis.io/arkestro/compliance/arkestro-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Arkestro's own page on 2026-11-09.
synthetic: false
tags:
- Procurement
- Sourcing
- Supply Chain
- Spend Management
- eSourcing
- Supplier Management
- Purchase Orders
- procurement-analytics
- Enterprise Software
- predictive-procurement
- MCP
- Webhook
---
