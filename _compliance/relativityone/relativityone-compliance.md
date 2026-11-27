---
api_specs:
- filename: relativityone-communications-api-openapi.yml
  format: yaml
  label: RelativityOne Communications API
  slug: relativityone-communications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relativityone/openapi/relativityone-communications-api-openapi.yml
- filename: relativityone-custodians-api-openapi.yml
  format: yaml
  label: RelativityOne Custodians API
  slug: relativityone-custodians-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relativityone/openapi/relativityone-custodians-api-openapi.yml
- filename: relativityone-entities-api-openapi.yml
  format: yaml
  label: RelativityOne Entities API
  slug: relativityone-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relativityone/openapi/relativityone-entities-api-openapi.yml
- filename: relativityone-legal-hold-projects-api-openapi.yml
  format: yaml
  label: RelativityOne Legal Hold Projects API
  slug: relativityone-legal-hold-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relativityone/openapi/relativityone-legal-hold-projects-api-openapi.yml
- filename: relativityone-preservation-api-openapi.yml
  format: yaml
  label: RelativityOne Preservation API
  slug: relativityone-preservation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relativityone/openapi/relativityone-preservation-api-openapi.yml
- filename: relativityone-tasks-api-openapi.yml
  format: yaml
  label: RelativityOne Tasks API
  slug: relativityone-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relativityone/openapi/relativityone-tasks-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: Relativity platform for government (FOIA environment)
    text: Unify requests, case management, review, and publishing in one FedRAMP-certified environment.
    type: certification
  trust_center:
    url: https://www.relativity.com/
frameworks:
- FedRAMP
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: RelativityOne
provenance_date: '2026-11-10'
provider_name: RelativityOne
provider_slug: relativityone
slug: relativityone-compliance
source_date: '2026-11-10'
source_filename: relativityone-compliance.yml
source_heading: Compliance
source_page: https://www.relativity.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: RelativityOne\naid: relativityone\nurl: https://www.relativity.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/relativityone-trust-center.yml\ntrust_center:\n  url: https://www.relativity.com/\nattestations:\n- framework: FedRAMP\n  type: certification\n  scope: Relativity platform for government (FOIA environment)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Unify requests, case management, review, and publishing in one FedRAMP-certified environment.\n"
source_yaml_url: https://artifacts.apis.io/relativityone/compliance/relativityone-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from RelativityOne's own page on 2026-11-10.
synthetic: false
tags:
- eDiscovery
- Legal
- Legal Hold
- Document Management
- Compliance
- Litigation
---
