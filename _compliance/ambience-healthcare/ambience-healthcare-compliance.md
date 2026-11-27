---
claim_count: 7
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type I
    type: Type I
  - framework: SOC2
    issuer: null
    period: '2026'
    report_access: unstated
    scope: null
    text: SOC 2 Type II - 2026
    type: Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: null
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA
    type: null
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Ambience platform
    source: https://www.ambiencehealthcare.com/informatics
    text: Fully HIPAA compliant
    type: compliance statement
  - framework: SOC2
    issuer: Independent auditor
    period: null
    report_access: unstated
    scope: Ambience
    source: https://www.ambiencehealthcare.com/informatics
    text: SOC 2 Type I & Type II certified
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: personal data processing, storage, and access
    source: https://www.ambiencehealthcare.com/informatics
    text: GDPR conformant
    type: conformance statement
  trust_center:
    url: https://trust.ambiencehealthcare.com/
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Ambience Healthcare
provenance_date: '2026-11-09'
provider_name: Ambience Healthcare
provider_slug: ambience-healthcare
slug: ambience-healthcare-compliance
source_date: '2026-11-09'
source_filename: ambience-healthcare-compliance.yml
source_heading: Compliance
source_page: https://trust.ambiencehealthcare.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Ambience Healthcare\naid: ambience-healthcare\nurl: https://trust.ambiencehealthcare.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/ambience-healthcare-trust-center.yml\n  sources:\n  - https://trust.ambiencehealthcare.com/\n  - https://www.ambiencehealthcare.com/informatics\ntrust_center:\n  url: https://trust.ambiencehealthcare.com/\nattestations:\n- framework: SOC2\n  type: Type I\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type I\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: '2026'\n  issuer: null\n  report_access: unstated\n  text:\
  \ SOC 2 Type II - 2026\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: HIPAA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA\n- framework: HIPAA\n  type: compliance statement\n  scope: Ambience platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Fully HIPAA compliant\n  source: https://www.ambiencehealthcare.com/informatics\n- framework: SOC2\n  type: certification\n  scope: Ambience\n  period: null\n  issuer: Independent auditor\n  report_access: unstated\n  text: SOC 2 Type I & Type II certified\n  source: https://www.ambiencehealthcare.com/informatics\n- framework: GDPR\n  type: conformance statement\n  scope: personal data processing, storage, and access\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR conformant\n  source: https://www.ambiencehealthcare.com/informatics\n"
source_yaml_url: https://artifacts.apis.io/ambience-healthcare/compliance/ambience-healthcare-compliance.yml
stated_fields:
- attestations
summary_line: 7 quoted statements, read from Ambience Healthcare's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Artificial Intelligence
- Clinical Documentation
- Ambient AI
- Medical Coding
- Electronic Health Records
- FHIR
- Health IT
- Speech Recognition
---
