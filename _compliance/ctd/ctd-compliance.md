---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent third party
    period: null
    report_access: on_request
    scope: security, availability, and confidentiality
    text: We undergo annual independent audits against the SOC 2 Type II standard, covering security, availability, and confidentiality.
    type: SOC 2 Type II audit
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: users in the EU
    text: We comply with GDPR for users in the EU and CCPA for California residents
    type: compliance with regulation
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: California residents
    text: We comply with GDPR for users in the EU and CCPA for California residents
    type: compliance with regulation
  trust_center:
    url: https://ctd.ai/security
frameworks:
- CCPA
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Connect The Dots
provenance_date: '2026-11-09'
provider_name: Connect The Dots
provider_slug: ctd
slug: ctd-compliance
source_date: '2026-11-09'
source_filename: ctd-compliance.yml
source_heading: Compliance
source_page: https://ctd.ai/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Connect The Dots\naid: ctd\nurl: https://ctd.ai/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/ctd-trust-center.yml\ntrust_center:\n  url: https://ctd.ai/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II audit\n  scope: security, availability, and confidentiality\n  period: null\n  issuer: independent third party\n  report_access: on_request\n  text: We undergo annual independent audits against the SOC 2 Type II standard, covering security, availability,\n    and confidentiality.\n- framework: GDPR\n  type: compliance with regulation\n  scope: users in the EU\n  period: null\n\
  \  issuer: null\n  report_access: unstated\n  text: We comply with GDPR for users in the EU and CCPA for California residents\n- framework: CCPA\n  type: compliance with regulation\n  scope: California residents\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We comply with GDPR for users in the EU and CCPA for California residents\n"
source_yaml_url: https://artifacts.apis.io/ctd/compliance/ctd-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Connect The Dots's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Relationship Intelligence
- Sales
- Warm Introductions
- Network Graph
- CRM
- MCP
- Venture Capital
---
