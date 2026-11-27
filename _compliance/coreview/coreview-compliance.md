---
api_specs:
- filename: coreview-connect-api-openapi.yml
  format: yaml
  label: CoreView Connect API
  slug: coreview-connect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coreview/openapi/coreview-connect-api-openapi.yml
- filename: coreview-public-api-openapi.yml
  format: yaml
  label: CoreView Public API
  slug: coreview-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coreview/openapi/coreview-public-api-openapi.yml
- filename: coreview-teams-api-openapi.yml
  format: yaml
  label: CoreView Teams API
  slug: coreview-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coreview/openapi/coreview-teams-api-openapi.yml
claim_count: 6
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: CoreView
    text: CoreView is ISO 27001 and ISO 27018 certified
    type: certification
  - framework: ISO27018
    issuer: null
    period: null
    report_access: unstated
    scope: CoreView
    text: CoreView is ISO 27001 and ISO 27018 certified
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: CoreView
    text: CoreView holds SOC 2 Type II and SOC 3 compliance
    type: Type II report
  - framework: SOC3
    issuer: null
    period: null
    report_access: unstated
    scope: CoreView
    text: CoreView holds SOC 2 Type II and SOC 3 compliance
    type: report
  - framework: ISO9001
    issuer: null
    period: null
    report_access: unstated
    scope: CoreView
    text: Our ISO 9001 certification reflects CoreView’s dedication to quality and customer satisfaction.
    type: certification
  - framework: IRAP
    issuer: null
    period: null
    report_access: unstated
    scope: CoreView
    text: CoreView is IRAP certified, ensuring alignment with the Australian government’s stringent security requirements.
    type: certification
  trust_center:
    url: https://www.coreview.com/security
frameworks:
- IRAP
- ISO27001
- ISO27018
- ISO9001
- SOC2
- SOC3
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: CoreView
provenance_date: '2026-11-09'
provider_name: CoreView
provider_slug: coreview
slug: coreview-compliance
source_date: '2026-11-09'
source_filename: coreview-compliance.yml
source_heading: Compliance
source_page: https://www.coreview.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: CoreView\naid: coreview\nurl: https://www.coreview.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.coreview.com/security\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: CoreView\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CoreView is ISO 27001 and ISO 27018 certified\n- framework: ISO27018\n  type: certification\n  scope: CoreView\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CoreView is ISO 27001 and ISO 27018 certified\n- framework: SOC2\n  type: Type II report\n  scope: CoreView\n  period: null\n  issuer: null\n\
  \  report_access: unstated\n  text: CoreView holds SOC 2 Type II and SOC 3 compliance\n- framework: SOC3\n  type: report\n  scope: CoreView\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CoreView holds SOC 2 Type II and SOC 3 compliance\n- framework: ISO9001\n  type: certification\n  scope: CoreView\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our ISO 9001 certification reflects CoreView’s dedication to quality and customer satisfaction.\n- framework: IRAP\n  type: certification\n  scope: CoreView\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CoreView is IRAP certified, ensuring alignment with the Australian government’s stringent security requirements.\n"
source_yaml_url: https://artifacts.apis.io/coreview/compliance/coreview-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from CoreView's own page on 2026-11-09.
synthetic: false
tags:
- Microsoft 365
- Tenant Resilience
- Configuration Management
- Identity Security
- License Optimization
- SharePoint Control
- Enterprise Saas
---
