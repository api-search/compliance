---
api_specs:
- filename: rybbit-analytics-api-openapi.yml
  format: yaml
  label: Rybbit Analytics API
  slug: rybbit-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rybbit/openapi/rybbit-analytics-api-openapi.yml
- filename: rybbit-event-tracking-api-openapi.yml
  format: yaml
  label: Rybbit Event Tracking API
  slug: rybbit-event-tracking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rybbit/openapi/rybbit-event-tracking-api-openapi.yml
- filename: rybbit-sessions-api-openapi.yml
  format: yaml
  label: Rybbit Sessions API
  slug: rybbit-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rybbit/openapi/rybbit-sessions-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR compliant (no personal data collection)
    type: self-declared compliance statement
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA compliant
    type: self-declared compliance statement
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PECR compliant (no cookie consent needed)
    type: self-declared compliance statement (PECR)
  trust_center:
    url: https://rybbit.com/security
frameworks:
- CCPA
- GDPR
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Rybbit
provenance_date: '2026-11-10'
provider_name: Rybbit
provider_slug: rybbit
slug: rybbit-compliance
source_date: '2026-11-10'
source_filename: rybbit-compliance.yml
source_heading: Compliance
source_page: https://rybbit.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Rybbit\naid: rybbit\nurl: https://rybbit.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://rybbit.com/security\nattestations:\n- framework: GDPR\n  type: self-declared compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR compliant (no personal data collection)\n- framework: CCPA\n  type: self-declared compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA compliant\n- framework: other\n  type: self-declared compliance statement (PECR)\n  scope: null\n  period: null\n  issuer: null\n\
  \  report_access: unstated\n  text: PECR compliant (no cookie consent needed)\n"
source_yaml_url: https://artifacts.apis.io/rybbit/compliance/rybbit-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Rybbit's own page on 2026-11-10.
synthetic: false
tags:
- Analytics
- Web Analytics
- Product Analytics
- Privacy
- Open Source
- Cookieless
---
