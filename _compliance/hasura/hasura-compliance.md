---
api_specs:
- filename: hasura-asyncapi.yml
  format: yaml
  label: Hasura GraphQL API
  slug: hasura-graphql-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/hasura/asyncapi/hasura-asyncapi.yml
- filename: hasura-healthz-api-openapi.yml
  format: yaml
  label: Hasura Healthz API
  slug: hasura-healthz-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hasura/openapi/hasura-healthz-api-openapi.yml
- filename: hasura-metadata-api-openapi.yml
  format: yaml
  label: Hasura Metadata API
  slug: hasura-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hasura/openapi/hasura-metadata-api-openapi.yml
- filename: hasura-query-api-openapi.yml
  format: yaml
  label: Hasura Query API
  slug: hasura-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hasura/openapi/hasura-query-api-openapi.yml
- filename: hasura-source-health-api-openapi.yml
  format: yaml
  label: Hasura Source Health API
  slug: hasura-source-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hasura/openapi/hasura-source-health-api-openapi.yml
- filename: hasura-v1alpha1-api-openapi.yml
  format: yaml
  label: Hasura V1alpha1 API
  slug: hasura-v1alpha1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hasura/openapi/hasura-v1alpha1-api-openapi.yml
- filename: hasura-v1beta1-api-openapi.yml
  format: yaml
  label: Hasura V1beta1 API
  slug: hasura-v1beta1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hasura/openapi/hasura-v1beta1-api-openapi.yml
- filename: hasura-version-api-openapi.yml
  format: yaml
  label: Hasura Version API
  slug: hasura-version-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hasura/openapi/hasura-version-api-openapi.yml
- filename: hasura-graph-ql-api-openapi.yml
  format: yaml
  label: Hasura Graph QL API
  slug: hasura-graph-ql-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hasura/openapi/hasura-graph-ql-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: Hasura Cloud
    text: Hasura Cloud is SOC 2 Type II Compliant
    type: Type II
  - framework: HIPAA
    issuer: independent third party
    period: null
    report_access: unstated
    scope: Hasura Cloud
    text: Hasura Cloud is HIPAA Compliant
    type: null
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Our offerings
    text: Our offerings are fully GDPR compliant.
    type: null
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Hasura GraphQL Engine
    text: We achieved multi-site certification, covering our primary office locations in San Francisco, United States and Bangalore, India.
    type: multi-site certification
  trust_center:
    url: https://hasura.io/security
frameworks:
- GDPR
- HIPAA
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Hasura
provenance_date: '2026-11-09'
provider_name: Hasura
provider_slug: hasura
slug: hasura-compliance
source_date: '2026-11-09'
source_filename: hasura-compliance.yml
source_heading: Compliance
source_page: https://hasura.io/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Hasura\naid: hasura\nurl: https://hasura.io/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/hasura-trust-center.yml\ntrust_center:\n  url: https://hasura.io/security\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: Hasura Cloud\n  period: null\n  issuer: null\n  report_access: nda\n  text: Hasura Cloud is SOC 2 Type II Compliant\n- framework: HIPAA\n  type: null\n  scope: Hasura Cloud\n  period: null\n  issuer: independent third party\n  report_access: unstated\n  text: Hasura Cloud is HIPAA Compliant\n- framework: GDPR\n  type: null\n  scope: Our offerings\n  period: null\n  issuer:\
  \ null\n  report_access: unstated\n  text: Our offerings are fully GDPR compliant.\n- framework: ISO27001\n  type: multi-site certification\n  scope: Hasura GraphQL Engine\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We achieved multi-site certification, covering our primary office locations in San Francisco, United States\n    and Bangalore, India.\n"
source_yaml_url: https://artifacts.apis.io/hasura/compliance/hasura-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Hasura's own page on 2026-11-09.
synthetic: false
tags:
- Data Access
- GraphQL
- Real-Time
---
