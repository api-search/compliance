---
api_specs:
- filename: scope-bid-carrier-feed-api-openapi.yml
  format: yaml
  label: scope-bid Carrier Feed API
  slug: scope-bid-carrier-feed-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scope-bid/openapi/scope-bid-carrier-feed-api-openapi.yml
- filename: scope-bid-deliverables-api-openapi.yml
  format: yaml
  label: scope-bid Deliverables API
  slug: scope-bid-deliverables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scope-bid/openapi/scope-bid-deliverables-api-openapi.yml
- filename: scope-bid-dispatches-api-openapi.yml
  format: yaml
  label: scope-bid Dispatches API
  slug: scope-bid-dispatches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scope-bid/openapi/scope-bid-dispatches-api-openapi.yml
- filename: scope-bid-exports-api-openapi.yml
  format: yaml
  label: scope-bid Exports API
  slug: scope-bid-exports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scope-bid/openapi/scope-bid-exports-api-openapi.yml
- filename: scope-bid-insights-api-openapi.yml
  format: yaml
  label: scope-bid Insights API
  slug: scope-bid-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scope-bid/openapi/scope-bid-insights-api-openapi.yml
- filename: scope-bid-matters-api-openapi.yml
  format: yaml
  label: scope-bid Matters API
  slug: scope-bid-matters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scope-bid/openapi/scope-bid-matters-api-openapi.yml
- filename: scope-bid-partner-authorizations-api-openapi.yml
  format: yaml
  label: scope-bid Partner Authorizations API
  slug: scope-bid-partner-authorizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scope-bid/openapi/scope-bid-partner-authorizations-api-openapi.yml
- filename: scope-bid-scopes-api-openapi.yml
  format: yaml
  label: scope-bid Scopes API
  slug: scope-bid-scopes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scope-bid/openapi/scope-bid-scopes-api-openapi.yml
- filename: scope-bid-vendors-api-openapi.yml
  format: yaml
  label: scope-bid Vendors API
  slug: scope-bid-vendors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scope-bid/openapi/scope-bid-vendors-api-openapi.yml
- filename: scope-bid-webhooks-api-openapi.yml
  format: yaml
  label: scope-bid Webhooks API
  slug: scope-bid-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scope-bid/openapi/scope-bid-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: Privacy (GDPR / state laws)
    text: Aligned with CCPA, CPRA, and equivalent state privacy laws.
    type: alignment statement
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Insurance claims (preview) vertical
    text: NAIC Model Cybersecurity Law alignment.
    type: alignment statement (NAIC Model Cybersecurity Law)
  trust_center:
    url: https://scope.bid/trust
frameworks:
- CCPA
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: scope-bid
provenance_date: '2026-11-10'
provider_name: scope-bid
provider_slug: scope-bid
slug: scope-bid-compliance
source_date: '2026-11-10'
source_filename: scope-bid-compliance.yml
source_heading: Compliance
source_page: https://scope.bid/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: scope-bid\naid: scope-bid\nurl: https://scope.bid/trust\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://scope.bid/trust\nattestations:\n- framework: CCPA\n  type: alignment statement\n  scope: Privacy (GDPR / state laws)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Aligned with CCPA, CPRA, and equivalent state privacy laws.\n- framework: other\n  type: alignment statement (NAIC Model Cybersecurity Law)\n  scope: Insurance claims (preview) vertical\n  period: null\n  issuer: null\n  report_access: unstated\n  text: NAIC Model Cybersecurity Law alignment.\n"
source_yaml_url: https://artifacts.apis.io/scope-bid/compliance/scope-bid-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from scope-bid's own page on 2026-11-10.
synthetic: false
tags:
- Construction
- Bidding
- Software-as-a-Service
- Collaboration
- Analytics
---
