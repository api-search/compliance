---
claim_count: 20
description: ''
doc:
  attestations:
  - framework: CyberEssentials
    issuer: null
    period: null
    report_access: public
    scope: UK locations supporting the UK Public sector
    text: Dell’s certificate certifies that the organization was assessed as meeting the Cyber Essentials implementation profile for its UK locations supporting the UK Public sector.
    type: certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: public
    scope: Dell Technologies Global ISO 27001 Multi-Site Certification ISMS
    text: Dell Technologies Global ISO 27001 Multi-Site Certification is an Information Security Management System (ISMS)
    type: certification
  - framework: SOC2
    issuer: PwC and Schellman Compliance
    period: null
    report_access: on_request
    scope: Dell services including AIOps, DMSP, MDR, MMS, Virtustream, Wyse Management Suite
    text: independently assessed and attested by PwC and Schellman Compliance. To access the report, please contact your dedicated sales and service representative.
    type: attestation
  - framework: SOC1
    issuer: PwC and Schellman Compliance
    period: null
    report_access: on_request
    scope: Remote Managed Services for Backup, Storage and Converged Infrastructure; Virtustream Enterprise Cloud; Virtustream Federal Cloud
    text: Virtustream Enterprise Cloud (VEC) Type 2 SOC 1 June 01, 2024 June 30, 2025
    type: attestation
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: Dell Inc. eCommerce merchant
    text: Dell Inc. is certified as a PCI DSS Level 2 Merchant.
    type: certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: public
    scope: Dell Technologies Global ISO 27001 Multi-Site Certification
    text: Download Certificate Download the Customer Redacted SoA
    type: certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: public
    scope: Dell services
    text: The ISO27001 Certificate should be referenced for the official program SoA version.
    type: certification
  - framework: other
    issuer: Scheme CA
    period: null
    report_access: public
    scope: Common Criteria evaluations for XtremIO, VxFlex, VxRail, Networking SmartFabric OS10 and others
    text: Dell EMC™ VxFlex 3.0.1.208 EAL2+, ALC_FLR.2 September 9, 2020 September 09, 2025 Certification Report
    type: certification
  - framework: IRAP
    issuer: independent IRAP assessor
    period: null
    report_access: unstated
    scope: Dell APEX Backup Services offerings
    text: An independent IRAP assessor examined the controls including people, processes, and technology against the requirements of the ISM.
    type: assessment
  - framework: NIST-CSF
    issuer: null
    period: null
    report_access: unstated
    scope: Corporate Security & Resilience cybersecurity controls
    text: Explore the cybersecurity controls most frequently requested by customers, aligned with the NIST Cybersecurity Framework.
    type: framework alignment
  - framework: other
    issuer: self-assessment
    period: null
    report_access: public
    scope: Client and IT Infrastructure Products
    text: Dell participates in the O-TTPS Certification Program by completing a self-assessment of its compliance with O-TTPS version 1.2 (ISO/IEC 20243:2023).
    type: self-assessment
  - framework: other
    issuer: KY3P
    period: null
    report_access: on_request
    scope: Dell corporate security environment, validated by KY3P
    text: KY3P ® has completed an independent comprehensive risk assessment of Dell Technologies corporate security environment
    type: assessment
  - framework: other
    issuer: CyberVadis
    period: null
    report_access: on_request
    scope: Dell corporate security environment, CyberVadis assessment
    text: To access the report, please contact your dedicated sales and service representative.
    type: assessment
  - framework: other
    issuer: CyberGRX strategic partners Deloitte and Touche and KPMG
    period: null
    report_access: on_request
    scope: Dell Technologies CyberGRX assessment
    text: Dell has completed the CyberGRX assessment, validated by CyberGRX strategic partners Deloitte and Touche and KPMG.
    type: assessment
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Information system supporting Dell Computer S.A.U., Spain Professional Services
    text: Dell has achieved ENS Basic certification
    type: certification
  - framework: NIST-800-53
    issuer: null
    period: null
    report_access: unstated
    scope: CyberVadis methodology maps to major standards
    text: CyberVadis is based on a methodology that maps to all major international compliance standards, including GDPR, NIST, NY DFS, CCPA, and many more.
    type: framework alignment
  - framework: other
    issuer: ENX Association
    period: null
    report_access: on_request
    scope: Dell Technologies corporate security, TISAX scope ID S8R56Z
    text: TISAX is a registered trademark and governed by the ENX Association.
    type: assessment
  - framework: other
    issuer: null
    period: null
    report_access: public
    scope: Dell services with NHS patient information
    text: Download Certification Here
    type: certification
  - framework: other
    issuer: JOSCAR
    period: null
    report_access: public
    scope: Dell Technologies Global ISO 27001 Multi-Site, JOSCAR certificate covers Dell products and services
    text: This JOSCAR certificate covers all of Dells Products and Services
    type: certification
  - framework: other
    issuer: Open Trusted Technology Provider
    period: null
    report_access: public
    scope: Dell Technologies Client and IT Infrastructure products
    text: Download Certificate here
    type: certification
  trust_center:
    url: https://www.dell.com/en-us/learn/our-company/lp/security-and-trust-center
