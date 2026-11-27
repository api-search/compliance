---
api_specs:
- filename: unico-api-integration.postman_collection.json
  format: json
  label: Unico IDCloud API
  slug: idcloud-api
  spec_type: Postman
  url: https://artifacts.apis.io/unico/postman/unico-api-integration.postman_collection.json
- filename: unico-web-sdk-integration.postman_collection.json
  format: json
  label: Unico IDCloud Web & SDK API
  slug: idcloud-web-sdk
  spec_type: Postman
  url: https://artifacts.apis.io/unico/postman/unico-web-sdk-integration.postman_collection.json
- filename: unico-oauth2.postman_collection.json
  format: json
  label: Unico Identity OAuth2
  slug: identity-oauth2
  spec_type: Postman
  url: https://artifacts.apis.io/unico/postman/unico-oauth2.postman_collection.json
claim_count: 6
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: nda
    scope: Information Security Management System (ISMS)
    text: ISO/IEC 27001 Information Security Management System (ISMS). Certified
    type: certification
  - framework: ISO27701
    issuer: null
    period: null
    report_access: nda
    scope: Privacy Information Management System (PIMS), extending 27001
    text: ISO/IEC 27701 Privacy Information Management System (PIMS), extending 27001. Certified
    type: certification
  - framework: ISO42001
    issuer: null
    period: null
    report_access: nda
    scope: AI Management System
    text: ISO/IEC 42001 AI Management System — responsible governance of AI models. Certified
    type: certification
  - framework: SOC2
    issuer: KPMG Assurance Services Ltda.
    period: January 1 to September 30, 2025
    report_access: nda
    scope: Security & Availability controls
    text: Unico holds a SOC 2 Type 2 report covering the Security and Availability Trust Services Criteria, audited by KPMG Assurance Services Ltda. for the period of January 1 to September 30, 2025.
    type: Type 2 audit, Security and Availability criteria
  - framework: other
    issuer: iBeta; BixeLab
    period: null
    report_access: nda
    scope: Liveness and anti-spoofing engines, iBeta and BixeLab levels 1 and 2
    text: Full certificates and audit reports are available under NDA — request them below.
    type: independent lab testing (ISO/IEC 30107-3 presentation attack detection)
  - framework: other
    issuer: UN Global Compact
    period: null
    report_access: public
    scope: Ten Principles
    text: UN Global Compact Signatory committed to the Ten Principles on human rights, labor, environment and anti-corruption.
    type: UN Global Compact signatory
  trust_center:
    url: https://unico.io/trust-center
frameworks:
- ISO27001
- ISO27701
- ISO42001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Unico
provenance_date: '2026-11-10'
provider_name: Unico
provider_slug: unico
slug: unico-compliance
source_date: '2026-11-10'
source_filename: unico-compliance.yml
source_heading: Compliance
source_page: https://unico.io/trust-center
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Unico\naid: unico\nurl: https://unico.io/trust-center\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/unico-trust-center.yml\ntrust_center:\n  url: https://unico.io/trust-center\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: Information Security Management System (ISMS)\n  period: null\n  issuer: null\n  report_access: nda\n  text: ISO/IEC 27001 Information Security Management System (ISMS). Certified\n- framework: ISO27701\n  type: certification\n  scope: Privacy Information Management System (PIMS), extending 27001\n  period: null\n  issuer: null\n  report_access: nda\n  text:\
  \ ISO/IEC 27701 Privacy Information Management System (PIMS), extending 27001. Certified\n- framework: ISO42001\n  type: certification\n  scope: AI Management System\n  period: null\n  issuer: null\n  report_access: nda\n  text: ISO/IEC 42001 AI Management System — responsible governance of AI models. Certified\n- framework: SOC2\n  type: Type 2 audit, Security and Availability criteria\n  scope: Security & Availability controls\n  period: January 1 to September 30, 2025\n  issuer: KPMG Assurance Services Ltda.\n  report_access: nda\n  text: Unico holds a SOC 2 Type 2 report covering the Security and Availability Trust Services Criteria, audited\n    by KPMG Assurance Services Ltda. for the period of January 1 to September 30, 2025.\n- framework: other\n  type: independent lab testing (ISO/IEC 30107-3 presentation attack detection)\n  scope: Liveness and anti-spoofing engines, iBeta and BixeLab levels 1 and 2\n  period: null\n  issuer: iBeta; BixeLab\n  report_access: nda\n  text: Full\
  \ certificates and audit reports are available under NDA — request them below.\n- framework: other\n  type: UN Global Compact signatory\n  scope: Ten Principles\n  period: null\n  issuer: UN Global Compact\n  report_access: public\n  text: UN Global Compact Signatory committed to the Ten Principles on human rights, labor, environment and anti-corruption.\n"
source_yaml_url: https://artifacts.apis.io/unico/compliance/unico-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from Unico's own page on 2026-11-10.
synthetic: false
tags:
- Identity Verification
- Biometrics
- Facial Recognition
- Liveness Detection
- KYC
- Fraud Prevention
- Onboarding
- Authentication
- AML
- Age Verification
- Document Verification
- Identity
- Brazil
- Latin America
---
