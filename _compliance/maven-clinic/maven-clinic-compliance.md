---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: HITRUST
    issuer: independent third-party assessor
    period: null
    report_access: on_request
    scope: Maven systems
    text: Maven holds HITRUST certification, one of the most rigorous healthcare security frameworks in the industry, validated by an independent third-party assessor.
    type: certification
  - framework: SOC2
    issuer: independent auditor
    period: verified annually
    report_access: on_request
    scope: security, availability, and confidentiality of our systems
    text: Our SOC 2 Type II attestation covers the security, availability, and confidentiality of our systems, verified annually by an independent auditor.
    type: Type II attestation
  - framework: ISO42001
    issuer: null
    period: null
    report_access: unstated
    scope: AI systems
    text: We govern our AI systems in accordance with ISO 42001, the international standard for AI management systems.
    type: governance standard
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: technology company and service provider
    text: Maven is a HIPAA-compliant technology company and service provider.
    type: compliance
  trust_center:
    url: https://www.mavenclinic.com/security
frameworks:
- HIPAA
- HITRUST
- ISO42001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Maven Clinic
provenance_date: '2026-11-10'
provider_name: Maven Clinic
provider_slug: maven-clinic
slug: maven-clinic-compliance
source_date: '2026-11-10'
source_filename: maven-clinic-compliance.yml
source_heading: Compliance
source_page: https://www.mavenclinic.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Maven Clinic\naid: maven-clinic\nurl: https://www.mavenclinic.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/maven-clinic-trust-center.yml\ntrust_center:\n  url: https://www.mavenclinic.com/security\nattestations:\n- framework: HITRUST\n  type: certification\n  scope: Maven systems\n  period: null\n  issuer: independent third-party assessor\n  report_access: on_request\n  text: Maven holds HITRUST certification, one of the most rigorous healthcare security frameworks in the industry,\n    validated by an independent third-party assessor.\n- framework: SOC2\n  type: Type II attestation\n\
  \  scope: security, availability, and confidentiality of our systems\n  period: verified annually\n  issuer: independent auditor\n  report_access: on_request\n  text: Our SOC 2 Type II attestation covers the security, availability, and confidentiality of our systems, verified\n    annually by an independent auditor.\n- framework: ISO42001\n  type: governance standard\n  scope: AI systems\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We govern our AI systems in accordance with ISO 42001, the international standard for AI management systems.\n- framework: HIPAA\n  type: compliance\n  scope: technology company and service provider\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Maven is a HIPAA-compliant technology company and service provider.\n"
source_yaml_url: https://artifacts.apis.io/maven-clinic/compliance/maven-clinic-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Maven Clinic's own page on 2026-11-10.
synthetic: false
tags:
- Femtech
- Women's Health
- Family Health
- Virtual Care
- Telehealth
- Fertility
- Maternity
- Menopause
- Employer Benefits
- Health Plans
---
