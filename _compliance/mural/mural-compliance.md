---
api_specs:
- filename: docs
  format: yaml
  label: Mural Public API
  slug: mural-public-api
  spec_type: Postman
  url: https://developers.mural.co/public/docs
claim_count: 6
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Trust Services Principles
    text: Mural maintains SOC 2 Type 2, ISO 27001, and ISO 42001 certifications and supports compliance with GDPR and CCPA requirements.
    type: SOC 2 Type 2 report
  - framework: SOC3
    issuer: null
    period: null
    report_access: public
    scope: null
    text: SOC 3 report
    type: SOC 3 report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Information Security Management System (ISMS)
    text: Information Security Management System (ISMS)
    type: certification
  - framework: ISO42001
    issuer: null
    period: null
    report_access: unstated
    scope: AI Management System (AIMS)
    text: AI Management System (AIMS)
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: General Data Protection Regulation
    type: stated compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: California Consumer Privacy Act
    type: stated compliance
  trust_center:
    url: https://www.mural.co/trust-and-security
frameworks:
- CCPA
- GDPR
- ISO27001
- ISO42001
- SOC2
- SOC3
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Mural
provenance_date: '2026-11-10'
provider_name: Mural
provider_slug: mural
slug: mural-compliance
source_date: '2026-11-10'
source_filename: mural-compliance.yml
source_heading: Compliance
source_page: https://www.mural.co/trust-and-security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Mural\naid: mural\nurl: https://www.mural.co/trust-and-security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/mural-trust-center.yml\ntrust_center:\n  url: https://www.mural.co/trust-and-security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: Trust Services Principles\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Mural maintains SOC 2 Type 2, ISO 27001, and ISO 42001 certifications and supports compliance with GDPR\n    and CCPA requirements.\n- framework: SOC3\n  type: SOC 3 report\n  scope: null\n  period: null\n  issuer: null\n  report_access:\
  \ public\n  text: SOC 3 report\n- framework: ISO27001\n  type: certification\n  scope: Information Security Management System (ISMS)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Information Security Management System (ISMS)\n- framework: ISO42001\n  type: certification\n  scope: AI Management System (AIMS)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AI Management System (AIMS)\n- framework: GDPR\n  type: stated compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: General Data Protection Regulation\n- framework: CCPA\n  type: stated compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: California Consumer Privacy Act\n"
source_yaml_url: https://artifacts.apis.io/mural/compliance/mural-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from Mural's own page on 2026-11-10.
synthetic: false
tags:
- Collaboration
- Whiteboard
- Workshops
- Enterprise
- OAuth
- Authentication
---
