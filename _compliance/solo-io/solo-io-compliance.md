---
api_specs:
- filename: solo-io-api-keys-api-openapi.yml
  format: yaml
  label: Solo.io API Keys API
  slug: solo-io-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/solo-io/openapi/solo-io-api-keys-api-openapi.yml
- filename: solo-io-api-products-api-openapi.yml
  format: yaml
  label: Solo.io API Products API
  slug: solo-io-api-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/solo-io/openapi/solo-io-api-products-api-openapi.yml
- filename: solo-io-applications-api-openapi.yml
  format: yaml
  label: Solo.io Applications API
  slug: solo-io-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/solo-io/openapi/solo-io-applications-api-openapi.yml
- filename: solo-io-apps-api-openapi.yml
  format: yaml
  label: Solo.io Apps API
  slug: solo-io-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/solo-io/openapi/solo-io-apps-api-openapi.yml
- filename: solo-io-auth-api-openapi.yml
  format: yaml
  label: Solo.io Auth API
  slug: solo-io-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/solo-io/openapi/solo-io-auth-api-openapi.yml
- filename: solo-io-health-api-openapi.yml
  format: yaml
  label: Solo.io Health API
  slug: solo-io-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/solo-io/openapi/solo-io-health-api-openapi.yml
- filename: solo-io-me-api-openapi.yml
  format: yaml
  label: Solo.io Me API
  slug: solo-io-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/solo-io/openapi/solo-io-me-api-openapi.yml
- filename: solo-io-metadata-api-openapi.yml
  format: yaml
  label: Solo.io Metadata API
  slug: solo-io-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/solo-io/openapi/solo-io-metadata-api-openapi.yml
- filename: solo-io-oauth-credentials-api-openapi.yml
  format: yaml
  label: Solo.io OAUTH Credentials API
  slug: solo-io-oauth-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/solo-io/openapi/solo-io-oauth-credentials-api-openapi.yml
- filename: solo-io-subscriptions-api-openapi.yml
  format: yaml
  label: Solo.io Subscriptions API
  slug: solo-io-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/solo-io/openapi/solo-io-subscriptions-api-openapi.yml
- filename: solo-io-teams-api-openapi.yml
  format: yaml
  label: Solo.io Teams API
  slug: solo-io-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/solo-io/openapi/solo-io-teams-api-openapi.yml
- filename: solo-io-user-api-openapi.yml
  format: yaml
  label: Solo.io User API
  slug: solo-io-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/solo-io/openapi/solo-io-user-api-openapi.yml
- filename: solo-io-users-api-openapi.yml
  format: yaml
  label: Solo.io Users API
  slug: solo-io-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/solo-io/openapi/solo-io-users-api-openapi.yml
- filename: solo-io-webhooks-api-openapi.yml
  format: yaml
  label: Solo.io Webhooks API
  slug: solo-io-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/solo-io/openapi/solo-io-webhooks-api-openapi.yml
- filename: solo-io-apis-api-openapi.yml
  format: yaml
  label: Solo.io APIs API
  slug: solo-io-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/solo-io/openapi/solo-io-apis-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type 1 SOC 2 Type 2
    type: SOC 2 Type 1 report
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Solo.io SOC 2 Type 2 2026 SOC 2 Type II Surveillance Period Engagement Confirmation Letter
    type: SOC 2 Type 2 report
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Solo Enterprise for Istio control plane and data plane (Envoy Proxy)
    source: https://www.solo.io/topics/security-and-compliance/fips
    text: Solo.io provides a hardened, FIPS 140-3 compliant version of Istio service mesh.
    type: FIPS 140-3 compliant builds (product claim)
  trust_center:
    url: https://trust.solo.io/
frameworks:
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Solo.io
provenance_date: '2026-11-10'
provider_name: Solo.io
provider_slug: solo-io
slug: solo-io-compliance
source_date: '2026-11-10'
source_filename: solo-io-compliance.yml
source_heading: Compliance
source_page: https://trust.solo.io/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Solo.io\naid: solo-io\nurl: https://trust.solo.io/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://trust.solo.io/\n  - https://www.solo.io/topics/security-and-compliance/fips\ntrust_center:\n  url: https://trust.solo.io/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 1 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 1 SOC 2 Type 2\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Solo.io SOC 2 Type 2 2026 SOC 2 Type II Surveillance Period Engagement Confirmation Letter\n\
  - framework: other\n  type: FIPS 140-3 compliant builds (product claim)\n  scope: Solo Enterprise for Istio control plane and data plane (Envoy Proxy)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Solo.io provides a hardened, FIPS 140-3 compliant version of Istio service mesh.\n  source: https://www.solo.io/topics/security-and-compliance/fips\n"
source_yaml_url: https://artifacts.apis.io/solo-io/compliance/solo-io-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Solo.io's own page on 2026-11-10.
synthetic: false
tags:
- Company
- API Gateway
- Service Mesh
- Kubernetes
- Istio
- Envoy
- AI Gateway
- AI Agents
- MCP
- Developer Portal
- Cloud-Native
- Open Source
---
