---
api_specs:
- filename: glide-apps-stashes-api-openapi.yml
  format: yaml
  label: Glide Stashes API
  slug: glide-apps-stashes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/glide-apps/openapi/glide-apps-stashes-api-openapi.yml
- filename: glide-apps-tables-api-openapi.yml
  format: yaml
  label: Glide Tables API
  slug: glide-apps-tables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/glide-apps/openapi/glide-apps-tables-api-openapi.yml
- filename: glide-apps-apps-api-openapi.yml
  format: yaml
  label: Glide Apps API
  slug: glide-apps-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/glide-apps/openapi/glide-apps-apps-api-openapi.yml
- filename: glide-apps-jobs-api-openapi.yml
  format: yaml
  label: Glide Jobs API
  slug: glide-apps-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/glide-apps/openapi/glide-apps-jobs-api-openapi.yml
- filename: glide-apps-me-api-openapi.yml
  format: yaml
  label: Glide Me API
  slug: glide-apps-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/glide-apps/openapi/glide-apps-me-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Yes, Glide is SOC 2 Type 2 certified.
    type: Type 2 certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We have implemented the appropriate technical and security processes to ensure compliance with GDPR obligations.
    type: approach to compliance
  trust_center:
    url: https://www.glideapps.com/security-center
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Glide
provenance_date: '2026-11-09'
provider_name: Glide
provider_slug: glide-apps
slug: glide-apps-compliance
source_date: '2026-11-09'
source_filename: glide-apps-compliance.yml
source_heading: Compliance
source_page: https://www.glideapps.com/security-center
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Glide\naid: glide-apps\nurl: https://www.glideapps.com/security-center\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/glide-apps-trust-center.yml\ntrust_center:\n  url: https://www.glideapps.com/security-center\nattestations:\n- framework: SOC2\n  type: Type 2 certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Yes, Glide is SOC 2 Type 2 certified.\n- framework: GDPR\n  type: approach to compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We have implemented the appropriate technical and security processes to ensure\
  \ compliance with GDPR obligations.\n"
source_yaml_url: https://artifacts.apis.io/glide-apps/compliance/glide-apps-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Glide's own page on 2026-11-09.
synthetic: false
tags:
- No-Code
- App Builder
- Tables
- Big Tables
- Data
- Artificial Intelligence
---
