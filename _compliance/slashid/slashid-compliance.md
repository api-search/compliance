---
api_specs:
- filename: slashid-identity-management-api-openapi.yml
  format: yaml
  label: SlashID Identity Management API
  slug: slashid-identity-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slashid/openapi/slashid-identity-management-api-openapi.yml
- filename: slashid-oidc-discovery-api-openapi.yml
  format: yaml
  label: SlashID OIDC discovery API
  slug: slashid-oidc-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slashid/openapi/slashid-oidc-discovery-api-openapi.yml
- filename: slashid-organization-sso-config-api-openapi.yml
  format: yaml
  label: SlashID Organization SSO config API
  slug: slashid-organization-sso-config-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slashid/openapi/slashid-organization-sso-config-api-openapi.yml
- filename: slashid-organization-webhooks-api-openapi.yml
  format: yaml
  label: SlashID Organization Webhooks API
  slug: slashid-organization-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slashid/openapi/slashid-organization-webhooks-api-openapi.yml
- filename: slashid-super-admin-management-api-openapi.yml
  format: yaml
  label: SlashID Super Admin Management API
  slug: slashid-super-admin-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slashid/openapi/slashid-super-admin-management-api-openapi.yml
- filename: slashid-tokens-api-openapi.yml
  format: yaml
  label: SlashID Tokens API
  slug: slashid-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slashid/openapi/slashid-tokens-api-openapi.yml
- filename: slashid-workflows-api-openapi.yml
  format: yaml
  label: SlashID Workflows API
  slug: slashid-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slashid/openapi/slashid-workflows-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: platform environment and team
    text: SOC 2 Type II Certified
    type: Type II
  trust_center:
    url: https://www.slashid.dev/security/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: SlashID
provenance_date: '2026-11-10'
provider_name: SlashID
provider_slug: slashid
slug: slashid-compliance
source_date: '2026-11-10'
source_filename: slashid-compliance.yml
source_heading: Compliance
source_page: https://www.slashid.dev/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: SlashID\naid: slashid\nurl: https://www.slashid.dev/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/slashid-trust-center.yml\ntrust_center:\n  url: https://www.slashid.dev/security/\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: platform environment and team\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II Certified\n"
source_yaml_url: https://artifacts.apis.io/slashid/compliance/slashid-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from SlashID's own page on 2026-11-10.
synthetic: false
tags:
- Identity
- Authentication
- Passwordless
- MFA
- Passkeys
- User Management
- CIAM
- OAuth
- OpenID Connect
- SSO
- RBAC
- Security
---
