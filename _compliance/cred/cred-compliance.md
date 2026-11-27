---
claim_count: 7
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: payment processing environments
    text: PCI DSS v4.0.1 (Level 1) Certified - We are a Level 1 PCI DSS v4.0.1 certified organization
    type: certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Information Security Management System
    text: ISO/IEC 27001:2022 Certified - Our ISO/IEC 27001:2022 certification confirms the implementation of a comprehensive Information Security Management System (ISMS)
    type: certification
  - framework: ISO27701
    issuer: null
    period: null
    report_access: unstated
    scope: Privacy Information Management System (PIMS)
    text: ISO/IEC 27701:2019 Certified - We are ISO/IEC 27701:2019 certified for our Privacy Information Management System (PIMS)
    type: certification
  - framework: other
    issuer: NPCI
    period: null
    report_access: unstated
    scope: UPI operational and security mandates under NPCI Circulars 15B and 32
    text: UPI Compliance – NPCI Circulars 15B & 32 - We have successfully completed UPI compliance in line with NPCI Circulars 15B and 32.
    type: regulatory compliance
  - framework: other
    issuer: Reserve Bank of India
    period: null
    report_access: unstated
    scope: RBI tokenisation guidelines for card-on-file and device-based tokenisation
    text: We fully comply with the Reserve Bank of India’s tokenisation guidelines for both card-on-file and device-based tokenisation.
    type: regulatory compliance
  - framework: other
    issuer: Reserve Bank of India
    period: null
    report_access: unstated
    scope: RBI data localisation mandates; customer data hosted within India
    text: In accordance with the Reserve Bank of India’s data localisation mandates, all customer data is securely hosted within India.
    type: regulatory compliance
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Credit Information Companies (Regulation) Act, 2005 Sections 19, 20, 22 and CIC Rules 2006
    text: We adhere to the Credit Information Companies (Regulation) Act, 2005, specifically complying with Sections 19, 20, and 22
    type: regulatory compliance
  trust_center:
    url: https://cred.club/security
frameworks:
- ISO27001
- ISO27701
- PCI-DSS
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: CRED
provenance_date: '2026-11-09'
provider_name: CRED
provider_slug: cred
slug: cred-compliance
source_date: '2026-11-09'
source_filename: cred-compliance.yml
source_heading: Compliance
source_page: https://cred.club/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: CRED\naid: cred\nurl: https://cred.club/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/cred-trust-center.yml\ntrust_center:\n  url: https://cred.club/security\nattestations:\n- framework: PCI-DSS\n  type: certification\n  scope: payment processing environments\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI DSS v4.0.1 (Level 1) Certified - We are a Level 1 PCI DSS v4.0.1 certified organization\n- framework: ISO27001\n  type: certification\n  scope: Information Security Management System\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO/IEC 27001:2022\
  \ Certified - Our ISO/IEC 27001:2022 certification confirms the implementation of a comprehensive\n    Information Security Management System (ISMS)\n- framework: ISO27701\n  type: certification\n  scope: Privacy Information Management System (PIMS)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO/IEC 27701:2019 Certified - We are ISO/IEC 27701:2019 certified for our Privacy Information Management\n    System (PIMS)\n- framework: other\n  type: regulatory compliance\n  scope: UPI operational and security mandates under NPCI Circulars 15B and 32\n  period: null\n  issuer: NPCI\n  report_access: unstated\n  text: UPI Compliance – NPCI Circulars 15B & 32 - We have successfully completed UPI compliance in line with NPCI\n    Circulars 15B and 32.\n- framework: other\n  type: regulatory compliance\n  scope: RBI tokenisation guidelines for card-on-file and device-based tokenisation\n  period: null\n  issuer: Reserve Bank of India\n  report_access: unstated\n  text: We\
  \ fully comply with the Reserve Bank of India’s tokenisation guidelines for both card-on-file and device-based\n    tokenisation.\n- framework: other\n  type: regulatory compliance\n  scope: RBI data localisation mandates; customer data hosted within India\n  period: null\n  issuer: Reserve Bank of India\n  report_access: unstated\n  text: In accordance with the Reserve Bank of India’s data localisation mandates, all customer data is securely\n    hosted within India.\n- framework: other\n  type: regulatory compliance\n  scope: Credit Information Companies (Regulation) Act, 2005 Sections 19, 20, 22 and CIC Rules 2006\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We adhere to the Credit Information Companies (Regulation) Act, 2005, specifically complying with Sections\n    19, 20, and 22\n"
source_yaml_url: https://artifacts.apis.io/cred/compliance/cred-compliance.yml
stated_fields:
- attestations
summary_line: 7 quoted statements, read from CRED's own page on 2026-11-09.
synthetic: false
tags:
- Consumer Fintech
- Credit Cards
- Bill Payments
- Rewards
- UPI
- Lending
- India
---
