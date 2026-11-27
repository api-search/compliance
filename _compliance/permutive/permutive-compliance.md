---
api_specs:
- filename: permutive-contextual-api-openapi.yml
  format: yaml
  label: Permutive Contextual API
  slug: permutive-contextual-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/permutive/openapi/permutive-contextual-api-openapi.yml
- filename: permutive-cohorts-api-openapi.yml
  format: yaml
  label: Permutive Cohorts API
  slug: permutive-cohorts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/permutive/openapi/permutive-cohorts-api-openapi.yml
- filename: permutive-events-api-openapi.yml
  format: yaml
  label: Permutive Events API
  slug: permutive-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/permutive/openapi/permutive-events-api-openapi.yml
- filename: permutive-identity-api-openapi.yml
  format: yaml
  label: Permutive Identity API
  slug: permutive-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/permutive/openapi/permutive-identity-api-openapi.yml
- filename: permutive-segmentation-api-openapi.yml
  format: yaml
  label: Permutive Segmentation API
  slug: permutive-segmentation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/permutive/openapi/permutive-segmentation-api-openapi.yml
- filename: permutive-taxonomy-api-openapi.yml
  format: yaml
  label: Permutive Taxonomy API
  slug: permutive-taxonomy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/permutive/openapi/permutive-taxonomy-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: '2026'
    report_access: on_request
    scope: null
    text: Permutive SOC 2 Type II Report - 2026
    type: SOC 2 Type II report
  - framework: SOC3
    issuer: null
    period: '2026'
    report_access: public
    scope: null
    text: Permutive SOC 3 Report - 2026
    type: SOC 3 report
  - framework: SOC2
    issuer: independent auditor
    period: annual
    report_access: on_request
    scope: null
    source: https://docs.permutive.com/governance/security
    text: Permutive undergoes annual independent SOC 2 Type II audits, with SOC 3 reports available publicly.
    type: SOC 2 Type II audit
  - framework: SOC3
    issuer: independent auditor
    period: null
    report_access: public
    scope: null
    source: https://docs.permutive.com/governance/security
    text: with SOC 3 reports available publicly
    type: SOC 3 report
  trust_center:
    url: https://trust.permutive.com/
frameworks:
- SOC2
- SOC3
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Permutive
provenance_date: '2026-11-10'
provider_name: Permutive
provider_slug: permutive
slug: permutive-compliance
source_date: '2026-11-10'
source_filename: permutive-compliance.yml
source_heading: Compliance
source_page: https://trust.permutive.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Permutive\naid: permutive\nurl: https://trust.permutive.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/permutive-trust-center.yml\n  sources:\n  - https://docs.permutive.com/governance/security\n  - https://trust.permutive.com/\ntrust_center:\n  url: https://trust.permutive.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: null\n  period: '2026'\n  issuer: null\n  report_access: on_request\n  text: Permutive SOC 2 Type II Report - 2026\n- framework: SOC3\n  type: SOC 3 report\n  scope: null\n  period: '2026'\n  issuer: null\n  report_access: public\n  text: Permutive\
  \ SOC 3 Report - 2026\n- framework: SOC2\n  type: SOC 2 Type II audit\n  scope: null\n  period: annual\n  issuer: independent auditor\n  report_access: on_request\n  text: Permutive undergoes annual independent SOC 2 Type II audits, with SOC 3 reports available publicly.\n  source: https://docs.permutive.com/governance/security\n- framework: SOC3\n  type: SOC 3 report\n  scope: null\n  period: null\n  issuer: independent auditor\n  report_access: public\n  text: with SOC 3 reports available publicly\n  source: https://docs.permutive.com/governance/security\n"
source_yaml_url: https://artifacts.apis.io/permutive/compliance/permutive-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Permutive's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Publishing
- Advertising
- AdTech
- MarTech
- Audiences
- Data Collaboration
- Data Management Platform
- Contextual
- Identity
- Segmentation
- Agents
- A2A
---
