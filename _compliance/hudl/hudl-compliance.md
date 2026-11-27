---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: NIST-800-53
    issuer: null
    period: null
    report_access: unstated
    scope: Hudl security program
    text: Hudl’s security program is aligned with the NIST 800-53 and SOC frameworks
    type: security program alignment
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Hudl services
    text: 'The following documents can be made available upon request: PCI SAQ-A and SAQ-C Full HECVAT TXRAMP Certificate Penetration Testing Attestation Letters SOC 2 Report'
    type: report
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: on_request
    scope: payment processing
    text: PCI SAQ-A and SAQ-C
    type: self-assessment questionnaire
  trust_center:
    url: https://www.hudl.com/security
frameworks:
- NIST-800-53
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Hudl
provenance_date: '2026-11-09'
provider_name: Hudl
provider_slug: hudl
slug: hudl-compliance
source_date: '2026-11-09'
source_filename: hudl-compliance.yml
source_heading: Compliance
source_page: https://www.hudl.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Hudl\naid: hudl\nurl: https://www.hudl.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/hudl-trust-center.yml\ntrust_center:\n  url: https://www.hudl.com/security\nattestations:\n- framework: NIST-800-53\n  type: security program alignment\n  scope: Hudl security program\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Hudl’s security program is aligned with the NIST 800-53 and SOC frameworks\n- framework: SOC2\n  type: report\n  scope: Hudl services\n  period: null\n  issuer: null\n  report_access: on_request\n  text: 'The following documents can be made available upon\
  \ request: PCI SAQ-A and SAQ-C Full HECVAT TXRAMP Certificate\n    Penetration Testing Attestation Letters SOC 2 Report'\n- framework: PCI-DSS\n  type: self-assessment questionnaire\n  scope: payment processing\n  period: null\n  issuer: null\n  report_access: on_request\n  text: PCI SAQ-A and SAQ-C\n"
source_yaml_url: https://artifacts.apis.io/hudl/compliance/hudl-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Hudl's own page on 2026-11-09.
synthetic: false
tags:
- Sports
- Sports Technology
- Sports Performance
- Sports Analytics
- Video Analysis
- Performance Analysis
- Video Capture
- AI Cameras
- Coaching
- Team Management
- Football Analytics
- Soccer Analytics
- Basketball
- Volleyball
- American Football
- Wyscout
- Statsbomb
- Sportscode
- Athlete Tracking
- Live Streaming
- Ticketing
- Sports Data
---
