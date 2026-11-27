---
claim_count: 9
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Security, Availability, and Confidentiality trust service criteria
    text: Our SOC 2 Type II report covers the Security trust service criteria and evaluates controls related to data integrity, backup and recovery processes (including disaster recovery)
    type: SOC 2 Type II report
  - framework: ISO27001
    issuer: null
    period: Valid until April 2028
    report_access: public
    scope: information security management
    text: ISO/IEC 27001:2022 Valid until April 2028
    type: ISO/IEC 27001:2022 certificate
  - framework: other
    issuer: null
    period: null
    report_access: public
    scope: transatlantic personal data transfers
    text: Certified under the EU-US and UK Extension to the Data Privacy Framework, demonstrating our commitment to lawful transatlantic data transfers.
    type: EU-US & UK-US Data Privacy Framework certification
  - framework: HITRUST
    issuer: null
    period: null
    report_access: on_request
    scope: HITRUST Essentials, 1-year (e1) cybersecurity hygiene
    text: Please request access to view the report.
    type: HITRUST e1 Certification
  - framework: CyberEssentials
    issuer: null
    period: null
    report_access: public
    scope: hands-on technical verification of cyber security in the UK
    text: The highest level of certification, this involves a hands-on technical verification of our cyber security in the UK.
    type: Cyber Essentials Plus certification
  - framework: other
    issuer: null
    period: null
    report_access: on_request
    scope: summary of latest third-party penetration test
    text: Summary of our latest third-party penetration test, validating the security of our platform and infrastructure.
    type: Penetration Test Attestation
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: healthcare customers' HIPAA compliance
    text: We support our healthcare customers’ compliance with HIPAA by signing Business Associate Agreements (BAAs)
    type: HIPAA support via Business Associate Agreements
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: customers subject to GDPR
    text: For customers subject to GDPR, we provide a Data Processing Addendum (DPA) that includes Standard Contractual Clauses (SCCs).
    type: GDPR Data Processing Addendum with SCCs
  - framework: other
    issuer: ONC-ACB
    period: null
    report_access: unstated
    scope: Rhapsody Integration Engine certified Health IT modules, including 170.315(d), (f) and (g) criteria
    source: https://rhapsody.health/onc-compliance/
    text: This Health IT Module is compliant with the ONC Certification Criteria for Health IT and has been certified by an ONC–ACB in accordance with the applicable certification criteria adopted by the Secretary of Health and Human Services.
    type: ONC Health IT Certification Program (Certification Criteria for Health IT)
  trust_center:
    url: https://rhapsody.health/trust-center/
frameworks:
- CyberEssentials
- GDPR
- HIPAA
- HITRUST
- ISO27001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Rhapsody
provenance_date: '2026-11-10'
provider_name: Rhapsody
provider_slug: rhapsody
slug: rhapsody-compliance
source_date: '2026-11-10'
source_filename: rhapsody-compliance.yml
source_heading: Compliance
source_page: https://rhapsody.health/trust-center/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Rhapsody\naid: rhapsody\nurl: https://rhapsody.health/trust-center/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/rhapsody-trust-center.yml\n  sources:\n  - https://rhapsody.health/onc-compliance/\n  - https://rhapsody.health/trust-center/\ntrust_center:\n  url: https://rhapsody.health/trust-center/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: Security, Availability, and Confidentiality trust service criteria\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Our SOC 2 Type II report covers the Security trust service criteria and evaluates controls\
  \ related to data\n    integrity, backup and recovery processes (including disaster recovery)\n- framework: ISO27001\n  type: ISO/IEC 27001:2022 certificate\n  scope: information security management\n  period: Valid until April 2028\n  issuer: null\n  report_access: public\n  text: ISO/IEC 27001:2022 Valid until April 2028\n- framework: other\n  type: EU-US & UK-US Data Privacy Framework certification\n  scope: transatlantic personal data transfers\n  period: null\n  issuer: null\n  report_access: public\n  text: Certified under the EU-US and UK Extension to the Data Privacy Framework, demonstrating our commitment to\n    lawful transatlantic data transfers.\n- framework: HITRUST\n  type: HITRUST e1 Certification\n  scope: HITRUST Essentials, 1-year (e1) cybersecurity hygiene\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Please request access to view the report.\n- framework: CyberEssentials\n  type: Cyber Essentials Plus certification\n  scope: hands-on technical\
  \ verification of cyber security in the UK\n  period: null\n  issuer: null\n  report_access: public\n  text: The highest level of certification, this involves a hands-on technical verification of our cyber security\n    in the UK.\n- framework: other\n  type: Penetration Test Attestation\n  scope: summary of latest third-party penetration test\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Summary of our latest third-party penetration test, validating the security of our platform and infrastructure.\n- framework: HIPAA\n  type: HIPAA support via Business Associate Agreements\n  scope: healthcare customers' HIPAA compliance\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We support our healthcare customers’ compliance with HIPAA by signing Business Associate Agreements (BAAs)\n- framework: GDPR\n  type: GDPR Data Processing Addendum with SCCs\n  scope: customers subject to GDPR\n  period: null\n  issuer: null\n  report_access: unstated\n  text:\
  \ For customers subject to GDPR, we provide a Data Processing Addendum (DPA) that includes Standard Contractual\n    Clauses (SCCs).\n- framework: other\n  type: ONC Health IT Certification Program (Certification Criteria for Health IT)\n  scope: Rhapsody Integration Engine certified Health IT modules, including 170.315(d), (f) and (g) criteria\n  period: null\n  issuer: ONC-ACB\n  report_access: unstated\n  text: This Health IT Module is compliant with the ONC Certification Criteria for Health IT and has been certified\n    by an ONC–ACB in accordance with the applicable certification criteria adopted by the Secretary of Health and\n    Human Services.\n  source: https://rhapsody.health/onc-compliance/\n"
source_yaml_url: https://artifacts.apis.io/rhapsody/compliance/rhapsody-compliance.yml
stated_fields:
- attestations
summary_line: 9 quoted statements, read from Rhapsody's own page on 2026-11-10.
synthetic: false
tags:
- Healthcare
- United States
- Interoperability
- Integration Engine
- FHIR
- HL7
- EMPI
- Terminology
- Health Data
- MCP
- API Gateway
---
