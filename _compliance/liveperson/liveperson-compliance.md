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
    text: SOC 2 Type II
    type: certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: LivePerson ISO 27001 Certificate Final
    type: certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: LivePerson HIPAA Final Report
    type: report
  - framework: HITRUST
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: LivePerson SOC 2 Type 2 + HITRUST Report
    type: report
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: LivePerson PCI-DSS Attestation of Compliance
    type: attestation of compliance
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: certification
  trust_center:
    url: https://trust.liveperson.com/
frameworks:
- GDPR
- HIPAA
- HITRUST
- ISO27001
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: LivePerson
provenance_date: '2026-11-09'
provider_name: LivePerson
provider_slug: liveperson
slug: liveperson-compliance
source_date: '2026-11-09'
source_filename: liveperson-compliance.yml
source_heading: Compliance
source_page: https://trust.liveperson.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: LivePerson\naid: liveperson\nurl: https://trust.liveperson.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/liveperson-trust-center.yml\ntrust_center:\n  url: https://trust.liveperson.com/\nattestations:\n- framework: SOC2\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: LivePerson ISO 27001 Certificate Final\n- framework: HIPAA\n  type: report\n  scope: null\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: LivePerson HIPAA Final Report\n- framework: HITRUST\n  type: report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: LivePerson SOC 2 Type 2 + HITRUST Report\n- framework: PCI-DSS\n  type: attestation of compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: LivePerson PCI-DSS Attestation of Compliance\n- framework: GDPR\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n"
source_yaml_url: https://artifacts.apis.io/liveperson/compliance/liveperson-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from LivePerson's own page on 2026-11-09.
synthetic: false
tags:
- Conversational AI
- Customer Engagement
- Messaging
- Contact Center
- Bots
- Chat
---
