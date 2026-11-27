---
api_specs:
- filename: capy-automations-api-openapi.yml
  format: yaml
  label: Capy Automations API
  slug: capy-automations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-automations-api-openapi.yml
- filename: capy-projects-api-openapi.yml
  format: yaml
  label: Capy Projects API
  slug: capy-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-projects-api-openapi.yml
- filename: capy-tasks-api-openapi.yml
  format: yaml
  label: Capy Tasks API
  slug: capy-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-tasks-api-openapi.yml
- filename: capy-threads-api-openapi.yml
  format: yaml
  label: Capy Threads API
  slug: capy-threads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-threads-api-openapi.yml
- filename: capy-usage-api-openapi.yml
  format: yaml
  label: Capy Usage API
  slug: capy-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-usage-api-openapi.yml
- filename: capy-captains-api-openapi.yml
  format: yaml
  label: Capy Captains API
  slug: capy-captains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-captains-api-openapi.yml
- filename: capy-folders-api-openapi.yml
  format: yaml
  label: Capy Folders API
  slug: capy-folders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-folders-api-openapi.yml
- filename: capy-messages-api-openapi.yml
  format: yaml
  label: Capy Messages API
  slug: capy-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-messages-api-openapi.yml
- filename: capy-reviewfilters-api-openapi.yml
  format: yaml
  label: Capy Review Filters API
  slug: capy-reviewfilters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-reviewfilters-api-openapi.yml
- filename: capy-reviewrules-api-openapi.yml
  format: yaml
  label: Capy Review Rules API
  slug: capy-reviewrules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-reviewrules-api-openapi.yml
- filename: capy-reviews-api-openapi.yml
  format: yaml
  label: Capy Reviews API
  slug: capy-reviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-reviews-api-openapi.yml
- filename: capy-streams-api-openapi.yml
  format: yaml
  label: Capy Streams API
  slug: capy-streams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-streams-api-openapi.yml
- filename: capy-subagents-api-openapi.yml
  format: yaml
  label: Capy Subagents API
  slug: capy-subagents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-subagents-api-openapi.yml
- filename: capy-users-api-openapi.yml
  format: yaml
  label: Capy Users API
  slug: capy-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-users-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type 2 Compliant
    type: Type 2
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: security, availability, and confidentiality controls
    source: https://capy.ai/security
    text: Yes. Capy is SOC 2 Type II compliant. Our controls are independently audited for security, availability, and confidentiality, and the report is available from our Trust Center at trust.capy.ai.
    type: SOC 2 Type II
  trust_center:
    url: https://trust.capy.ai/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Capy
provenance_date: '2026-11-09'
provider_name: Capy
provider_slug: capy
slug: capy-compliance
source_date: '2026-11-09'
source_filename: capy-compliance.yml
source_heading: Compliance
source_page: https://trust.capy.ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Capy\naid: capy\nurl: https://trust.capy.ai/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/capy-trust-center.yml\n  sources:\n  - https://capy.ai/security\n  - https://trust.capy.ai/\ntrust_center:\n  url: https://trust.capy.ai/\nattestations:\n- framework: SOC2\n  type: Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2 Compliant\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: security, availability, and confidentiality controls\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Yes. Capy is SOC 2 Type II compliant. Our controls\
  \ are independently audited for security, availability,\n    and confidentiality, and the report is available from our Trust Center at trust.capy.ai.\n  source: https://capy.ai/security\n"
source_yaml_url: https://artifacts.apis.io/capy/compliance/capy-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Capy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Coding Agents
- Software Engineering
- Developer Tools
- Automation
- Code Review
- DevOps
---
