---
api_specs:
- filename: sanas-stream-asyncapi.yml
  format: yaml
  label: Sanas Stream API
  slug: sanas-stream-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/sanas/asyncapi/sanas-stream-asyncapi.yml
claim_count: 15
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Compliance PCI DSS V4.0.1 2 documents
    type: compliance documents
  - framework: SOC3
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Compliance SOC 3 1 document
    type: compliance documents
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Compliance SOC 2 1 document
    type: compliance documents
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Compliance HIPAA 1 document
    type: compliance documents
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Compliance GDPR 1 document
    type: compliance documents
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Compliance CCPA 1 document
    type: compliance documents
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001:2022
    type: certification listed
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CSA STAR
    type: certification listed
  - framework: HITRUST
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HITRUST I1
    type: certification listed
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: information security management system
    source: https://developer.sanas.ai/Docs/Enterprise/Compliance-and-Data-Residency
    text: ISO 27001:2022 Information security management system certified.
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://developer.sanas.ai/Docs/Enterprise/Compliance-and-Data-Residency
    text: SOC 2 Type II SSAE-21 SOC 2 Type 2 attested.
    type: Type II attestation
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://developer.sanas.ai/Docs/Enterprise/Compliance-and-Data-Residency
    text: HIPAA Compliant. BAA available for enterprise customers.
    type: compliance
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: EU, UK, and Swiss data protection regulations
    source: https://developer.sanas.ai/Docs/Enterprise/Compliance-and-Data-Residency
    text: GDPR Compliant with EU, UK, and Swiss data protection regulations.
    type: compliance
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://developer.sanas.ai/Docs/Enterprise/Compliance-and-Data-Residency
    text: PCI DSS Payment card industry data security standard compliant.
    type: compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: California Consumer Privacy Act
    source: https://developer.sanas.ai/Docs/Enterprise/Compliance-and-Data-Residency
    text: CCPA California Consumer Privacy Act compliant.
    type: compliance
  trust_center:
    url: https://trust.sanas.ai/
frameworks:
- CCPA
- CSA-STAR
- GDPR
- HIPAA
- HITRUST
- ISO27001
- PCI-DSS
- SOC2
- SOC3
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Sanas
provenance_date: '2026-11-10'
provider_name: Sanas
provider_slug: sanas
slug: sanas-compliance
source_date: '2026-11-10'
source_filename: sanas-compliance.yml
source_heading: Compliance
source_page: https://trust.sanas.ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Sanas\naid: sanas\nurl: https://trust.sanas.ai/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://developer.sanas.ai/Docs/Enterprise/Compliance-and-Data-Residency\n  - https://trust.sanas.ai/\ntrust_center:\n  url: https://trust.sanas.ai/\nattestations:\n- framework: PCI-DSS\n  type: compliance documents\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliance PCI DSS V4.0.1 2 documents\n- framework: SOC3\n  type: compliance documents\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliance SOC 3 1 document\n- framework: SOC2\n  type:\
  \ compliance documents\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliance SOC 2 1 document\n- framework: HIPAA\n  type: compliance documents\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliance HIPAA 1 document\n- framework: GDPR\n  type: compliance documents\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliance GDPR 1 document\n- framework: CCPA\n  type: compliance documents\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliance CCPA 1 document\n- framework: ISO27001\n  type: certification listed\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022\n- framework: CSA-STAR\n  type: certification listed\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CSA STAR\n- framework: HITRUST\n  type: certification listed\n  scope: null\n  period: null\n  issuer:\
  \ null\n  report_access: unstated\n  text: HITRUST I1\n- framework: ISO27001\n  type: certification\n  scope: information security management system\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022 Information security management system certified.\n  source: https://developer.sanas.ai/Docs/Enterprise/Compliance-and-Data-Residency\n- framework: SOC2\n  type: Type II attestation\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II SSAE-21 SOC 2 Type 2 attested.\n  source: https://developer.sanas.ai/Docs/Enterprise/Compliance-and-Data-Residency\n- framework: HIPAA\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA Compliant. BAA available for enterprise customers.\n  source: https://developer.sanas.ai/Docs/Enterprise/Compliance-and-Data-Residency\n- framework: GDPR\n  type: compliance\n  scope: EU, UK, and Swiss data protection regulations\n  period: null\n\
  \  issuer: null\n  report_access: unstated\n  text: GDPR Compliant with EU, UK, and Swiss data protection regulations.\n  source: https://developer.sanas.ai/Docs/Enterprise/Compliance-and-Data-Residency\n- framework: PCI-DSS\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI DSS Payment card industry data security standard compliant.\n  source: https://developer.sanas.ai/Docs/Enterprise/Compliance-and-Data-Residency\n- framework: CCPA\n  type: compliance\n  scope: California Consumer Privacy Act\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA California Consumer Privacy Act compliant.\n  source: https://developer.sanas.ai/Docs/Enterprise/Compliance-and-Data-Residency\n"
source_yaml_url: https://artifacts.apis.io/sanas/compliance/sanas-compliance.yml
stated_fields:
- attestations
summary_line: 15 quoted statements, read from Sanas's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Speech AI
- Voice AI
- Accent Translation
- Language Translation
- Speech Enhancement
- Real-Time Audio
- SDK
- WebSocket
- Contact Center
- Real-Time
---
