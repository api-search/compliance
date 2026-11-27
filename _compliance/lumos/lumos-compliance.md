---
api_specs:
- filename: lumos-tasks-api-openapi.yml
  format: yaml
  label: Lumos Tasks API
  slug: lumos-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lumos/openapi/lumos-tasks-api-openapi.yml
- filename: lumos-access-reviews-api-openapi.yml
  format: yaml
  label: Lumos Access Reviews API
  slug: lumos-access-reviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lumos/openapi/lumos-access-reviews-api-openapi.yml
- filename: lumos-core-api-openapi.yml
  format: yaml
  label: Lumos Core API
  slug: lumos-core-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lumos/openapi/lumos-core-api-openapi.yml
- filename: lumos-integration-webhooks-api-openapi.yml
  format: yaml
  label: Lumos Integration Webhooks API
  slug: lumos-integration-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lumos/openapi/lumos-integration-webhooks-api-openapi.yml
- filename: lumos-knowledge-api-openapi.yml
  format: yaml
  label: Lumos Knowledge API
  slug: lumos-knowledge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lumos/openapi/lumos-knowledge-api-openapi.yml
- filename: lumos-lifecycle-management-api-openapi.yml
  format: yaml
  label: Lumos Lifecycle Management API
  slug: lumos-lifecycle-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lumos/openapi/lumos-lifecycle-management-api-openapi.yml
- filename: lumos-meta-api-openapi.yml
  format: yaml
  label: Lumos Meta API
  slug: lumos-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lumos/openapi/lumos-meta-api-openapi.yml
- filename: lumos-vendor-management-api-openapi.yml
  format: yaml
  label: Lumos Vendor Management API
  slug: lumos-vendor-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lumos/openapi/lumos-vendor-management-api-openapi.yml
- filename: lumos-app-store-api-openapi.yml
  format: yaml
  label: Lumos App Store API
  slug: lumos-app-store-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lumos/openapi/lumos-app-store-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II S SOC 1 Type II ISO 27001:2022
    type: SOC 2 Type II
  - framework: SOC1
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 1 Type II Bridge Letter
    type: SOC 1 Type II
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001:2022
    type: ISO 27001:2022
  trust_center:
    url: https://trust.lumos.com/
frameworks:
- ISO27001
- SOC1
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Lumos
provenance_date: '2026-11-10'
provider_name: Lumos
provider_slug: lumos
slug: lumos-compliance
source_date: '2026-11-10'
source_filename: lumos-compliance.yml
source_heading: Compliance
source_page: https://trust.lumos.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Lumos\naid: lumos\nurl: https://trust.lumos.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.lumos.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II S SOC 1 Type II ISO 27001:2022\n- framework: SOC1\n  type: SOC 1 Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 1 Type II Bridge Letter\n- framework: ISO27001\n  type: ISO 27001:2022\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022\n"
source_yaml_url: https://artifacts.apis.io/lumos/compliance/lumos-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Lumos's own page on 2026-11-10.
synthetic: false
tags:
- Identity and Access Management
- Access Reviews
- Deprovisioning
- Identity Governance
- Identity Platform
- Least Privilege
- Provisioning
- SaaS Management
- Shadow IT
---
