---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: Security, availability, confidentiality
    text: Our security team can provide our SOC 2 report, Google CASA assessment summary, a signed DPA, and standard contractual clauses under NDA.
    type: SOC 2 Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Lawful basis, DPA, data-subject rights, transfers
    text: GDPR Aligned Lawful basis, DPA, data-subject rights, transfers
    type: Aligned
  - framework: other
    issuer: null
    period: null
    report_access: nda
    scope: App & API security for Workspace data and OAuth scopes
    text: Our security team can provide our SOC 2 report, Google CASA assessment summary, a signed DPA, and standard contractual clauses under NDA.
    type: Google CASA Tier 2 assessed
  trust_center:
    url: https://www.evercontact.com/dpa-compliance.html
frameworks:
- GDPR
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Evercontact
provenance_date: '2026-11-09'
provider_name: Evercontact
provider_slug: evercontact
slug: evercontact-compliance
source_date: '2026-11-09'
source_filename: evercontact-compliance.yml
source_heading: Compliance
source_page: https://www.evercontact.com/dpa-compliance.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Evercontact\naid: evercontact\nurl: https://www.evercontact.com/dpa-compliance.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.evercontact.com/dpa-compliance.html\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: Security, availability, confidentiality\n  period: null\n  issuer: null\n  report_access: nda\n  text: Our security team can provide our SOC 2 report, Google CASA assessment summary, a signed DPA, and standard\n    contractual clauses under NDA.\n- framework: GDPR\n  type: Aligned\n  scope: Lawful basis, DPA, data-subject rights, transfers\n  period: null\n  issuer:\
  \ null\n  report_access: unstated\n  text: GDPR Aligned Lawful basis, DPA, data-subject rights, transfers\n- framework: other\n  type: Google CASA Tier 2 assessed\n  scope: App & API security for Workspace data and OAuth scopes\n  period: null\n  issuer: null\n  report_access: nda\n  text: Our security team can provide our SOC 2 report, Google CASA assessment summary, a signed DPA, and standard\n    contractual clauses under NDA.\n"
source_yaml_url: https://artifacts.apis.io/evercontact/compliance/evercontact-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Evercontact's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Contact Management
- Contact Data
- Data Enrichment
- Email
- Signature Parsing
- Data Extraction
- CRM
---
