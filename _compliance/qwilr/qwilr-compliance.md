---
claim_count: 6
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: each year
    report_access: unstated
    scope: null
    text: Qwilr completes a SOC 2 Type 2 audit each year
    type: SOC 2 Type 2 audit
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: payment processing via Stripe
    text: Qwilr is PCI-DSS compliant
    type: PCI-DSS compliance
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: insofar as they apply to Qwilr
    text: Qwilr is compliant with GDPR requirements
    type: GDPR compliance
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: electronic signatures
    text: Qwilr is compliant with UETA requirements
    type: UETA compliance (e-signatures)
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: electronic signatures
    text: Qwilr is compliant with the requirements for Electronic Signatures
    type: eIDAS compliance (e-signatures)
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: electronic signatures
    text: Qwilr is compliant with the E-SIGN Act requirements
    type: E-SIGN Act compliance (e-signatures)
  trust_center:
    url: https://qwilr.com/trust-and-security/
frameworks:
- GDPR
- PCI-DSS
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Qwilr
provenance_date: '2026-11-10'
provider_name: Qwilr
provider_slug: qwilr
slug: qwilr-compliance
source_date: '2026-11-10'
source_filename: qwilr-compliance.yml
source_heading: Compliance
source_page: https://qwilr.com/trust-and-security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Qwilr\naid: qwilr\nurl: https://qwilr.com/trust-and-security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/qwilr-trust-center.yml\ntrust_center:\n  url: https://qwilr.com/trust-and-security/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 audit\n  scope: null\n  period: each year\n  issuer: null\n  report_access: unstated\n  text: Qwilr completes a SOC 2 Type 2 audit each year\n- framework: PCI-DSS\n  type: PCI-DSS compliance\n  scope: payment processing via Stripe\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Qwilr is PCI-DSS compliant\n- framework: GDPR\n  type: GDPR\
  \ compliance\n  scope: insofar as they apply to Qwilr\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Qwilr is compliant with GDPR requirements\n- framework: other\n  type: UETA compliance (e-signatures)\n  scope: electronic signatures\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Qwilr is compliant with UETA requirements\n- framework: other\n  type: eIDAS compliance (e-signatures)\n  scope: electronic signatures\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Qwilr is compliant with the requirements for Electronic Signatures\n- framework: other\n  type: E-SIGN Act compliance (e-signatures)\n  scope: electronic signatures\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Qwilr is compliant with the E-SIGN Act requirements\n"
source_yaml_url: https://artifacts.apis.io/qwilr/compliance/qwilr-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from Qwilr's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Proposals
- Documents
- Sales
- Quotes
- Contracts
- E-Signature
- Webhook
- MCP
- Software-as-a-Service
---
