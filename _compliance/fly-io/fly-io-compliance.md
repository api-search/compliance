---
api_specs:
- filename: fly-io-machines-api-openapi.yml
  format: yaml
  label: Fly.io Machines API
  slug: machines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fly-io/openapi/fly-io-machines-api-openapi.yml
- filename: fly-io-extensions-api-openapi.yml
  format: yaml
  label: Fly.io Extensions API
  slug: extensions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fly-io/openapi/fly-io-extensions-api-openapi.yml
- filename: fly-io-apps-api-openapi.yml
  format: yaml
  label: fly-io Apps API
  slug: fly-io-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fly-io/openapi/fly-io-apps-api-openapi.yml
- filename: fly-io-sso-api-openapi.yml
  format: yaml
  label: fly-io SSO API
  slug: fly-io-sso-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fly-io/openapi/fly-io-sso-api-openapi.yml
- filename: fly-io-tokens-api-openapi.yml
  format: yaml
  label: fly-io Tokens API
  slug: fly-io-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fly-io/openapi/fly-io-tokens-api-openapi.yml
- filename: fly-io-volumes-api-openapi.yml
  format: yaml
  label: fly-io Volumes API
  slug: fly-io-volumes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fly-io/openapi/fly-io-volumes-api-openapi.yml
- filename: fly-io-webhooks-api-openapi.yml
  format: yaml
  label: fly-io Webhooks API
  slug: fly-io-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fly-io/openapi/fly-io-webhooks-api-openapi.yml
- filename: fly-io-oauth-api-openapi.yml
  format: yaml
  label: Fly Io O Auth API
  slug: fly-io-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fly-io/openapi/fly-io-oauth-api-openapi.yml
- filename: fly-io-organizations-api-openapi.yml
  format: yaml
  label: Fly Io Organizations API
  slug: fly-io-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fly-io/openapi/fly-io-organizations-api-openapi.yml
- filename: fly-io-platform-api-openapi.yml
  format: yaml
  label: Fly Io Platform API
  slug: fly-io-platform-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fly-io/openapi/fly-io-platform-api-openapi.yml
- filename: fly-io-postgres-clusters-api-openapi.yml
  format: yaml
  label: Fly Io Postgres Clusters API
  slug: fly-io-postgres-clusters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fly-io/openapi/fly-io-postgres-clusters-api-openapi.yml
- filename: fly-io-secrets-api-openapi.yml
  format: yaml
  label: Fly Io Secrets API
  slug: fly-io-secrets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fly-io/openapi/fly-io-secrets-api-openapi.yml
- filename: fly-io-tls-certificates-api-openapi.yml
  format: yaml
  label: Fly Io TLS Certificates API
  slug: fly-io-tls-certificates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fly-io/openapi/fly-io-tls-certificates-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Yeah, We’re SOC 2 Type 2 We're certified
    type: Type 2
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: our hardware runs in ISO 27001 datacenters
    text: our hardware runs in ISO 27001 datacenters
    type: datacenter hosting
  trust_center:
    url: https://fly.io/security/
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Fly Io
provenance_date: '2026-11-09'
provider_name: Fly Io
provider_slug: fly-io
slug: fly-io-compliance
source_date: '2026-11-09'
source_filename: fly-io-compliance.yml
source_heading: Compliance
source_page: https://fly.io/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Fly Io\naid: fly-io\nurl: https://fly.io/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/fly-io-trust-center.yml\ntrust_center:\n  url: https://fly.io/security/\nattestations:\n- framework: SOC2\n  type: Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Yeah, We’re SOC 2 Type 2 We're certified\n- framework: ISO27001\n  type: datacenter hosting\n  scope: our hardware runs in ISO 27001 datacenters\n  period: null\n  issuer: null\n  report_access: unstated\n  text: our hardware runs in ISO 27001 datacenters\n"
source_yaml_url: https://artifacts.apis.io/fly-io/compliance/fly-io-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Fly Io's own page on 2026-11-09.
synthetic: false
tags:
- Platform
- Infrastructure
- Edge Computing
- Networking
- Hosting
- Deployment
- Serverless
---
