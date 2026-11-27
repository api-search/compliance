---
api_specs:
- filename: avo-app-openapi-generated.yml
  format: yaml
  label: Avo API
  slug: avo-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avo-app/openapi/_ae-authored/avo-app-openapi-generated.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type 2 Compliant
    type: Type 2
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR Compliant
    type: null
  trust_center:
    url: https://www.avo.app/security
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Avo
provenance_date: '2026-11-09'
provider_name: Avo
provider_slug: avo-app
slug: avo-app-compliance
source_date: '2026-11-09'
source_filename: avo-app-compliance.yml
source_heading: Compliance
source_page: https://www.avo.app/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Avo\naid: avo-app\nurl: https://www.avo.app/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.avo.app/security\nattestations:\n- framework: SOC2\n  type: Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2 Compliant\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR Compliant\n"
source_yaml_url: https://artifacts.apis.io/avo-app/compliance/avo-app-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Avo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Governance
- Analytics
- Artificial Intelligence
- Software-as-a-Service
---
