---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent auditor
    period: null
    report_access: unstated
    scope: Encord business process, information technology, and risk management controls
    text: Encord has successfully completed its Systems and Organizational Control (SOC)-2 Examination.
    type: SOC 2 Examination
  - framework: HIPAA
    issuer: Vanta
    period: null
    report_access: unstated
    scope: protection of customers' sensitive health information
    text: uses Vanta to verify its security, privacy, and HIPAA compliance controls.
    type: HIPAA compliance controls
  - framework: GDPR
    issuer: Vanta
    period: null
    report_access: unstated
    scope: security measures and data handling practices
    text: Encord maintains GDPR compliance through comprehensive security measures and responsible data handling practices.
    type: GDPR compliance
  trust_center:
    url: https://encord.com/security/
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Encord
provenance_date: '2026-11-09'
provider_name: Encord
provider_slug: encord
slug: encord-compliance
source_date: '2026-11-09'
source_filename: encord-compliance.yml
source_heading: Compliance
source_page: https://encord.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Encord\naid: encord\nurl: https://encord.com/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/encord-trust-center.yml\ntrust_center:\n  url: https://encord.com/security/\nattestations:\n- framework: SOC2\n  type: SOC 2 Examination\n  scope: Encord business process, information technology, and risk management controls\n  period: null\n  issuer: independent auditor\n  report_access: unstated\n  text: Encord has successfully completed its Systems and Organizational Control (SOC)-2 Examination.\n- framework: HIPAA\n  type: HIPAA compliance controls\n  scope: protection of customers' sensitive\
  \ health information\n  period: null\n  issuer: Vanta\n  report_access: unstated\n  text: uses Vanta to verify its security, privacy, and HIPAA compliance controls.\n- framework: GDPR\n  type: GDPR compliance\n  scope: security measures and data handling practices\n  period: null\n  issuer: Vanta\n  report_access: unstated\n  text: Encord maintains GDPR compliance through comprehensive security measures and responsible data handling practices.\n"
source_yaml_url: https://artifacts.apis.io/encord/compliance/encord-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Encord's own page on 2026-11-09.
synthetic: false
tags:
- Computer Vision
- Data Labeling
- Annotation
- Machine Learning
- Model Evaluation
- Dataset Management
- Artificial Intelligence
- Image Annotation
- Video Annotation
- DICOM
- Active Learning
- Quality Assurance
---
