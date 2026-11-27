---
api_specs:
- filename: productplan-bars-api-openapi.yml
  format: yaml
  label: ProductPlan Bars API
  slug: productplan-bars-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/productplan/openapi/productplan-bars-api-openapi.yml
- filename: productplan-discovery-api-openapi.yml
  format: yaml
  label: ProductPlan Discovery API
  slug: productplan-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/productplan/openapi/productplan-discovery-api-openapi.yml
- filename: productplan-launches-api-openapi.yml
  format: yaml
  label: ProductPlan Launches API
  slug: productplan-launches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/productplan/openapi/productplan-launches-api-openapi.yml
- filename: productplan-roadmaps-api-openapi.yml
  format: yaml
  label: ProductPlan Roadmaps API
  slug: productplan-roadmaps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/productplan/openapi/productplan-roadmaps-api-openapi.yml
- filename: productplan-status-api-openapi.yml
  format: yaml
  label: ProductPlan Status API
  slug: productplan-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/productplan/openapi/productplan-status-api-openapi.yml
- filename: productplan-strategy-api-openapi.yml
  format: yaml
  label: ProductPlan Strategy API
  slug: productplan-strategy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/productplan/openapi/productplan-strategy-api-openapi.yml
- filename: productplan-teams-api-openapi.yml
  format: yaml
  label: ProductPlan Teams API
  slug: productplan-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/productplan/openapi/productplan-teams-api-openapi.yml
- filename: productplan-users-api-openapi.yml
  format: yaml
  label: ProductPlan Users API
  slug: productplan-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/productplan/openapi/productplan-users-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: AICPA
    period: null
    report_access: on_request
    scope: security, availability, and confidentiality
    text: A copy of our report is available to enterprise customers upon request.
    type: SOC 2 Type II attestation
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: 'GDPR: General Data Protection Regulation (EU) compliant'
    type: compliance statement
  trust_center:
    url: https://www.productplan.com/security
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: ProductPlan
provenance_date: '2026-11-10'
provider_name: ProductPlan
provider_slug: productplan
slug: productplan-compliance
source_date: '2026-11-10'
source_filename: productplan-compliance.yml
source_heading: Compliance
source_page: https://www.productplan.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: ProductPlan\naid: productplan\nurl: https://www.productplan.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/productplan-trust-center.yml\ntrust_center:\n  url: https://www.productplan.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II attestation\n  scope: security, availability, and confidentiality\n  period: null\n  issuer: AICPA\n  report_access: on_request\n  text: A copy of our report is available to enterprise customers upon request.\n- framework: GDPR\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text:\
  \ 'GDPR: General Data Protection Regulation (EU) compliant'\n"
source_yaml_url: https://artifacts.apis.io/productplan/compliance/productplan-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from ProductPlan's own page on 2026-11-10.
synthetic: false
tags:
- Roadmapping
- Product Management
- OKRs
- Roadmaps
- Features
- Product Strategy
- Launches
- Discovery
- Integration
---
