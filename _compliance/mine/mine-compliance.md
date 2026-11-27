---
api_specs:
- filename: mine-aispm-api-openapi.yml
  format: yaml
  label: MINE Aispm API
  slug: mine-aispm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mine/openapi/mine-aispm-api-openapi.yml
- filename: mine-aispmdeviceflags-api-openapi.yml
  format: yaml
  label: MINE AispmDeviceFlags API
  slug: mine-aispmdeviceflags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mine/openapi/mine-aispmdeviceflags-api-openapi.yml
- filename: mine-aispmenroll-api-openapi.yml
  format: yaml
  label: MINE AispmEnroll API
  slug: mine-aispmenroll-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mine/openapi/mine-aispmenroll-api-openapi.yml
- filename: mine-aispmenrollmenttokens-api-openapi.yml
  format: yaml
  label: MINE AispmEnrollmentTokens API
  slug: mine-aispmenrollmenttokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mine/openapi/mine-aispmenrollmenttokens-api-openapi.yml
- filename: mine-aispmingest-api-openapi.yml
  format: yaml
  label: MINE AispmIngest API
  slug: mine-aispmingest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mine/openapi/mine-aispmingest-api-openapi.yml
- filename: mine-aispminsights-api-openapi.yml
  format: yaml
  label: MINE AispmInsights API
  slug: mine-aispminsights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mine/openapi/mine-aispminsights-api-openapi.yml
- filename: mine-aispmpublicagents-api-openapi.yml
  format: yaml
  label: MINE AispmPublicAgents API
  slug: mine-aispmpublicagents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mine/openapi/mine-aispmpublicagents-api-openapi.yml
- filename: mine-aispmpublicdevices-api-openapi.yml
  format: yaml
  label: MINE AispmPublicDevices API
  slug: mine-aispmpublicdevices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mine/openapi/mine-aispmpublicdevices-api-openapi.yml
- filename: mine-assessment-api-openapi.yml
  format: yaml
  label: MINE Assessment API
  slug: mine-assessment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mine/openapi/mine-assessment-api-openapi.yml
- filename: mine-assessmenttemplate-api-openapi.yml
  format: yaml
  label: MINE AssessmentTemplate API
  slug: mine-assessmenttemplate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mine/openapi/mine-assessmenttemplate-api-openapi.yml
- filename: mine-employee-api-openapi.yml
  format: yaml
  label: MINE Employee API
  slug: mine-employee-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mine/openapi/mine-employee-api-openapi.yml
- filename: mine-evidencesearch-api-openapi.yml
  format: yaml
  label: MINE EvidenceSearch API
  slug: mine-evidencesearch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mine/openapi/mine-evidencesearch-api-openapi.yml
- filename: mine-partners-api-openapi.yml
  format: yaml
  label: MINE Partners API
  slug: mine-partners-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mine/openapi/mine-partners-api-openapi.yml
- filename: mine-privacyrightspublic-api-openapi.yml
  format: yaml
  label: MINE PrivacyRightsPublic API
  slug: mine-privacyrightspublic-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mine/openapi/mine-privacyrightspublic-api-openapi.yml
- filename: mine-system-api-openapi.yml
  format: yaml
  label: MINE System API
  slug: mine-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mine/openapi/mine-system-api-openapi.yml
- filename: mine-test-api-openapi.yml
  format: yaml
  label: MINE Test API
  slug: mine-test-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mine/openapi/mine-test-api-openapi.yml
- filename: mine-tickets-api-openapi.yml
  format: yaml
  label: MINE Tickets API
  slug: mine-tickets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mine/openapi/mine-tickets-api-openapi.yml
- filename: mine-webhooks-api-openapi.yml
  format: yaml
  label: MINE Webhooks API
  slug: mine-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mine/openapi/mine-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: MineOS
    text: MineOS operates with certifications for ISO/IEC 27001:2013 & SOC 2 Type 2
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: MineOS
    text: MineOS operates with certifications for ISO/IEC 27001:2013 & SOC 2 Type 2
    type: Type 2
  trust_center:
    url: https://mineos.ai/about-security
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: MINE
provenance_date: '2026-11-10'
provider_name: MINE
provider_slug: mine
slug: mine-compliance
source_date: '2026-11-10'
source_filename: mine-compliance.yml
source_heading: Compliance
source_page: https://mineos.ai/about-security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: MINE\naid: mine\nurl: https://mineos.ai/about-security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://mineos.ai/about-security\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: MineOS\n  period: null\n  issuer: null\n  report_access: unstated\n  text: MineOS operates with certifications for ISO/IEC 27001:2013 & SOC 2 Type 2\n- framework: SOC2\n  type: Type 2\n  scope: MineOS\n  period: null\n  issuer: null\n  report_access: unstated\n  text: MineOS operates with certifications for ISO/IEC 27001:2013 & SOC 2 Type 2\n"
source_yaml_url: https://artifacts.apis.io/mine/compliance/mine-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from MINE's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Privacy
- Data Governance
- Privacy Operations
- Consent Management
- AI Governance
- Third-Party Risk Management
- Compliance
- Security
---
