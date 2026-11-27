---
api_specs:
- filename: sapling-account-api-openapi.yml
  format: yaml
  label: Sapling Account API
  slug: sapling-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sapling/openapi/sapling-account-api-openapi.yml
- filename: sapling-analysis-api-openapi.yml
  format: yaml
  label: Sapling Analysis API
  slug: sapling-analysis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sapling/openapi/sapling-analysis-api-openapi.yml
- filename: sapling-detection-api-openapi.yml
  format: yaml
  label: Sapling Detection API
  slug: sapling-detection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sapling/openapi/sapling-detection-api-openapi.yml
- filename: sapling-files-api-openapi.yml
  format: yaml
  label: Sapling Files API
  slug: sapling-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sapling/openapi/sapling-files-api-openapi.yml
- filename: sapling-generation-api-openapi.yml
  format: yaml
  label: Sapling Generation API
  slug: sapling-generation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sapling/openapi/sapling-generation-api-openapi.yml
- filename: sapling-proofreading-api-openapi.yml
  format: yaml
  label: Sapling Proofreading API
  slug: sapling-proofreading-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sapling/openapi/sapling-proofreading-api-openapi.yml
- filename: sapling-service-api-openapi.yml
  format: yaml
  label: Sapling Service API
  slug: sapling-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sapling/openapi/sapling-service-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: is also GDPR compliant and SOC 2 Type II certified.
    type: Type II certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: is also GDPR compliant and SOC 2 Type II certified.
    type: compliance
  trust_center:
    url: https://sapling.ai/security
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Sapling
provenance_date: '2026-11-10'
provider_name: Sapling
provider_slug: sapling
slug: sapling-compliance
source_date: '2026-11-10'
source_filename: sapling-compliance.yml
source_heading: Compliance
source_page: https://sapling.ai/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Sapling\naid: sapling\nurl: https://sapling.ai/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://sapling.ai/security\nattestations:\n- framework: SOC2\n  type: Type II certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: is also GDPR compliant and SOC 2 Type II certified.\n- framework: GDPR\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: is also GDPR compliant and SOC 2 Type II certified.\n"
source_yaml_url: https://artifacts.apis.io/sapling/compliance/sapling-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Sapling's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Language-Model
- Enterprise
- Productivity
---
