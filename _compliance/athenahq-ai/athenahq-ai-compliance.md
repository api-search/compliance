---
api_specs:
- filename: athenahq-ai-ai-access-api-openapi.yml
  format: yaml
  label: AthenaHQ AI Access API
  slug: athenahq-ai-ai-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/athenahq-ai/openapi/athenahq-ai-ai-access-api-openapi.yml
- filename: athenahq-ai-ai-search-value-api-openapi.yml
  format: yaml
  label: AthenaHQ AI Search Value API
  slug: athenahq-ai-ai-search-value-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/athenahq-ai/openapi/athenahq-ai-ai-search-value-api-openapi.yml
- filename: athenahq-ai-analytics-api-openapi.yml
  format: yaml
  label: AthenaHQ Analytics API
  slug: athenahq-ai-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/athenahq-ai/openapi/athenahq-ai-analytics-api-openapi.yml
- filename: athenahq-ai-attributes-api-openapi.yml
  format: yaml
  label: AthenaHQ Attributes API
  slug: athenahq-ai-attributes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/athenahq-ai/openapi/athenahq-ai-attributes-api-openapi.yml
- filename: athenahq-ai-basics-api-openapi.yml
  format: yaml
  label: AthenaHQ Basics API
  slug: athenahq-ai-basics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/athenahq-ai/openapi/athenahq-ai-basics-api-openapi.yml
- filename: athenahq-ai-billing-api-openapi.yml
  format: yaml
  label: AthenaHQ Billing API
  slug: athenahq-ai-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/athenahq-ai/openapi/athenahq-ai-billing-api-openapi.yml
- filename: athenahq-ai-content-api-openapi.yml
  format: yaml
  label: AthenaHQ Content API
  slug: athenahq-ai-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/athenahq-ai/openapi/athenahq-ai-content-api-openapi.yml
- filename: athenahq-ai-groups-api-openapi.yml
  format: yaml
  label: AthenaHQ Groups API
  slug: athenahq-ai-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/athenahq-ai/openapi/athenahq-ai-groups-api-openapi.yml
- filename: athenahq-ai-knowledge-base-api-openapi.yml
  format: yaml
  label: AthenaHQ Knowledge Base API
  slug: athenahq-ai-knowledge-base-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/athenahq-ai/openapi/athenahq-ai-knowledge-base-api-openapi.yml
- filename: athenahq-ai-metrics-api-openapi.yml
  format: yaml
  label: AthenaHQ Metrics API
  slug: athenahq-ai-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/athenahq-ai/openapi/athenahq-ai-metrics-api-openapi.yml
- filename: athenahq-ai-pitch-workspace-api-openapi.yml
  format: yaml
  label: AthenaHQ Pitch Workspace API
  slug: athenahq-ai-pitch-workspace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/athenahq-ai/openapi/athenahq-ai-pitch-workspace-api-openapi.yml
- filename: athenahq-ai-seo-recommendations-api-openapi.yml
  format: yaml
  label: AthenaHQ SEO Recommendations API
  slug: athenahq-ai-seo-recommendations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/athenahq-ai/openapi/athenahq-ai-seo-recommendations-api-openapi.yml
- filename: athenahq-ai-sources-api-openapi.yml
  format: yaml
  label: AthenaHQ Sources API
  slug: athenahq-ai-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/athenahq-ai/openapi/athenahq-ai-sources-api-openapi.yml
- filename: athenahq-ai-team-management-api-openapi.yml
  format: yaml
  label: AthenaHQ Team Management API
  slug: athenahq-ai-team-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/athenahq-ai/openapi/athenahq-ai-team-management-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: '2025'
    report_access: unstated
    scope: null
    text: SOC 2 Type 2 Report (2025)
    type: SOC 2 Type 2 report
  - framework: SOC2
    issuer: null
    period: October 2026
    report_access: unstated
    scope: null
    text: SOC 2 Bridge Letter (October 2026)
    type: SOC 2 Bridge Letter
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type 1
    type: SOC 2 Type 1
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: GDPR compliance
  trust_center:
    url: https://trust.athenahq.ai/
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: AthenaHQ
provenance_date: '2026-11-09'
provider_name: AthenaHQ
provider_slug: athenahq-ai
slug: athenahq-ai-compliance
source_date: '2026-11-09'
source_filename: athenahq-ai-compliance.yml
source_heading: Compliance
source_page: https://trust.athenahq.ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: AthenaHQ\naid: athenahq-ai\nurl: https://trust.athenahq.ai/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.athenahq.ai/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: null\n  period: '2025'\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2 Report (2025)\n- framework: SOC2\n  type: SOC 2 Bridge Letter\n  scope: null\n  period: October 2026\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Bridge Letter (October 2026)\n- framework: SOC2\n  type: SOC 2 Type 1\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type\
  \ 1\n- framework: GDPR\n  type: GDPR compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n"
source_yaml_url: https://artifacts.apis.io/athenahq-ai/compliance/athenahq-ai-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from AthenaHQ's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Marketing
- Search
- Platform
- Enterprise
---
