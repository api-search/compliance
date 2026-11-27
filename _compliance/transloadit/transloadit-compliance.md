---
claim_count: 6
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: null
    text: Our full SOC 2 Type II report is available on request, once an NDA is in place.
    type: Type II report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: are certified to ISO/IEC 27001.
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We operate in compliance with GDPR and CCPA requirements
    type: compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We operate in compliance with GDPR and CCPA requirements
    type: compliance
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: HIPAA-regulated workloads
    text: support HIPAA-regulated workloads under a Business Associate Agreement
    type: Business Associate Agreement support
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: credit card payments for subscriptions handled by Stripe
    text: Stripe, a PCI DSS Level 1 certified payment processor.
    type: certified payment processor (Stripe)
  trust_center:
    url: https://transloadit.com/security/
frameworks:
- CCPA
- GDPR
- HIPAA
- ISO27001
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Transloadit
provenance_date: '2026-11-10'
provider_name: Transloadit
provider_slug: transloadit
slug: transloadit-compliance
source_date: '2026-11-10'
source_filename: transloadit-compliance.yml
source_heading: Compliance
source_page: https://transloadit.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Transloadit\naid: transloadit\nurl: https://transloadit.com/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/transloadit-trust-center.yml\ntrust_center:\n  url: https://transloadit.com/security/\nattestations:\n- framework: SOC2\n  type: Type II report\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: Our full SOC 2 Type II report is available on request, once an NDA is in place.\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: are certified to ISO/IEC 27001.\n- framework: GDPR\n  type:\
  \ compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We operate in compliance with GDPR and CCPA requirements\n- framework: CCPA\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We operate in compliance with GDPR and CCPA requirements\n- framework: HIPAA\n  type: Business Associate Agreement support\n  scope: HIPAA-regulated workloads\n  period: null\n  issuer: null\n  report_access: unstated\n  text: support HIPAA-regulated workloads under a Business Associate Agreement\n- framework: PCI-DSS\n  type: certified payment processor (Stripe)\n  scope: credit card payments for subscriptions handled by Stripe\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Stripe, a PCI DSS Level 1 certified payment processor.\n"
source_yaml_url: https://artifacts.apis.io/transloadit/compliance/transloadit-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from Transloadit's own page on 2026-11-10.
synthetic: false
tags:
- File Processing
- Media Encoding
- Video Transcoding
- Image Resizing
- Audio Extraction
- Thumbnail Generation
- File Uploading
- Media API
---
