---
api_specs:
- filename: convex-asyncapi.yml
  format: yaml
  label: Convex Sync Protocol
  slug: sync-protocol
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/convex/asyncapi/convex-asyncapi.yml
- filename: convex-actions-api-openapi.yml
  format: yaml
  label: Convex Actions API
  slug: convex-actions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convex/openapi/convex-actions-api-openapi.yml
- filename: convex-deployments-api-openapi.yml
  format: yaml
  label: Convex Deployments API
  slug: convex-deployments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convex/openapi/convex-deployments-api-openapi.yml
- filename: convex-functions-api-openapi.yml
  format: yaml
  label: Convex Functions API
  slug: convex-functions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convex/openapi/convex-functions-api-openapi.yml
- filename: convex-mutations-api-openapi.yml
  format: yaml
  label: Convex Mutations API
  slug: convex-mutations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convex/openapi/convex-mutations-api-openapi.yml
- filename: convex-projects-api-openapi.yml
  format: yaml
  label: Convex Projects API
  slug: convex-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convex/openapi/convex-projects-api-openapi.yml
- filename: convex-queries-api-openapi.yml
  format: yaml
  label: Convex Queries API
  slug: convex-queries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convex/openapi/convex-queries-api-openapi.yml
- filename: convex-teams-api-openapi.yml
  format: yaml
  label: Convex Teams API
  slug: convex-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convex/openapi/convex-teams-api-openapi.yml
- filename: convex-access-tokens-api-openapi.yml
  format: yaml
  label: Convex Access Tokens API
  slug: convex-access-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convex/openapi/convex-access-tokens-api-openapi.yml
- filename: convex-custom-domains-api-openapi.yml
  format: yaml
  label: Convex Custom Domains API
  slug: convex-custom-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convex/openapi/convex-custom-domains-api-openapi.yml
- filename: convex-environment-variables-api-openapi.yml
  format: yaml
  label: Convex Environment Variables API
  slug: convex-environment-variables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convex/openapi/convex-environment-variables-api-openapi.yml
- filename: convex-custom-roles-api-openapi.yml
  format: yaml
  label: Convex Custom Roles API
  slug: convex-custom-roles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convex/openapi/convex-custom-roles-api-openapi.yml
- filename: convex-deploy-keys-api-openapi.yml
  format: yaml
  label: Convex Deploy Keys API
  slug: convex-deploy-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convex/openapi/convex-deploy-keys-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Convex platform
    text: Convex is SOC 2 Type 2 compliant
    type: SOC 2 Type 2 compliance
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: businesses subject to HIPAA who sign Convex's Business Associate Agreement
    text: Provided businesses subject to HIPAA sign Convex’s Business Associate Agreement they may process PHI on the platform.
    type: HIPAA compliance via Business Associate Agreement
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: delivery of service to customers
    text: Convex complies with the GDPR in the delivery of our service to our customers
    type: GDPR compliance
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: payment processing via Stripe
    text: Convex uses Stripe, a certified PCI Service Provider Level 1, for payment processing.
    type: Stripe is a certified PCI Service Provider Level 1 (third-party payment processor)
  trust_center:
    url: https://www.convex.dev/security
frameworks:
- GDPR
- HIPAA
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Convex
provenance_date: '2026-11-09'
provider_name: Convex
provider_slug: convex
slug: convex-compliance
source_date: '2026-11-09'
source_filename: convex-compliance.yml
source_heading: Compliance
source_page: https://www.convex.dev/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Convex\naid: convex\nurl: https://www.convex.dev/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/convex-trust-center.yml\ntrust_center:\n  url: https://www.convex.dev/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 compliance\n  scope: Convex platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Convex is SOC 2 Type 2 compliant\n- framework: HIPAA\n  type: HIPAA compliance via Business Associate Agreement\n  scope: businesses subject to HIPAA who sign Convex's Business Associate Agreement\n  period: null\n  issuer: null\n  report_access: unstated\n \
  \ text: Provided businesses subject to HIPAA sign Convex’s Business Associate Agreement they may process PHI on\n    the platform.\n- framework: GDPR\n  type: GDPR compliance\n  scope: delivery of service to customers\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Convex complies with the GDPR in the delivery of our service to our customers\n- framework: PCI-DSS\n  type: Stripe is a certified PCI Service Provider Level 1 (third-party payment processor)\n  scope: payment processing via Stripe\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Convex uses Stripe, a certified PCI Service Provider Level 1, for payment processing.\n"
source_yaml_url: https://artifacts.apis.io/convex/compliance/convex-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Convex's own page on 2026-11-09.
synthetic: false
tags:
- Backend
- Database
- Functions
- Real-Time
- Reactive
- Serverless
- TypeScript
---
