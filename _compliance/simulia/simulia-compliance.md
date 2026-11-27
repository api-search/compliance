---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Dassault Systèmes holds multiple security certifications, including ISO 27001 (Information Security Management System).
    type: certification
  - framework: ISO27701
    issuer: null
    period: null
    report_access: unstated
    scope: 3D EXPERIENCE platform on the cloud
    text: The 3D EXPERIENCE platform on the cloud is specifically ISO 27701 certified for privacy information management.
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Dassault Systèmes has implemented a personal data compliance program to ensure compliance with GDPR and other relevant data protection laws.
    type: compliance program
  trust_center:
    url: https://www.3ds.com/trust-center
frameworks:
- GDPR
- ISO27001
- ISO27701
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: SIMULIA (Dassault Systemes)
provenance_date: '2026-11-10'
provider_name: SIMULIA (Dassault Systemes)
provider_slug: simulia
slug: simulia-compliance
source_date: '2026-11-10'
source_filename: simulia-compliance.yml
source_heading: Compliance
source_page: https://www.3ds.com/trust-center
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: SIMULIA (Dassault Systemes)\naid: simulia\nurl: https://www.3ds.com/trust-center\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/simulia-trust-center.yml\ntrust_center:\n  url: https://www.3ds.com/trust-center\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Dassault Systèmes holds multiple security certifications, including ISO 27001 (Information Security Management\n    System).\n- framework: ISO27701\n  type: certification\n  scope: 3D EXPERIENCE platform on the cloud\n  period: null\n  issuer: null\n\
  \  report_access: unstated\n  text: The 3D EXPERIENCE platform on the cloud is specifically ISO 27701 certified for privacy information management.\n- framework: GDPR\n  type: compliance program\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Dassault Systèmes has implemented a personal data compliance program to ensure compliance with GDPR and\n    other relevant data protection laws.\n"
source_yaml_url: https://artifacts.apis.io/simulia/compliance/simulia-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from SIMULIA (Dassault Systemes)'s own page on 2026-11-10.
synthetic: false
tags:
- Simulation
- FEA
- CFD
- Electromagnetics
- Optimization
- Engineering
- Dassault Systemes
- 3DEXPERIENCE
---
