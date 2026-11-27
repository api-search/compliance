---
api_specs:
- filename: propelauth-api-keys-api-openapi.yml
  format: yaml
  label: PropelAuth End-User API Keys API
  slug: propelauth-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propelauth/openapi/propelauth-api-keys-api-openapi.yml
- filename: propelauth-access-tokens-api-openapi.yml
  format: yaml
  label: PropelAuth Access Tokens API
  slug: propelauth-access-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propelauth/openapi/propelauth-access-tokens-api-openapi.yml
- filename: propelauth-discovery-api-openapi.yml
  format: yaml
  label: PropelAuth Discovery API
  slug: propelauth-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propelauth/openapi/propelauth-discovery-api-openapi.yml
- filename: propelauth-dynamic-client-registration-api-openapi.yml
  format: yaml
  label: PropelAuth Dynamic Client Registration API
  slug: propelauth-dynamic-client-registration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propelauth/openapi/propelauth-dynamic-client-registration-api-openapi.yml
- filename: propelauth-employees-api-openapi.yml
  format: yaml
  label: PropelAuth Employees API
  slug: propelauth-employees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propelauth/openapi/propelauth-employees-api-openapi.yml
- filename: propelauth-invites-api-openapi.yml
  format: yaml
  label: PropelAuth Invites API
  slug: propelauth-invites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propelauth/openapi/propelauth-invites-api-openapi.yml
- filename: propelauth-magic-links-api-openapi.yml
  format: yaml
  label: PropelAuth Magic Links API
  slug: propelauth-magic-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propelauth/openapi/propelauth-magic-links-api-openapi.yml
- filename: propelauth-mcp-oauth-2-1-api-openapi.yml
  format: yaml
  label: PropelAuth MCP OAuth 2.1 API
  slug: propelauth-mcp-oauth-2-1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propelauth/openapi/propelauth-mcp-oauth-2-1-api-openapi.yml
- filename: propelauth-members-api-openapi.yml
  format: yaml
  label: PropelAuth Members API
  slug: propelauth-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propelauth/openapi/propelauth-members-api-openapi.yml
- filename: propelauth-metadata-api-openapi.yml
  format: yaml
  label: PropelAuth Metadata API
  slug: propelauth-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propelauth/openapi/propelauth-metadata-api-openapi.yml
- filename: propelauth-migration-api-openapi.yml
  format: yaml
  label: PropelAuth Migration API
  slug: propelauth-migration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propelauth/openapi/propelauth-migration-api-openapi.yml
- filename: propelauth-organizations-api-openapi.yml
  format: yaml
  label: PropelAuth Organizations API
  slug: propelauth-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propelauth/openapi/propelauth-organizations-api-openapi.yml
- filename: propelauth-role-mappings-api-openapi.yml
  format: yaml
  label: PropelAuth Role Mappings API
  slug: propelauth-role-mappings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propelauth/openapi/propelauth-role-mappings-api-openapi.yml
- filename: propelauth-sessions-api-openapi.yml
  format: yaml
  label: PropelAuth Sessions API
  slug: propelauth-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propelauth/openapi/propelauth-sessions-api-openapi.yml
- filename: propelauth-usage-api-openapi.yml
  format: yaml
  label: PropelAuth Usage API
  slug: propelauth-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propelauth/openapi/propelauth-usage-api-openapi.yml
- filename: propelauth-users-api-openapi.yml
  format: yaml
  label: PropelAuth Users API
  slug: propelauth-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propelauth/openapi/propelauth-users-api-openapi.yml
- filename: propelauth-validation-api-openapi.yml
  format: yaml
  label: PropelAuth Validation API
  slug: propelauth-validation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propelauth/openapi/propelauth-validation-api-openapi.yml
- filename: propelauth-oauth2-api-openapi.yml
  format: yaml
  label: PropelAuth O Auth2 API
  slug: propelauth-oauth2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propelauth/openapi/propelauth-oauth2-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: external audit
    period: null
    report_access: on_request
    scope: null
    text: PropelAuth is certified as SOC2 Type 2 compliant, following an external audit.
    type: SOC 2 Type 2
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We can sign DPAs with companies with GDPR concerns.
    type: DPA available
  trust_center:
    url: https://www.propelauth.com/security
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: PropelAuth
provenance_date: '2026-11-10'
provider_name: PropelAuth
provider_slug: propelauth
slug: propelauth-compliance
source_date: '2026-11-10'
source_filename: propelauth-compliance.yml
source_heading: Compliance
source_page: https://www.propelauth.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: PropelAuth\naid: propelauth\nurl: https://www.propelauth.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/propelauth-trust-center.yml\ntrust_center:\n  url: https://www.propelauth.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2\n  scope: null\n  period: null\n  issuer: external audit\n  report_access: on_request\n  text: PropelAuth is certified as SOC2 Type 2 compliant, following an external audit.\n- framework: GDPR\n  type: DPA available\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We can sign DPAs with companies with GDPR concerns.\n"
source_yaml_url: https://artifacts.apis.io/propelauth/compliance/propelauth-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from PropelAuth's own page on 2026-11-10.
synthetic: false
tags:
- Authentication
- Identity
- B2B
- Multi-Tenancy
- Authorization
- RBAC
- SSO
- SCIM
- MCP
- APIKeys
- Identity Federation
---
