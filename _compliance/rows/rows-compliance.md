---
api_specs:
- filename: rows-data-api-openapi.yml
  format: yaml
  label: Rows Data API
  slug: rows-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rows/openapi/rows-data-api-openapi.yml
- filename: rows-folders-api-openapi.yml
  format: yaml
  label: Rows Folders API
  slug: rows-folders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rows/openapi/rows-folders-api-openapi.yml
- filename: rows-spreadsheets-api-openapi.yml
  format: yaml
  label: Rows Spreadsheets API
  slug: rows-spreadsheets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rows/openapi/rows-spreadsheets-api-openapi.yml
- filename: rows-vision-api-openapi.yml
  format: yaml
  label: Rows Vision API
  slug: rows-vision-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rows/openapi/rows-vision-api-openapi.yml
- filename: rows-workspaces-api-openapi.yml
  format: yaml
  label: Rows Workspaces API
  slug: rows-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rows/openapi/rows-workspaces-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: security, availability, and confidentiality criteria
    text: 'SOC 2 Type II Certified : This certification confirms that Rows meets strict criteria for security, availability, and confidentiality'
    type: SOC 2 Type II certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: personal data processing for users in the European Union and beyond
    text: 'GDPR Compliant : We ensure that personal data is processed in accordance with the General Data Protection Regulation (GDPR)'
    type: GDPR compliance
  trust_center:
    url: https://rows.com/docs/how-do-you-manage-security
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Rows
provenance_date: '2026-11-10'
provider_name: Rows
provider_slug: rows
slug: rows-compliance
source_date: '2026-11-10'
source_filename: rows-compliance.yml
source_heading: Compliance
source_page: https://rows.com/docs/how-do-you-manage-security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Rows\naid: rows\nurl: https://rows.com/docs/how-do-you-manage-security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://rows.com/docs/how-do-you-manage-security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II certification\n  scope: security, availability, and confidentiality criteria\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'SOC 2 Type II Certified : This certification confirms that Rows meets strict criteria for security, availability,\n    and confidentiality'\n- framework: GDPR\n  type: GDPR compliance\n  scope: personal data processing for users in the European\
  \ Union and beyond\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'GDPR Compliant : We ensure that personal data is processed in accordance with the General Data Protection\n    Regulation (GDPR)'\n"
source_yaml_url: https://artifacts.apis.io/rows/compliance/rows-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Rows's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Productivity
- Spreadsheets
- Data
- No-Code
- Automation
- Artificial Intelligence
- Analytics
- Business Intelligence
---
