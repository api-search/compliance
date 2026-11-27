---
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: KirkpatrickPrice
    period: annual
    report_access: unstated
    scope: AdvicePay reporting controls relating to security and availability
    text: AdvicePay performs an annual SOC 2 Type II audit that is performed and delivered by CPA firm, KirkpatrickPrice.
    type: SOC 2 Type II audit
  - framework: PCI-DSS
    issuer: AdvicePay self-assessment
    period: annual
    report_access: unstated
    scope: AdvicePay as merchant service provider
    text: As a merchant service provider, AdvicePay performs a PCI Self Assessment Questionnaire (PCI SAQ A) on an annual basis as required by our partner Stripe.
    type: PCI Self Assessment Questionnaire SAQ A
  - framework: PCI-DSS
    issuer: Stripe
    period: null
    report_access: unstated
    scope: Stripe payment processing, used by AdvicePay
    text: Stripe has been audited by a Payment Card Industry (PCI)-certified auditor and is certified to PCI DSS Service Provider Level 1.
    type: PCI DSS Service Provider Level 1 certification (Stripe)
  - framework: SOC2
    issuer: Stripe
    period: annual
    report_access: unstated
    scope: Stripe services used by AdvicePay
    text: Stripe annually performs a SOC 2 Type II audit for compliance.
    type: SOC 2 Type II audit (Stripe)
  - framework: ISO27001
    issuer: Amazon Web Services
    period: null
    report_access: unstated
    scope: Amazon data center operations hosting AdvicePay infrastructure
    text: 'Amazon’s data center operations have been accredited under: ISO 27001, ISO 27017, ISO 27018'
    type: Accreditation (AWS data centers)
  trust_center:
    url: https://advicepay.com/security/
frameworks:
- ISO27001
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: AdvicePay
provenance_date: '2026-11-09'
provider_name: AdvicePay
provider_slug: advicepay
slug: advicepay-compliance
source_date: '2026-11-09'
source_filename: advicepay-compliance.yml
source_heading: Compliance
source_page: https://advicepay.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: AdvicePay\naid: advicepay\nurl: https://advicepay.com/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://advicepay.com/security/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II audit\n  scope: AdvicePay reporting controls relating to security and availability\n  period: annual\n  issuer: KirkpatrickPrice\n  report_access: unstated\n  text: AdvicePay performs an annual SOC 2 Type II audit that is performed and delivered by CPA firm, KirkpatrickPrice.\n- framework: PCI-DSS\n  type: PCI Self Assessment Questionnaire SAQ A\n  scope: AdvicePay as merchant service provider\n  period: annual\n\
  \  issuer: AdvicePay self-assessment\n  report_access: unstated\n  text: As a merchant service provider, AdvicePay performs a PCI Self Assessment Questionnaire (PCI SAQ A) on an\n    annual basis as required by our partner Stripe.\n- framework: PCI-DSS\n  type: PCI DSS Service Provider Level 1 certification (Stripe)\n  scope: Stripe payment processing, used by AdvicePay\n  period: null\n  issuer: Stripe\n  report_access: unstated\n  text: Stripe has been audited by a Payment Card Industry (PCI)-certified auditor and is certified to PCI DSS Service\n    Provider Level 1.\n- framework: SOC2\n  type: SOC 2 Type II audit (Stripe)\n  scope: Stripe services used by AdvicePay\n  period: annual\n  issuer: Stripe\n  report_access: unstated\n  text: Stripe annually performs a SOC 2 Type II audit for compliance.\n- framework: ISO27001\n  type: Accreditation (AWS data centers)\n  scope: Amazon data center operations hosting AdvicePay infrastructure\n  period: null\n  issuer: Amazon Web Services\n\
  \  report_access: unstated\n  text: 'Amazon’s data center operations have been accredited under: ISO 27001, ISO 27017, ISO 27018'\n"
source_yaml_url: https://artifacts.apis.io/advicepay/compliance/advicepay-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from AdvicePay's own page on 2026-11-09.
synthetic: false
tags:
- Financial Services
- Payments
- Billing
- Invoicing
- Financial Planning
- Wealth Management
- Subscription
- E-Signature
- Compliance
- Fintech
---
