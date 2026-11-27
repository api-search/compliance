---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: SOC 2 Type II
    type: SOC 2 Type II report
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: FedRAMP Moderate Rev. 5
    type: FedRAMP Moderate Rev. 5
  - framework: ISO27001
    issuer: Standards Institution of Israel (SII)
    period: null
    report_access: on_request
    scope: 'Hexagate: development and design of blockchain security products, including monitoring and supporting infrastructure'
    text: 'Scope: The certification covers the development and design of blockchain security products, including monitoring and supporting infrastructure.'
    type: ISO/IEC 27001:2022 certification
  - framework: CyberEssentials
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Cyber Essentials
    type: Cyber Essentials
  trust_center:
    url: https://trust.chainalysis.com/
frameworks:
- CyberEssentials
- FedRAMP
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Chainalysis
provenance_date: '2026-11-09'
provider_name: Chainalysis
provider_slug: chainalysis
slug: chainalysis-compliance
source_date: '2026-11-09'
source_filename: chainalysis-compliance.yml
source_heading: Compliance
source_page: https://trust.chainalysis.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Chainalysis\naid: chainalysis\nurl: https://trust.chainalysis.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.chainalysis.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Type II\n- framework: FedRAMP\n  type: FedRAMP Moderate Rev. 5\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: FedRAMP Moderate Rev. 5\n- framework: ISO27001\n  type: ISO/IEC 27001:2022 certification\n  scope: 'Hexagate: development and design of blockchain security products, including\
  \ monitoring and supporting\n    infrastructure'\n  period: null\n  issuer: Standards Institution of Israel (SII)\n  report_access: on_request\n  text: 'Scope: The certification covers the development and design of blockchain security products, including monitoring\n    and supporting infrastructure.'\n- framework: CyberEssentials\n  type: Cyber Essentials\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Cyber Essentials\n"
source_yaml_url: https://artifacts.apis.io/chainalysis/compliance/chainalysis-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Chainalysis's own page on 2026-11-09.
synthetic: false
tags:
- Compliance
- AML
- Transaction Monitoring
- Sanctions
- Investigations
- Blockchain Analytics
- Risk Management
- Cryptocurrency
---
