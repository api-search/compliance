---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: BillGO security controls
    text: BillGO undergoes annual SOC 1 Type I and SOC 2 Type II audits to ensure its security controls meet industry standards.
    type: SOC 2 Type II audit
  - framework: SOC1
    issuer: null
    period: null
    report_access: unstated
    scope: BillGO security controls
    text: BillGO undergoes annual SOC 1 Type I and SOC 2 Type II audits to ensure its security controls meet industry standards.
    type: SOC 1 Type I audit
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: BillGO Exchange card payments
    text: As a certified Level 1 PCI-compliant card issuer, we adhere to the highest security standards.
    type: Level 1 PCI compliant card issuer
  trust_center:
    url: https://billgo.com/security
frameworks:
- PCI-DSS
- SOC1
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: BillGO
provenance_date: '2026-11-09'
provider_name: BillGO
provider_slug: billgo
slug: billgo-compliance
source_date: '2026-11-09'
source_filename: billgo-compliance.yml
source_heading: Compliance
source_page: https://billgo.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: BillGO\naid: billgo\nurl: https://billgo.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://billgo.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II audit\n  scope: BillGO security controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: BillGO undergoes annual SOC 1 Type I and SOC 2 Type II audits to ensure its security controls meet industry\n    standards.\n- framework: SOC1\n  type: SOC 1 Type I audit\n  scope: BillGO security controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: BillGO undergoes annual SOC 1 Type I and SOC\
  \ 2 Type II audits to ensure its security controls meet industry\n    standards.\n- framework: PCI-DSS\n  type: Level 1 PCI compliant card issuer\n  scope: BillGO Exchange card payments\n  period: null\n  issuer: null\n  report_access: unstated\n  text: As a certified Level 1 PCI-compliant card issuer, we adhere to the highest security standards.\n"
source_yaml_url: https://artifacts.apis.io/billgo/compliance/billgo-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from BillGO's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- Bill Pay
- Financial Services
- Banking
- ACH
- Virtual Cards
- Fintech
- GraphQL
---
