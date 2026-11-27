---
api_specs:
- filename: configcat-openapi.json
  format: json
  label: ConfigCat Public Management API
  slug: configcat-public-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configcat/openapi/configcat-openapi.json
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001:2022 Certified
    type: certification
  - framework: ISO27001
    issuer: null
    period: '2025'
    report_access: unstated
    scope: null
    text: ISO audit report (Recertification Audit, 2025)
    type: audit report
  trust_center:
    url: https://configcat.com/trust-center/
frameworks:
- ISO27001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: ConfigCat
provenance_date: '2026-11-09'
provider_name: ConfigCat
provider_slug: configcat
slug: configcat-compliance
source_date: '2026-11-09'
source_filename: configcat-compliance.yml
source_heading: Compliance
source_page: https://configcat.com/trust-center/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: ConfigCat\naid: configcat\nurl: https://configcat.com/trust-center/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://configcat.com/trust-center/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022 Certified\n- framework: ISO27001\n  type: audit report\n  scope: null\n  period: '2025'\n  issuer: null\n  report_access: unstated\n  text: ISO audit report (Recertification Audit, 2025)\n"
source_yaml_url: https://artifacts.apis.io/configcat/compliance/configcat-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from ConfigCat's own page on 2026-11-09.
synthetic: false
tags:
- Feature-Flag
- Software-as-a-Service
- Developer Tools
- Cloud
---
