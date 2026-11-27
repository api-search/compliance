---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: as of November 2025
    report_access: unstated
    scope: null
    text: Evernote is ISO 27001 certified , as of November 2025 .
    type: certification
  - framework: other
    issuer: Google
    period: annual basis
    report_access: unstated
    scope: null
    text: we undergo the Google CASA (Cloud Application Security Assessment) Tier 2 evaluation on an annual basis.
    type: Google CASA Tier 2 evaluation
  trust_center:
    url: https://evernote.com/security
frameworks:
- ISO27001
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: evernote
provenance_date: '2026-11-09'
provider_name: evernote
provider_slug: evernote
slug: evernote-compliance
source_date: '2026-11-09'
source_filename: evernote-compliance.yml
source_heading: Compliance
source_page: https://evernote.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: evernote\naid: evernote\nurl: https://evernote.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://evernote.com/security\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: as of November 2025\n  issuer: null\n  report_access: unstated\n  text: Evernote is ISO 27001 certified , as of November 2025 .\n- framework: other\n  type: Google CASA Tier 2 evaluation\n  scope: null\n  period: annual basis\n  issuer: Google\n  report_access: unstated\n  text: we undergo the Google CASA (Cloud Application Security Assessment) Tier 2 evaluation on an annual basis.\n"
source_yaml_url: https://artifacts.apis.io/evernote/compliance/evernote-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from evernote's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Note Taking
- Productivity
- Knowledge Management
- Notes
- Content
- Software-as-a-Service
- Sync
---
