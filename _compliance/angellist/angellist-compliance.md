---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Trust Services Principles
    text: SOC 2 Type 2 Service Organization Controls (Soc2) (Type II) Trust Services Principles Request
    type: SOC 2 Type 2 Service Organization Controls (Soc2) (Type II)
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Protect the personal data and privacy of EU citizens for transactions that occur within EU member states
    text: Protect the personal data and privacy of EU citizens for transactions that occur within EU member states
    type: GDPR compliance
  trust_center:
    url: https://trust-portal.angellist.com/
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: AngelList
provenance_date: '2026-11-09'
provider_name: AngelList
provider_slug: angellist
slug: angellist-compliance
source_date: '2026-11-09'
source_filename: angellist-compliance.yml
source_heading: Compliance
source_page: https://trust-portal.angellist.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: AngelList\naid: angellist\nurl: https://trust-portal.angellist.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust-portal.angellist.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 Service Organization Controls (Soc2) (Type II)\n  scope: Trust Services Principles\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Type 2 Service Organization Controls (Soc2) (Type II) Trust Services Principles Request\n- framework: GDPR\n  type: GDPR compliance\n  scope: Protect the personal data and privacy of EU citizens for transactions that occur within EU member states\n\
  \  period: null\n  issuer: null\n  report_access: unstated\n  text: Protect the personal data and privacy of EU citizens for transactions that occur within EU member states\n"
source_yaml_url: https://artifacts.apis.io/angellist/compliance/angellist-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from AngelList's own page on 2026-11-09.
synthetic: false
tags:
- Documents
- Fund
- Investing
- Job
- Startups
- Transaction
- Venture Capital
- A2A
---
