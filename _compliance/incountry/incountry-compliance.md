---
api_specs:
- filename: RestAPI_Demo_oAuth.postman_collection-e8b012cac5488563ba466e6ea44c309c.json
  format: json
  label: InCountry REST API
  slug: incountry-rest-api
  spec_type: Postman
  url: https://docs.incountry.com/assets/files/RestAPI_Demo_oAuth.postman_collection-e8b012cac5488563ba466e6ea44c309c.json
claim_count: 12
description: ''
doc:
  attestations:
  - framework: SOC1
    issuer: null
    period: null
    report_access: on_request
    scope: internal controls on financial reporting
    text: Our internal controls report, conducted in accordance with industry standards (SSAE No. 16 and ISAE No. 3402)
    type: Type II
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: security, availability, and confidentiality
    text: InCountry has obtained a SOC 2 Type II (Service Organization Controls) report based on the AICPA Trust Service Principles (TSP) and Criteria
    type: Type II
  - framework: SOC3
    issuer: null
    period: null
    report_access: unstated
    scope: Cloud Service Provider controls
    text: A SOC 3 (Service Organization Controls) report is an abbreviated version of a SOC 2 report
    type: SOC 3 report
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: on_request
    scope: handling of credit card information
    text: The Payment Card Industry-Data Security Standard (PCI-DSS) is an industry level information security standard
    type: PCI DSS
  - framework: HIPAA
    issuer: null
    period: null
    report_access: on_request
    scope: patient health information
    text: The Health Insurance Portability and Accountability Act (HIPAA) provides U.S. federal protections for patient health information
    type: HIPAA
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: personal data under Russian law
    text: InCountry complies with Federal Law No. 152
    type: FZ-152 (Federal Law No. 152)
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: unstated
    scope: security of cloud service provider
    text: The Security Trust Assurance and Risk (STAR) Level 2 Certification is a rigorous third-party independent assessment
    type: STAR Level 2 Certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: information security management system
    text: ISO/IEC 27001:2022 is a risk-based set of information security requirements
    type: ISO/IEC 27001:2022
  - framework: ISO27017
    issuer: null
    period: null
    report_access: unstated
    scope: cloud-specific information security controls
    text: ISO/IEC 27017:2015 provides guidance on the information security aspects of cloud computing
    type: ISO/IEC 27017:2015
  - framework: ISO27018
    issuer: null
    period: null
    report_access: unstated
    scope: protection of personal data in the cloud
    text: ISO/IEC 27018:2019 is a code of practice that focuses on the protection of personal data in the cloud
    type: ISO/IEC 27018:2019
  - framework: ISO27701
    issuer: null
    period: null
    report_access: unstated
    scope: privacy information management system
    text: The design goal of ISO 27701 is to enhance the existing Information Security Management System (ISMS)
    type: ISO 27701
  - framework: other
    issuer: null
    period: null
    report_access: on_request
    scope: good clinical, laboratory, and manufacturing practices
    text: Compliance on the InCountry platform enables a secure and highly available data distribution and localization
    type: GxP compliance
  trust_center:
    url: https://incountry.com/resource/security-and-compliance/
frameworks:
- CSA-STAR
- HIPAA
- ISO27001
- ISO27017
- ISO27018
- ISO27701
- PCI-DSS
- SOC1
- SOC2
- SOC3
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: InCountry
provenance_date: '2026-11-09'
provider_name: InCountry
provider_slug: incountry
slug: incountry-compliance
source_date: '2026-11-09'
source_filename: incountry-compliance.yml
source_heading: Compliance
source_page: https://incountry.com/resource/security-and-compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: InCountry\naid: incountry\nurl: https://incountry.com/resource/security-and-compliance/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://incountry.com/resource/security-and-compliance/\nattestations:\n- framework: SOC1\n  type: Type II\n  scope: internal controls on financial reporting\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Our internal controls report, conducted in accordance with industry standards (SSAE No. 16 and ISAE No.\n    3402)\n- framework: SOC2\n  type: Type II\n  scope: security, availability, and confidentiality\n  period: null\n  issuer: null\n  report_access:\
  \ on_request\n  text: InCountry has obtained a SOC 2 Type II (Service Organization Controls) report based on the AICPA Trust Service\n    Principles (TSP) and Criteria\n- framework: SOC3\n  type: SOC 3 report\n  scope: Cloud Service Provider controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: A SOC 3 (Service Organization Controls) report is an abbreviated version of a SOC 2 report\n- framework: PCI-DSS\n  type: PCI DSS\n  scope: handling of credit card information\n  period: null\n  issuer: null\n  report_access: on_request\n  text: The Payment Card Industry-Data Security Standard (PCI-DSS) is an industry level information security standard\n- framework: HIPAA\n  type: HIPAA\n  scope: patient health information\n  period: null\n  issuer: null\n  report_access: on_request\n  text: The Health Insurance Portability and Accountability Act (HIPAA) provides U.S. federal protections for patient\n    health information\n- framework: other\n  type: FZ-152 (Federal Law\
  \ No. 152)\n  scope: personal data under Russian law\n  period: null\n  issuer: null\n  report_access: unstated\n  text: InCountry complies with Federal Law No. 152\n- framework: CSA-STAR\n  type: STAR Level 2 Certification\n  scope: security of cloud service provider\n  period: null\n  issuer: null\n  report_access: unstated\n  text: The Security Trust Assurance and Risk (STAR) Level 2 Certification is a rigorous third-party independent\n    assessment\n- framework: ISO27001\n  type: ISO/IEC 27001:2022\n  scope: information security management system\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO/IEC 27001:2022 is a risk-based set of information security requirements\n- framework: ISO27017\n  type: ISO/IEC 27017:2015\n  scope: cloud-specific information security controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO/IEC 27017:2015 provides guidance on the information security aspects of cloud computing\n- framework: ISO27018\n  type:\
  \ ISO/IEC 27018:2019\n  scope: protection of personal data in the cloud\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO/IEC 27018:2019 is a code of practice that focuses on the protection of personal data in the cloud\n- framework: ISO27701\n  type: ISO 27701\n  scope: privacy information management system\n  period: null\n  issuer: null\n  report_access: unstated\n  text: The design goal of ISO 27701 is to enhance the existing Information Security Management System (ISMS)\n- framework: other\n  type: GxP compliance\n  scope: good clinical, laboratory, and manufacturing practices\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Compliance on the InCountry platform enables a secure and highly available data distribution and localization\n"
source_yaml_url: https://artifacts.apis.io/incountry/compliance/incountry-compliance.yml
stated_fields:
- attestations
summary_line: 12 quoted statements, read from InCountry's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Residency
- Data Localization
- Compliance
- Privacy
- Data Security
- Encryption
- PII
- GDPR
- Data Sovereignty
- MCP
---
