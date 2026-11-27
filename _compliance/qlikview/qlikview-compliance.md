---
claim_count: 18
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent accounting firm
    period: null
    report_access: unstated
    scope: Qlik internal controls
    text: Qlik has successfully completed a SOC 2 Type 2 + HITRUST CSF Attestation which provides an evaluation on the suitability of the design and operating effectiveness of Qlik's internal controls.
    type: SOC 2 Type 2 + HITRUST CSF Attestation
  - framework: SOC1
    issuer: null
    period: null
    report_access: unstated
    scope: Qlik internal controls relevant to financial reporting
    text: Qlik has successfully completed a SOC 1 Type 2 assessment which provides an evaluation on the suitability of the design and operating effectiveness of Qlik's internal controls
    type: SOC 1 Type 2 assessment
  - framework: SOC3
    issuer: independent accounting firm
    period: null
    report_access: unstated
    scope: Qlik internal controls
    text: Qlik has successfully completed a SOC 3 assessment which provides an evaluation on the suitability of the design and operating effectiveness of Qlik's internal controls.
    type: SOC 3 assessment
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Qlik internal controls relative to Personal Health Information
    text: Qlik has successfully completed a SOC 2 Type 2 + HITRUST CSF Attestation which provides an evaluation on the suitability of the design and operating effectiveness of Qlik's internal controls relative to the protection of Personal Health Information subject to US HIPAA Regulatory requirements.
    type: HIPAA attestation
  - framework: HITRUST
    issuer: null
    period: null
    report_access: unstated
    scope: Qlik internal controls
    text: The HITRUST CSF is a widely adopted security and privacy framework across multiple industries.
    type: HITRUST CSF attestation
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Information security management systems
    text: Qlik meets the standards of ISO 27001, an information management security specification for information management systems (ISMS).
    type: ISO 27001:2022 certification
  - framework: ISO27017
    issuer: null
    period: null
    report_access: unstated
    scope: Cloud security controls
    text: Qlik meets the standards of ISO 27017 an information management security specification for information management systems (ISMS) covering cloud security controls for cloud service providers.
    type: ISO 27017:2015
  - framework: ISO27018
    issuer: null
    period: null
    report_access: unstated
    scope: Cloud privacy requirements and security controls
    text: Qlik meets the standards of ISO 27018, an information management security specification for information management systems (ISMS) covering cloud privacy requirements and security controls for cloud service providers.
    type: ISO 27018:2019
  - framework: ISO42001
    issuer: null
    period: null
    report_access: unstated
    scope: Artificial Intelligence Management System
    text: Qlik meets the standards of ISO/IEC 42001:2023 an Artificial Intelligence Management System standard
    type: ISO/IEC 42001:2023
  - framework: TISAX
    issuer: null
    period: null
    report_access: unstated
    scope: Information security for European automotive industry
    text: Qlik has completed the Trust Information Security Assessment Exchange (TISAX) assessment.
    type: TISAX assessment
  - framework: CyberEssentials
    issuer: UK Government-backed
    period: null
    report_access: unstated
    scope: Operational security against common cyber-attacks
    text: Qlik has successfully completed the Cyber Essentials Certification
    type: Cyber Essentials Certification
  - framework: CyberEssentials
    issuer: UK Government-backed
    period: null
    report_access: unstated
    scope: Operational security against common cyber-attacks
    text: Qlik has successfully completed the Cyber Essentials Plus Certification
    type: Cyber Essentials Plus Certification
  - framework: C5
    issuer: Germany's Federal Office for Information Security (BSI)
    period: null
    report_access: unstated
    scope: Cloud services security criteria
    text: Qlik has successfully completed an attestation for Germany's Federal Office for Information Security (BSI) security criteria for cloud services.
    type: C5 attestation
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: Qlik Cloud Government
    text: Qlik Cloud Government FedRAMP FedRAMP Marketplace GovRAMP
    type: FedRAMP listing
  - framework: other
    issuer: Texas Department of Information Resources
    period: null
    report_access: unstated
    scope: Qlik Cloud Government confidential agency data
    text: Qlik Cloud Government has achieved TX-RAMP (Texas Risk and Authorization Management Program) Level 2 Authorization
    type: TX-RAMP Level 2 authorization
  - framework: other
    issuer: DISA
    period: null
    report_access: unstated
    scope: Qlik Cloud Government - DoD
    text: Qlik Cloud Government - DoD has successfully met the standards for Impact Level (IL) 2 set by DISA
    type: DISA IL2 and IL4 standards met
  - framework: other
    issuer: App Defense Alliance
    period: null
    report_access: unstated
    scope: Qlik Cloud integration to Google
    text: Qlik Cloud has achieved Cloud Application Security Assessment (CASA) Tier 3 Certification from the App Defense Alliance, for Qlik Cloud’s integration to Google.
    type: CASA Tier 3 certification
  - framework: other
    issuer: UK Government Digital Marketplace
    period: null
    report_access: unstated
    scope: Qlik Cloud authorized supplier on G-Cloud v14
    text: Qlik Cloud is an authorized supplier for UK G Cloud v14 on the UK Government's Digital Marketplace
    type: UK G-Cloud supplier
  trust_center:
    url: https://www.qlik.com/us/company/trust
