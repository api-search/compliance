---
api_specs:
- filename: livekit-asyncapi.yml
  format: yaml
  label: LiveKit Signaling Protocol (WebSocket)
  slug: signaling-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/livekit/asyncapi/livekit-asyncapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: security, availability, and confidentiality
    text: Independently audited against the AICPA's Trust Services Criteria for security, availability, and confidentiality.
    type: Type II audit
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Aligned with EU data protection and privacy law.
    type: alignment
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Scale and Enterprise customers handling protected health information
    text: BAAs available for Scale and Enterprise customers handling protected health information.
    type: BAA available
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: California consumer privacy law, including data access and deletion rights
    text: Compliant with California consumer privacy law, including data access and deletion rights.
    type: compliance
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: lawful transfer of personal data from the EU to the United States
    text: Certified for the lawful transfer of personal data from the EU to the United States.
    type: EU-US Data Privacy Framework certification
  trust_center:
    url: https://livekit.com/security
frameworks:
- CCPA
- GDPR
- HIPAA
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: LiveKit
provenance_date: '2026-11-09'
provider_name: LiveKit
provider_slug: livekit
slug: livekit-compliance
source_date: '2026-11-09'
source_filename: livekit-compliance.yml
source_heading: Compliance
source_page: https://livekit.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: LiveKit\naid: livekit\nurl: https://livekit.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/livekit-trust-center.yml\ntrust_center:\n  url: https://livekit.com/security\nattestations:\n- framework: SOC2\n  type: Type II audit\n  scope: security, availability, and confidentiality\n  period: null\n  issuer: null\n  report_access: nda\n  text: Independently audited against the AICPA's Trust Services Criteria for security, availability, and confidentiality.\n- framework: GDPR\n  type: alignment\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Aligned with\
  \ EU data protection and privacy law.\n- framework: HIPAA\n  type: BAA available\n  scope: Scale and Enterprise customers handling protected health information\n  period: null\n  issuer: null\n  report_access: unstated\n  text: BAAs available for Scale and Enterprise customers handling protected health information.\n- framework: CCPA\n  type: compliance\n  scope: California consumer privacy law, including data access and deletion rights\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliant with California consumer privacy law, including data access and deletion rights.\n- framework: other\n  type: EU-US Data Privacy Framework certification\n  scope: lawful transfer of personal data from the EU to the United States\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Certified for the lawful transfer of personal data from the EU to the United States.\n"
source_yaml_url: https://artifacts.apis.io/livekit/compliance/livekit-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from LiveKit's own page on 2026-11-09.
synthetic: false
tags:
- Real-Time
- WebRTC
- Audio
- Video
- Open Source
- AI Agents
- Voice
- Cloud
---
