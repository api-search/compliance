---
api_specs:
- filename: urlbox-render-api-openapi.yml
  format: yaml
  label: Urlbox Render API
  slug: urlbox-render-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/urlbox/openapi/urlbox-render-api-openapi.yml
- filename: urlbox-render-links-api-openapi.yml
  format: yaml
  label: Urlbox Render Links API
  slug: urlbox-render-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/urlbox/openapi/urlbox-render-links-api-openapi.yml
- filename: urlbox-status-api-openapi.yml
  format: yaml
  label: Urlbox Status API
  slug: urlbox-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/urlbox/openapi/urlbox-status-api-openapi.yml
- filename: urlbox-usage-api-openapi.yml
  format: yaml
  label: Urlbox Usage API
  slug: urlbox-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/urlbox/openapi/urlbox-usage-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Urlbox is SOC2 Type II attested, ensuring our security controls meet established enterprise standards.
    type: SOC 2 Type II attestation
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We are fully compliant with the GDPR.
    type: compliance statement
  trust_center:
    url: https://urlbox.com/security
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Urlbox
provenance_date: '2026-11-10'
provider_name: Urlbox
provider_slug: urlbox
slug: urlbox-compliance
source_date: '2026-11-10'
source_filename: urlbox-compliance.yml
source_heading: Compliance
source_page: https://urlbox.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Urlbox\naid: urlbox\nurl: https://urlbox.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/urlbox-trust-center.yml\ntrust_center:\n  url: https://urlbox.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II attestation\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Urlbox is SOC2 Type II attested, ensuring our security controls meet established enterprise standards.\n- framework: GDPR\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We are fully compliant with the GDPR.\n"
source_yaml_url: https://artifacts.apis.io/urlbox/compliance/urlbox-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Urlbox's own page on 2026-11-10.
synthetic: false
tags:
- Screenshots
- Rendering
- PDF
- Video
- Web Capture
---
