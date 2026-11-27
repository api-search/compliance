---
api_specs:
- filename: workday-reporting-report-metadata-api-openapi.yml
  format: yaml
  label: Workday Reporting Report Metadata API
  slug: workday-reporting-report-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-reporting/openapi/workday-reporting-report-metadata-api-openapi.yml
- filename: workday-reporting-reports-api-openapi.yml
  format: yaml
  label: Workday Reporting Reports API
  slug: workday-reporting-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-reporting/openapi/workday-reporting-reports-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: defense-in-depth security architecture
    text: Workday is engineered on a defense-in-depth security architecture aligned with ISO 27001, SOC 2 Type II, and NIST Cybersecurity Framework controls.
    type: control alignment
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: defense-in-depth security architecture
    text: Workday is engineered on a defense-in-depth security architecture aligned with ISO 27001, SOC 2 Type II, and NIST Cybersecurity Framework controls.
    type: control alignment
  - framework: NIST-CSF
    issuer: null
    period: null
    report_access: unstated
    scope: defense-in-depth security architecture
    text: Workday is engineered on a defense-in-depth security architecture aligned with ISO 27001, SOC 2 Type II, and NIST Cybersecurity Framework controls.
    type: control alignment
  trust_center:
    url: https://security.workday.com/
frameworks:
- ISO27001
- NIST-CSF
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Workday Reporting
provenance_date: '2026-11-10'
provider_name: Workday Reporting
provider_slug: workday-reporting
slug: workday-reporting-compliance
source_date: '2026-11-10'
source_filename: workday-reporting-compliance.yml
source_heading: Compliance
source_page: https://security.workday.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Workday Reporting\naid: workday-reporting\nurl: https://security.workday.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/workday-reporting-trust-center.yml\ntrust_center:\n  url: https://security.workday.com/\nattestations:\n- framework: ISO27001\n  type: control alignment\n  scope: defense-in-depth security architecture\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Workday is engineered on a defense-in-depth security architecture aligned with ISO 27001, SOC 2 Type II,\n    and NIST Cybersecurity Framework controls.\n- framework: SOC2\n  type: control alignment\n  scope:\
  \ defense-in-depth security architecture\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Workday is engineered on a defense-in-depth security architecture aligned with ISO 27001, SOC 2 Type II,\n    and NIST Cybersecurity Framework controls.\n- framework: NIST-CSF\n  type: control alignment\n  scope: defense-in-depth security architecture\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Workday is engineered on a defense-in-depth security architecture aligned with ISO 27001, SOC 2 Type II,\n    and NIST Cybersecurity Framework controls.\n"
source_yaml_url: https://artifacts.apis.io/workday-reporting/compliance/workday-reporting-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Workday Reporting's own page on 2026-11-10.
synthetic: false
tags:
- Analytics
- Business Intelligence
- Financial Reporting
- HR Data
- Reporting
---
