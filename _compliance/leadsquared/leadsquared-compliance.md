---
api_specs:
- filename: postman.yaml
  format: yaml
  label: LeadSquared REST API
  slug: rest-api
  spec_type: Postman
  url: https://apidocs.leadsquared.com/leadsquared-run-in-postman/
- filename: leadsquared-activities-api-openapi.yml
  format: yaml
  label: LeadSquared Activities API
  slug: leadsquared-activities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadsquared/openapi/leadsquared-activities-api-openapi.yml
- filename: leadsquared-leads-api-openapi.yml
  format: yaml
  label: LeadSquared Leads API
  slug: leadsquared-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadsquared/openapi/leadsquared-leads-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: British Standards Institute (BSI)
    period: null
    report_access: unstated
    scope: entire LeadSquared product, cloud services, IT infrastructure, administration, finance, and internal functions
    text: LeadSquared is ISO 27001:2022 certified by the British Standards Institute (BSI).
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: LeadSquared product and processing as processor
    text: LeadSquared is fully committed to following the guidelines cited by GDPR.
    type: stated compliance commitment
  trust_center:
    url: https://www.leadsquared.com/security/
frameworks:
- GDPR
- ISO27001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: LeadSquared
provenance_date: '2026-11-09'
provider_name: LeadSquared
provider_slug: leadsquared
slug: leadsquared-compliance
source_date: '2026-11-09'
source_filename: leadsquared-compliance.yml
source_heading: Compliance
source_page: https://www.leadsquared.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: LeadSquared\naid: leadsquared\nurl: https://www.leadsquared.com/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.leadsquared.com/security/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: entire LeadSquared product, cloud services, IT infrastructure, administration, finance, and internal functions\n  period: null\n  issuer: British Standards Institute (BSI)\n  report_access: unstated\n  text: LeadSquared is ISO 27001:2022 certified by the British Standards Institute (BSI).\n- framework: GDPR\n  type: stated compliance commitment\n  scope: LeadSquared product and processing\
  \ as processor\n  period: null\n  issuer: null\n  report_access: unstated\n  text: LeadSquared is fully committed to following the guidelines cited by GDPR.\n"
source_yaml_url: https://artifacts.apis.io/leadsquared/compliance/leadsquared-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from LeadSquared's own page on 2026-11-09.
synthetic: false
tags:
- Marketing Automation
- CRM
- Sales Automation
- Lead Management
- Customer Engagement
- Field Force Automation
---
