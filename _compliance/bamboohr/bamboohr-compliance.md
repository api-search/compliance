---
api_specs:
- filename: bamboohr-asyncapi.yml
  format: yaml
  label: BambooHR Webhooks
  slug: webhooks
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/bamboohr/openapi/bamboohr-asyncapi.yml
- filename: bamboohr-directory-api-openapi.yml
  format: yaml
  label: BambooHR Directory API
  slug: bamboohr-directory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bamboohr/openapi/bamboohr-directory-api-openapi.yml
- filename: bamboohr-employees-api-openapi.yml
  format: yaml
  label: BambooHR Employees API
  slug: bamboohr-employees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bamboohr/openapi/bamboohr-employees-api-openapi.yml
- filename: bamboohr-files-api-openapi.yml
  format: yaml
  label: BambooHR Files API
  slug: bamboohr-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bamboohr/openapi/bamboohr-files-api-openapi.yml
- filename: bamboohr-meta-api-openapi.yml
  format: yaml
  label: BambooHR Meta API
  slug: bamboohr-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bamboohr/openapi/bamboohr-meta-api-openapi.yml
- filename: bamboohr-reports-api-openapi.yml
  format: yaml
  label: BambooHR Reports API
  slug: bamboohr-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bamboohr/openapi/bamboohr-reports-api-openapi.yml
- filename: bamboohr-time-off-api-openapi.yml
  format: yaml
  label: BambooHR Time Off API
  slug: bamboohr-time-off-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bamboohr/openapi/bamboohr-time-off-api-openapi.yml
claim_count: 6
description: ''
doc:
  attestations:
  - framework: SOC1
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 1
    type: SOC 1
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type 2
    type: Type 2
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PCI DSS
    type: PCI DSS
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: EU - US DPF
    type: EU-US DPF
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: UK Extension to EU-US DPF
    type: UK Extension to EU-US DPF
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Swiss-US DPF
    type: Swiss-US DPF
  trust_center:
    url: https://trust.bamboohr.com/
frameworks:
- PCI-DSS
- SOC1
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: BambooHR
provenance_date: '2026-11-09'
provider_name: BambooHR
provider_slug: bamboohr
slug: bamboohr-compliance
source_date: '2026-11-09'
source_filename: bamboohr-compliance.yml
source_heading: Compliance
source_page: https://trust.bamboohr.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: BambooHR\naid: bamboohr\nurl: https://trust.bamboohr.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/bamboohr-trust-center.yml\ntrust_center:\n  url: https://trust.bamboohr.com/\nattestations:\n- framework: SOC1\n  type: SOC 1\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 1\n- framework: SOC2\n  type: Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2\n- framework: PCI-DSS\n  type: PCI DSS\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI DSS\n- framework: other\n \
  \ type: EU-US DPF\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: EU - US DPF\n- framework: other\n  type: UK Extension to EU-US DPF\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: UK Extension to EU-US DPF\n- framework: other\n  type: Swiss-US DPF\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Swiss-US DPF\n"
source_yaml_url: https://artifacts.apis.io/bamboohr/compliance/bamboohr-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from BambooHR's own page on 2026-11-09.
synthetic: false
tags:
- Human Resources
- HRIS
- Payroll
- Time Tracking
- Applicant Tracking
- Performance Management
---
