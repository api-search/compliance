---
api_specs:
- filename: workato-data-tables-api-openapi.yml
  format: yaml
  label: Workato Data Tables API
  slug: workato-data-tables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workato/openapi/workato-data-tables-api-openapi.yml
- filename: workato-genies-api-openapi.yml
  format: yaml
  label: Workato Genies API
  slug: workato-genies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workato/openapi/workato-genies-api-openapi.yml
- filename: workato-knowledge-bases-api-openapi.yml
  format: yaml
  label: Workato Knowledge Bases API
  slug: workato-knowledge-bases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workato/openapi/workato-knowledge-bases-api-openapi.yml
- filename: workato-mcp-servers-api-openapi.yml
  format: yaml
  label: Workato MCP Servers API
  slug: workato-mcp-servers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workato/openapi/workato-mcp-servers-api-openapi.yml
- filename: workato-messages-api-openapi.yml
  format: yaml
  label: Workato Messages API
  slug: workato-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workato/openapi/workato-messages-api-openapi.yml
- filename: workato-policies-api-openapi.yml
  format: yaml
  label: Workato Policies API
  slug: workato-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workato/openapi/workato-policies-api-openapi.yml
- filename: workato-recipes-api-openapi.yml
  format: yaml
  label: Workato Recipes API
  slug: workato-recipes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workato/openapi/workato-recipes-api-openapi.yml
- filename: workato-skills-api-openapi.yml
  format: yaml
  label: Workato Skills API
  slug: workato-skills-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workato/openapi/workato-skills-api-openapi.yml
- filename: workato-tools-api-openapi.yml
  format: yaml
  label: Workato Tools API
  slug: workato-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workato/openapi/workato-tools-api-openapi.yml
- filename: workato-user-groups-api-openapi.yml
  format: yaml
  label: Workato User Groups API
  slug: workato-user-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workato/openapi/workato-user-groups-api-openapi.yml
claim_count: 12
description: ''
doc:
  attestations:
  - framework: SOC1
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 1
    type: null
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2
    type: null
  - framework: SOC3
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 3
    type: null
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA
    type: null
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PCI
    type: null
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: null
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA
    type: null
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001-A
    type: null
  - framework: ISO27701
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27701- A
    type: null
  - framework: ISO42001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 42001-A
    type: null
  - framework: NIST-CSF
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: NIST
    type: null
  - framework: DORA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: DORA
    type: null
  trust_center:
    url: https://trust.workato.com/
frameworks:
- CCPA
- DORA
- GDPR
- HIPAA
- ISO27001
- ISO27701
- ISO42001
- NIST-CSF
- PCI-DSS
- SOC1
- SOC2
- SOC3
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Workato
provenance_date: '2026-11-10'
provider_name: Workato
provider_slug: workato
slug: workato-compliance
source_date: '2026-11-10'
source_filename: workato-compliance.yml
source_heading: Compliance
source_page: https://trust.workato.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Workato\naid: workato\nurl: https://trust.workato.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.workato.com/\nattestations:\n- framework: SOC1\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 1\n- framework: SOC2\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2\n- framework: SOC3\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 3\n- framework: HIPAA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: HIPAA\n- framework: PCI-DSS\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: CCPA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA\n- framework: ISO27001\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001-A\n- framework: ISO27701\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27701- A\n- framework: ISO42001\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 42001-A\n- framework: NIST-CSF\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: NIST\n- framework: DORA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: DORA\n"
source_yaml_url: https://artifacts.apis.io/workato/compliance/workato-compliance.yml
stated_fields:
- attestations
summary_line: 12 quoted statements, read from Workato's own page on 2026-11-10.
synthetic: false
tags:
- AI Agents
- API Management
- Automation
- B2B
- Embedded iPaaS
- Enterprise
- Integration
- iPaaS
- Orchestration
- Workflows
- Workflow Automation
---
