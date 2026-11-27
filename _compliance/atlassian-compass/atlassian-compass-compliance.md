---
api_specs:
- filename: atlassian-compass-events-api-openapi.yml
  format: yaml
  label: Atlassian Compass Events API
  slug: atlassian-compass-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atlassian-compass/openapi/atlassian-compass-events-api-openapi.yml
- filename: atlassian-compass-metrics-api-openapi.yml
  format: yaml
  label: Atlassian Compass Metrics API
  slug: atlassian-compass-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atlassian-compass/openapi/atlassian-compass-metrics-api-openapi.yml
- filename: atlassian-compass-attachment-rest-controller-api-openapi.yml
  format: yaml
  label: Atlassian Compass Attachment Rest Controller API
  slug: atlassian-compass-attachment-rest-controller-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atlassian-compass/openapi/atlassian-compass-attachment-rest-controller-api-openapi.yml
- filename: atlassian-compass-entitlement-rest-controller-api-openapi.yml
  format: yaml
  label: Atlassian Compass Entitlement Rest Controller API
  slug: atlassian-compass-entitlement-rest-controller-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atlassian-compass/openapi/atlassian-compass-entitlement-rest-controller-api-openapi.yml
- filename: atlassian-compass-incoming-webhooks-rest-controller-api-openapi.yml
  format: yaml
  label: Atlassian Compass Incoming Webhooks Rest Controller API
  slug: atlassian-compass-incoming-webhooks-rest-controller-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atlassian-compass/openapi/atlassian-compass-incoming-webhooks-rest-controller-api-openapi.yml
- filename: atlassian-compass-package-dependencies-api-openapi.yml
  format: yaml
  label: Atlassian Compass Package Dependencies API
  slug: atlassian-compass-package-dependencies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atlassian-compass/openapi/atlassian-compass-package-dependencies-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: public sector solutions
    text: FedRAMP Compliant solutions for the public sector
    type: compliant solutions
  trust_center:
    url: https://www.atlassian.com/trust
frameworks:
- FedRAMP
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Atlassian Compass
provenance_date: '2026-11-09'
provider_name: Atlassian Compass
provider_slug: atlassian-compass
slug: atlassian-compass-compliance
source_date: '2026-11-09'
source_filename: atlassian-compass-compliance.yml
source_heading: Compliance
source_page: https://www.atlassian.com/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Atlassian Compass\naid: atlassian-compass\nurl: https://www.atlassian.com/trust\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/atlassian-compass-trust-center.yml\ntrust_center:\n  url: https://www.atlassian.com/trust\nattestations:\n- framework: FedRAMP\n  type: compliant solutions\n  scope: public sector solutions\n  period: null\n  issuer: null\n  report_access: unstated\n  text: FedRAMP Compliant solutions for the public sector\n"
source_yaml_url: https://artifacts.apis.io/atlassian-compass/compliance/atlassian-compass-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Atlassian Compass's own page on 2026-11-09.
synthetic: false
tags:
- Atlassian
- Component Management
- Developer Experience
- Software Catalog
- GraphQL
---
