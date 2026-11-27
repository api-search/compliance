---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: FedRAMP
    issuer: Knox Systems
    period: null
    report_access: unstated
    scope: Tractian GovCloud deployed on Knox's FedRAMP High Authorized platform
    text: Tractian GovCloud is now available on Knox Systems'FedRAMP High Authorized platform
    type: FedRAMP High authorization via Knox Systems
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type 2
    type: SOC 2 Type 2
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO-IEC 27001-2022 Certificate
    type: ISO 27001:2022 certificate
  - framework: ISO9001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 9001:2015
    type: ISO 9001:2015
  trust_center:
    url: https://trust.tractian.com/
frameworks:
- FedRAMP
- ISO27001
- ISO9001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Tractian
provenance_date: '2026-11-10'
provider_name: Tractian
provider_slug: tractian
slug: tractian-compliance
source_date: '2026-11-10'
source_filename: tractian-compliance.yml
source_heading: Compliance
source_page: https://trust.tractian.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Tractian\naid: tractian\nurl: https://trust.tractian.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.tractian.com/\nattestations:\n- framework: FedRAMP\n  type: FedRAMP High authorization via Knox Systems\n  scope: Tractian GovCloud deployed on Knox's FedRAMP High Authorized platform\n  period: null\n  issuer: Knox Systems\n  report_access: unstated\n  text: Tractian GovCloud is now available on Knox Systems'FedRAMP High Authorized platform\n- framework: SOC2\n  type: SOC 2 Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2\n- framework:\
  \ ISO27001\n  type: ISO 27001:2022 certificate\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO-IEC 27001-2022 Certificate\n- framework: ISO9001\n  type: ISO 9001:2015\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 9001:2015\n"
source_yaml_url: https://artifacts.apis.io/tractian/compliance/tractian-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Tractian's own page on 2026-11-10.
synthetic: false
tags:
- Condition Monitoring
- Predictive Maintenance
- CMMS
- Asset Management
- Industrial IoT
- Sensors
- Energy Monitoring
- Manufacturing
---
