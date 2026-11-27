---
claim_count: 9
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: development, maintenance and operation of SaaS services (Remote Desktop Service System)
    text: Splashtop is now ISO/IEC 27001:2022 certified
    type: certification
  - framework: SOC2
    issuer: independent auditors
    period: null
    report_access: nda
    scope: AICPA Trust Services Criteria for Security and Confidentiality
    text: Additional SOC 2 documentation available upon NDA and by request
    type: SOC 2 Type 2 report
  - framework: SOC3
    issuer: null
    period: null
    report_access: public
    scope: null
    text: A public SOC 3 report is available for reference.
    type: SOC 3 report
  - framework: CSA-STAR
    issuer: CSA STAR Registry
    period: null
    report_access: public
    scope: CSA Cloud Controls Matrix (CCM) and CAIQ
    text: Splashtop has earned CSA STAR Level 1 compliance
    type: CSA STAR Level 1 self-assessment
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Splashtop and Foxpass as Data Controller and Data Processor
    text: Foxpass and Splashtop comply with the principles and obligations of the EU GDPR as both Data Controller and Data Processor.
    type: self-declared compliance with GDPR principles and obligations
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: California residents' privacy rights
    text: In compliance with the CCPA, California residents may request access to, deletion of, or opt-out from the sale or sharing of their personal information.
    type: compliance statement
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: Splashtop solutions help meet PCI DSS requirements; no single product makes an organization compliant
    text: No single product can make an organization PCI DSS compliant.
    type: support statement
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Splashtop Remote Access, Remote Support, SRS Premium, Enterprise and On-Prem products may help fulfill HIPAA guidelines
    text: may help organizations fulfill HIPAA guidelines for the privacy and security of remote access to healthcare information
    type: support statement
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Foxpass helps educational institutions support FERPA compliance
    text: Foxpass helps educational institutions support FERPA compliance by securing network and system access
    type: regulatory support statement (FERPA)
  trust_center:
    url: https://www.splashtop.com/security/compliance
frameworks:
- CCPA
- CSA-STAR
- GDPR
- HIPAA
- ISO27001
- PCI-DSS
- SOC2
- SOC3
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Splashtop
provenance_date: '2026-11-10'
provider_name: Splashtop
provider_slug: splashtop
slug: splashtop-compliance
source_date: '2026-11-10'
source_filename: splashtop-compliance.yml
source_heading: Compliance
source_page: https://www.splashtop.com/security/compliance
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Splashtop\naid: splashtop\nurl: https://www.splashtop.com/security/compliance\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.splashtop.com/security/compliance\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: development, maintenance and operation of SaaS services (Remote Desktop Service System)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Splashtop is now ISO/IEC 27001:2022 certified\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: AICPA Trust Services Criteria for Security and Confidentiality\n  period: null\n  issuer: independent auditors\n\
  \  report_access: nda\n  text: Additional SOC 2 documentation available upon NDA and by request\n- framework: SOC3\n  type: SOC 3 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: public\n  text: A public SOC 3 report is available for reference.\n- framework: CSA-STAR\n  type: CSA STAR Level 1 self-assessment\n  scope: CSA Cloud Controls Matrix (CCM) and CAIQ\n  period: null\n  issuer: CSA STAR Registry\n  report_access: public\n  text: Splashtop has earned CSA STAR Level 1 compliance\n- framework: GDPR\n  type: self-declared compliance with GDPR principles and obligations\n  scope: Splashtop and Foxpass as Data Controller and Data Processor\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Foxpass and Splashtop comply with the principles and obligations of the EU GDPR as both Data Controller\n    and Data Processor.\n- framework: CCPA\n  type: compliance statement\n  scope: California residents' privacy rights\n  period: null\n  issuer: null\n \
  \ report_access: unstated\n  text: In compliance with the CCPA, California residents may request access to, deletion of, or opt-out from the\n    sale or sharing of their personal information.\n- framework: PCI-DSS\n  type: support statement\n  scope: Splashtop solutions help meet PCI DSS requirements; no single product makes an organization compliant\n  period: null\n  issuer: null\n  report_access: unstated\n  text: No single product can make an organization PCI DSS compliant.\n- framework: HIPAA\n  type: support statement\n  scope: Splashtop Remote Access, Remote Support, SRS Premium, Enterprise and On-Prem products may help fulfill\n    HIPAA guidelines\n  period: null\n  issuer: null\n  report_access: unstated\n  text: may help organizations fulfill HIPAA guidelines for the privacy and security of remote access to healthcare\n    information\n- framework: other\n  type: regulatory support statement (FERPA)\n  scope: Foxpass helps educational institutions support FERPA compliance\n\
  \  period: null\n  issuer: null\n  report_access: unstated\n  text: Foxpass helps educational institutions support FERPA compliance by securing network and system access\n"
source_yaml_url: https://artifacts.apis.io/splashtop/compliance/splashtop-compliance.yml
stated_fields:
- attestations
summary_line: 9 quoted statements, read from Splashtop's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Software-as-a-Service
- Remote Access
- Remote Support
- Remote Desktop
- Endpoint Management
- IT Management
- MSP
- Security
- Remote Work
---
