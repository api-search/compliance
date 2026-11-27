---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: SolarWinds Loggly
    text: 'We currently offer SOC2/Type 2 reports for: SolarWinds Pingdom ® SolarWinds Loggly ® SolarWinds Service Desk SolarWinds Observability SaaS'
    type: SOC 2 Type 2 report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: SolarWinds products and services (monitoring, observability, incident response and service management)
    text: The scope of the ISO/IEC 27001:2022 certification is limited to the information security management system (ISMS) supporting the development, maintenance, operations, and support of the SolarWinds products and services
    type: ISO/IEC 27001:2022 certification
  trust_center:
    url: https://www.solarwinds.com/trust-center
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Loggly
provenance_date: '2026-11-09'
provider_name: Loggly
provider_slug: loggly
slug: loggly-compliance
source_date: '2026-11-09'
source_filename: loggly-compliance.yml
source_heading: Compliance
source_page: https://www.solarwinds.com/trust-center
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Loggly\naid: loggly\nurl: https://www.solarwinds.com/trust-center\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.solarwinds.com/trust-center\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: SolarWinds Loggly\n  period: null\n  issuer: null\n  report_access: on_request\n  text: 'We currently offer SOC2/Type 2 reports for: SolarWinds Pingdom ® SolarWinds Loggly ® SolarWinds Service\n    Desk SolarWinds Observability SaaS'\n- framework: ISO27001\n  type: ISO/IEC 27001:2022 certification\n  scope: SolarWinds products and services (monitoring, observability, incident response\
  \ and service management)\n  period: null\n  issuer: null\n  report_access: on_request\n  text: The scope of the ISO/IEC 27001:2022 certification is limited to the information security management system\n    (ISMS) supporting the development, maintenance, operations, and support of the SolarWinds products and services\n"
source_yaml_url: https://artifacts.apis.io/loggly/compliance/loggly-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Loggly's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Developer Tools
- Logging
- Log Management
- Observability
- Monitoring
- DevOps
- Analytics
- Software-as-a-Service
---
