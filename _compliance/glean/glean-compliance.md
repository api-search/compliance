---
api_specs:
- filename: glean-activity-api-openapi.yml
  format: yaml
  label: Glean Activity API
  slug: glean-activity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/glean/openapi/glean-activity-api-openapi.yml
- filename: glean-agents-api-openapi.yml
  format: yaml
  label: Glean Agents API
  slug: glean-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/glean/openapi/glean-agents-api-openapi.yml
- filename: glean-announcements-api-openapi.yml
  format: yaml
  label: Glean Announcements API
  slug: glean-announcements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/glean/openapi/glean-announcements-api-openapi.yml
- filename: glean-answers-api-openapi.yml
  format: yaml
  label: Glean Answers API
  slug: glean-answers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/glean/openapi/glean-answers-api-openapi.yml
- filename: glean-chat-api-openapi.yml
  format: yaml
  label: Glean Chat API
  slug: glean-chat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/glean/openapi/glean-chat-api-openapi.yml
- filename: glean-collections-api-openapi.yml
  format: yaml
  label: Glean Collections API
  slug: glean-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/glean/openapi/glean-collections-api-openapi.yml
- filename: glean-documents-api-openapi.yml
  format: yaml
  label: Glean Documents API
  slug: glean-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/glean/openapi/glean-documents-api-openapi.yml
- filename: glean-governance-api-openapi.yml
  format: yaml
  label: Glean Governance API
  slug: glean-governance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/glean/openapi/glean-governance-api-openapi.yml
- filename: glean-insights-api-openapi.yml
  format: yaml
  label: Glean Insights API
  slug: glean-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/glean/openapi/glean-insights-api-openapi.yml
- filename: glean-people-api-openapi.yml
  format: yaml
  label: Glean People API
  slug: glean-people-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/glean/openapi/glean-people-api-openapi.yml
- filename: glean-pins-api-openapi.yml
  format: yaml
  label: Glean Pins API
  slug: glean-pins-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/glean/openapi/glean-pins-api-openapi.yml
- filename: glean-search-api-openapi.yml
  format: yaml
  label: Glean Search API
  slug: glean-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/glean/openapi/glean-search-api-openapi.yml
- filename: glean-shortcuts-api-openapi.yml
  format: yaml
  label: Glean Shortcuts API
  slug: glean-shortcuts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/glean/openapi/glean-shortcuts-api-openapi.yml
- filename: glean-summarize-api-openapi.yml
  format: yaml
  label: Glean Summarize API
  slug: glean-summarize-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/glean/openapi/glean-summarize-api-openapi.yml
- filename: glean-tools-api-openapi.yml
  format: yaml
  label: Glean Tools API
  slug: glean-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/glean/openapi/glean-tools-api-openapi.yml
- filename: glean-verification-api-openapi.yml
  format: yaml
  label: Glean Verification API
  slug: glean-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/glean/openapi/glean-verification-api-openapi.yml
claim_count: 6
description: ''
doc:
  attestations:
  - framework: ISO42001
    issuer: null
    period: null
    report_access: unstated
    scope: Glean
    text: ISO 42001
    type: compliance listing
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Glean
    text: HIPAA
    type: compliance listing
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Glean
    text: TX-RAMP Level 2
    type: compliance listing (TX-RAMP Level 2)
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Glean
    text: SOC 2 Type II
    type: compliance listing (Type II)
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Glean
    text: ISO 27001
    type: compliance listing
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Glean
    text: GDPR
    type: compliance listing
  trust_center:
    url: https://www.glean.com/platform/security
frameworks:
- GDPR
- HIPAA
- ISO27001
- ISO42001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Glean
provenance_date: '2026-11-09'
provider_name: Glean
provider_slug: glean
slug: glean-compliance
source_date: '2026-11-09'
source_filename: glean-compliance.yml
source_heading: Compliance
source_page: https://www.glean.com/platform/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Glean\naid: glean\nurl: https://www.glean.com/platform/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/glean-trust-center.yml\ntrust_center:\n  url: https://www.glean.com/platform/security\nattestations:\n- framework: ISO42001\n  type: compliance listing\n  scope: Glean\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 42001\n- framework: HIPAA\n  type: compliance listing\n  scope: Glean\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA\n- framework: other\n  type: compliance listing (TX-RAMP Level 2)\n  scope: Glean\n  period: null\n  issuer:\
  \ null\n  report_access: unstated\n  text: TX-RAMP Level 2\n- framework: SOC2\n  type: compliance listing (Type II)\n  scope: Glean\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II\n- framework: ISO27001\n  type: compliance listing\n  scope: Glean\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001\n- framework: GDPR\n  type: compliance listing\n  scope: Glean\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n"
source_yaml_url: https://artifacts.apis.io/glean/compliance/glean-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from Glean's own page on 2026-11-09.
synthetic: false
tags:
- Agents
- Artificial Intelligence
- Answers
- Chat
- Connectors
- Enterprise Search
- Generative AI
- Indexing
- Knowledge
- RAG
- Search
- Work Assistant
- Knowledge Management
---
