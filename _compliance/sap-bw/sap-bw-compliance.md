---
claim_count: 15
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001 Security Management System
    type: ISO/IEC 27001 certification
  - framework: ISO27017
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27017 Code of Practice for Cloud Service Information Security
    type: ISO/IEC 27017 certification
  - framework: ISO27018
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27018 Code of Practice for Personally Identifiable information
    type: ISO/IEC 27018 certification
  - framework: ISO42001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SAP has achieved certification for ISO/IEC 42001, the first global standard for AI management systems.
    type: ISO/IEC 42001 certification
  - framework: ISO9001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 9001 Quality Management System
    type: ISO 9001 certification
  - framework: SOC1
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 1 reports follow the SSAE 18 and ISAE 3402 standards for auditing engagements
    type: SOC 1 report
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 reports follow the ISAE 3000 and AT 101 auditing standards
    type: SOC 2 report
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Payment Card Industry Data Security Standard (PCI DSS)
    type: PCI DSS attestations
  - framework: TISAX
    issuer: null
    period: null
    report_access: unstated
    scope: Several SAP locations at AL3
    text: Trusted Information Security Assessment Exchange (TISAX)
    type: TISAX assessment
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Find CSA Star certificates
    type: CSA STAR certificates
  - framework: C5
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Find C5 audit reports
    type: C5 audit reports
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: See FedRAMP authorizations
    type: FedRAMP authorizations
  - framework: DORA
    issuer: European Supervisory Authorities
    period: null
    report_access: unstated
    scope: null
    text: SAP has been officially designated by the European Supervisory Authorities (ESAs) as a Critical ICT Third-Party Service Provider (CTPP)
    type: Critical ICT third-party service provider designation
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: global certifications
    source: https://www.sap.com/about/trust-center/security/incident-management.html
    text: We secure your business with strong infrastructure protection, continuous 24/7 monitoring, rapid incident response, and built-in disaster recovery.
    type: certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://www.sap.com/about/trust-center.html
    text: ISO/IEC 42001 for AI management systems
    type: null
  trust_center:
    url: https://www.sap.com/about/trust-center/certification-compliance.html
frameworks:
- C5
- CSA-STAR
- DORA
- FedRAMP
- ISO27001
- ISO27017
- ISO27018
- ISO42001
- ISO9001
- PCI-DSS
- SOC1
- SOC2
- TISAX
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: SAP BW
provenance_date: '2026-11-10'
provider_name: SAP BW
provider_slug: sap-bw
slug: sap-bw-compliance
source_date: '2026-11-10'
source_filename: sap-bw-compliance.yml
source_heading: Compliance
source_page: https://www.sap.com/about/trust-center/certification-compliance.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: SAP BW\naid: sap-bw\nurl: https://www.sap.com/about/trust-center/certification-compliance.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/sap-bw-trust-center.yml\n  sources:\n  - https://www.sap.com/about/trust-center.html\n  - https://www.sap.com/about/trust-center/certification-compliance.html\n  - https://www.sap.com/about/trust-center/security/incident-management.html\ntrust_center:\n  url: https://www.sap.com/about/trust-center/certification-compliance.html\nattestations:\n- framework: ISO27001\n  type: ISO/IEC 27001 certification\n  scope: null\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: ISO 27001 Security Management System\n- framework: ISO27017\n  type: ISO/IEC 27017 certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27017 Code of Practice for Cloud Service Information Security\n- framework: ISO27018\n  type: ISO/IEC 27018 certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27018 Code of Practice for Personally Identifiable information\n- framework: ISO42001\n  type: ISO/IEC 42001 certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SAP has achieved certification for ISO/IEC 42001, the first global standard for AI management systems.\n- framework: ISO9001\n  type: ISO 9001 certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 9001 Quality Management System\n- framework: SOC1\n  type: SOC 1 report\n  scope: null\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: SOC 1 reports follow the SSAE 18 and ISAE 3402 standards for auditing engagements\n- framework: SOC2\n  type: SOC 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 reports follow the ISAE 3000 and AT 101 auditing standards\n- framework: PCI-DSS\n  type: PCI DSS attestations\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Payment Card Industry Data Security Standard (PCI DSS)\n- framework: TISAX\n  type: TISAX assessment\n  scope: Several SAP locations at AL3\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Trusted Information Security Assessment Exchange (TISAX)\n- framework: CSA-STAR\n  type: CSA STAR certificates\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Find CSA Star certificates\n- framework: C5\n  type: C5 audit reports\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Find C5 audit reports\n\
  - framework: FedRAMP\n  type: FedRAMP authorizations\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: See FedRAMP authorizations\n- framework: DORA\n  type: Critical ICT third-party service provider designation\n  scope: null\n  period: null\n  issuer: European Supervisory Authorities\n  report_access: unstated\n  text: SAP has been officially designated by the European Supervisory Authorities (ESAs) as a Critical ICT Third-Party\n    Service Provider (CTPP)\n- framework: ISO27001\n  type: certification\n  scope: global certifications\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We secure your business with strong infrastructure protection, continuous 24/7 monitoring, rapid incident\n    response, and built-in disaster recovery.\n  source: https://www.sap.com/about/trust-center/security/incident-management.html\n- framework: ISO27001\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text:\
  \ ISO/IEC 42001 for AI management systems\n  source: https://www.sap.com/about/trust-center.html\n"
source_yaml_url: https://artifacts.apis.io/sap-bw/compliance/sap-bw-compliance.yml
stated_fields:
- attestations
summary_line: 15 quoted statements, read from SAP BW's own page on 2026-11-10.
synthetic: false
tags:
- Business Intelligence
- Data Warehousing
- Enterprise
- ETL
- SAP
---
