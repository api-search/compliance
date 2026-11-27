---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Zomma platform
    text: SOC 2 Type 1 audited. Type 2 pending.
    type: Type 1 audit
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: data handling
    text: GDPR/CCPA-aligned data handling.
    type: alignment
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Zomma platform
    source: https://www.zommalabs.com/security
    text: SOC 2 Type 1 audited. Type 2 pending.
    type: SOC 2 Type 1 audit
  trust_center:
    url: https://www.zommalabs.com/security
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Zomma
provenance_date: '2026-11-10'
provider_name: Zomma
provider_slug: zomma
slug: zomma-compliance
source_date: '2026-11-10'
source_filename: zomma-compliance.yml
source_heading: Compliance
source_page: https://www.zommalabs.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Zomma\naid: zomma\nurl: https://www.zommalabs.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/zomma-trust-center.yml\n  sources:\n  - https://www.zommalabs.com/security\ntrust_center:\n  url: https://www.zommalabs.com/security\nattestations:\n- framework: SOC2\n  type: Type 1 audit\n  scope: Zomma platform\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Type 1 audited. Type 2 pending.\n- framework: GDPR\n  type: alignment\n  scope: data handling\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR/CCPA-aligned data handling.\n- framework:\
  \ SOC2\n  type: SOC 2 Type 1 audit\n  scope: Zomma platform\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Type 1 audited. Type 2 pending.\n  source: https://www.zommalabs.com/security\n"
source_yaml_url: https://artifacts.apis.io/zomma/compliance/zomma-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Zomma's own page on 2026-11-10.
synthetic: false
tags:
- Company
- AI Agents
- Computer Use
- Automation
- Fintech
- Back Office
- Reconciliation
- KYC
- Finance
---
