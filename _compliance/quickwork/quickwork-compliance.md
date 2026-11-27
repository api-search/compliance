---
api_specs:
- filename: quickwork-embedded-api-openapi.yml
  format: yaml
  label: Quickwork Embedded API
  slug: quickwork-embedded-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quickwork/openapi/quickwork-embedded-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II compliant
    type: SOC 2 Type II compliance
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: 'ISO/IEC 27001: 2022 certification completed'
    type: ISO/IEC 27001:2022 certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: EU GDPR compliant
    type: EU GDPR compliance
  trust_center:
    url: https://www.quickwork.co/security
frameworks:
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Quickwork
provenance_date: '2026-11-10'
provider_name: Quickwork
provider_slug: quickwork
slug: quickwork-compliance
source_date: '2026-11-10'
source_filename: quickwork-compliance.yml
source_heading: Compliance
source_page: https://www.quickwork.co/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Quickwork\naid: quickwork\nurl: https://www.quickwork.co/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.quickwork.co/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II compliant\n- framework: ISO27001\n  type: ISO/IEC 27001:2022 certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'ISO/IEC 27001: 2022 certification completed'\n- framework: GDPR\n  type: EU GDPR compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: EU GDPR compliant\n"
source_yaml_url: https://artifacts.apis.io/quickwork/compliance/quickwork-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Quickwork's own page on 2026-11-10.
synthetic: false
tags:
- Integration
- Automation
- Workflows
- API Platform
- Enterprise
---
