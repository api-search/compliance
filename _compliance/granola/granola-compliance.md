---
api_specs:
- filename: granola-inbox-messages-api-openapi.yml
  format: yaml
  label: Granola Inbox Messages API
  slug: granola-inbox-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/granola/openapi/granola-inbox-messages-api-openapi.yml
- filename: granola-inboxes-api-openapi.yml
  format: yaml
  label: Granola Inboxes API
  slug: granola-inboxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/granola/openapi/granola-inboxes-api-openapi.yml
- filename: granola-trigger-inbox-api-api-openapi.yml
  format: yaml
  label: Granola Trigger Inbox API
  slug: granola-trigger-inbox-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/granola/openapi/granola-trigger-inbox-api-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: July 2025
    report_access: unstated
    scope: null
    text: We achieved full SOC-2 Type 2 compliance in July 2025.
    type: SOC 2 Type 2
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We're committed to GDPR compliance and have a Data Processing Agreement available upon request
    type: GDPR compliance commitment
  trust_center:
    url: https://www.granola.ai/security
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Granola
provenance_date: '2026-11-09'
provider_name: Granola
provider_slug: granola
slug: granola-compliance
source_date: '2026-11-09'
source_filename: granola-compliance.yml
source_heading: Compliance
source_page: https://www.granola.ai/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Granola\naid: granola\nurl: https://www.granola.ai/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/granola-trust-center.yml\ntrust_center:\n  url: https://www.granola.ai/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2\n  scope: null\n  period: July 2025\n  issuer: null\n  report_access: unstated\n  text: We achieved full SOC-2 Type 2 compliance in July 2025.\n- framework: GDPR\n  type: GDPR compliance commitment\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We're committed to GDPR compliance and have a Data Processing Agreement available\
  \ upon request\n"
source_yaml_url: https://artifacts.apis.io/granola/compliance/granola-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Granola's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Meeting Notes
- Transcription
- Productivity
- MCP
- Zapier
- Business
- Enterprise
---
