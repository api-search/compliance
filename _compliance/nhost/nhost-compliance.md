---
api_specs:
- filename: nhost-authentication-api-openapi.yml
  format: yaml
  label: Nhost Authentication API
  slug: nhost-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nhost/openapi/nhost-authentication-api-openapi.yml
- filename: nhost-documentation-api-openapi.yml
  format: yaml
  label: Nhost Documentation API
  slug: nhost-documentation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nhost/openapi/nhost-documentation-api-openapi.yml
- filename: nhost-excludeme-api-openapi.yml
  format: yaml
  label: Nhost Excludeme API
  slug: nhost-excludeme-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nhost/openapi/nhost-excludeme-api-openapi.yml
- filename: nhost-files-api-openapi.yml
  format: yaml
  label: Nhost Files API
  slug: nhost-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nhost/openapi/nhost-files-api-openapi.yml
- filename: nhost-operations-api-openapi.yml
  format: yaml
  label: Nhost Operations API
  slug: nhost-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nhost/openapi/nhost-operations-api-openapi.yml
- filename: nhost-security-api-openapi.yml
  format: yaml
  label: Nhost Security API
  slug: nhost-security-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nhost/openapi/nhost-security-api-openapi.yml
- filename: nhost-session-api-openapi.yml
  format: yaml
  label: Nhost Session API
  slug: nhost-session-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nhost/openapi/nhost-session-api-openapi.yml
- filename: nhost-storage-api-openapi.yml
  format: yaml
  label: Nhost Storage API
  slug: nhost-storage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nhost/openapi/nhost-storage-api-openapi.yml
- filename: nhost-system-api-openapi.yml
  format: yaml
  label: Nhost System API
  slug: nhost-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nhost/openapi/nhost-system-api-openapi.yml
- filename: nhost-user-api-openapi.yml
  format: yaml
  label: Nhost User API
  slug: nhost-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nhost/openapi/nhost-user-api-openapi.yml
- filename: nhost-verification-api-openapi.yml
  format: yaml
  label: Nhost Verification API
  slug: nhost-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nhost/openapi/nhost-verification-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: Nhost platform security controls and data handling practices
    text: Team & Enterprise customers have access to our SOC 2 report directly through the Nhost Dashboard
    type: Type II
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Storage of Protected Health Information (PHI) on hosted platform
    text: Nhost is working towards HIPAA compliance.
    type: compliance in progress
  trust_center:
    url: https://nhost.io/security
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Nhost
provenance_date: '2026-11-10'
provider_name: Nhost
provider_slug: nhost
slug: nhost-compliance
source_date: '2026-11-10'
source_filename: nhost-compliance.yml
source_heading: Compliance
source_page: https://nhost.io/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Nhost\naid: nhost\nurl: https://nhost.io/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/nhost-trust-center.yml\ntrust_center:\n  url: https://nhost.io/security\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: Nhost platform security controls and data handling practices\n  period: null\n  issuer: null\n  report_access: nda\n  text: Team & Enterprise customers have access to our SOC 2 report directly through the Nhost Dashboard\n- framework: HIPAA\n  type: compliance in progress\n  scope: Storage of Protected Health Information (PHI) on hosted platform\n  period: null\n  issuer:\
  \ null\n  report_access: unstated\n  text: Nhost is working towards HIPAA compliance.\n"
source_yaml_url: https://artifacts.apis.io/nhost/compliance/nhost-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Nhost's own page on 2026-11-10.
synthetic: false
tags:
- GraphQL
- PostgreSQL
- Authentication
- File Storage
- Serverless Functions
- Real-Time
- Open Source
- Firebase Alternative
- Backend-as-a-Service
- Passwordless
---
