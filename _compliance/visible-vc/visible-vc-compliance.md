---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Visible platform
    text: Visible undergoes an independent SOC 2 Type II audit annually. Our latest report is available on request
    type: SOC 2 Type II audit
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR EU GDPR Compliant
    type: GDPR compliance
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: Payment processing by Stripe
    text: Payments are processed entirely through Stripe, a PCI Level 1 certified provider.
    type: PCI Level 1 certified provider (Stripe)
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Heroku and AWS infrastructure
    text: These providers undergo independent security assessments, including ISO 27001 certification and SOC audits
    type: ISO 27001 certification of hosting providers
  trust_center:
    url: https://visible.vc/security/
frameworks:
- GDPR
- ISO27001
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Visible.vc
provenance_date: '2026-11-10'
provider_name: Visible.vc
provider_slug: visible-vc
slug: visible-vc-compliance
source_date: '2026-11-10'
source_filename: visible-vc-compliance.yml
source_heading: Compliance
source_page: https://visible.vc/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Visible.vc\naid: visible-vc\nurl: https://visible.vc/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://visible.vc/security/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II audit\n  scope: Visible platform\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Visible undergoes an independent SOC 2 Type II audit annually. Our latest report is available on request\n- framework: GDPR\n  type: GDPR compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR EU GDPR Compliant\n- framework: PCI-DSS\n  type: PCI Level 1 certified provider\
  \ (Stripe)\n  scope: Payment processing by Stripe\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Payments are processed entirely through Stripe, a PCI Level 1 certified provider.\n- framework: ISO27001\n  type: ISO 27001 certification of hosting providers\n  scope: Heroku and AWS infrastructure\n  period: null\n  issuer: null\n  report_access: unstated\n  text: These providers undergo independent security assessments, including ISO 27001 certification and SOC audits\n"
source_yaml_url: https://artifacts.apis.io/visible-vc/compliance/visible-vc-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Visible.vc's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Venture Capital
- Portfolio Management
- Data Analytics
---
