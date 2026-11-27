---
api_specs:
- filename: oso-centralized-authorization-data-api-openapi.yml
  format: yaml
  label: Oso Cloud Centralized Authorization Data API
  slug: oso-centralized-authorization-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oso/openapi/oso-centralized-authorization-data-api-openapi.yml
- filename: oso-check-api-api-openapi.yml
  format: yaml
  label: Oso Cloud Check API
  slug: oso-check-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oso/openapi/oso-check-api-api-openapi.yml
- filename: oso-local-check-api-api-openapi.yml
  format: yaml
  label: Oso Cloud Local Check API
  slug: oso-local-check-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oso/openapi/oso-local-check-api-api-openapi.yml
- filename: oso-policy-api-openapi.yml
  format: yaml
  label: Oso Cloud Policy API
  slug: oso-policy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oso/openapi/oso-policy-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Oso Cloud
    text: Oso is SOC 2 certified.
    type: certification
  trust_center:
    url: https://www.osohq.com/company/security
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Oso Cloud
provenance_date: '2026-11-10'
provider_name: Oso Cloud
provider_slug: oso
slug: oso-compliance
source_date: '2026-11-10'
source_filename: oso-compliance.yml
source_heading: Compliance
source_page: https://www.osohq.com/company/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Oso Cloud\naid: oso\nurl: https://www.osohq.com/company/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/oso-trust-center.yml\ntrust_center:\n  url: https://www.osohq.com/company/security\nattestations:\n- framework: SOC2\n  type: certification\n  scope: Oso Cloud\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Oso is SOC 2 certified.\n"
source_yaml_url: https://artifacts.apis.io/oso/compliance/oso-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Oso Cloud's own page on 2026-11-10.
synthetic: false
tags:
- Authorization
- Access Control
- RBAC
- ReBAC
- ABAC
- Permissions
- Policy
- Security
- Identity
---
