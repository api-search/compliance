---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: third party auditor
    period: null
    report_access: unstated
    scope: security, availability, processing integrity, confidentiality, and privacy
    text: This is a third party report conducted by an auditor assuring that KOHO’s controls on security, availability, processing integrity, confidentiality, and privacy are sufficient.
    type: Type 2
  - framework: PCI-DSS
    issuer: PCI Qualified Security Assessor (QSA)
    period: annually
    report_access: unstated
    scope: dedicated environment storing payment card data
    text: Your payment card data is securely stored away in a dedicated environment that’s audited annually by a PCI Qualified Security Assessor (QSA).
    type: annual QSA audit
  - framework: other
    issuer: FINTRAC
    period: null
    report_access: unstated
    scope: money services business activities
    text: KOHO is regulated as a Money Service Business (MSB) by FINTRAC.
    type: Money Service Business registration
  trust_center:
    url: https://www.koho.ca/security/
frameworks:
- PCI-DSS
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: KOHO
provenance_date: '2026-11-09'
provider_name: KOHO
provider_slug: koho
slug: koho-compliance
source_date: '2026-11-09'
source_filename: koho-compliance.yml
source_heading: Compliance
source_page: https://www.koho.ca/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: KOHO\naid: koho\nurl: https://www.koho.ca/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.koho.ca/security/\nattestations:\n- framework: SOC2\n  type: Type 2\n  scope: security, availability, processing integrity, confidentiality, and privacy\n  period: null\n  issuer: third party auditor\n  report_access: unstated\n  text: This is a third party report conducted by an auditor assuring that KOHO’s controls on security, availability,\n    processing integrity, confidentiality, and privacy are sufficient.\n- framework: PCI-DSS\n  type: annual QSA audit\n  scope: dedicated environment storing\
  \ payment card data\n  period: annually\n  issuer: PCI Qualified Security Assessor (QSA)\n  report_access: unstated\n  text: Your payment card data is securely stored away in a dedicated environment that’s audited annually by a PCI\n    Qualified Security Assessor (QSA).\n- framework: other\n  type: Money Service Business registration\n  scope: money services business activities\n  period: null\n  issuer: FINTRAC\n  report_access: unstated\n  text: KOHO is regulated as a Money Service Business (MSB) by FINTRAC.\n"
source_yaml_url: https://artifacts.apis.io/koho/compliance/koho-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from KOHO's own page on 2026-11-09.
synthetic: false
tags:
- Financial Services
- Banking
- Canada
- Fintech
- Neobank
- Payments
- Interac
- Consumer-Driven Banking
---
