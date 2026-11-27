---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA Compliance with Rewind
    type: HIPAA compliance
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Rewind’s DPA and standard contractual clauses (SCC) ensure compliance with the GDPR.
    type: Data Protection Addendum
  trust_center:
    url: https://rewind.com/trust/
frameworks:
- GDPR
- HIPAA
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Rewind
provenance_date: '2026-11-10'
provider_name: Rewind
provider_slug: rewind
slug: rewind-compliance
source_date: '2026-11-10'
source_filename: rewind-compliance.yml
source_heading: Compliance
source_page: https://rewind.com/trust/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Rewind\naid: rewind\nurl: https://rewind.com/trust/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://rewind.com/trust/\nattestations:\n- framework: HIPAA\n  type: HIPAA compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA Compliance with Rewind\n- framework: GDPR\n  type: Data Protection Addendum\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Rewind’s DPA and standard contractual clauses (SCC) ensure compliance with the GDPR.\n"
source_yaml_url: https://artifacts.apis.io/rewind/compliance/rewind-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Rewind's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cloud
- Backup
- Data Recovery
- Software-as-a-Service
- Data Protection
- Disaster Recovery
- Security
---
