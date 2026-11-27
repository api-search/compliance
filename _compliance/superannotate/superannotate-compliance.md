---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: trust service principles
    text: SOC 2 Service Organization Controls (SOC 2) (Type II) trust service principles
    type: SOC 2 Type II report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: ISO/IEC 27001:2022 Information security, cybersecurity and privacy protection
    type: ISO/IEC 27001:2022 certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: personal data of EU citizens
    text: Protect the personal data and privacy of EU citizens for transaction that occur within EU member states
    type: regulation compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: California residents
    text: CCPA California Consumer Privacy Act, is legislation designed to improve the data privacy of California residents
    type: regulation compliance
  trust_center:
    url: https://trust.superannotate.com/
frameworks:
- CCPA
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: SuperAnnotate
provenance_date: '2026-11-10'
provider_name: SuperAnnotate
provider_slug: superannotate
slug: superannotate-compliance
source_date: '2026-11-10'
source_filename: superannotate-compliance.yml
source_heading: Compliance
source_page: https://trust.superannotate.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: SuperAnnotate\naid: superannotate\nurl: https://trust.superannotate.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/superannotate-trust-center.yml\ntrust_center:\n  url: https://trust.superannotate.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: trust service principles\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Service Organization Controls (SOC 2) (Type II) trust service principles\n- framework: ISO27001\n  type: ISO/IEC 27001:2022 certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text:\
  \ ISO/IEC 27001:2022 Information security, cybersecurity and privacy protection\n- framework: GDPR\n  type: regulation compliance\n  scope: personal data of EU citizens\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Protect the personal data and privacy of EU citizens for transaction that occur within EU member states\n- framework: CCPA\n  type: regulation compliance\n  scope: California residents\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA California Consumer Privacy Act, is legislation designed to improve the data privacy of California\n    residents\n"
source_yaml_url: https://artifacts.apis.io/superannotate/compliance/superannotate-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from SuperAnnotate's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Annotation
- Data Labeling
- Computer Vision
- Natural Language Processing
- Machine Learning
- Training Data
- Image Annotation
- Video Annotation
- Text Annotation
- Audio Annotation
- MLOps
---
