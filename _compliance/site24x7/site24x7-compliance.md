---
api_specs:
- filename: site24x7-alarms-api-openapi.yml
  format: yaml
  label: Site24x7 Alarms API
  slug: site24x7-alarms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/site24x7/openapi/site24x7-alarms-api-openapi.yml
- filename: site24x7-current-status-api-openapi.yml
  format: yaml
  label: Site24x7 Current Status API
  slug: site24x7-current-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/site24x7/openapi/site24x7-current-status-api-openapi.yml
- filename: site24x7-maintenance-windows-api-openapi.yml
  format: yaml
  label: Site24x7 Maintenance Windows API
  slug: site24x7-maintenance-windows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/site24x7/openapi/site24x7-maintenance-windows-api-openapi.yml
- filename: site24x7-monitor-groups-api-openapi.yml
  format: yaml
  label: Site24x7 Monitor Groups API
  slug: site24x7-monitor-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/site24x7/openapi/site24x7-monitor-groups-api-openapi.yml
- filename: site24x7-monitors-api-openapi.yml
  format: yaml
  label: Site24x7 Monitors API
  slug: site24x7-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/site24x7/openapi/site24x7-monitors-api-openapi.yml
- filename: site24x7-notification-profiles-api-openapi.yml
  format: yaml
  label: Site24x7 Notification Profiles API
  slug: site24x7-notification-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/site24x7/openapi/site24x7-notification-profiles-api-openapi.yml
- filename: site24x7-outages-api-openapi.yml
  format: yaml
  label: Site24x7 Outages API
  slug: site24x7-outages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/site24x7/openapi/site24x7-outages-api-openapi.yml
- filename: site24x7-reports-api-openapi.yml
  format: yaml
  label: Site24x7 Reports API
  slug: site24x7-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/site24x7/openapi/site24x7-reports-api-openapi.yml
- filename: site24x7-tags-api-openapi.yml
  format: yaml
  label: Site24x7 Tags API
  slug: site24x7-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/site24x7/openapi/site24x7-tags-api-openapi.yml
- filename: site24x7-threshold-profiles-api-openapi.yml
  format: yaml
  label: Site24x7 Threshold Profiles API
  slug: site24x7-threshold-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/site24x7/openapi/site24x7-threshold-profiles-api-openapi.yml
- filename: site24x7-users-api-openapi.yml
  format: yaml
  label: Site24x7 Users API
  slug: site24x7-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/site24x7/openapi/site24x7-users-api-openapi.yml
claim_count: 10
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: nda
    scope: Site24x7 services
    text: ISO/IEC 27001 – Information Security Management System (ISMS)
    type: certification
  - framework: ISO27701
    issuer: null
    period: null
    report_access: nda
    scope: Site24x7 services
    text: ISO/IEC 27701 – Privacy Information Management System (PIMS)
    type: certification
  - framework: ISO27017
    issuer: null
    period: null
    report_access: nda
    scope: Site24x7 services
    text: ISO/IEC 27017 – Cloud Security Controls
    type: certification
  - framework: ISO27018
    issuer: null
    period: null
    report_access: nda
    scope: Site24x7 services
    text: ISO/IEC 27018 – Protection of Personally Identifiable Information (PII) in Public Clouds
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: null
    text: SOC 2 Type II
    type: Type II
  - framework: SOC1
    issuer: null
    period: null
    report_access: nda
    scope: null
    text: SOC 1 Type II
    type: Type II
  - framework: ISO9001
    issuer: null
    period: null
    report_access: nda
    scope: Site24x7 services
    text: ISO 9001 – Quality Management System (QMS)
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA
    type: compliance
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CSA STAR LEVEL ONE
    type: certification
  trust_center:
    url: https://trust.site24x7.com/
frameworks:
- CCPA
- CSA-STAR
- GDPR
- ISO27001
- ISO27017
- ISO27018
- ISO27701
- ISO9001
- SOC1
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Site24x7
provenance_date: '2026-11-10'
provider_name: Site24x7
provider_slug: site24x7
slug: site24x7-compliance
source_date: '2026-11-10'
source_filename: site24x7-compliance.yml
source_heading: Compliance
source_page: https://trust.site24x7.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Site24x7\naid: site24x7\nurl: https://trust.site24x7.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/site24x7-trust-center.yml\ntrust_center:\n  url: https://trust.site24x7.com/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: Site24x7 services\n  period: null\n  issuer: null\n  report_access: nda\n  text: ISO/IEC 27001 – Information Security Management System (ISMS)\n- framework: ISO27701\n  type: certification\n  scope: Site24x7 services\n  period: null\n  issuer: null\n  report_access: nda\n  text: ISO/IEC 27701 – Privacy Information Management System (PIMS)\n- framework:\
  \ ISO27017\n  type: certification\n  scope: Site24x7 services\n  period: null\n  issuer: null\n  report_access: nda\n  text: ISO/IEC 27017 – Cloud Security Controls\n- framework: ISO27018\n  type: certification\n  scope: Site24x7 services\n  period: null\n  issuer: null\n  report_access: nda\n  text: ISO/IEC 27018 – Protection of Personally Identifiable Information (PII) in Public Clouds\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: SOC 2 Type II\n- framework: SOC1\n  type: Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: SOC 1 Type II\n- framework: ISO9001\n  type: certification\n  scope: Site24x7 services\n  period: null\n  issuer: null\n  report_access: nda\n  text: ISO 9001 – Quality Management System (QMS)\n- framework: GDPR\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: CCPA\n  type: compliance\n  scope:\
  \ null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA\n- framework: CSA-STAR\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CSA STAR LEVEL ONE\n"
source_yaml_url: https://artifacts.apis.io/site24x7/compliance/site24x7-compliance.yml
stated_fields:
- attestations
summary_line: 10 quoted statements, read from Site24x7's own page on 2026-11-10.
synthetic: false
tags:
- Monitoring
- Observability
- Uptime
- Infrastructure
- Cloud
- APM
- SLA
- Alerts
- Synthetic Monitoring
- Real User Monitoring
- Network Monitoring
- Server Monitoring
- Website Monitoring
- On-Call
- Status Pages
---
