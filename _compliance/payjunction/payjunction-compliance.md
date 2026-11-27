---
claim_count: 6
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: '2025'
    report_access: unstated
    scope: null
    text: 2025 PCI DSS v4.0.1 Attestation of Compliance
    type: Attestation of Compliance
  - framework: PCI-DSS
    issuer: null
    period: '2026'
    report_access: unstated
    scope: null
    text: 2026 PCI DSS v4.0.1 Attestation of Compliance
    type: Attestation of Compliance
  - framework: SOC2
    issuer: null
    period: '2025'
    report_access: unstated
    scope: null
    text: 2025 SOC 2 Type II Report
    type: SOC 2 Type II Report
  - framework: HIPAA
    issuer: null
    period: '2025'
    report_access: unstated
    scope: null
    text: 2025 HIPAA Certificate of Compliance
    type: Certificate of Compliance
  - framework: NIST-CSF
    issuer: null
    period: '2025'
    report_access: unstated
    scope: null
    text: 2025 NIST CSF Report
    type: Report
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA COMPLIANT
    type: Compliance
  trust_center:
    url: https://trust.payjunction.com/
frameworks:
- CCPA
- HIPAA
- NIST-CSF
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: PayJunction
provenance_date: '2026-11-10'
provider_name: PayJunction
provider_slug: payjunction
slug: payjunction-compliance
source_date: '2026-11-10'
source_filename: payjunction-compliance.yml
source_heading: Compliance
source_page: https://trust.payjunction.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: PayJunction\naid: payjunction\nurl: https://trust.payjunction.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.payjunction.com/\nattestations:\n- framework: PCI-DSS\n  type: Attestation of Compliance\n  scope: null\n  period: '2025'\n  issuer: null\n  report_access: unstated\n  text: 2025 PCI DSS v4.0.1 Attestation of Compliance\n- framework: PCI-DSS\n  type: Attestation of Compliance\n  scope: null\n  period: '2026'\n  issuer: null\n  report_access: unstated\n  text: 2026 PCI DSS v4.0.1 Attestation of Compliance\n- framework: SOC2\n  type: SOC 2 Type II Report\n  scope: null\n  period: '2025'\n\
  \  issuer: null\n  report_access: unstated\n  text: 2025 SOC 2 Type II Report\n- framework: HIPAA\n  type: Certificate of Compliance\n  scope: null\n  period: '2025'\n  issuer: null\n  report_access: unstated\n  text: 2025 HIPAA Certificate of Compliance\n- framework: NIST-CSF\n  type: Report\n  scope: null\n  period: '2025'\n  issuer: null\n  report_access: unstated\n  text: 2025 NIST CSF Report\n- framework: CCPA\n  type: Compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA COMPLIANT\n"
source_yaml_url: https://artifacts.apis.io/payjunction/compliance/payjunction-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from PayJunction's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- Fintech
- Software-as-a-Service
- B2B
---
