---
api_specs:
- filename: gamesight-measurement-api-openapi.yml
  format: yaml
  label: Gamesight Measurement API
  slug: gamesight-measurement-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gamesight/openapi/gamesight-measurement-api-openapi.yml
- filename: gamesight-reporting-api-openapi.yml
  format: yaml
  label: Gamesight Reporting API
  slug: gamesight-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gamesight/openapi/gamesight-reporting-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: design, security, and operational effectiveness of services
    text: Independently audited compliance for design, security, and operational effectiveness of our services.
    type: SOC 2 Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Compliant with EU General Data Protection Regulation. DPA available on request.
    type: compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: including player opt-out workflows
    text: Aligned with the California Consumer Privacy Act, including player opt-out workflows.
    type: alignment
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: organization for secure data handling operations
    source: https://gamesight.io/gdpr
    text: our organization is SOC-II certified for secure data handling operations
    type: certification
  trust_center:
    url: https://console.gamesight.io/trust
frameworks:
- CCPA
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Gamesight
provenance_date: '2026-11-09'
provider_name: Gamesight
provider_slug: gamesight
slug: gamesight-compliance
source_date: '2026-11-09'
source_filename: gamesight-compliance.yml
source_heading: Compliance
source_page: https://console.gamesight.io/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Gamesight\naid: gamesight\nurl: https://console.gamesight.io/trust\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/gamesight-trust-center.yml\n  sources:\n  - https://console.gamesight.io/trust\n  - https://gamesight.io/gdpr\ntrust_center:\n  url: https://console.gamesight.io/trust\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: design, security, and operational effectiveness of services\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Independently audited compliance for design, security, and operational effectiveness of our services.\n- framework: GDPR\n  type:\
  \ compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliant with EU General Data Protection Regulation. DPA available on request.\n- framework: CCPA\n  type: alignment\n  scope: including player opt-out workflows\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Aligned with the California Consumer Privacy Act, including player opt-out workflows.\n- framework: SOC2\n  type: certification\n  scope: organization for secure data handling operations\n  period: null\n  issuer: null\n  report_access: on_request\n  text: our organization is SOC-II certified for secure data handling operations\n  source: https://gamesight.io/gdpr\n"
source_yaml_url: https://artifacts.apis.io/gamesight/compliance/gamesight-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Gamesight's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Gaming
- Marketing
- Analytics
- Attribution
- Measurements
- Advertising
- Creators
- Game Development
---
