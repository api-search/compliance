---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC1
    issuer: third party
    period: annually
    report_access: on_request
    scope: internal controls over financial reporting
    text: PayNearMe conducts SOC1, SOC2, NACHA, and PCI-DSS audits annually and audit reports can be provided upon request.
    type: audit report
  - framework: SOC2
    issuer: third party
    period: null
    report_access: on_request
    scope: security, availability, and confidentiality
    text: The SOC 2 (System and Organization Controls 2) report verifies that a company’s systems meet strict criteria for security, availability, and confidentiality, building trust with customers and partners.
    type: audit report
  - framework: PCI-DSS
    issuer: Qualified Security Assessor (QSA)
    period: null
    report_access: on_request
    scope: PCI DSS version 4.0.1 at Service Provider Level 1
    text: PayNearMe is certified as compliant under PCI DSS version 4.0.1 at Service Provider Level 1.
    type: attestation of compliance
  - framework: other
    issuer: NACHA
    period: annual ACH audits
    report_access: unstated
    scope: NACHA ACH network processing standards
    text: As a member of the Third Party Payment Processors Association [TPPPA], PayNearMe adheres to the rigorous requirements of NACHA, including successful completion of annual ACH audits.
    type: accreditation
  trust_center:
    url: https://home.paynearme.com/data-security/
frameworks:
- PCI-DSS
- SOC1
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: PayNearMe
provenance_date: '2026-11-10'
provider_name: PayNearMe
provider_slug: paynearme
slug: paynearme-compliance
source_date: '2026-11-10'
source_filename: paynearme-compliance.yml
source_heading: Compliance
source_page: https://home.paynearme.com/data-security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: PayNearMe\naid: paynearme\nurl: https://home.paynearme.com/data-security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://home.paynearme.com/data-security/\nattestations:\n- framework: SOC1\n  type: audit report\n  scope: internal controls over financial reporting\n  period: annually\n  issuer: third party\n  report_access: on_request\n  text: PayNearMe conducts SOC1, SOC2, NACHA, and PCI-DSS audits annually and audit reports can be provided upon\n    request.\n- framework: SOC2\n  type: audit report\n  scope: security, availability, and confidentiality\n  period: null\n  issuer: third party\n  report_access:\
  \ on_request\n  text: The SOC 2 (System and Organization Controls 2) report verifies that a company’s systems meet strict criteria\n    for security, availability, and confidentiality, building trust with customers and partners.\n- framework: PCI-DSS\n  type: attestation of compliance\n  scope: PCI DSS version 4.0.1 at Service Provider Level 1\n  period: null\n  issuer: Qualified Security Assessor (QSA)\n  report_access: on_request\n  text: PayNearMe is certified as compliant under PCI DSS version 4.0.1 at Service Provider Level 1.\n- framework: other\n  type: accreditation\n  scope: NACHA ACH network processing standards\n  period: annual ACH audits\n  issuer: NACHA\n  report_access: unstated\n  text: As a member of the Third Party Payment Processors Association [TPPPA], PayNearMe adheres to the rigorous\n    requirements of NACHA, including successful completion of annual ACH audits.\n"
source_yaml_url: https://artifacts.apis.io/paynearme/compliance/paynearme-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from PayNearMe's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Billing
- ACH
- Cash
- Digital Wallet
- Lending
- iGaming
- Webhook
---
