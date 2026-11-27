---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Spline holds Type 1 and Type 2 certifications.
    type: Type 1 and Type 2 certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Spline holds ISO 27001 certification.
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Spline fully complies with GDPR requirements.
    type: compliance
  trust_center:
    url: https://spline.design/security
frameworks:
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Spline
provenance_date: '2026-11-10'
provider_name: Spline
provider_slug: spline
slug: spline-compliance
source_date: '2026-11-10'
source_filename: spline-compliance.yml
source_heading: Compliance
source_page: https://spline.design/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Spline\naid: spline\nurl: https://spline.design/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/spline-trust-center.yml\ntrust_center:\n  url: https://spline.design/security\nattestations:\n- framework: SOC2\n  type: Type 1 and Type 2 certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Spline holds Type 1 and Type 2 certifications.\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Spline holds ISO 27001 certification.\n- framework: GDPR\n  type: compliance\n  scope:\
  \ null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Spline fully complies with GDPR requirements.\n"
source_yaml_url: https://artifacts.apis.io/spline/compliance/spline-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Spline's own page on 2026-11-10.
synthetic: false
tags:
- 3D
- Design
- Artificial Intelligence
- Collaboration
- Web
- SDK
---