frameworks:
- C5
- CyberEssentials
- FedRAMP
- HIPAA
- HITRUST
- ISO27001
- ISO27017
- ISO27018
- ISO42001
- SOC1
- SOC2
- SOC3
- TISAX
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: QlikView
provenance_date: '2026-11-10'
provider_name: QlikView
provider_slug: qlikview
slug: qlikview-compliance
source_date: '2026-11-10'
source_filename: qlikview-compliance.yml
source_heading: Compliance
source_page: https://www.qlik.com/us/company/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: QlikView\naid: qlikview\nurl: https://www.qlik.com/us/company/trust\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.qlik.com/us/company/trust\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 + HITRUST CSF Attestation\n  scope: Qlik internal controls\n  period: null\n  issuer: independent accounting firm\n  report_access: unstated\n  text: Qlik has successfully completed a SOC 2 Type 2 + HITRUST CSF Attestation which provides an evaluation on\n    the suitability of the design and operating effectiveness of Qlik's internal controls.\n- framework: SOC1\n  type: SOC 1 Type 2 assessment\n  scope:\
  \ Qlik internal controls relevant to financial reporting\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Qlik has successfully completed a SOC 1 Type 2 assessment which provides an evaluation on the suitability\n    of the design and operating effectiveness of Qlik's internal controls\n- framework: SOC3\n  type: SOC 3 assessment\n  scope: Qlik internal controls\n  period: null\n  issuer: independent accounting firm\n  report_access: unstated\n  text: Qlik has successfully completed a SOC 3 assessment which provides an evaluation on the suitability of the\n    design and operating effectiveness of Qlik's internal controls.\n- framework: HIPAA\n  type: HIPAA attestation\n  scope: Qlik internal controls relative to Personal Health Information\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Qlik has successfully completed a SOC 2 Type 2 + HITRUST CSF Attestation which provides an evaluation on\n    the suitability of the design and operating effectiveness\
  \ of Qlik's internal controls relative to the protection\n    of Personal Health Information subject to US HIPAA Regulatory requirements.\n- framework: HITRUST\n  type: HITRUST CSF attestation\n  scope: Qlik internal controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: The HITRUST CSF is a widely adopted security and privacy framework across multiple industries.\n- framework: ISO27001\n  type: ISO 27001:2022 certification\n  scope: Information security management systems\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Qlik meets the standards of ISO 27001, an information management security specification for information\n    management systems (ISMS).\n- framework: ISO27017\n  type: ISO 27017:2015\n  scope: Cloud security controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Qlik meets the standards of ISO 27017 an information management security specification for information management\n    systems (ISMS) covering cloud\
  \ security controls for cloud service providers.\n- framework: ISO27018\n  type: ISO 27018:2019\n  scope: Cloud privacy requirements and security controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Qlik meets the standards of ISO 27018, an information management security specification for information\n    management systems (ISMS) covering cloud privacy requirements and security controls for cloud service providers.\n- framework: ISO42001\n  type: ISO/IEC 42001:2023\n  scope: Artificial Intelligence Management System\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Qlik meets the standards of ISO/IEC 42001:2023 an Artificial Intelligence Management System standard\n- framework: TISAX\n  type: TISAX assessment\n  scope: Information security for European automotive industry\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Qlik has completed the Trust Information Security Assessment Exchange (TISAX) assessment.\n- framework: CyberEssentials\n\
  \  type: Cyber Essentials Certification\n  scope: Operational security against common cyber-attacks\n  period: null\n  issuer: UK Government-backed\n  report_access: unstated\n  text: Qlik has successfully completed the Cyber Essentials Certification\n- framework: CyberEssentials\n  type: Cyber Essentials Plus Certification\n  scope: Operational security against common cyber-attacks\n  period: null\n  issuer: UK Government-backed\n  report_access: unstated\n  text: Qlik has successfully completed the Cyber Essentials Plus Certification\n- framework: C5\n  type: C5 attestation\n  scope: Cloud services security criteria\n  period: null\n  issuer: Germany's Federal Office for Information Security (BSI)\n  report_access: unstated\n  text: Qlik has successfully completed an attestation for Germany's Federal Office for Information Security (BSI)\n    security criteria for cloud services.\n- framework: FedRAMP\n  type: FedRAMP listing\n  scope: Qlik Cloud Government\n  period: null\n  issuer:\
  \ null\n  report_access: unstated\n  text: Qlik Cloud Government FedRAMP FedRAMP Marketplace GovRAMP\n- framework: other\n  type: TX-RAMP Level 2 authorization\n  scope: Qlik Cloud Government confidential agency data\n  period: null\n  issuer: Texas Department of Information Resources\n  report_access: unstated\n  text: Qlik Cloud Government has achieved TX-RAMP (Texas Risk and Authorization Management Program) Level 2 Authorization\n- framework: other\n  type: DISA IL2 and IL4 standards met\n  scope: Qlik Cloud Government - DoD\n  period: null\n  issuer: DISA\n  report_access: unstated\n  text: Qlik Cloud Government - DoD has successfully met the standards for Impact Level (IL) 2 set by DISA\n- framework: other\n  type: CASA Tier 3 certification\n  scope: Qlik Cloud integration to Google\n  period: null\n  issuer: App Defense Alliance\n  report_access: unstated\n  text: Qlik Cloud has achieved Cloud Application Security Assessment (CASA) Tier 3 Certification from the App Defense\n   \
  \ Alliance, for Qlik Cloud’s integration to Google.\n- framework: other\n  type: UK G-Cloud supplier\n  scope: Qlik Cloud authorized supplier on G-Cloud v14\n  period: null\n  issuer: UK Government Digital Marketplace\n  report_access: unstated\n  text: Qlik Cloud is an authorized supplier for UK G Cloud v14 on the UK Government's Digital Marketplace\n"
source_yaml_url: https://artifacts.apis.io/qlikview/compliance/qlikview-compliance.yml
stated_fields:
- attestations
summary_line: 18 quoted statements, read from QlikView's own page on 2026-11-10.
synthetic: false
tags:
- Analytics
- Business Intelligence
- Dashboards
- Data Discovery
- Data Visualization
- Embedded Analytics
- On-Premises
- SOAP
- Guided Analytics
- Reporting
---
