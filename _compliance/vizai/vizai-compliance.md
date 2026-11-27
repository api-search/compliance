---
claim_count: 8
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Viz.ai production systems and supporting infrastructure
    text: 'SOC 2 Type II: Independent audit demonstrating the effectiveness of controls across security, availability, confidentiality, processing integrity, and privacy over a defined audit period.'
    type: Type II audit
  - framework: HIPAA
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: 'HIPAA: Viz.ai operates a comprehensive HIPAA compliance program, including administrative, technical, and physical safeguards for the protection of PHI.'
    type: compliance program
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: 'ISO 27001 (Information Security Management System): Global standard for information security management systems (ISMS), demonstrating structured risk management and governance.'
    type: certification
  - framework: ISO27701
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: 'ISO 27701 (Privacy Information Management System): Extension of ISO 27001 focused on privacy, supporting GDPR and global privacy obligations.'
    type: certification
  - framework: other
    issuer: null
    period: null
    report_access: on_request
    scope: healthcare-specific security controls for clinical environments and PHI
    text: 'ISO 27799: Healthcare-specific security controls tailored for clinical environments and PHI.'
    type: certification (ISO 27799)
  - framework: ISO27017
    issuer: null
    period: null
    report_access: on_request
    scope: cloud-hosted infrastructure
    text: 'ISO 27017 / 27018: Cloud security and data protection standards governing our cloud-hosted infrastructure.'
    type: certification
  - framework: other
    issuer: null
    period: null
    report_access: on_request
    scope: business continuity and resilience
    text: 'ISO 22301: Business continuity and resilience to ensure uninterrupted clinical workflows.'
    type: certification (ISO 22301)
  - framework: ISO42001
    issuer: null
    period: null
    report_access: on_request
    scope: AI systems lifecycle
    text: 'ISO 42001: Responsibly develop, evaluate, and deploy AI systems while managing ethical considerations, transparency, data privacy, and security throughout the entire AI lifecycle.'
    type: certification
  trust_center:
    url: https://www.viz.ai/trust-center
frameworks:
- HIPAA
- ISO27001
- ISO27017
- ISO27701
- ISO42001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Viz.ai
provenance_date: '2026-11-10'
provider_name: Viz.ai
provider_slug: vizai
slug: vizai-compliance
source_date: '2026-11-10'
source_filename: vizai-compliance.yml
source_heading: Compliance
source_page: https://www.viz.ai/trust-center
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Viz.ai\naid: vizai\nurl: https://www.viz.ai/trust-center\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/vizai-trust-center.yml\ntrust_center:\n  url: https://www.viz.ai/trust-center\nattestations:\n- framework: SOC2\n  type: Type II audit\n  scope: Viz.ai production systems and supporting infrastructure\n  period: null\n  issuer: null\n  report_access: on_request\n  text: 'SOC 2 Type II: Independent audit demonstrating the effectiveness of controls across security, availability,\n    confidentiality, processing integrity, and privacy over a defined audit period.'\n- framework: HIPAA\n  type: compliance\
  \ program\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: 'HIPAA: Viz.ai operates a comprehensive HIPAA compliance program, including administrative, technical, and\n    physical safeguards for the protection of PHI.'\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: 'ISO 27001 (Information Security Management System): Global standard for information security management\n    systems (ISMS), demonstrating structured risk management and governance.'\n- framework: ISO27701\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: 'ISO 27701 (Privacy Information Management System): Extension of ISO 27001 focused on privacy, supporting\n    GDPR and global privacy obligations.'\n- framework: other\n  type: certification (ISO 27799)\n  scope: healthcare-specific security controls for clinical environments and PHI\n  period: null\n\
  \  issuer: null\n  report_access: on_request\n  text: 'ISO 27799: Healthcare-specific security controls tailored for clinical environments and PHI.'\n- framework: ISO27017\n  type: certification\n  scope: cloud-hosted infrastructure\n  period: null\n  issuer: null\n  report_access: on_request\n  text: 'ISO 27017 / 27018: Cloud security and data protection standards governing our cloud-hosted infrastructure.'\n- framework: other\n  type: certification (ISO 22301)\n  scope: business continuity and resilience\n  period: null\n  issuer: null\n  report_access: on_request\n  text: 'ISO 22301: Business continuity and resilience to ensure uninterrupted clinical workflows.'\n- framework: ISO42001\n  type: certification\n  scope: AI systems lifecycle\n  period: null\n  issuer: null\n  report_access: on_request\n  text: 'ISO 42001: Responsibly develop, evaluate, and deploy AI systems while managing ethical considerations,\n    transparency, data privacy, and security throughout the entire AI lifecycle.'\n"
source_yaml_url: https://artifacts.apis.io/vizai/compliance/vizai-compliance.yml
stated_fields:
- attestations
summary_line: 8 quoted statements, read from Viz.ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Artificial Intelligence
- Medical Imaging
- Care Coordination
- Clinical
- Diagnostics
- Stroke
---
