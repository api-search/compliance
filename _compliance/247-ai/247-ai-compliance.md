---
claim_count: 9
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: third-party auditors
    period: null
    report_access: unstated
    scope: managing customer data based on AICPA Trust Service Principles
    text: In addition to our 3rd party tested SOC 2 Type 2, [24]7 is compliant with Health Insurance Portability and Accountability Act (HIPAA).
    type: SOC 2 Type 2 attestation
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Privacy, Security, and Breach Notification Rules
    text: We ensure our compliance with all HIPAA Rules (Privacy, Security, and Breach Notification) and adhere to the regulated Administrative, Physical, and Technical Safeguards.
    type: compliance with HIPAA Rules
  - framework: ISO27001
    issuer: independent third-party auditors
    period: null
    report_access: unstated
    scope: Information Security Management System
    text: ISO/IEC 27001:2022 is a security management standard that specifies security management best practices and comprehensive security controls following the ISO/IEC best practice guidance.
    type: certification
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: cardholder data and sensitive authentication data
    text: In addition to our own compliance, [24]7.ai is committed to offering services and resources to our customers to help them comply with PCI DSS requirements that may apply to their activities.
    type: compliance
  - framework: GDPR
    issuer: third-party auditors
    period: null
    report_access: unstated
    scope: EU personal data protection
    text: Customers can transfer data from EU regions to the US regions with the knowledge that [24]7.ai is compliant with EU data protection requirements.
    type: compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: California consumer privacy rights
    text: In addition to our own compliance, [24]7.ai is committed to offering services and resources to our customers to help them comply with CCPA requirements that may apply to their activities.
    type: compliance support
  - framework: other
    issuer: global forum listing
    period: null
    report_access: unstated
    scope: APEC Cross-Border Privacy Rules System
    text: are listed in the global forum listing for all organisation under APEC CBPR.
    type: APEC CBPR certification listing
  - framework: NIST-800-53
    issuer: null
    period: null
    report_access: unstated
    scope: security, privacy and risk controls
    text: '[24]7.ai internally evaluates security, privacy, risk, and security status against the U.S. Commerce Department’s National Institute of Standards and Technology (NIST) SP 800-53 R4/R5'
    type: internal evaluation
  - framework: NIST-CSF
    issuer: null
    period: null
    report_access: unstated
    scope: cybersecurity risk framework
    text: and the NIST Cybersecurity Framework (CSF).
    type: internal evaluation
  trust_center:
    url: https://www.247.ai/security/
frameworks:
- CCPA
- GDPR
- HIPAA
- ISO27001
- NIST-800-53
- NIST-CSF
- PCI-DSS
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: '[24]7.ai'
provenance_date: '2026-11-09'
provider_name: '[24]7.ai'
provider_slug: 247-ai
slug: 247-ai-compliance
source_date: '2026-11-09'
source_filename: 247-ai-compliance.yml
source_heading: Compliance
source_page: https://www.247.ai/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: '[24]7.ai'\naid: 247-ai\nurl: https://www.247.ai/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.247.ai/security/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 attestation\n  scope: managing customer data based on AICPA Trust Service Principles\n  period: null\n  issuer: third-party auditors\n  report_access: unstated\n  text: In addition to our 3rd party tested SOC 2 Type 2, [24]7 is compliant with Health Insurance Portability and\n    Accountability Act (HIPAA).\n- framework: HIPAA\n  type: compliance with HIPAA Rules\n  scope: Privacy, Security, and Breach Notification Rules\n\
  \  period: null\n  issuer: null\n  report_access: unstated\n  text: We ensure our compliance with all HIPAA Rules (Privacy, Security, and Breach Notification) and adhere to\n    the regulated Administrative, Physical, and Technical Safeguards.\n- framework: ISO27001\n  type: certification\n  scope: Information Security Management System\n  period: null\n  issuer: independent third-party auditors\n  report_access: unstated\n  text: ISO/IEC 27001:2022 is a security management standard that specifies security management best practices and\n    comprehensive security controls following the ISO/IEC best practice guidance.\n- framework: PCI-DSS\n  type: compliance\n  scope: cardholder data and sensitive authentication data\n  period: null\n  issuer: null\n  report_access: unstated\n  text: In addition to our own compliance, [24]7.ai is committed to offering services and resources to our customers\n    to help them comply with PCI DSS requirements that may apply to their activities.\n- framework:\
  \ GDPR\n  type: compliance\n  scope: EU personal data protection\n  period: null\n  issuer: third-party auditors\n  report_access: unstated\n  text: Customers can transfer data from EU regions to the US regions with the knowledge that [24]7.ai is compliant\n    with EU data protection requirements.\n- framework: CCPA\n  type: compliance support\n  scope: California consumer privacy rights\n  period: null\n  issuer: null\n  report_access: unstated\n  text: In addition to our own compliance, [24]7.ai is committed to offering services and resources to our customers\n    to help them comply with CCPA requirements that may apply to their activities.\n- framework: other\n  type: APEC CBPR certification listing\n  scope: APEC Cross-Border Privacy Rules System\n  period: null\n  issuer: global forum listing\n  report_access: unstated\n  text: are listed in the global forum listing for all organisation under APEC CBPR.\n- framework: NIST-800-53\n  type: internal evaluation\n  scope: security, privacy\
  \ and risk controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: '[24]7.ai internally evaluates security, privacy, risk, and security status against the U.S. Commerce Department’s\n    National Institute of Standards and Technology (NIST) SP 800-53 R4/R5'\n- framework: NIST-CSF\n  type: internal evaluation\n  scope: cybersecurity risk framework\n  period: null\n  issuer: null\n  report_access: unstated\n  text: and the NIST Cybersecurity Framework (CSF).\n"
source_yaml_url: https://artifacts.apis.io/247-ai/compliance/247-ai-compliance.yml
stated_fields:
- attestations
summary_line: 9 quoted statements, read from [24]7.ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Customer Experience
- Conversational AI
- Contact Center
- Customer Service
- Chatbots
- CCaaS
- Artificial Intelligence
- Interaction Analytics
- Business Process Outsourcing
---
