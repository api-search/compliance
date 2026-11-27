---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Boardable platform
    text: Soc 2 Type II
    type: Type II
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Boardable platform
    text: How does Boardable comply with HIPAA? Technical and administrative safeguards align with HIPAA requirements.
    type: compliance
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Boardable
    text: Is Boardable ISO 27001 certified? Not yet; it is on our compliance roadmap.
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Boardable
    text: GDPR
    type: compliance
  trust_center:
    url: https://boardable.com/boardable-trust-center/
frameworks:
- GDPR
- HIPAA
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Boardable
provenance_date: '2026-11-09'
provider_name: Boardable
provider_slug: boardable
slug: boardable-compliance
source_date: '2026-11-09'
source_filename: boardable-compliance.yml
source_heading: Compliance
source_page: https://boardable.com/boardable-trust-center/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Boardable\naid: boardable\nurl: https://boardable.com/boardable-trust-center/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/boardable-trust-center.yml\ntrust_center:\n  url: https://boardable.com/boardable-trust-center/\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: Boardable platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Soc 2 Type II\n- framework: HIPAA\n  type: compliance\n  scope: Boardable platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: How does Boardable comply with HIPAA? Technical and administrative safeguards align\
  \ with HIPAA requirements.\n- framework: ISO27001\n  type: certification\n  scope: Boardable\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Is Boardable ISO 27001 certified? Not yet; it is on our compliance roadmap.\n- framework: GDPR\n  type: compliance\n  scope: Boardable\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n"
source_yaml_url: https://artifacts.apis.io/boardable/compliance/boardable-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Boardable's own page on 2026-11-09.
synthetic: false
tags:
- Board Management
- Governance
- Non-Profit
- Meetings
- Collaboration
---
