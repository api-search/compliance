---
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC1
    issuer: independent third party auditor
    period: null
    report_access: on_request
    scope: Maestro
    text: Annual SOC1 Type II reports
    type: Type II audit
  - framework: SOC2
    issuer: independent third party auditor
    period: null
    report_access: on_request
    scope: Maestro
    text: Annual SOC2 Type II reports
    type: Type II audit
  - framework: C5
    issuer: German Federal Office for Information Security (BSI) framework
    period: null
    report_access: on_request
    scope: Maestro
    text: Annual BSI-C5 Type II reports
    type: Type II audit
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: Kinaxis operations
    text: Kinaxis is certified under ISO 27001:2022, the international standard for information security management systems (ISMS)
    type: certificate
  - framework: CSA-STAR
    issuer: Cloud Security Alliance
    period: null
    report_access: public
    scope: Kinaxis
    text: Kinaxis is a Cloud Security Alliance Trusted Cloud Provider and maintains STAR Registry level 1.
    type: STAR Registry level 1
  trust_center:
    url: https://www.kinaxis.com/en/trust-center
frameworks:
- C5
- CSA-STAR
- ISO27001
- SOC1
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Kinaxis
provenance_date: '2026-11-09'
provider_name: Kinaxis
provider_slug: kinaxis
slug: kinaxis-compliance
source_date: '2026-11-09'
source_filename: kinaxis-compliance.yml
source_heading: Compliance
source_page: https://www.kinaxis.com/en/trust-center
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Kinaxis\naid: kinaxis\nurl: https://www.kinaxis.com/en/trust-center\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.kinaxis.com/en/trust-center\nattestations:\n- framework: SOC1\n  type: Type II audit\n  scope: Maestro\n  period: null\n  issuer: independent third party auditor\n  report_access: on_request\n  text: Annual SOC1 Type II reports\n- framework: SOC2\n  type: Type II audit\n  scope: Maestro\n  period: null\n  issuer: independent third party auditor\n  report_access: on_request\n  text: Annual SOC2 Type II reports\n- framework: C5\n  type: Type II audit\n  scope: Maestro\n  period: null\n\
  \  issuer: German Federal Office for Information Security (BSI) framework\n  report_access: on_request\n  text: Annual BSI-C5 Type II reports\n- framework: ISO27001\n  type: certificate\n  scope: Kinaxis operations\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Kinaxis is certified under ISO 27001:2022, the international standard for information security management\n    systems (ISMS)\n- framework: CSA-STAR\n  type: STAR Registry level 1\n  scope: Kinaxis\n  period: null\n  issuer: Cloud Security Alliance\n  report_access: public\n  text: Kinaxis is a Cloud Security Alliance Trusted Cloud Provider and maintains STAR Registry level 1.\n"
source_yaml_url: https://artifacts.apis.io/kinaxis/compliance/kinaxis-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Kinaxis's own page on 2026-11-09.
synthetic: false
tags:
- Supply Chain
- Supply Chain Planning
- Demand Sensing
- Scenario Modeling
- Supply Planning
- Inventory Optimization
- S&OP
- Control Tower
- Enterprise Software
- Artificial Intelligence
- Canada
---
