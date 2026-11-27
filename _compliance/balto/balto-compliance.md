---
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type 2 Report
    type: SOC 2 Type 2
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PCI-DSS 4.0
    type: PCI-DSS 4.0
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA
    type: HIPAA
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: GDPR
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Balto (client data)
    source: https://www.balto.ai/security/
    text: Balto is SOC 2 compliant and uses advanced security infrastructure and protocols
    type: certification claim
  trust_center:
    url: https://trust.balto.ai/
frameworks:
- GDPR
- HIPAA
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Balto
provenance_date: '2026-11-09'
provider_name: Balto
provider_slug: balto
slug: balto-compliance
source_date: '2026-11-09'
source_filename: balto-compliance.yml
source_heading: Compliance
source_page: https://trust.balto.ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Balto\naid: balto\nurl: https://trust.balto.ai/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://trust.balto.ai/\n  - https://www.balto.ai/security/\ntrust_center:\n  url: https://trust.balto.ai/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2 Report\n- framework: PCI-DSS\n  type: PCI-DSS 4.0\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI-DSS 4.0\n- framework: HIPAA\n  type: HIPAA\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA\n\
  - framework: GDPR\n  type: GDPR\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: SOC2\n  type: certification claim\n  scope: Balto (client data)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Balto is SOC 2 compliant and uses advanced security infrastructure and protocols\n  source: https://www.balto.ai/security/\n"
source_yaml_url: https://artifacts.apis.io/balto/compliance/balto-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Balto's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Contact Center
- Conversation Intelligence
- Agent Assist
- Real-Time Guidance
- Quality Assurance
- Compliance
- Call Center
- CCaaS
- Voice AI
---
