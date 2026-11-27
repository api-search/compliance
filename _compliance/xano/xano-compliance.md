---
api_specs:
- filename: xano-api-groups-api-openapi.yml
  format: yaml
  label: Xano API Groups API
  slug: xano-api-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xano/openapi/xano-api-groups-api-openapi.yml
- filename: xano-auth-api-openapi.yml
  format: yaml
  label: Xano Auth API
  slug: xano-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xano/openapi/xano-auth-api-openapi.yml
- filename: xano-content-api-openapi.yml
  format: yaml
  label: Xano Content API
  slug: xano-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xano/openapi/xano-content-api-openapi.yml
- filename: xano-files-api-openapi.yml
  format: yaml
  label: Xano Files API
  slug: xano-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xano/openapi/xano-files-api-openapi.yml
- filename: xano-tables-api-openapi.yml
  format: yaml
  label: Xano Tables API
  slug: xano-tables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xano/openapi/xano-tables-api-openapi.yml
- filename: xano-workspace-api-openapi.yml
  format: yaml
  label: Xano Workspace API
  slug: xano-workspace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xano/openapi/xano-workspace-api-openapi.yml
claim_count: 9
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II
    type: SOC 2 Type II
  - framework: SOC3
    issuer: null
    period: null
    report_access: public
    scope: null
    text: SOC 3 Type II
    type: SOC 3 Type II
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001
    type: ISO 27001
  - framework: ISO27701
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27701
    type: ISO 27701
  - framework: ISO9001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 9001
    type: ISO 9001
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: GDPR
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA
    type: HIPAA
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HDS
    type: HDS
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: DPF
    type: DPF
  trust_center:
    url: https://security.xano.com/
frameworks:
- GDPR
- HIPAA
- ISO27001
- ISO27701
- ISO9001
- SOC2
- SOC3
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Xano
provenance_date: '2026-11-10'
provider_name: Xano
provider_slug: xano
slug: xano-compliance
source_date: '2026-11-10'
source_filename: xano-compliance.yml
source_heading: Compliance
source_page: https://security.xano.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Xano\naid: xano\nurl: https://security.xano.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/xano-trust-center.yml\ntrust_center:\n  url: https://security.xano.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II\n- framework: SOC3\n  type: SOC 3 Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: public\n  text: SOC 3 Type II\n- framework: ISO27001\n  type: ISO 27001\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001\n- framework:\
  \ ISO27701\n  type: ISO 27701\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27701\n- framework: ISO9001\n  type: ISO 9001\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 9001\n- framework: GDPR\n  type: GDPR\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: HIPAA\n  type: HIPAA\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA\n- framework: other\n  type: HDS\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HDS\n- framework: other\n  type: DPF\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: DPF\n"
source_yaml_url: https://artifacts.apis.io/xano/compliance/xano-compliance.yml
stated_fields:
- attestations
summary_line: 9 quoted statements, read from Xano's own page on 2026-11-10.
synthetic: false
tags:
- No-Code
- Backend-as-a-Service
- API Builder
- Database
- Serverless
---
