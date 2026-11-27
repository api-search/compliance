---
api_specs:
- filename: arctic-wolf-attachment-api-openapi.yml
  format: yaml
  label: Arctic Wolf Attachment API
  slug: arctic-wolf-attachment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arctic-wolf/openapi/arctic-wolf-attachment-api-openapi.yml
- filename: arctic-wolf-comment-api-openapi.yml
  format: yaml
  label: Arctic Wolf Comment API
  slug: arctic-wolf-comment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arctic-wolf/openapi/arctic-wolf-comment-api-openapi.yml
- filename: arctic-wolf-ticket-api-openapi.yml
  format: yaml
  label: Arctic Wolf Ticket API
  slug: arctic-wolf-ticket-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arctic-wolf/openapi/arctic-wolf-ticket-api-openapi.yml
claim_count: 7
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II
    type: SOC 2 Type II
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001
    type: ISO 27001
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type I
    type: SOC 2 Type I
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SIG
    type: SIG
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: TX-RAMP
    type: TX-RAMP
  - framework: SOC2
    issuer: third party
    period: null
    report_access: unstated
    scope: null
    source: https://arcticwolf.com/compliance/
    text: Hold third party audited SOC II Type 2 and ISO 27001-2013 certifications.
    type: Type 2 audit
  - framework: ISO27001
    issuer: third party
    period: null
    report_access: unstated
    scope: null
    source: https://arcticwolf.com/compliance/
    text: Hold third party audited SOC II Type 2 and ISO 27001-2013 certifications.
    type: certification
  trust_center:
    url: https://trust.arcticwolf.com/
frameworks:
- ISO27001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Arctic Wolf
provenance_date: '2026-11-09'
provider_name: Arctic Wolf
provider_slug: arctic-wolf
slug: arctic-wolf-compliance
source_date: '2026-11-09'
source_filename: arctic-wolf-compliance.yml
source_heading: Compliance
source_page: https://trust.arcticwolf.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Arctic Wolf\naid: arctic-wolf\nurl: https://trust.arcticwolf.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/arctic-wolf-trust-center.yml\n  sources:\n  - https://arcticwolf.com/compliance/\n  - https://trust.arcticwolf.com/\ntrust_center:\n  url: https://trust.arcticwolf.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II\n- framework: ISO27001\n  type: ISO 27001\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001\n- framework: SOC2\n  type: SOC 2\
  \ Type I\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type I\n- framework: other\n  type: SIG\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SIG\n- framework: other\n  type: TX-RAMP\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: TX-RAMP\n- framework: SOC2\n  type: Type 2 audit\n  scope: null\n  period: null\n  issuer: third party\n  report_access: unstated\n  text: Hold third party audited SOC II Type 2 and ISO 27001-2013 certifications.\n  source: https://arcticwolf.com/compliance/\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: third party\n  report_access: unstated\n  text: Hold third party audited SOC II Type 2 and ISO 27001-2013 certifications.\n  source: https://arcticwolf.com/compliance/\n"
source_yaml_url: https://artifacts.apis.io/arctic-wolf/compliance/arctic-wolf-compliance.yml
stated_fields:
- attestations
summary_line: 7 quoted statements, read from Arctic Wolf's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Cybersecurity
- Managed Detection and Response
- Security Operations
- Threat Intelligence
- Ticketing
- Endpoint Security
- SOC
---
