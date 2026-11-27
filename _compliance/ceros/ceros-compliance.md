---
api_specs:
- filename: ceros-accounts-api-openapi.yml
  format: yaml
  label: Ceros Accounts API
  slug: ceros-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ceros/openapi/ceros-accounts-api-openapi.yml
- filename: ceros-embedcodes-api-openapi.yml
  format: yaml
  label: Ceros Embed Codes API
  slug: ceros-embedcodes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ceros/openapi/ceros-embedcodes-api-openapi.yml
- filename: ceros-experience-api-openapi.yml
  format: yaml
  label: Ceros Experience API
  slug: ceros-experience-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ceros/openapi/ceros-experience-api-openapi.yml
- filename: ceros-experiencepage-api-openapi.yml
  format: yaml
  label: Ceros Experience Page API
  slug: ceros-experiencepage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ceros/openapi/ceros-experiencepage-api-openapi.yml
- filename: ceros-folders-api-openapi.yml
  format: yaml
  label: Ceros Folders API
  slug: ceros-folders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ceros/openapi/ceros-folders-api-openapi.yml
- filename: ceros-o-embed-api-openapi.yml
  format: yaml
  label: Ceros o Embed API
  slug: ceros-o-embed-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ceros/openapi/ceros-o-embed-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: September 1, 2024, to October 31, 2025
    report_access: unstated
    scope: Ceros service
    text: The Ceros Service Organization Control (SOC) 2 Type 2 report for the period of September 1, 2024, to October 31, 2025 is now available in the "Resources" tab for review.
    type: Type 2 report
  - framework: ISO27001
    issuer: Prescient Security LLC
    period: valid through November 18, 2027
    report_access: unstated
    scope: null
    text: The certification, issued by Prescient Security LLC remains valid through November 18, 2027, and is subject to annual surveillance audits.
    type: certification
  trust_center:
    url: https://trust.ceros.com/
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Ceros
provenance_date: '2026-11-09'
provider_name: Ceros
provider_slug: ceros
slug: ceros-compliance
source_date: '2026-11-09'
source_filename: ceros-compliance.yml
source_heading: Compliance
source_page: https://trust.ceros.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Ceros\naid: ceros\nurl: https://trust.ceros.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/ceros-trust-center.yml\ntrust_center:\n  url: https://trust.ceros.com/\nattestations:\n- framework: SOC2\n  type: Type 2 report\n  scope: Ceros service\n  period: September 1, 2024, to October 31, 2025\n  issuer: null\n  report_access: unstated\n  text: The Ceros Service Organization Control (SOC) 2 Type 2 report for the period of September 1, 2024, to October\n    31, 2025 is now available in the \"Resources\" tab for review.\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: valid\
  \ through November 18, 2027\n  issuer: Prescient Security LLC\n  report_access: unstated\n  text: The certification, issued by Prescient Security LLC remains valid through November 18, 2027, and is subject\n    to annual surveillance audits.\n"
source_yaml_url: https://artifacts.apis.io/ceros/compliance/ceros-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Ceros's own page on 2026-11-09.
synthetic: false
tags:
- Content Management
- Interactive Content
- Digital Experience
- Embed
- oEmbed
- CMS Integration
- Marketing
- Design
- No-Code
- Content Delivery
- Media and Publishing
- SDK
---
