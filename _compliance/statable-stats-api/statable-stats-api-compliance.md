---
api_specs:
- filename: statable-stats-api-bootstrap-api-openapi.yml
  format: yaml
  label: Statable Stats API Bootstrap API
  slug: statable-stats-api-bootstrap-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/statable-stats-api/openapi/statable-stats-api-bootstrap-api-openapi.yml
- filename: statable-stats-api-keys-api-openapi.yml
  format: yaml
  label: Statable Stats API Keys API
  slug: statable-stats-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/statable-stats-api/openapi/statable-stats-api-keys-api-openapi.yml
- filename: statable-stats-api-sites-api-openapi.yml
  format: yaml
  label: Statable Stats API Sites API
  slug: statable-stats-api-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/statable-stats-api/openapi/statable-stats-api-sites-api-openapi.yml
- filename: statable-stats-api-stats-api-openapi.yml
  format: yaml
  label: Statable Stats API Stats API
  slug: statable-stats-api-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/statable-stats-api/openapi/statable-stats-api-stats-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Statable as data controller for accounts and data processor for analytics data
    text: We are fully committed to GDPR compliance
    type: self-stated compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: California personal information
    text: CCPA / CPRA (California) — we do not sell personal information and do not engage in cross-context behavioral advertising
    type: self-stated compliance
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Cookie and browser storage rules
    text: ePrivacy Directive (PECR) — no cookies or browser storage used
    type: self-stated compliance (ePrivacy Directive / PECR)
  trust_center:
    url: https://statable.com/gdpr
frameworks:
- CCPA
- GDPR
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Statable Stats API
provenance_date: '2026-11-10'
provider_name: Statable Stats API
provider_slug: statable-stats-api
slug: statable-stats-api-compliance
source_date: '2026-11-10'
source_filename: statable-stats-api-compliance.yml
source_heading: Compliance
source_page: https://statable.com/gdpr
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Statable Stats API\naid: statable-stats-api\nurl: https://statable.com/gdpr\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://statable.com/gdpr\nattestations:\n- framework: GDPR\n  type: self-stated compliance\n  scope: Statable as data controller for accounts and data processor for analytics data\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We are fully committed to GDPR compliance\n- framework: CCPA\n  type: self-stated compliance\n  scope: California personal information\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA / CPRA (California) — we do not sell\
  \ personal information and do not engage in cross-context behavioral\n    advertising\n- framework: other\n  type: self-stated compliance (ePrivacy Directive / PECR)\n  scope: Cookie and browser storage rules\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ePrivacy Directive (PECR) — no cookies or browser storage used\n"
source_yaml_url: https://artifacts.apis.io/statable-stats-api/compliance/statable-stats-api-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Statable Stats API's own page on 2026-11-10.
synthetic: false
tags:
- Analytics
- Web Analytics
- Cookieless
- Privacy
- GDPR
- OpenAPI
- MCP
- Llms.txt
- EU-hosted
---
