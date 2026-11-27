---
api_specs:
- filename: soax-web-data-api-openapi.yml
  format: yaml
  label: SOAX Web Data API
  slug: soax-web-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soax/openapi/soax-web-data-api-openapi.yml
- filename: soax-ecommerce-data-api-openapi.yml
  format: yaml
  label: SOAX Ecommerce Data API
  slug: soax-ecommerce-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soax/openapi/soax-ecommerce-data-api-openapi.yml
- filename: soax-geo-targeting-api-openapi.yml
  format: yaml
  label: SOAX Geo Targeting API
  slug: soax-geo-targeting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soax/openapi/soax-geo-targeting-api-openapi.yml
- filename: soax-ip-whitelist-api-openapi.yml
  format: yaml
  label: SOAX IP Whitelist API
  slug: soax-ip-whitelist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soax/openapi/soax-ip-whitelist-api-openapi.yml
- filename: soax-serp-data-api-openapi.yml
  format: yaml
  label: SOAX SERP Data API
  slug: soax-serp-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soax/openapi/soax-serp-data-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: SOAX and partners data protection
    text: SOAX and our partners comply with all relevant data protection regulations, including the General Data Protection Regulation (GDPR) and the California Consumer Privacy Act (CCPA).
    type: regulatory compliance statement
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: SOAX and partners data protection
    text: We implement strict privacy measures and fully comply with GDPR and CCPA to safeguard your data with complete transparency.
    type: regulatory compliance statement
  trust_center:
    url: https://soax.com/trust
frameworks:
- CCPA
- GDPR
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: SOAX
provenance_date: '2026-11-10'
provider_name: SOAX
provider_slug: soax
slug: soax-compliance
source_date: '2026-11-10'
source_filename: soax-compliance.yml
source_heading: Compliance
source_page: https://soax.com/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: SOAX\naid: soax\nurl: https://soax.com/trust\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/soax-trust-center.yml\ntrust_center:\n  url: https://soax.com/trust\nattestations:\n- framework: GDPR\n  type: regulatory compliance statement\n  scope: SOAX and partners data protection\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOAX and our partners comply with all relevant data protection regulations, including the General Data Protection\n    Regulation (GDPR) and the California Consumer Privacy Act (CCPA).\n- framework: CCPA\n  type: regulatory compliance statement\n  scope: SOAX\
  \ and partners data protection\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We implement strict privacy measures and fully comply with GDPR and CCPA to safeguard your data with complete\n    transparency.\n"
source_yaml_url: https://artifacts.apis.io/soax/compliance/soax-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from SOAX's own page on 2026-11-10.
synthetic: false
tags:
- Proxy
- Web Scraping
- Residential Proxies
- Mobile Proxies
- Datacenter Proxies
- Data Extraction
- Anti-Bot Bypass
---
