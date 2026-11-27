---
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: security, availability, and confidentiality trust services criteria
    text: SardineAI Corp. has successfully completed a System and Organization Controls (SOC) 2 Type II audit, report available under 'Resources'.
    type: SOC 2 Type II audit
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Sardine PCI-DSS-v4_0_1-SAQ-A_Sardine_AI (2026-03-13).pdf
    type: PCI DSS SAQ A
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 GDPR CCPA COMPLIANT CCPA
    type: compliance badge
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA COMPLIANT CCPA
    type: compliance badge
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://www.sardine.ai/security
    text: Trust Center with SOC2, pentest reports, and other security documentation
    type: SOC2 report referenced via Trust Center
  trust_center:
    url: https://security.sardine.ai/
frameworks:
- CCPA
- GDPR
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Sardine
provenance_date: '2026-11-10'
provider_name: Sardine
provider_slug: sardine-ai
slug: sardine-ai-compliance
source_date: '2026-11-10'
source_filename: sardine-ai-compliance.yml
source_heading: Compliance
source_page: https://security.sardine.ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Sardine\naid: sardine-ai\nurl: https://security.sardine.ai/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/sardine-ai-trust-center.yml\n  sources:\n  - https://security.sardine.ai/\n  - https://www.sardine.ai/security\ntrust_center:\n  url: https://security.sardine.ai/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II audit\n  scope: security, availability, and confidentiality trust services criteria\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SardineAI Corp. has successfully completed a System and Organization Controls (SOC) 2 Type II audit, report\n    available\
  \ under 'Resources'.\n- framework: PCI-DSS\n  type: PCI DSS SAQ A\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Sardine PCI-DSS-v4_0_1-SAQ-A_Sardine_AI (2026-03-13).pdf\n- framework: GDPR\n  type: compliance badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 GDPR CCPA COMPLIANT CCPA\n- framework: CCPA\n  type: compliance badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA COMPLIANT CCPA\n- framework: SOC2\n  type: SOC2 report referenced via Trust Center\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Trust Center with SOC2, pentest reports, and other security documentation\n  source: https://www.sardine.ai/security\n"
source_yaml_url: https://artifacts.apis.io/sardine-ai/compliance/sardine-ai-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Sardine's own page on 2026-11-10.
synthetic: false
tags:
- Fraud Prevention
- AML
- Compliance
- KYC
- KYB
- Identity Verification
- Transaction Monitoring
- Device Intelligence
- Behavioral Biometrics
- Risk Management
- Financial Crime
- AI Agents
- Fintech
---
