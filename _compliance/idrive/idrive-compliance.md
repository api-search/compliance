---
api_specs:
- filename: idrive-reseller-api-openapi.yml
  format: yaml
  label: IDrive Reseller API
  slug: idrive-reseller-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idrive/openapi/idrive-reseller-api-openapi.yml
- filename: idrive-subusers-api-openapi.yml
  format: yaml
  label: IDrive Subusers API
  slug: idrive-subusers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idrive/openapi/idrive-subusers-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: IDrive e2 cloud object storage
    text: SOC 2, GDPR, HIPAA Compliance
    type: null
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: IDrive e2 cloud object storage
    text: SOC 2, GDPR, HIPAA Compliance
    type: null
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: IDrive e2 cloud object storage
    text: SOC 2, GDPR, HIPAA Compliance
    type: null
  trust_center:
    url: https://security.idrive.com/
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: IDrive
provenance_date: '2026-11-09'
provider_name: IDrive
provider_slug: idrive
slug: idrive-compliance
source_date: '2026-11-09'
source_filename: idrive-compliance.yml
source_heading: Compliance
source_page: https://security.idrive.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: IDrive\naid: idrive\nurl: https://security.idrive.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://security.idrive.com/\nattestations:\n- framework: SOC2\n  type: null\n  scope: IDrive e2 cloud object storage\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2, GDPR, HIPAA Compliance\n- framework: GDPR\n  type: null\n  scope: IDrive e2 cloud object storage\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2, GDPR, HIPAA Compliance\n- framework: HIPAA\n  type: null\n  scope: IDrive e2 cloud object storage\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: SOC 2, GDPR, HIPAA Compliance\n"
source_yaml_url: https://artifacts.apis.io/idrive/compliance/idrive-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from IDrive's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Object Storage
- S3 Compatible
- Cloud Storage
- Backup
- Reseller
- MCP
---
