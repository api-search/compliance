---
api_specs:
- filename: bundle-social-analytics-api-openapi.yml
  format: yaml
  label: bundle.social Analytics API
  slug: bundle-social-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bundle-social/openapi/bundle-social-analytics-api-openapi.yml
- filename: bundle-social-app-api-openapi.yml
  format: yaml
  label: bundle.social App API
  slug: bundle-social-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bundle-social/openapi/bundle-social-app-api-openapi.yml
- filename: bundle-social-automation-api-openapi.yml
  format: yaml
  label: bundle.social Automation API
  slug: bundle-social-automation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bundle-social/openapi/bundle-social-automation-api-openapi.yml
- filename: bundle-social-comment-api-openapi.yml
  format: yaml
  label: bundle.social Comment API
  slug: bundle-social-comment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bundle-social/openapi/bundle-social-comment-api-openapi.yml
- filename: bundle-social-conversation-api-openapi.yml
  format: yaml
  label: bundle.social Conversation API
  slug: bundle-social-conversation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bundle-social/openapi/bundle-social-conversation-api-openapi.yml
- filename: bundle-social-credit-api-openapi.yml
  format: yaml
  label: bundle.social Credit API
  slug: bundle-social-credit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bundle-social/openapi/bundle-social-credit-api-openapi.yml
- filename: bundle-social-misc-api-openapi.yml
  format: yaml
  label: bundle.social Misc API
  slug: bundle-social-misc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bundle-social/openapi/bundle-social-misc-api-openapi.yml
- filename: bundle-social-organization-api-openapi.yml
  format: yaml
  label: bundle.social Organization API
  slug: bundle-social-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bundle-social/openapi/bundle-social-organization-api-openapi.yml
- filename: bundle-social-post-api-openapi.yml
  format: yaml
  label: bundle.social Post API
  slug: bundle-social-post-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bundle-social/openapi/bundle-social-post-api-openapi.yml
- filename: bundle-social-postcsv-api-openapi.yml
  format: yaml
  label: bundle.social Post CSV API
  slug: bundle-social-postcsv-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bundle-social/openapi/bundle-social-postcsv-api-openapi.yml
- filename: bundle-social-postimport-api-openapi.yml
  format: yaml
  label: bundle.social Post Import API
  slug: bundle-social-postimport-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bundle-social/openapi/bundle-social-postimport-api-openapi.yml
- filename: bundle-social-socialaccount-api-openapi.yml
  format: yaml
  label: bundle.social Social Account API
  slug: bundle-social-socialaccount-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bundle-social/openapi/bundle-social-socialaccount-api-openapi.yml
- filename: bundle-social-team-api-openapi.yml
  format: yaml
  label: bundle.social Team API
  slug: bundle-social-team-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bundle-social/openapi/bundle-social-team-api-openapi.yml
- filename: bundle-social-upload-api-openapi.yml
  format: yaml
  label: bundle.social Upload API
  slug: bundle-social-upload-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bundle-social/openapi/bundle-social-upload-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Trust Services Criteria, assessed control by control
    text: We assess ourselves against the SOC 2 Trust Services Criteria and ISO/IEC 27001:2022 Annex A, control by control
    type: self-assessment
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: ISO/IEC 27001:2022 Annex A
    text: We run an internal assessment against the SOC 2 Trust Services Criteria and ISO/IEC 27001:2022 Annex A, and share an overview of it on request.
    type: self-assessment
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: GDPR run as a working process
    text: run GDPR as a working process rather than a page of promises
    type: self-assessment
  trust_center:
    url: https://bundle.social/trust
frameworks:
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: bundle.social
provenance_date: '2026-11-09'
provider_name: bundle.social
provider_slug: bundle-social
slug: bundle-social-compliance
source_date: '2026-11-09'
source_filename: bundle-social-compliance.yml
source_heading: Compliance
source_page: https://bundle.social/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: bundle.social\naid: bundle-social\nurl: https://bundle.social/trust\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://bundle.social/trust\nattestations:\n- framework: SOC2\n  type: self-assessment\n  scope: Trust Services Criteria, assessed control by control\n  period: null\n  issuer: null\n  report_access: on_request\n  text: We assess ourselves against the SOC 2 Trust Services Criteria and ISO/IEC 27001:2022 Annex A, control by\n    control\n- framework: ISO27001\n  type: self-assessment\n  scope: ISO/IEC 27001:2022 Annex A\n  period: null\n  issuer: null\n  report_access: on_request\n  text: We run\
  \ an internal assessment against the SOC 2 Trust Services Criteria and ISO/IEC 27001:2022 Annex A,\n    and share an overview of it on request.\n- framework: GDPR\n  type: self-assessment\n  scope: GDPR run as a working process\n  period: null\n  issuer: null\n  report_access: unstated\n  text: run GDPR as a working process rather than a page of promises\n"
source_yaml_url: https://artifacts.apis.io/bundle-social/compliance/bundle-social-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from bundle.social's own page on 2026-11-09.
synthetic: false
tags:
- Social
- Media
- Integration
- Unlimited
- Automation
---
