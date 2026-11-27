---
api_specs:
- filename: gitclear-api-tokens-api-openapi.yml
  format: yaml
  label: GitClear API Tokens API
  slug: gitclear-api-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gitclear/openapi/gitclear-api-tokens-api-openapi.yml
- filename: gitclear-code-introspection-api-openapi.yml
  format: yaml
  label: GitClear Code Introspection API
  slug: gitclear-code-introspection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gitclear/openapi/gitclear-code-introspection-api-openapi.yml
- filename: gitclear-data-audit-api-openapi.yml
  format: yaml
  label: GitClear Data Audit API
  slug: gitclear-data-audit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gitclear/openapi/gitclear-data-audit-api-openapi.yml
- filename: gitclear-developers-api-openapi.yml
  format: yaml
  label: GitClear Developers API
  slug: gitclear-developers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gitclear/openapi/gitclear-developers-api-openapi.yml
- filename: gitclear-imports-api-openapi.yml
  format: yaml
  label: GitClear Imports API
  slug: gitclear-imports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gitclear/openapi/gitclear-imports-api-openapi.yml
- filename: gitclear-releases-api-openapi.yml
  format: yaml
  label: GitClear Releases API
  slug: gitclear-releases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gitclear/openapi/gitclear-releases-api-openapi.yml
- filename: gitclear-reports-api-openapi.yml
  format: yaml
  label: GitClear Reports API
  slug: gitclear-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gitclear/openapi/gitclear-reports-api-openapi.yml
- filename: gitclear-teams-api-openapi.yml
  format: yaml
  label: GitClear Teams API
  slug: gitclear-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gitclear/openapi/gitclear-teams-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: Laika Compliance
    period: null
    report_access: on_request
    scope: unstated
    text: GitClear is officially certified against ISO/IEC 27001:2022 , as well as SOC2 (Type 1 and 2)
    type: Type 1 and 2 certification
  - framework: ISO27001
    issuer: Johanson Group LLP
    period: null
    report_access: public
    scope: unstated
    text: View GitClear's ISO/IEC 27001:2022 certificate
    type: certification (ISO/IEC 27001:2022)
  - framework: other
    issuer: unstated
    period: null
    report_access: on_request
    scope: application security
    text: GitClear has submitted and passed the Google Vendor Self-Assessment Quiz
    type: Google Vendor Self-Assessment Quiz (passed)
  trust_center:
    url: https://www.gitclear.com/security
frameworks:
- ISO27001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: GitClear
provenance_date: '2026-11-09'
provider_name: GitClear
provider_slug: gitclear
slug: gitclear-compliance
source_date: '2026-11-09'
source_filename: gitclear-compliance.yml
source_heading: Compliance
source_page: https://www.gitclear.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: GitClear\naid: gitclear\nurl: https://www.gitclear.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/gitclear-trust-center.yml\ntrust_center:\n  url: https://www.gitclear.com/security\nattestations:\n- framework: SOC2\n  type: Type 1 and 2 certification\n  scope: unstated\n  period: null\n  issuer: Laika Compliance\n  report_access: on_request\n  text: GitClear is officially certified against ISO/IEC 27001:2022 , as well as SOC2 (Type 1 and 2)\n- framework: ISO27001\n  type: certification (ISO/IEC 27001:2022)\n  scope: unstated\n  period: null\n  issuer: Johanson Group LLP\n  report_access:\
  \ public\n  text: View GitClear's ISO/IEC 27001:2022 certificate\n- framework: other\n  type: Google Vendor Self-Assessment Quiz (passed)\n  scope: application security\n  period: null\n  issuer: unstated\n  report_access: on_request\n  text: GitClear has submitted and passed the Google Vendor Self-Assessment Quiz\n"
source_yaml_url: https://artifacts.apis.io/gitclear/compliance/gitclear-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from GitClear's own page on 2026-11-09.
synthetic: false
tags:
- Code Analytics
- Commit Analytics
- Developer Productivity
- Diff Delta
- Engineering Metrics
---
