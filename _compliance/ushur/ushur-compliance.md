---
claim_count: 17
description: ''
doc:
  attestations:
  - framework: HITRUST
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HITRUST r2 Certified
    type: certification
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PCI DSS
    type: compliance badge
  - framework: SOC2
    issuer: AICPA
    period: null
    report_access: unstated
    scope: null
    text: AICPA SOC 2
    type: attestation
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA Compliant
    type: compliance badge
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR Compliant
    type: compliance badge
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA Compliant
    type: compliance badge
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PIPEDA Compliant
    type: compliance badge (PIPEDA)
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: TCPA Compliant
    type: compliance badge (TCPA)
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: FSQS Registered
    type: compliance badge (FSQS)
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Section 508 Compliant
    type: compliance badge (Section 508)
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Commitment to comply with CIS and SOC2 standards
    type: commitment to standards (CIS)
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.ushur.ai/
    text: Compliance SOC 2 1 document
    type: document
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.ushur.ai/
    text: Compliance ISO 27001:2022 1 document
    type: document
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.ushur.ai/
    text: Compliance PCI DSS V4.0 1 document
    type: document
  - framework: HITRUST
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.ushur.ai/
    text: Compliance HITRUST R2 1 document
    type: document
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.ushur.ai/
    text: Compliance FSQS 1 document
    type: document
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.ushur.ai/
    text: Compliance ADA-WCAG 1 document
    type: document
  trust_center:
    url: https://ushur.ai/security-and-compliance
frameworks:
- CCPA
- GDPR
- HIPAA
- HITRUST
- ISO27001
- PCI-DSS
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Ushur
provenance_date: '2026-11-10'
provider_name: Ushur
provider_slug: ushur
slug: ushur-compliance
source_date: '2026-11-10'
source_filename: ushur-compliance.yml
source_heading: Compliance
source_page: https://ushur.ai/security-and-compliance
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Ushur\naid: ushur\nurl: https://ushur.ai/security-and-compliance\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/ushur-trust-center.yml\n  sources:\n  - https://trust.ushur.ai/\n  - https://ushur.ai/security-and-compliance\ntrust_center:\n  url: https://ushur.ai/security-and-compliance\nattestations:\n- framework: HITRUST\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HITRUST r2 Certified\n- framework: PCI-DSS\n  type: compliance badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI DSS\n- framework: SOC2\n\
  \  type: attestation\n  scope: null\n  period: null\n  issuer: AICPA\n  report_access: unstated\n  text: AICPA SOC 2\n- framework: HIPAA\n  type: compliance badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA Compliant\n- framework: GDPR\n  type: compliance badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR Compliant\n- framework: CCPA\n  type: compliance badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA Compliant\n- framework: other\n  type: compliance badge (PIPEDA)\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PIPEDA Compliant\n- framework: other\n  type: compliance badge (TCPA)\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: TCPA Compliant\n- framework: other\n  type: compliance badge (FSQS)\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: FSQS Registered\n\
  - framework: other\n  type: compliance badge (Section 508)\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Section 508 Compliant\n- framework: other\n  type: commitment to standards (CIS)\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Commitment to comply with CIS and SOC2 standards\n- framework: SOC2\n  type: document\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliance SOC 2 1 document\n  source: https://trust.ushur.ai/\n- framework: ISO27001\n  type: document\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliance ISO 27001:2022 1 document\n  source: https://trust.ushur.ai/\n- framework: PCI-DSS\n  type: document\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliance PCI DSS V4.0 1 document\n  source: https://trust.ushur.ai/\n- framework: HITRUST\n  type: document\n  scope: null\n  period: null\n\
  \  issuer: null\n  report_access: unstated\n  text: Compliance HITRUST R2 1 document\n  source: https://trust.ushur.ai/\n- framework: other\n  type: document\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliance FSQS 1 document\n  source: https://trust.ushur.ai/\n- framework: other\n  type: document\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliance ADA-WCAG 1 document\n  source: https://trust.ushur.ai/\n"
source_yaml_url: https://artifacts.apis.io/ushur/compliance/ushur-compliance.yml
stated_fields:
- attestations
summary_line: 17 quoted statements, read from Ushur's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Customer Experience
- Automation
- Healthcare
- Insurance
- Financial Services
- Agents
---
