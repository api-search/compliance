---
api_specs:
- filename: evari-quotes-api-openapi.yml
  format: yaml
  label: Evari Quotes API
  slug: evari-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evari/openapi/evari-quotes-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: accredited third-party certification body
    period: null
    report_access: unstated
    scope: Evari platform information security management system
    text: We hold ISO 27001 certification and operate under a formal Information Security Management System (ISMS) that is independently audited every year.
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: UK GDPR and EU GDPR
    text: We comply fully with the UK GDPR and EU GDPR, and handle personal information in line with the Australian Privacy Principles and the New Zealand Privacy Act 2020.
    type: compliance statement
  - framework: ISO27001
    issuer: accredited third-party certification body
    period: null
    report_access: unstated
    scope: Information Security Management System covering design, development, and operation of the Evari platform
    source: https://www.evari.tech/trust
    text: We hold ISO 27001 certification and operate under a formal Information Security Management System (ISMS) that is independently audited every year.
    type: certification
  trust_center:
    url: https://www.evari.tech/trust
frameworks:
- GDPR
- ISO27001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Evari
provenance_date: '2026-11-09'
provider_name: Evari
provider_slug: evari
slug: evari-compliance
source_date: '2026-11-09'
source_filename: evari-compliance.yml
source_heading: Compliance
source_page: https://www.evari.tech/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Evari\naid: evari\nurl: https://www.evari.tech/trust\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/evari-trust-center.yml\n  sources:\n  - https://www.evari.tech/trust\ntrust_center:\n  url: https://www.evari.tech/trust\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: Evari platform information security management system\n  period: null\n  issuer: accredited third-party certification body\n  report_access: unstated\n  text: We hold ISO 27001 certification and operate under a formal Information Security Management System (ISMS)\n    that is independently audited every year.\n\
  - framework: GDPR\n  type: compliance statement\n  scope: UK GDPR and EU GDPR\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We comply fully with the UK GDPR and EU GDPR, and handle personal information in line with the Australian\n    Privacy Principles and the New Zealand Privacy Act 2020.\n- framework: ISO27001\n  type: certification\n  scope: Information Security Management System covering design, development, and operation of the Evari platform\n  period: null\n  issuer: accredited third-party certification body\n  report_access: unstated\n  text: We hold ISO 27001 certification and operate under a formal Information Security Management System (ISMS)\n    that is independently audited every year.\n  source: https://www.evari.tech/trust\n"
source_yaml_url: https://artifacts.apis.io/evari/compliance/evari-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Evari's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Australia
- Insurtech
- Policy Administration
- Core Systems
- Property and Casualty
- Underwriting
- Claims
- Brokerage
- MGA
- Artificial Intelligence
- Quoting
- Endorsements
---
