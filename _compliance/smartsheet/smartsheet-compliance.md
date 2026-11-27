---
api_specs:
- filename: smartsheet-columns-api-openapi.yml
  format: yaml
  label: Smartsheet Columns API
  slug: smartsheet-columns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartsheet/openapi/smartsheet-columns-api-openapi.yml
- filename: smartsheet-reports-api-openapi.yml
  format: yaml
  label: Smartsheet Reports API
  slug: smartsheet-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartsheet/openapi/smartsheet-reports-api-openapi.yml
- filename: smartsheet-rows-api-openapi.yml
  format: yaml
  label: Smartsheet Rows API
  slug: smartsheet-rows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartsheet/openapi/smartsheet-rows-api-openapi.yml
- filename: smartsheet-sheets-api-openapi.yml
  format: yaml
  label: Smartsheet Sheets API
  slug: smartsheet-sheets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartsheet/openapi/smartsheet-sheets-api-openapi.yml
- filename: smartsheet-webhooks-api-openapi.yml
  format: yaml
  label: Smartsheet Webhooks API
  slug: smartsheet-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartsheet/openapi/smartsheet-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Smartsheet is built around international privacy standards including GDPR and CCPA, so you stay in control of how your data is handled.
    type: privacy standard
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Smartsheet is built around international privacy standards including GDPR and CCPA, so you stay in control of how your data is handled.
    type: privacy standard
  trust_center:
    url: https://www.smartsheet.com/trust
frameworks:
- CCPA
- GDPR
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Smartsheet
provenance_date: '2026-11-10'
provider_name: Smartsheet
provider_slug: smartsheet
slug: smartsheet-compliance
source_date: '2026-11-10'
source_filename: smartsheet-compliance.yml
source_heading: Compliance
source_page: https://www.smartsheet.com/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Smartsheet\naid: smartsheet\nurl: https://www.smartsheet.com/trust\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/smartsheet-trust-center.yml\ntrust_center:\n  url: https://www.smartsheet.com/trust\nattestations:\n- framework: GDPR\n  type: privacy standard\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Smartsheet is built around international privacy standards including GDPR and CCPA, so you stay in control\n    of how your data is handled.\n- framework: CCPA\n  type: privacy standard\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n \
  \ text: Smartsheet is built around international privacy standards including GDPR and CCPA, so you stay in control\n    of how your data is handled.\n"
source_yaml_url: https://artifacts.apis.io/smartsheet/compliance/smartsheet-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Smartsheet's own page on 2026-11-10.
synthetic: false
tags:
- Work Management
- Project Management
- Collaboration
- Productivity
- Workflow Automation
- Spreadsheets
---
