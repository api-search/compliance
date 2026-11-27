---
api_specs:
- filename: sparetech-authentication-api-openapi.yml
  format: yaml
  label: Sparetech Authentication API
  slug: sparetech-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sparetech/openapi/sparetech-authentication-api-openapi.yml
- filename: sparetech-changeintent-api-openapi.yml
  format: yaml
  label: Sparetech ChangeIntent API
  slug: sparetech-changeintent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sparetech/openapi/sparetech-changeintent-api-openapi.yml
- filename: sparetech-creationintent-api-openapi.yml
  format: yaml
  label: Sparetech CreationIntent API
  slug: sparetech-creationintent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sparetech/openapi/sparetech-creationintent-api-openapi.yml
- filename: sparetech-extensionintent-api-openapi.yml
  format: yaml
  label: Sparetech ExtensionIntent API
  slug: sparetech-extensionintent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sparetech/openapi/sparetech-extensionintent-api-openapi.yml
- filename: sparetech-material-master-sync-api-openapi.yml
  format: yaml
  label: Sparetech Material Master Sync API
  slug: sparetech-material-master-sync-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sparetech/openapi/sparetech-material-master-sync-api-openapi.yml
- filename: sparetech-schema-api-openapi.yml
  format: yaml
  label: Sparetech Schema API
  slug: sparetech-schema-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sparetech/openapi/sparetech-schema-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: '2025'
    report_access: unstated
    scope: not stated
    text: SOC2 Type II report 2025
    type: Type II
  - framework: SOC2
    issuer: null
    period: '2026'
    report_access: unstated
    scope: not stated
    text: SOC2 Type II report 2026
    type: Type II
  - framework: SOC2
    issuer: independent third-party certified public accounting (CPA) firm
    period: null
    report_access: on_request
    scope: null
    source: https://sparetech.io/security-and-compliance
    text: If you’d like a copy of the compliance reports, please reach out to your account manager or security@sparetech.io for our Trust Portal.
    type: SOC 2 Type II
  trust_center:
    url: https://trust.sparetech.io/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Sparetech
provenance_date: '2026-11-10'
provider_name: Sparetech
provider_slug: sparetech
slug: sparetech-compliance
source_date: '2026-11-10'
source_filename: sparetech-compliance.yml
source_heading: Compliance
source_page: https://trust.sparetech.io/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Sparetech\naid: sparetech\nurl: https://trust.sparetech.io/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://sparetech.io/security-and-compliance\n  - https://trust.sparetech.io/\ntrust_center:\n  url: https://trust.sparetech.io/\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: not stated\n  period: '2025'\n  issuer: null\n  report_access: unstated\n  text: SOC2 Type II report 2025\n- framework: SOC2\n  type: Type II\n  scope: not stated\n  period: '2026'\n  issuer: null\n  report_access: unstated\n  text: SOC2 Type II report 2026\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period:\
  \ null\n  issuer: independent third-party certified public accounting (CPA) firm\n  report_access: on_request\n  text: If you’d like a copy of the compliance reports, please reach out to your account manager or security@sparetech.io\n    for our Trust Portal.\n  source: https://sparetech.io/security-and-compliance\n"
source_yaml_url: https://artifacts.apis.io/sparetech/compliance/sparetech-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Sparetech's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Manufacturing
- Spare Parts
- MRO
- Maintenance
- Procurement
- Inventory Optimization
- ERP Integration
- SAP
- Master Data Management
---
