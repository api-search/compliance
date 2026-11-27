---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II Aligned
    type: Type II (aligned)
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR Compliant
    type: compliance
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA Ready
    type: readiness
  trust_center:
    url: https://www.luminos.ai/security/
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Luminos.AI
provenance_date: '2026-11-10'
provider_name: Luminos.AI
provider_slug: luminosai
slug: luminosai-compliance
source_date: '2026-11-10'
source_filename: luminosai-compliance.yml
source_heading: Compliance
source_page: https://www.luminos.ai/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Luminos.AI\naid: luminosai\nurl: https://www.luminos.ai/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/luminosai-trust-center.yml\ntrust_center:\n  url: https://www.luminos.ai/security/\nattestations:\n- framework: SOC2\n  type: Type II (aligned)\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II Aligned\n- framework: GDPR\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR Compliant\n- framework: HIPAA\n  type: readiness\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: HIPAA Ready\n"
source_yaml_url: https://artifacts.apis.io/luminosai/compliance/luminosai-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Luminos.AI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- AI Governance
- AI Evaluation
- Compliance
- Risk Management
- AI Safety
- RegTech
- AI Agents
---
