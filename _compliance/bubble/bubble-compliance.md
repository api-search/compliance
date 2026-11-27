---
api_specs:
- filename: bubble-action-api-openapi.yml
  format: yaml
  label: Bubble Action API
  slug: bubble-action-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bubble/openapi/bubble-action-api-openapi.yml
- filename: bubble-context-api-openapi.yml
  format: yaml
  label: Bubble Context API
  slug: bubble-context-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bubble/openapi/bubble-context-api-openapi.yml
- filename: bubble-element-api-openapi.yml
  format: yaml
  label: Bubble Element API
  slug: bubble-element-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bubble/openapi/bubble-element-api-openapi.yml
- filename: bubble-thing-api-openapi.yml
  format: yaml
  label: Bubble Thing API
  slug: bubble-thing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bubble/openapi/bubble-thing-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Bubble platform security program
    text: Bubble complies with the SOC 2 Type II standard for security and offers a GDPR-compliant data processing agreement (DPA).
    type: SOC 2 Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Bubble data processing
    text: offers a GDPR-compliant data processing agreement (DPA)
    type: GDPR-compliant data processing agreement
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Bubble infrastructure hosted on AWS
    text: Bubble hosts its infrastructure on Amazon Web Services (AWS), which is SOC 2 Type II, CSA CAIQ, and ISO/IEC 27001 compliant.
    type: ISO/IEC 27001 compliance (AWS hosting)
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: security
    source: https://manual.bubble.io/help-guides/security.md
    text: Bubble is compliant with the SOC 2 Type II standard for security
    type: SOC 2 Type II
  trust_center:
    url: https://bubble.io/security
frameworks:
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Bubble
provenance_date: '2026-11-09'
provider_name: Bubble
provider_slug: bubble
slug: bubble-compliance
source_date: '2026-11-09'
source_filename: bubble-compliance.yml
source_heading: Compliance
source_page: https://bubble.io/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Bubble\naid: bubble\nurl: https://bubble.io/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/bubble-trust-center.yml\n  sources:\n  - https://bubble.io/security\n  - https://manual.bubble.io/help-guides/security.md\ntrust_center:\n  url: https://bubble.io/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: Bubble platform security program\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Bubble complies with the SOC 2 Type II standard for security and offers a GDPR-compliant data processing\n    agreement (DPA).\n- framework: GDPR\n  type: GDPR-compliant\
  \ data processing agreement\n  scope: Bubble data processing\n  period: null\n  issuer: null\n  report_access: unstated\n  text: offers a GDPR-compliant data processing agreement (DPA)\n- framework: ISO27001\n  type: ISO/IEC 27001 compliance (AWS hosting)\n  scope: Bubble infrastructure hosted on AWS\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Bubble hosts its infrastructure on Amazon Web Services (AWS), which is SOC 2 Type II, CSA CAIQ, and ISO/IEC\n    27001 compliant.\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: security\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Bubble is compliant with the SOC 2 Type II standard for security\n  source: https://manual.bubble.io/help-guides/security.md\n"
source_yaml_url: https://artifacts.apis.io/bubble/compliance/bubble-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Bubble's own page on 2026-11-09.
synthetic: false
tags:
- No-Code
- Application Platform
- Database
- Workflow Automation
- Plugins
---
