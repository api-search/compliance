---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: data subject rights and transfers
    text: Self-assessed GDPR EU General Data Protection Regulation. We support data subject rights and use Standard Contractual Clauses for transfers.
    type: Self-assessed
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: California Consumer Privacy Act as amended by the CPRA
    text: Self-assessed CCPA California Consumer Privacy Act, as amended by the CPRA.
    type: Self-assessed
  - framework: PCI-DSS
    issuer: Stripe
    period: null
    report_access: unstated
    scope: card payments handled by Stripe
    text: Card payments are handled by Stripe, a PCI DSS Level 1 certified provider.
    type: Via third-party provider (Stripe)
  trust_center:
    url: https://www.1lookup.io/security
frameworks:
- CCPA
- GDPR
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: 1Lookup
provenance_date: '2026-11-09'
provider_name: 1Lookup
provider_slug: 1lookup
slug: 1lookup-compliance
source_date: '2026-11-09'
source_filename: 1lookup-compliance.yml
source_heading: Compliance
source_page: https://www.1lookup.io/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: 1Lookup\naid: 1lookup\nurl: https://www.1lookup.io/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.1lookup.io/security\nattestations:\n- framework: GDPR\n  type: Self-assessed\n  scope: data subject rights and transfers\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Self-assessed GDPR EU General Data Protection Regulation. We support data subject rights and use Standard\n    Contractual Clauses for transfers.\n- framework: CCPA\n  type: Self-assessed\n  scope: California Consumer Privacy Act as amended by the CPRA\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: Self-assessed CCPA California Consumer Privacy Act, as amended by the CPRA.\n- framework: PCI-DSS\n  type: Via third-party provider (Stripe)\n  scope: card payments handled by Stripe\n  period: null\n  issuer: Stripe\n  report_access: unstated\n  text: Card payments are handled by Stripe, a PCI DSS Level 1 certified provider.\n"
source_yaml_url: https://artifacts.apis.io/1lookup/compliance/1lookup-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from 1Lookup's own page on 2026-11-09.
synthetic: false
tags:
- Phone Validation
- Email Verification
- IP Intelligence
- Fraud and Risk
- Data Enrichment
- B2B contact & company data
- SEO / web analytics
- Audio Transcription
- MCP / agent-native
- REST API
---
