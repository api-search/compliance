---
claim_count: 6
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II compliance
    type: SOC 2 Type II
  - framework: SOC3
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: our SOC 3 report is available for review
    type: SOC 3 report
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: payment information processing
    text: Your payment information is processed securely through PCI-compliant systems.
    type: PCI Compliance
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Rev's enterprise tier transcription services
    text: Rev's enterprise tier provides HIPAA-compliant* transcription services to protect sensitive healthcare data.
    type: HIPAA compliance
  - framework: other
    issuer: Third-party assessor
    period: null
    report_access: unstated
    scope: Enterprise accounts
    text: Third-party assessed to meet FBI security standards, with annual testing.
    type: CJIS Compliance
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We are GDPR compliant
    type: GDPR compliance
  trust_center:
    url: https://www.rev.ai/security
frameworks:
- GDPR
- HIPAA
- PCI-DSS
- SOC2
- SOC3
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Rev AI
provenance_date: '2026-11-10'
provider_name: Rev AI
provider_slug: rev-ai
slug: rev-ai-compliance
source_date: '2026-11-10'
source_filename: rev-ai-compliance.yml
source_heading: Compliance
source_page: https://www.rev.ai/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Rev AI\naid: rev-ai\nurl: https://www.rev.ai/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/rev-ai-trust-center.yml\ntrust_center:\n  url: https://www.rev.ai/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II compliance\n- framework: SOC3\n  type: SOC 3 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: our SOC 3 report is available for review\n- framework: PCI-DSS\n  type: PCI Compliance\n  scope: payment information processing\n  period:\
  \ null\n  issuer: null\n  report_access: unstated\n  text: Your payment information is processed securely through PCI-compliant systems.\n- framework: HIPAA\n  type: HIPAA compliance\n  scope: Rev's enterprise tier transcription services\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Rev's enterprise tier provides HIPAA-compliant* transcription services to protect sensitive healthcare data.\n- framework: other\n  type: CJIS Compliance\n  scope: Enterprise accounts\n  period: null\n  issuer: Third-party assessor\n  report_access: unstated\n  text: Third-party assessed to meet FBI security standards, with annual testing.\n- framework: GDPR\n  type: GDPR compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We are GDPR compliant\n"
source_yaml_url: https://artifacts.apis.io/rev-ai/compliance/rev-ai-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from Rev AI's own page on 2026-11-10.
synthetic: false
tags:
- Speech Recognition
- Speech-to-Text
- Transcription
- Audio
- Natural Language Processing
- Streaming
- Real-Time
- Sentiment Analysis
- Topic Extraction
- Language Identification
- Voice
---
