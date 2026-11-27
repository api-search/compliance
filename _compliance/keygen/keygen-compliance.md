---
api_specs:
- filename: keygen-artifacts-api-openapi.yml
  format: yaml
  label: Keygen Artifacts API
  slug: keygen-artifacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keygen/openapi/keygen-artifacts-api-openapi.yml
- filename: keygen-components-api-openapi.yml
  format: yaml
  label: Keygen Components API
  slug: keygen-components-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keygen/openapi/keygen-components-api-openapi.yml
- filename: keygen-entitlements-api-openapi.yml
  format: yaml
  label: Keygen Entitlements API
  slug: keygen-entitlements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keygen/openapi/keygen-entitlements-api-openapi.yml
- filename: keygen-licenses-api-openapi.yml
  format: yaml
  label: Keygen Licenses API
  slug: keygen-licenses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keygen/openapi/keygen-licenses-api-openapi.yml
- filename: keygen-machines-api-openapi.yml
  format: yaml
  label: Keygen Machines API
  slug: keygen-machines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keygen/openapi/keygen-machines-api-openapi.yml
- filename: keygen-policies-api-openapi.yml
  format: yaml
  label: Keygen Policies API
  slug: keygen-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keygen/openapi/keygen-policies-api-openapi.yml
- filename: keygen-processes-api-openapi.yml
  format: yaml
  label: Keygen Processes API
  slug: keygen-processes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keygen/openapi/keygen-processes-api-openapi.yml
- filename: keygen-products-api-openapi.yml
  format: yaml
  label: Keygen Products API
  slug: keygen-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keygen/openapi/keygen-products-api-openapi.yml
- filename: keygen-releases-api-openapi.yml
  format: yaml
  label: Keygen Releases API
  slug: keygen-releases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keygen/openapi/keygen-releases-api-openapi.yml
- filename: keygen-tokens-api-openapi.yml
  format: yaml
  label: Keygen Tokens API
  slug: keygen-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keygen/openapi/keygen-tokens-api-openapi.yml
- filename: keygen-users-api-openapi.yml
  format: yaml
  label: Keygen Users API
  slug: keygen-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keygen/openapi/keygen-users-api-openapi.yml
- filename: keygen-webhooks-api-openapi.yml
  format: yaml
  label: Keygen Webhooks API
  slug: keygen-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keygen/openapi/keygen-webhooks-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Keygen cloud service
    text: We are SOC 2 Type II compliant.
    type: Type II
  trust_center:
    url: https://keygen.sh/security/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Keygen
provenance_date: '2026-11-09'
provider_name: Keygen
provider_slug: keygen
slug: keygen-compliance
source_date: '2026-11-09'
source_filename: keygen-compliance.yml
source_heading: Compliance
source_page: https://keygen.sh/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Keygen\naid: keygen\nurl: https://keygen.sh/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/keygen-trust-center.yml\ntrust_center:\n  url: https://keygen.sh/security/\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: Keygen cloud service\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We are SOC 2 Type II compliant.\n"
source_yaml_url: https://artifacts.apis.io/keygen/compliance/keygen-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Keygen's own page on 2026-11-09.
synthetic: false
tags:
- Software Licensing
- Entitlements
- License Keys
- Machine Activation
- Distribution
- Auto-Update
---
