---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Plume services
    text: 'For access to Plume’s SOC 2 report, please email: infosec@plume.com'
    type: SOC 2 Type 1 certification; Type 2 audit in progress
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Information Security Management System
    text: Plume is ISO/IEC 27001:2022 certified
    type: ISO/IEC 27001:2022 certification
  - framework: ISO27701
    issuer: null
    period: null
    report_access: unstated
    scope: Privacy Information Management System
    text: Plume is ISO/IEC 27701:2019 certified
    type: ISO/IEC 27701:2019 certification
  trust_center:
    url: https://www.plume.com/trust
frameworks:
- ISO27001
- ISO27701
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Plume
provenance_date: '2026-11-10'
provider_name: Plume
provider_slug: plume
slug: plume-compliance
source_date: '2026-11-10'
source_filename: plume-compliance.yml
source_heading: Compliance
source_page: https://www.plume.com/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Plume\naid: plume\nurl: https://www.plume.com/trust\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.plume.com/trust\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 1 certification; Type 2 audit in progress\n  scope: Plume services\n  period: null\n  issuer: null\n  report_access: on_request\n  text: 'For access to Plume’s SOC 2 report, please email: infosec@plume.com'\n- framework: ISO27001\n  type: ISO/IEC 27001:2022 certification\n  scope: Information Security Management System\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Plume is ISO/IEC 27001:2022 certified\n- framework:\
  \ ISO27701\n  type: ISO/IEC 27701:2019 certification\n  scope: Privacy Information Management System\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Plume is ISO/IEC 27701:2019 certified\n"
source_yaml_url: https://artifacts.apis.io/plume/compliance/plume-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Plume's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise
- Wi-Fi
- ISP
- Smart Home
- Network Intelligence
- Cybersecurity
- Software-as-a-Service
- OpenSync
- CPE
- Connectivity
---
