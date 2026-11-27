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
    text: SOC2 type 2 report
    type: type 2 report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: null
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA
    type: null
  trust_center:
    url: https://trust.stonly.com/
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Stonly
provenance_date: '2026-11-10'
provider_name: Stonly
provider_slug: stonly
slug: stonly-compliance
source_date: '2026-11-10'
source_filename: stonly-compliance.yml
source_heading: Compliance
source_page: https://trust.stonly.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Stonly\naid: stonly\nurl: https://trust.stonly.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/stonly-trust-center.yml\ntrust_center:\n  url: https://trust.stonly.com/\nattestations:\n- framework: SOC2\n  type: type 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC2 type 2 report\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: HIPAA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA\n"
source_yaml_url: https://artifacts.apis.io/stonly/compliance/stonly-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Stonly's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cloud Saas
- Knowledge Base
- Knowledge Management
- Customer Service
- Self-Service
- Help Center
- AI Chatbot
- Mobile SDK
- Customer Experience
---
