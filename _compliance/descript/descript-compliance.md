---
api_specs:
- filename: descript-api-endpoints-api-openapi.yml
  format: yaml
  label: Descript API Endpoints API
  slug: descript-api-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/descript/openapi/descript-api-endpoints-api-openapi.yml
- filename: descript-edit-in-descript-api-openapi.yml
  format: yaml
  label: Descript Edit in Descript API
  slug: descript-edit-in-descript-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/descript/openapi/descript-edit-in-descript-api-openapi.yml
- filename: descript-export-from-descript-api-openapi.yml
  format: yaml
  label: Descript Export from Descript API
  slug: descript-export-from-descript-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/descript/openapi/descript-export-from-descript-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: Certified Public Accounting firm (not named)
    period: null
    report_access: unstated
    scope: null
    text: We are SOC 2 Type II compliant
    type: SOC 2 Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We're SOC 2 Type II compliant and follow its standards and guidelines, as well as GDPR, CCPA, and the Privacy by Design framework.
    type: regulatory compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We're SOC 2 Type II compliant and follow its standards and guidelines, as well as GDPR, CCPA, and the Privacy by Design framework.
    type: regulatory compliance
  trust_center:
    url: https://www.descript.com/security
frameworks:
- CCPA
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Descript
provenance_date: '2026-11-09'
provider_name: Descript
provider_slug: descript
slug: descript-compliance
source_date: '2026-11-09'
source_filename: descript-compliance.yml
source_heading: Compliance
source_page: https://www.descript.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Descript\naid: descript\nurl: https://www.descript.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/descript-trust-center.yml\ntrust_center:\n  url: https://www.descript.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: null\n  issuer: Certified Public Accounting firm (not named)\n  report_access: unstated\n  text: We are SOC 2 Type II compliant\n- framework: GDPR\n  type: regulatory compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We're SOC 2 Type II compliant and follow its standards and guidelines,\
  \ as well as GDPR, CCPA, and the Privacy\n    by Design framework.\n- framework: CCPA\n  type: regulatory compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We're SOC 2 Type II compliant and follow its standards and guidelines, as well as GDPR, CCPA, and the Privacy\n    by Design framework.\n"
source_yaml_url: https://artifacts.apis.io/descript/compliance/descript-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Descript's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Audio Editing
- Captions
- Media
- Podcasts
- Transcription
- Video Editing
- Audio
---
