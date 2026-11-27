---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: Fiat card and ACH checkouts handled by Stripe
    text: Card details are tokenized directly within Stripe's infrastructure, rendering Aradia fully eligible for PCI-DSS Self-Assessment Questionnaire A (SAQ A).
    type: SAQ A eligibility via Stripe
  - framework: ISO42001
    issuer: null
    period: null
    report_access: unstated
    scope: Supports client ISO/IEC 42001 lifecycle governance
    text: Supports client ISO/IEC 42001 lifecycle governance through deterministic local controls
    type: Alignment claim
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: AI compute remains inside the enterprise's existing SOC 2 audited perimeter
    text: 'Simplified SOC 2 Scope: AI compute remains inside the enterprise''s existing SOC 2 audited perimeter.'
    type: Client alignment
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: On-premise hardware supports HIPAA Security Rule
    text: 'HIPAA & HITECH Act Security Rule: On-premise DGX hardware guarantees that Protected Health Information (PHI) and electronic PHI (ePHI) never exit the covered entity''s physical premises.'
    type: Alignment claim
  trust_center:
    url: https://aradia.com/compliance/
frameworks:
- HIPAA
- ISO42001
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Aradia Systems
provenance_date: '2026-11-09'
provider_name: Aradia Systems
provider_slug: aradia-com
slug: aradia-com-compliance
source_date: '2026-11-09'
source_filename: aradia-com-compliance.yml
source_heading: Compliance
source_page: https://aradia.com/compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Aradia Systems\naid: aradia-com\nurl: https://aradia.com/compliance/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://aradia.com/compliance/\nattestations:\n- framework: PCI-DSS\n  type: SAQ A eligibility via Stripe\n  scope: Fiat card and ACH checkouts handled by Stripe\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Card details are tokenized directly within Stripe's infrastructure, rendering Aradia fully eligible for\n    PCI-DSS Self-Assessment Questionnaire A (SAQ A).\n- framework: ISO42001\n  type: Alignment claim\n  scope: Supports client ISO/IEC 42001 lifecycle governance\n\
  \  period: null\n  issuer: null\n  report_access: unstated\n  text: Supports client ISO/IEC 42001 lifecycle governance through deterministic local controls\n- framework: SOC2\n  type: Client alignment\n  scope: AI compute remains inside the enterprise's existing SOC 2 audited perimeter\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'Simplified SOC 2 Scope: AI compute remains inside the enterprise''s existing SOC 2 audited perimeter.'\n- framework: HIPAA\n  type: Alignment claim\n  scope: On-premise hardware supports HIPAA Security Rule\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'HIPAA & HITECH Act Security Rule: On-premise DGX hardware guarantees that Protected Health Information\n    (PHI) and electronic PHI (ePHI) never exit the covered entity''s physical premises.'\n"
source_yaml_url: https://artifacts.apis.io/aradia-com/compliance/aradia-com-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Aradia Systems's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Private AI
- Infrastructure
- NVIDIA
- DGX
- Sovereign
- On-Prem
- AI Agents
---
