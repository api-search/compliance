---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Information Security Management System
    text: Our Information Security Management System is ISO 27001 certified
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Sketch services, extended to all customers including those outside the EU
    text: We comply with the European Union General Data Protection Regulation (GDPR)
    type: regulatory compliance
  trust_center:
    url: https://www.sketch.com/security/
frameworks:
- GDPR
- ISO27001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Sketch
provenance_date: '2026-11-10'
provider_name: Sketch
provider_slug: sketch
slug: sketch-compliance
source_date: '2026-11-10'
source_filename: sketch-compliance.yml
source_heading: Compliance
source_page: https://www.sketch.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Sketch\naid: sketch\nurl: https://www.sketch.com/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/sketch-trust-center.yml\ntrust_center:\n  url: https://www.sketch.com/security/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: Information Security Management System\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our Information Security Management System is ISO 27001 certified\n- framework: GDPR\n  type: regulatory compliance\n  scope: Sketch services, extended to all customers including those outside the EU\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: We comply with the European Union General Data Protection Regulation (GDPR)\n"
source_yaml_url: https://artifacts.apis.io/sketch/compliance/sketch-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Sketch's own page on 2026-11-10.
synthetic: false
tags:
- Design
- Collaboration
- Prototyping
- Workspace
- Documents
- Library
- Components
---
