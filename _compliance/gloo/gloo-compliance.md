---
api_specs:
- filename: gloo-api-products-api-openapi.yml
  format: yaml
  label: Gloo API Products API
  slug: gloo-api-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gloo/openapi/gloo-api-products-api-openapi.yml
- filename: gloo-applications-api-openapi.yml
  format: yaml
  label: Gloo Applications API
  slug: gloo-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gloo/openapi/gloo-applications-api-openapi.yml
- filename: gloo-me-api-openapi.yml
  format: yaml
  label: Gloo Me API
  slug: gloo-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gloo/openapi/gloo-me-api-openapi.yml
- filename: gloo-subscriptions-api-openapi.yml
  format: yaml
  label: Gloo Subscriptions API
  slug: gloo-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gloo/openapi/gloo-subscriptions-api-openapi.yml
- filename: gloo-teams-api-openapi.yml
  format: yaml
  label: Gloo Teams API
  slug: gloo-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gloo/openapi/gloo-teams-api-openapi.yml
- filename: gloo-user-api-openapi.yml
  format: yaml
  label: Gloo User API
  slug: gloo-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gloo/openapi/gloo-user-api-openapi.yml
- filename: gloo-webhooks-api-openapi.yml
  format: yaml
  label: Gloo Webhooks API
  slug: gloo-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gloo/openapi/gloo-webhooks-api-openapi.yml
- filename: gloo-apis-api-openapi.yml
  format: yaml
  label: Gloo APIs API
  slug: gloo-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gloo/openapi/gloo-apis-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type 1
    type: Type 1 report
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type 2
    type: Type 2 report
  trust_center:
    url: https://trust.solo.io/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Gloo
provenance_date: '2026-11-09'
provider_name: Gloo
provider_slug: gloo
slug: gloo-compliance
source_date: '2026-11-09'
source_filename: gloo-compliance.yml
source_heading: Compliance
source_page: https://trust.solo.io/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Gloo\naid: gloo\nurl: https://trust.solo.io/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.solo.io/\nattestations:\n- framework: SOC2\n  type: Type 1 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 1\n- framework: SOC2\n  type: Type 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2\n"
source_yaml_url: https://artifacts.apis.io/gloo/compliance/gloo-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Gloo's own page on 2026-11-09.
synthetic: false
tags:
- API Gateway
- Cloud-Native
- Developer Portal
- Envoy
- Istio
- Kubernetes
- Kubernetes Gateway API
- Open Source
- Service Mesh
---
