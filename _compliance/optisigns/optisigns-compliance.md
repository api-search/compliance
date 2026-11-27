---
api_specs:
- filename: optisigns.opencollection.json
  format: json
  label: OptiSigns Devices API
  slug: optisigns-devices-api
  spec_type: Postman
  url: https://artifacts.apis.io/optisigns/collections/optisigns.opencollection.json
- filename: optisigns.opencollection.json
  format: json
  label: OptiSigns Assets API
  slug: optisigns-assets-api
  spec_type: Postman
  url: https://artifacts.apis.io/optisigns/collections/optisigns.opencollection.json
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: Sensiba LLP
    period: null
    report_access: on_request
    scope: Security, Availability, and Confidentiality
    text: Independent annual examination by Sensiba LLP across Security, Availability, and Confidentiality.
    type: SOC 2 Type 2 examination
  - framework: other
    issuer: Texas DIR
    period: null
    report_access: unstated
    scope: Texas Risk and Authorization Management Program
    text: TX-RAMP Level 1 Certified under the Texas Risk and Authorization Management Program
    type: TX-RAMP Level 1 certification
  - framework: other
    issuer: AICPA examination
    period: as of November 15, 2025
    report_access: on_request
    scope: Security Rule and Breach Notification controls
    text: Independent AICPA examination of our Security Rule and Breach Notification controls as a Business Associate — zero exceptions, as of November 15, 2025.
    type: HIPAA examination (Security Rule and Breach Notification as Business Associate)
  - framework: other
    issuer: null
    period: null
    report_access: on_request
    scope: Section 508 and accessibility procurement reviews
    text: A completed VPAT (WCAG edition, Levels A and AA) is available for Section 508 and accessibility procurement reviews.
    type: VPAT (WCAG edition, Levels A and AA)
  trust_center:
    url: https://www.optisigns.com/trust-center
frameworks:
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: OptiSigns
provenance_date: '2026-11-10'
provider_name: OptiSigns
provider_slug: optisigns
slug: optisigns-compliance
source_date: '2026-11-10'
source_filename: optisigns-compliance.yml
source_heading: Compliance
source_page: https://www.optisigns.com/trust-center
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: OptiSigns\naid: optisigns\nurl: https://www.optisigns.com/trust-center\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/optisigns-trust-center.yml\ntrust_center:\n  url: https://www.optisigns.com/trust-center\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 examination\n  scope: Security, Availability, and Confidentiality\n  period: null\n  issuer: Sensiba LLP\n  report_access: on_request\n  text: Independent annual examination by Sensiba LLP across Security, Availability, and Confidentiality.\n- framework: other\n  type: TX-RAMP Level 1 certification\n  scope: Texas Risk and Authorization Management\
  \ Program\n  period: null\n  issuer: Texas DIR\n  report_access: unstated\n  text: TX-RAMP Level 1 Certified under the Texas Risk and Authorization Management Program\n- framework: other\n  type: HIPAA examination (Security Rule and Breach Notification as Business Associate)\n  scope: Security Rule and Breach Notification controls\n  period: as of November 15, 2025\n  issuer: AICPA examination\n  report_access: on_request\n  text: Independent AICPA examination of our Security Rule and Breach Notification controls as a Business Associate\n    — zero exceptions, as of November 15, 2025.\n- framework: other\n  type: VPAT (WCAG edition, Levels A and AA)\n  scope: Section 508 and accessibility procurement reviews\n  period: null\n  issuer: null\n  report_access: on_request\n  text: A completed VPAT (WCAG edition, Levels A and AA) is available for Section 508 and accessibility procurement\n    reviews.\n"
source_yaml_url: https://artifacts.apis.io/optisigns/compliance/optisigns-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from OptiSigns's own page on 2026-11-10.
synthetic: false
tags:
- Digital Signage
- Screens
- Content Management
- GraphQL
- Displays
- Playlists
---
