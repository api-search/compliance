---
api_specs:
- filename: zyte-extract-api-openapi.yml
  format: yaml
  label: Zyte Extract API
  slug: zyte-extract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zyte/openapi/zyte-extract-api-openapi.yml
- filename: zyte-stats-api-openapi.yml
  format: yaml
  label: Zyte Stats API
  slug: zyte-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zyte/openapi/zyte-stats-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Zyte infrastructure and services
    text: Zyte is ISO 27001 certified and all of its hosting providers have achieved ISO 27001 certification
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: customer data processing
    text: Zyte is committed to GDPR compliance.
    type: compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: customer data
    text: Zyte also comply with data protection regulations such as GDPR and CCPA
    type: compliance
  trust_center:
    url: https://www.zyte.com/trust-center/
frameworks:
- CCPA
- GDPR
- ISO27001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Zyte
provenance_date: '2026-11-10'
provider_name: Zyte
provider_slug: zyte
slug: zyte-compliance
source_date: '2026-11-10'
source_filename: zyte-compliance.yml
source_heading: Compliance
source_page: https://www.zyte.com/trust-center/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Zyte\naid: zyte\nurl: https://www.zyte.com/trust-center/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/zyte-trust-center.yml\ntrust_center:\n  url: https://www.zyte.com/trust-center/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: Zyte infrastructure and services\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Zyte is ISO 27001 certified and all of its hosting providers have achieved ISO 27001 certification\n- framework: GDPR\n  type: compliance\n  scope: customer data processing\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Zyte is\
  \ committed to GDPR compliance.\n- framework: CCPA\n  type: compliance\n  scope: customer data\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Zyte also comply with data protection regulations such as GDPR and CCPA\n"
source_yaml_url: https://artifacts.apis.io/zyte/compliance/zyte-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Zyte's own page on 2026-11-10.
synthetic: false
tags:
- Crawling
- Data Extraction
- Web Scraping
- Proxies
- Browser Automation
- Anti-Ban
- SERP
- Agent Skills
- Developer Tools
---
