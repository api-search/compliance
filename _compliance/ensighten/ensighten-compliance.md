---
api_specs:
- filename: ensighten-authentication-api-openapi.yml
  format: yaml
  label: Ensighten Authentication API
  slug: ensighten-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ensighten/openapi/ensighten-authentication-api-openapi.yml
- filename: ensighten-conditions-api-openapi.yml
  format: yaml
  label: Ensighten Conditions API
  slug: ensighten-conditions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ensighten/openapi/ensighten-conditions-api-openapi.yml
- filename: ensighten-data-definitions-api-openapi.yml
  format: yaml
  label: Ensighten Data Definitions API
  slug: ensighten-data-definitions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ensighten/openapi/ensighten-data-definitions-api-openapi.yml
- filename: ensighten-deployments-api-openapi.yml
  format: yaml
  label: Ensighten Deployments API
  slug: ensighten-deployments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ensighten/openapi/ensighten-deployments-api-openapi.yml
- filename: ensighten-event-definitions-api-openapi.yml
  format: yaml
  label: Ensighten Event Definitions API
  slug: ensighten-event-definitions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ensighten/openapi/ensighten-event-definitions-api-openapi.yml
- filename: ensighten-git-api-openapi.yml
  format: yaml
  label: Ensighten GIT API
  slug: ensighten-git-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ensighten/openapi/ensighten-git-api-openapi.yml
- filename: ensighten-labels-api-openapi.yml
  format: yaml
  label: Ensighten Labels API
  slug: ensighten-labels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ensighten/openapi/ensighten-labels-api-openapi.yml
- filename: ensighten-publish-paths-api-openapi.yml
  format: yaml
  label: Ensighten Publish Paths API
  slug: ensighten-publish-paths-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ensighten/openapi/ensighten-publish-paths-api-openapi.yml
- filename: ensighten-roles-api-openapi.yml
  format: yaml
  label: Ensighten Roles API
  slug: ensighten-roles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ensighten/openapi/ensighten-roles-api-openapi.yml
- filename: ensighten-scim-2-0-api-openapi.yml
  format: yaml
  label: Ensighten SCIM 2.0 API
  slug: ensighten-scim-2-0-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ensighten/openapi/ensighten-scim-2-0-api-openapi.yml
- filename: ensighten-spaces-api-openapi.yml
  format: yaml
  label: Ensighten Spaces API
  slug: ensighten-spaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ensighten/openapi/ensighten-spaces-api-openapi.yml
- filename: ensighten-tdn-api-openapi.yml
  format: yaml
  label: Ensighten TDN API
  slug: ensighten-tdn-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ensighten/openapi/ensighten-tdn-api-openapi.yml
- filename: ensighten-users-api-openapi.yml
  format: yaml
  label: Ensighten Users API
  slug: ensighten-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ensighten/openapi/ensighten-users-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: security, engineering and compliance controls
    text: maintain controls that meet leading industry standards, including SOC 2 Type II, ISO 27001, ISO 27701 and ISO 42001
    type: SOC 2 Type II
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: security, engineering and compliance controls
    text: maintain controls that meet leading industry standards, including SOC 2 Type II, ISO 27001, ISO 27701 and ISO 42001
    type: ISO/IEC 27001
  - framework: ISO27701
    issuer: null
    period: null
    report_access: unstated
    scope: security, engineering and compliance controls
    text: maintain controls that meet leading industry standards, including SOC 2 Type II, ISO 27001, ISO 27701 and ISO 42001
    type: ISO/IEC 27701
  - framework: ISO42001
    issuer: null
    period: null
    report_access: unstated
    scope: security, engineering and compliance controls
    text: maintain controls that meet leading industry standards, including SOC 2 Type II, ISO 27001, ISO 27701 and ISO 42001
    type: ISO/IEC 42001
  trust_center:
    url: https://cheq.ai/trust/
frameworks:
- ISO27001
- ISO27701
- ISO42001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Ensighten
provenance_date: '2026-11-09'
provider_name: Ensighten
provider_slug: ensighten
slug: ensighten-compliance
source_date: '2026-11-09'
source_filename: ensighten-compliance.yml
source_heading: Compliance
source_page: https://cheq.ai/trust/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Ensighten\naid: ensighten\nurl: https://cheq.ai/trust/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://cheq.ai/trust/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: security, engineering and compliance controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: maintain controls that meet leading industry standards, including SOC 2 Type II, ISO 27001, ISO 27701 and\n    ISO 42001\n- framework: ISO27001\n  type: ISO/IEC 27001\n  scope: security, engineering and compliance controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: maintain controls\
  \ that meet leading industry standards, including SOC 2 Type II, ISO 27001, ISO 27701 and\n    ISO 42001\n- framework: ISO27701\n  type: ISO/IEC 27701\n  scope: security, engineering and compliance controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: maintain controls that meet leading industry standards, including SOC 2 Type II, ISO 27001, ISO 27701 and\n    ISO 42001\n- framework: ISO42001\n  type: ISO/IEC 42001\n  scope: security, engineering and compliance controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: maintain controls that meet leading industry standards, including SOC 2 Type II, ISO 27001, ISO 27701 and\n    ISO 42001\n"
source_yaml_url: https://artifacts.apis.io/ensighten/compliance/ensighten-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Ensighten's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- Tag Management
- Data Governance
- Client-Side Security
- Consent Management
- Privacy Compliance
- Marketing Technology
---
