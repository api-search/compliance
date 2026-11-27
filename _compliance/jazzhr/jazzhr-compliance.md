---
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: Schellman
    period: null
    report_access: on_request
    scope: JazzHR by Employ platform
    text: Schellman, an independent third-party auditor, has issued JazzHR by Employ's SOC 2 Type 2 report.
    type: SOC 2 Type 2 report
  - framework: ISO27001
    issuer: Schellman
    period: null
    report_access: on_request
    scope: Employ
    text: Schellman, an independent third-party auditor, has issued Employ's ISO/IEC 27001 certificate.
    type: ISO/IEC 27001 certificate
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: JazzHR by Employ information security parameters
    text: JazzHR by Employ's information security parameters comply with the General Data Protection Regulation (GDPR) and California Consumer Privacy Act (CCPA)
    type: self-stated compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: JazzHR by Employ information security parameters
    text: JazzHR by Employ's information security parameters comply with the General Data Protection Regulation (GDPR) and California Consumer Privacy Act (CCPA)
    type: self-stated compliance
  - framework: CSA-STAR
    issuer: Cloud Security Alliance
    period: null
    report_access: public
    scope: Employ
    text: Employ has joined the Cloud Security Alliance's (CSA) mission to promote best practice in the provision of security assurance within Cloud Computing environments by completing the Consensus Assessments Initiative Questionnaire (CAIQ).
    type: CAIQ questionnaire completion
  trust_center:
    url: https://www.jazzhr.com/security
frameworks:
- CCPA
- CSA-STAR
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: JazzHR
provenance_date: '2026-11-09'
provider_name: JazzHR
provider_slug: jazzhr
slug: jazzhr-compliance
source_date: '2026-11-09'
source_filename: jazzhr-compliance.yml
source_heading: Compliance
source_page: https://www.jazzhr.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: JazzHR\naid: jazzhr\nurl: https://www.jazzhr.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.jazzhr.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: JazzHR by Employ platform\n  period: null\n  issuer: Schellman\n  report_access: on_request\n  text: Schellman, an independent third-party auditor, has issued JazzHR by Employ's SOC 2 Type 2 report.\n- framework: ISO27001\n  type: ISO/IEC 27001 certificate\n  scope: Employ\n  period: null\n  issuer: Schellman\n  report_access: on_request\n  text: Schellman, an independent third-party auditor, has issued\
  \ Employ's ISO/IEC 27001 certificate.\n- framework: GDPR\n  type: self-stated compliance\n  scope: JazzHR by Employ information security parameters\n  period: null\n  issuer: null\n  report_access: unstated\n  text: JazzHR by Employ's information security parameters comply with the General Data Protection Regulation (GDPR)\n    and California Consumer Privacy Act (CCPA)\n- framework: CCPA\n  type: self-stated compliance\n  scope: JazzHR by Employ information security parameters\n  period: null\n  issuer: null\n  report_access: unstated\n  text: JazzHR by Employ's information security parameters comply with the General Data Protection Regulation (GDPR)\n    and California Consumer Privacy Act (CCPA)\n- framework: CSA-STAR\n  type: CAIQ questionnaire completion\n  scope: Employ\n  period: null\n  issuer: Cloud Security Alliance\n  report_access: public\n  text: Employ has joined the Cloud Security Alliance's (CSA) mission to promote best practice in the provision\n    of security assurance\
  \ within Cloud Computing environments by completing the Consensus Assessments Initiative\n    Questionnaire (CAIQ).\n"
source_yaml_url: https://artifacts.apis.io/jazzhr/compliance/jazzhr-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from JazzHR's own page on 2026-11-09.
synthetic: false
tags:
- Recruiting
- Applicant Tracking
- Small Business
- Hiring
- Software-as-a-Service
- Company
---
