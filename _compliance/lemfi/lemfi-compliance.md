---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Request SOC 2 Type II - Bridge Letter Request PCI DSS Certificate Request PCI DSS AOC Report
    type: SOC 2 Type II report
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Request PCI DSS Certificate Request PCI DSS AOC Report
    type: PCI DSS certificate and AOC report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Compliance SOC 2 PCI GDPR
    type: compliance listing
  trust_center:
    url: https://trust.lemfi.com/
frameworks:
- GDPR
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: LemFi
provenance_date: '2026-11-09'
provider_name: LemFi
provider_slug: lemfi
slug: lemfi-compliance
source_date: '2026-11-09'
source_filename: lemfi-compliance.yml
source_heading: Compliance
source_page: https://trust.lemfi.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: LemFi\naid: lemfi\nurl: https://trust.lemfi.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/lemfi-trust-center.yml\ntrust_center:\n  url: https://trust.lemfi.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Request SOC 2 Type II - Bridge Letter Request PCI DSS Certificate Request PCI DSS AOC Report\n- framework: PCI-DSS\n  type: PCI DSS certificate and AOC report\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Request PCI DSS Certificate Request PCI DSS\
  \ AOC Report\n- framework: GDPR\n  type: compliance listing\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliance SOC 2 PCI GDPR\n"
source_yaml_url: https://artifacts.apis.io/lemfi/compliance/lemfi-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from LemFi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- Payments
- Remittances
- Cross-Border Payments
- Money Transfer
- Consumer Finance
- Mobile Banking
- eSIM
---
