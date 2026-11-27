---
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: Johanson Group LLP
    period: null
    report_access: unstated
    scope: null
    text: AuditFile has successfully completed a SOC 2 Type II examination, performed by Johanson Group LLP.
    type: SOC 2 Type II examination
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: AuditFile is in compliance with the EU General Data Protection Regulation (GDPR).
    type: compliance statement
  - framework: NIST-800-53
    issuer: null
    period: null
    report_access: unstated
    scope: NIST 800-53 Revision 5
    text: AuditFile is in compliance with NIST 800-53 Revision 5.
    type: compliance statement
  - framework: PCI-DSS
    issuer: null
    period: December 6, 2023
    report_access: unstated
    scope: SAQ A
    text: AuditFile completed PCI DSS v3.2.1 SAQ A on December 6, 2023.
    type: self-assessment questionnaire
  - framework: other
    issuer: U.S. Department of Commerce
    period: null
    report_access: unstated
    scope: EU-U.S. Data Privacy Framework
    text: AuditFile, Inc. complies with the EU-U.S. Data Privacy Framework (EU-U.S. DPF)
    type: data privacy framework certification
  trust_center:
    url: https://auditfile.com/security
frameworks:
- GDPR
- NIST-800-53
- PCI-DSS
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: AuditFile
provenance_date: '2026-11-09'
provider_name: AuditFile
provider_slug: auditfile
slug: auditfile-compliance
source_date: '2026-11-09'
source_filename: auditfile-compliance.yml
source_heading: Compliance
source_page: https://auditfile.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: AuditFile\naid: auditfile\nurl: https://auditfile.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://auditfile.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II examination\n  scope: null\n  period: null\n  issuer: Johanson Group LLP\n  report_access: unstated\n  text: AuditFile has successfully completed a SOC 2 Type II examination, performed by Johanson Group LLP.\n- framework: GDPR\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AuditFile is in compliance with the EU General Data Protection Regulation (GDPR).\n\
  - framework: NIST-800-53\n  type: compliance statement\n  scope: NIST 800-53 Revision 5\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AuditFile is in compliance with NIST 800-53 Revision 5.\n- framework: PCI-DSS\n  type: self-assessment questionnaire\n  scope: SAQ A\n  period: December 6, 2023\n  issuer: null\n  report_access: unstated\n  text: AuditFile completed PCI DSS v3.2.1 SAQ A on December 6, 2023.\n- framework: other\n  type: data privacy framework certification\n  scope: EU-U.S. Data Privacy Framework\n  period: null\n  issuer: U.S. Department of Commerce\n  report_access: unstated\n  text: AuditFile, Inc. complies with the EU-U.S. Data Privacy Framework (EU-U.S. DPF)\n"
source_yaml_url: https://artifacts.apis.io/auditfile/compliance/auditfile-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from AuditFile's own page on 2026-11-09.
synthetic: false
tags:
- Accounting
- Audit
- Cloud
- Artificial Intelligence
- CPA
---
