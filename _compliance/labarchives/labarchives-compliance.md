---
claim_count: 7
description: ''
doc:
  attestations:
  - framework: FedRAMP
    issuer: FedRAMP Project Management Office
    period: null
    report_access: unstated
    scope: LabArchives for Government environment
    text: LabArchives is a secure ELN with FedRAMP Moderate authorization, SOC 2 Type II, and ISO 27001:2022 certification, plus HIPAA, GDPR, and FERPA alignment.
    type: authorization
  - framework: SOC2
    issuer: independent third party auditor
    period: null
    report_access: nda
    scope: ELN and corporate processes
    text: SOC 2 and ISO access will require a signed NDA and special handling by requesters.
    type: SOC 2 Type II audit
  - framework: ISO27001
    issuer: Schellman
    period: null
    report_access: nda
    scope: ELN operations, software development, and cloud hosting
    text: LabArchives has been awarded ISO 27001:2022 certification by Schellman, following an external review of our Information Security Management System (ISMS).
    type: ISO 27001:2022 certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA (Health Insurance Portability and Accountability Act)
    type: alignment
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR (General Data Protection Regulation)
    type: alignment
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: FERPA (Family Educational Rights and Privacy Act)
    type: alignment (FERPA)
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: ELN when using built-in page signing/witnessing feature
    text: FDA – 21 CFR Part 11 (ELN when using built-in page signing/witnessing feature)
    type: alignment (FDA 21 CFR Part 11)
  trust_center:
    url: https://www.labarchives.com/security-compliance
frameworks:
- FedRAMP
- GDPR
- HIPAA
- ISO27001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: LabArchives
provenance_date: '2026-11-09'
provider_name: LabArchives
provider_slug: labarchives
slug: labarchives-compliance
source_date: '2026-11-09'
source_filename: labarchives-compliance.yml
source_heading: Compliance
source_page: https://www.labarchives.com/security-compliance
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: LabArchives\naid: labarchives\nurl: https://www.labarchives.com/security-compliance\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.labarchives.com/security-compliance\nattestations:\n- framework: FedRAMP\n  type: authorization\n  scope: LabArchives for Government environment\n  period: null\n  issuer: FedRAMP Project Management Office\n  report_access: unstated\n  text: LabArchives is a secure ELN with FedRAMP Moderate authorization, SOC 2 Type II, and ISO 27001:2022 certification,\n    plus HIPAA, GDPR, and FERPA alignment.\n- framework: SOC2\n  type: SOC 2 Type II audit\n  scope: ELN and corporate\
  \ processes\n  period: null\n  issuer: independent third party auditor\n  report_access: nda\n  text: SOC 2 and ISO access will require a signed NDA and special handling by requesters.\n- framework: ISO27001\n  type: ISO 27001:2022 certification\n  scope: ELN operations, software development, and cloud hosting\n  period: null\n  issuer: Schellman\n  report_access: nda\n  text: LabArchives has been awarded ISO 27001:2022 certification by Schellman, following an external review of\n    our Information Security Management System (ISMS).\n- framework: HIPAA\n  type: alignment\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA (Health Insurance Portability and Accountability Act)\n- framework: GDPR\n  type: alignment\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR (General Data Protection Regulation)\n- framework: other\n  type: alignment (FERPA)\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: FERPA (Family Educational Rights and Privacy Act)\n- framework: other\n  type: alignment (FDA 21 CFR Part 11)\n  scope: ELN when using built-in page signing/witnessing feature\n  period: null\n  issuer: null\n  report_access: unstated\n  text: FDA – 21 CFR Part 11 (ELN when using built-in page signing/witnessing feature)\n"
source_yaml_url: https://artifacts.apis.io/labarchives/compliance/labarchives-compliance.yml
stated_fields:
- attestations
summary_line: 7 quoted statements, read from LabArchives's own page on 2026-11-09.
synthetic: false
tags:
- Company
- ELN
- Data Management
- Research
- Collaboration
---
