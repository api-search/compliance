---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent third-party auditor
    period: null
    report_access: on_request
    scope: Reduct
    text: For a copy of our SOC2 report please email support@reduct.video .
    type: SOC 2 Type II certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: on_request
    scope: Reduct
    text: Reduct is designed to be GDPR compliant, and organizations in the EU or who work with EU-based constituents can contact us about engaging in a Data Processing Agreement with Reduct.
    type: GDPR compliance
  - framework: HIPAA
    issuer: null
    period: null
    report_access: on_request
    scope: AI and human transcription services
    text: Reduct offers HIPAA-compliant services for both AI and human transcription.
    type: HIPAA-compliant services with Business Associate Agreement
  trust_center:
    url: https://reduct.video/security/
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Reduct
provenance_date: '2026-11-10'
provider_name: Reduct
provider_slug: reduct
slug: reduct-compliance
source_date: '2026-11-10'
source_filename: reduct-compliance.yml
source_heading: Compliance
source_page: https://reduct.video/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Reduct\naid: reduct\nurl: https://reduct.video/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://reduct.video/security/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II certification\n  scope: Reduct\n  period: null\n  issuer: independent third-party auditor\n  report_access: on_request\n  text: For a copy of our SOC2 report please email support@reduct.video .\n- framework: GDPR\n  type: GDPR compliance\n  scope: Reduct\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Reduct is designed to be GDPR compliant, and organizations in the EU or who work with EU-based constituents\n\
  \    can contact us about engaging in a Data Processing Agreement with Reduct.\n- framework: HIPAA\n  type: HIPAA-compliant services with Business Associate Agreement\n  scope: AI and human transcription services\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Reduct offers HIPAA-compliant services for both AI and human transcription.\n"
source_yaml_url: https://artifacts.apis.io/reduct/compliance/reduct-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Reduct's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Application
- Video
- Transcription
- Translation
- Redaction
- Video Editing
- Media
- Artificial Intelligence
---