frameworks:
- CyberEssentials
- IRAP
- ISO27001
- NIST-800-53
- NIST-CSF
- PCI-DSS
- SOC1
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: EMC
provenance_date: '2026-11-09'
provider_name: EMC
provider_slug: emc
slug: emc-compliance
source_date: '2026-11-09'
source_filename: emc-compliance.yml
source_heading: Compliance
source_page: https://www.dell.com/en-us/learn/our-company/lp/security-and-trust-center
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: EMC\naid: emc\nurl: https://www.dell.com/en-us/learn/our-company/lp/security-and-trust-center\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/emc-trust-center.yml\ntrust_center:\n  url: https://www.dell.com/en-us/learn/our-company/lp/security-and-trust-center\nattestations:\n- framework: CyberEssentials\n  type: certification\n  scope: UK locations supporting the UK Public sector\n  period: null\n  issuer: null\n  report_access: public\n  text: Dell’s certificate certifies that the organization was assessed as meeting the Cyber Essentials implementation\n    profile for its UK locations supporting\
  \ the UK Public sector.\n- framework: ISO27001\n  type: certification\n  scope: Dell Technologies Global ISO 27001 Multi-Site Certification ISMS\n  period: null\n  issuer: null\n  report_access: public\n  text: Dell Technologies Global ISO 27001 Multi-Site Certification is an Information Security Management System\n    (ISMS)\n- framework: SOC2\n  type: attestation\n  scope: Dell services including AIOps, DMSP, MDR, MMS, Virtustream, Wyse Management Suite\n  period: null\n  issuer: PwC and Schellman Compliance\n  report_access: on_request\n  text: independently assessed and attested by PwC and Schellman Compliance. To access the report, please contact\n    your dedicated sales and service representative.\n- framework: SOC1\n  type: attestation\n  scope: Remote Managed Services for Backup, Storage and Converged Infrastructure; Virtustream Enterprise Cloud;\n    Virtustream Federal Cloud\n  period: null\n  issuer: PwC and Schellman Compliance\n  report_access: on_request\n  text: Virtustream\
  \ Enterprise Cloud (VEC) Type 2 SOC 1 June 01, 2024 June 30, 2025\n- framework: PCI-DSS\n  type: certification\n  scope: Dell Inc. eCommerce merchant\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Dell Inc. is certified as a PCI DSS Level 2 Merchant.\n- framework: ISO27001\n  type: certification\n  scope: Dell Technologies Global ISO 27001 Multi-Site Certification\n  period: null\n  issuer: null\n  report_access: public\n  text: Download Certificate Download the Customer Redacted SoA\n- framework: ISO27001\n  type: certification\n  scope: Dell services\n  period: null\n  issuer: null\n  report_access: public\n  text: The ISO27001 Certificate should be referenced for the official program SoA version.\n- framework: other\n  type: certification\n  scope: Common Criteria evaluations for XtremIO, VxFlex, VxRail, Networking SmartFabric OS10 and others\n  period: null\n  issuer: Scheme CA\n  report_access: public\n  text: Dell EMC™ VxFlex 3.0.1.208 EAL2+, ALC_FLR.2 September\
  \ 9, 2020 September 09, 2025 Certification Report\n- framework: IRAP\n  type: assessment\n  scope: Dell APEX Backup Services offerings\n  period: null\n  issuer: independent IRAP assessor\n  report_access: unstated\n  text: An independent IRAP assessor examined the controls including people, processes, and technology against the\n    requirements of the ISM.\n- framework: NIST-CSF\n  type: framework alignment\n  scope: Corporate Security & Resilience cybersecurity controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Explore the cybersecurity controls most frequently requested by customers, aligned with the NIST Cybersecurity\n    Framework.\n- framework: other\n  type: self-assessment\n  scope: Client and IT Infrastructure Products\n  period: null\n  issuer: self-assessment\n  report_access: public\n  text: Dell participates in the O-TTPS Certification Program by completing a self-assessment of its compliance\n    with O-TTPS version 1.2 (ISO/IEC 20243:2023).\n\
  - framework: other\n  type: assessment\n  scope: Dell corporate security environment, validated by KY3P\n  period: null\n  issuer: KY3P\n  report_access: on_request\n  text: KY3P ® has completed an independent comprehensive risk assessment of Dell Technologies corporate security\n    environment\n- framework: other\n  type: assessment\n  scope: Dell corporate security environment, CyberVadis assessment\n  period: null\n  issuer: CyberVadis\n  report_access: on_request\n  text: To access the report, please contact your dedicated sales and service representative.\n- framework: other\n  type: assessment\n  scope: Dell Technologies CyberGRX assessment\n  period: null\n  issuer: CyberGRX strategic partners Deloitte and Touche and KPMG\n  report_access: on_request\n  text: Dell has completed the CyberGRX assessment, validated by CyberGRX strategic partners Deloitte and Touche\n    and KPMG.\n- framework: other\n  type: certification\n  scope: Information system supporting Dell Computer S.A.U.,\
  \ Spain Professional Services\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Dell has achieved ENS Basic certification\n- framework: NIST-800-53\n  type: framework alignment\n  scope: CyberVadis methodology maps to major standards\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CyberVadis is based on a methodology that maps to all major international compliance standards, including\n    GDPR, NIST, NY DFS, CCPA, and many more.\n- framework: other\n  type: assessment\n  scope: Dell Technologies corporate security, TISAX scope ID S8R56Z\n  period: null\n  issuer: ENX Association\n  report_access: on_request\n  text: TISAX is a registered trademark and governed by the ENX Association.\n- framework: other\n  type: certification\n  scope: Dell services with NHS patient information\n  period: null\n  issuer: null\n  report_access: public\n  text: Download Certification Here\n- framework: other\n  type: certification\n  scope: Dell Technologies Global\
  \ ISO 27001 Multi-Site, JOSCAR certificate covers Dell products and services\n  period: null\n  issuer: JOSCAR\n  report_access: public\n  text: This JOSCAR certificate covers all of Dells Products and Services\n- framework: other\n  type: certification\n  scope: Dell Technologies Client and IT Infrastructure products\n  period: null\n  issuer: Open Trusted Technology Provider\n  report_access: public\n  text: Download Certificate here\n"
source_yaml_url: https://artifacts.apis.io/emc/compliance/emc-compliance.yml
stated_fields:
- attestations
summary_line: 20 quoted statements, read from EMC's own page on 2026-11-09.
synthetic: false
tags:
- Cloud Infrastructure
- Data Management
- Data Protection
- Enterprise Storage
- Object Storage
- Storage
- S3 Compatible
- Fortune 500
---
