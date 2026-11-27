---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: Armanino
    period: null
    report_access: unstated
    scope: controls around security, availability, and confidentiality of customer data
    text: Unit21 partnered with Armanino, one of the largest independent business auditing firms in the country to attest to Unit21's compliance with SOC 2 Type I and Type II stringent standards.
    type: SOC 2 Type I and Type II attestation
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: personal data of EU individuals
    text: Unit21 is compliant with both the GDPR and CCPA.
    type: compliance with regulation
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: personal data of California residents
    text: Unit21 is compliant with both the GDPR and CCPA.
    type: compliance with regulation
  trust_center:
    url: https://www.unit21.ai/security
frameworks:
- CCPA
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Unit21
provenance_date: '2026-11-10'
provider_name: Unit21
provider_slug: unit21
slug: unit21-compliance
source_date: '2026-11-10'
source_filename: unit21-compliance.yml
source_heading: Compliance
source_page: https://www.unit21.ai/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Unit21\naid: unit21\nurl: https://www.unit21.ai/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/unit21-trust-center.yml\ntrust_center:\n  url: https://www.unit21.ai/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type I and Type II attestation\n  scope: controls around security, availability, and confidentiality of customer data\n  period: null\n  issuer: Armanino\n  report_access: unstated\n  text: Unit21 partnered with Armanino, one of the largest independent business auditing firms in the country to\n    attest to Unit21's compliance with SOC 2 Type I and Type II stringent standards.\n\
  - framework: GDPR\n  type: compliance with regulation\n  scope: personal data of EU individuals\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Unit21 is compliant with both the GDPR and CCPA.\n- framework: CCPA\n  type: compliance with regulation\n  scope: personal data of California residents\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Unit21 is compliant with both the GDPR and CCPA.\n"
source_yaml_url: https://artifacts.apis.io/unit21/compliance/unit21-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Unit21's own page on 2026-11-10.
synthetic: false
tags:
- Fraud Prevention
- AML
- Compliance
- Fintech
- Transaction Monitoring
- Risk Management
- SAR
- Financial Crime
- Suspicious Activity Reports
---
