---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: on_request
    scope: payment processing
    text: Flywire maintains PCI Level 1 Certification with third-party attestations—the highest level.
    type: PCI Level 1 Certification with third-party attestations
  - framework: SOC2
    issuer: null
    period: annual
    report_access: on_request
    scope: information management processes
    text: Flywire undergoes an annual SOC 2 Type II audit supporting information management processes.
    type: SOC 2 Type II audit
  - framework: HITRUST
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HITRUST Global Registry of Service Providers
    type: HITRUST Global Registry of Service Providers
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CSA STAR Registry
    type: CSA STAR Registry
  trust_center:
    url: https://www.flywire.com/company/security
frameworks:
- CSA-STAR
- HITRUST
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Flywire
provenance_date: '2026-11-09'
provider_name: Flywire
provider_slug: flywire
slug: flywire-compliance
source_date: '2026-11-09'
source_filename: flywire-compliance.yml
source_heading: Compliance
source_page: https://www.flywire.com/company/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Flywire\naid: flywire\nurl: https://www.flywire.com/company/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.flywire.com/company/security\nattestations:\n- framework: PCI-DSS\n  type: PCI Level 1 Certification with third-party attestations\n  scope: payment processing\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Flywire maintains PCI Level 1 Certification with third-party attestations—the highest level.\n- framework: SOC2\n  type: SOC 2 Type II audit\n  scope: information management processes\n  period: annual\n  issuer: null\n  report_access: on_request\n  text:\
  \ Flywire undergoes an annual SOC 2 Type II audit supporting information management processes.\n- framework: HITRUST\n  type: HITRUST Global Registry of Service Providers\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HITRUST Global Registry of Service Providers\n- framework: CSA-STAR\n  type: CSA STAR Registry\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CSA STAR Registry\n"
source_yaml_url: https://artifacts.apis.io/flywire/compliance/flywire-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Flywire's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Cross-Border Payments
- Fintech
- Education Payments
- Healthcare Payments
- Travel Payments
- B2B Payments
- Checkout
- Webhook
---
