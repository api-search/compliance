---
api_specs:
- filename: gumloop-agents-api-openapi.yml
  format: yaml
  label: Gumloop Agents API
  slug: gumloop-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gumloop/openapi/gumloop-agents-api-openapi.yml
- filename: gumloop-artifacts-api-openapi.yml
  format: yaml
  label: Gumloop Artifacts API
  slug: gumloop-artifacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gumloop/openapi/gumloop-artifacts-api-openapi.yml
- filename: gumloop-brain-api-openapi.yml
  format: yaml
  label: Gumloop Brain API
  slug: gumloop-brain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gumloop/openapi/gumloop-brain-api-openapi.yml
- filename: gumloop-chat-completions-api-openapi.yml
  format: yaml
  label: Gumloop Chat completions API
  slug: gumloop-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gumloop/openapi/gumloop-chat-completions-api-openapi.yml
- filename: gumloop-data-access-api-openapi.yml
  format: yaml
  label: Gumloop Data Access API
  slug: gumloop-data-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gumloop/openapi/gumloop-data-access-api-openapi.yml
- filename: gumloop-evaluations-api-openapi.yml
  format: yaml
  label: Gumloop Evaluations API
  slug: gumloop-evaluations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gumloop/openapi/gumloop-evaluations-api-openapi.yml
- filename: gumloop-execution-api-openapi.yml
  format: yaml
  label: Gumloop Execution API
  slug: gumloop-execution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gumloop/openapi/gumloop-execution-api-openapi.yml
- filename: gumloop-file-handling-api-openapi.yml
  format: yaml
  label: Gumloop File Handling API
  slug: gumloop-file-handling-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gumloop/openapi/gumloop-file-handling-api-openapi.yml
- filename: gumloop-mcp-api-openapi.yml
  format: yaml
  label: Gumloop MCP API
  slug: gumloop-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gumloop/openapi/gumloop-mcp-api-openapi.yml
- filename: gumloop-models-api-openapi.yml
  format: yaml
  label: Gumloop Models API
  slug: gumloop-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gumloop/openapi/gumloop-models-api-openapi.yml
- filename: gumloop-organization-api-openapi.yml
  format: yaml
  label: Gumloop Organization API
  slug: gumloop-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gumloop/openapi/gumloop-organization-api-openapi.yml
- filename: gumloop-sessions-api-openapi.yml
  format: yaml
  label: Gumloop Sessions API
  slug: gumloop-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gumloop/openapi/gumloop-sessions-api-openapi.yml
- filename: gumloop-skills-api-openapi.yml
  format: yaml
  label: Gumloop Skills API
  slug: gumloop-skills-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gumloop/openapi/gumloop-skills-api-openapi.yml
- filename: gumloop-teams-api-openapi.yml
  format: yaml
  label: Gumloop Teams API
  slug: gumloop-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gumloop/openapi/gumloop-teams-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: October 2025 to April 2026
    report_access: on_request
    scope: null
    text: Gumloop - SOC 2 Type II Audit Report (October 2025 to April 2026) Request access
    type: SOC 2 Type 2 audit report
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type 2 Compliant
    type: SOC 2 Type 2 compliance status
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR Compliant
    type: compliance status
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA Compliant
    type: compliance status
  trust_center:
    url: https://trust.gumloop.com/
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Gumloop
provenance_date: '2026-11-09'
provider_name: Gumloop
provider_slug: gumloop
slug: gumloop-compliance
source_date: '2026-11-09'
source_filename: gumloop-compliance.yml
source_heading: Compliance
source_page: https://trust.gumloop.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Gumloop\naid: gumloop\nurl: https://trust.gumloop.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.gumloop.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 audit report\n  scope: null\n  period: October 2025 to April 2026\n  issuer: null\n  report_access: on_request\n  text: Gumloop - SOC 2 Type II Audit Report (October 2025 to April 2026) Request access\n- framework: SOC2\n  type: SOC 2 Type 2 compliance status\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2 Compliant\n- framework: GDPR\n  type: compliance status\n  scope: null\n\
  \  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR Compliant\n- framework: HIPAA\n  type: compliance status\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA Compliant\n"
source_yaml_url: https://artifacts.apis.io/gumloop/compliance/gumloop-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Gumloop's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Automation
- Workflow Automation
- Agent Platform
- MCP
- LLM
- No-Code
- Developer Tools
---
