---
api_specs:
- filename: restate-cluster-health-api-openapi.yml
  format: yaml
  label: Restate Cluster Health API
  slug: restate-cluster-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/restate/openapi/restate-cluster-health-api-openapi.yml
- filename: restate-deployment-api-openapi.yml
  format: yaml
  label: Restate Deployment API
  slug: restate-deployment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/restate/openapi/restate-deployment-api-openapi.yml
- filename: restate-health-api-openapi.yml
  format: yaml
  label: Restate Health API
  slug: restate-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/restate/openapi/restate-health-api-openapi.yml
- filename: restate-invocation-api-openapi.yml
  format: yaml
  label: Restate Invocation API
  slug: restate-invocation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/restate/openapi/restate-invocation-api-openapi.yml
- filename: restate-service-api-openapi.yml
  format: yaml
  label: Restate Service API
  slug: restate-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/restate/openapi/restate-service-api-openapi.yml
- filename: restate-service-handler-api-openapi.yml
  format: yaml
  label: Restate Service Handler API
  slug: restate-service-handler-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/restate/openapi/restate-service-handler-api-openapi.yml
- filename: restate-subscription-api-openapi.yml
  format: yaml
  label: Restate Subscription API
  slug: restate-subscription-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/restate/openapi/restate-subscription-api-openapi.yml
- filename: restate-version-api-openapi.yml
  format: yaml
  label: Restate Version API
  slug: restate-version-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/restate/openapi/restate-version-api-openapi.yml
- filename: restate-open-api-api-openapi.yml
  format: yaml
  label: Restate Open API
  slug: restate-open-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/restate/openapi/restate-open-api-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent auditor
    period: null
    report_access: nda
    scope: Restate Cloud Platform security trust services criteria
    text: Restate has completed a SOC 2 Type 1 audit and is currently in the observation period for an upcoming SOC 2 Type 2 audit.
    type: Type 1 audit
  - framework: SOC2
    issuer: independent auditor
    period: null
    report_access: nda
    scope: Security trust service category for the Restate Cloud Platform
    text: Restate has completed its SOC 2 Type II examination for the Security trust service category.
    type: Type 2 report
  trust_center:
    url: https://trust.restate.dev/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Restate
provenance_date: '2026-11-10'
provider_name: Restate
provider_slug: restate
slug: restate-compliance
source_date: '2026-11-10'
source_filename: restate-compliance.yml
source_heading: Compliance
source_page: https://trust.restate.dev/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Restate\naid: restate\nurl: https://trust.restate.dev/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/restate-trust-center.yml\ntrust_center:\n  url: https://trust.restate.dev/\nattestations:\n- framework: SOC2\n  type: Type 1 audit\n  scope: Restate Cloud Platform security trust services criteria\n  period: null\n  issuer: independent auditor\n  report_access: nda\n  text: Restate has completed a SOC 2 Type 1 audit and is currently in the observation period for an upcoming SOC\n    2 Type 2 audit.\n- framework: SOC2\n  type: Type 2 report\n  scope: Security trust service category for the Restate\
  \ Cloud Platform\n  period: null\n  issuer: independent auditor\n  report_access: nda\n  text: Restate has completed its SOC 2 Type II examination for the Security trust service category.\n"
source_yaml_url: https://artifacts.apis.io/restate/compliance/restate-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Restate's own page on 2026-11-10.
synthetic: false
tags:
- Durable Execution
- Workflows
- Microservices
- Orchestration
- Distributed Systems
---
