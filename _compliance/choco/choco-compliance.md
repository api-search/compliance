---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: third-party auditor
    period: null
    report_access: unstated
    scope: Security, Availability, and Confidentiality criteria
    text: 'Choco''s SOC 2 ® compliance covers three Trust Services Criteria: Security, Availability, and Confidentiality — independently verified by a third-party auditor.'
    type: SOC 2 report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: lawful basis, data minimization, purpose limitation, data subject rights
    text: Lawful basis, data minimization, purpose limitation, and data subject rights — including deletion — are embedded into our operational practices.
    type: compliance statement
  trust_center:
    url: https://choco.com/us/security
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Choco
provenance_date: '2026-11-09'
provider_name: Choco
provider_slug: choco
slug: choco-compliance
source_date: '2026-11-09'
source_filename: choco-compliance.yml
source_heading: Compliance
source_page: https://choco.com/us/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Choco\naid: choco\nurl: https://choco.com/us/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/choco-trust-center.yml\ntrust_center:\n  url: https://choco.com/us/security\nattestations:\n- framework: SOC2\n  type: SOC 2 report\n  scope: Security, Availability, and Confidentiality criteria\n  period: null\n  issuer: third-party auditor\n  report_access: unstated\n  text: 'Choco''s SOC 2 ® compliance covers three Trust Services Criteria: Security, Availability, and Confidentiality\n    — independently verified by a third-party auditor.'\n- framework: GDPR\n  type: compliance statement\n  scope:\
  \ lawful basis, data minimization, purpose limitation, data subject rights\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Lawful basis, data minimization, purpose limitation, and data subject rights — including deletion — are\n    embedded into our operational practices.\n"
source_yaml_url: https://artifacts.apis.io/choco/compliance/choco-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Choco's own page on 2026-11-09.
synthetic: false
tags:
- Restaurant
- Ordering
- Food Distribution
- Suppliers
- ERP Integration
- Artificial Intelligence
- Supply Chain
- Food Service
---
