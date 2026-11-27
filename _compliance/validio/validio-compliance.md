---
api_specs:
- filename: validio-openapi-generated.yml
  format: yaml
  label: Validio API
  slug: validio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/validio/openapi/_ae-authored/validio-openapi-generated.yml
- filename: validio-export-api-openapi.yml
  format: yaml
  label: Validio Export API
  slug: validio-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/validio/openapi/validio-export-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: independent auditor
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001 and SOC 2 certified by an independent auditor
    type: certification
  - framework: SOC2
    issuer: independent auditor
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001 and SOC 2 certified by an independent auditor
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Compliant with ISO 27001, SOC 2, GDPR, EU AI Act & HIPAA
    type: compliance statement
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Compliant with ISO 27001, SOC 2, GDPR, EU AI Act & HIPAA
    type: compliance statement
  trust_center:
    url: https://validio.io/security
frameworks:
- GDPR
- HIPAA
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Validio
provenance_date: '2026-11-10'
provider_name: Validio
provider_slug: validio
slug: validio-compliance
source_date: '2026-11-10'
source_filename: validio-compliance.yml
source_heading: Compliance
source_page: https://validio.io/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Validio\naid: validio\nurl: https://validio.io/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://validio.io/security\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: independent auditor\n  report_access: unstated\n  text: ISO 27001 and SOC 2 certified by an independent auditor\n- framework: SOC2\n  type: certification\n  scope: null\n  period: null\n  issuer: independent auditor\n  report_access: unstated\n  text: ISO 27001 and SOC 2 certified by an independent auditor\n- framework: GDPR\n  type: compliance statement\n  scope: null\n  period:\
  \ null\n  issuer: null\n  report_access: unstated\n  text: Compliant with ISO 27001, SOC 2, GDPR, EU AI Act & HIPAA\n- framework: HIPAA\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliant with ISO 27001, SOC 2, GDPR, EU AI Act & HIPAA\n"
source_yaml_url: https://artifacts.apis.io/validio/compliance/validio-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Validio's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data Quality
- Observability
- Data Lineage
- Artificial Intelligence
---
