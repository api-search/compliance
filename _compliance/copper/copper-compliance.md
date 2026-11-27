---
api_specs:
- filename: copper-activities-api-openapi.yml
  format: yaml
  label: Copper Activities API
  slug: copper-activities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copper/openapi/copper-activities-api-openapi.yml
- filename: copper-companies-api-openapi.yml
  format: yaml
  label: Copper Companies API
  slug: copper-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copper/openapi/copper-companies-api-openapi.yml
- filename: copper-leads-api-openapi.yml
  format: yaml
  label: Copper Leads API
  slug: copper-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copper/openapi/copper-leads-api-openapi.yml
- filename: copper-opportunities-api-openapi.yml
  format: yaml
  label: Copper Opportunities API
  slug: copper-opportunities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copper/openapi/copper-opportunities-api-openapi.yml
- filename: copper-people-api-openapi.yml
  format: yaml
  label: Copper People API
  slug: copper-people-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copper/openapi/copper-people-api-openapi.yml
- filename: copper-tasks-api-openapi.yml
  format: yaml
  label: Copper Tasks API
  slug: copper-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copper/openapi/copper-tasks-api-openapi.yml
- filename: copper-webhooks-api-openapi.yml
  format: yaml
  label: Copper Webhooks API
  slug: copper-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copper/openapi/copper-webhooks-api-openapi.yml
claim_count: 9
description: ''
doc:
  attestations:
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: TRUSTe Data Privacy Framework Verification Compliant
    type: TRUSTe Data Privacy Framework Verification
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CPRA (formerly CCPA) Compliant
    type: CPRA compliance
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR Compliant
    type: GDPR compliance
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: EU-U.S. Data Privacy Framework (EU-U.S. DPF) Compliant
    type: EU-U.S. Data Privacy Framework
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: UK Extension to the EU-U.S. Data Privacy Framework Compliant
    type: UK Extension to the EU-U.S. Data Privacy Framework
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Swiss-U.S. Data Privacy Framework (Swiss-U.S. DPF) Compliant
    type: Swiss-U.S. Data Privacy Framework
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Virginia Consumer Data Protection Act (VCDPA) Compliant
    type: Virginia Consumer Data Protection Act
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Colorado Privacy Act (ColoPA) Compliant
    type: Colorado Privacy Act
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PIPEDA Compliant
    type: PIPEDA
  trust_center:
    url: https://trust.copper.com/
frameworks:
- CCPA
- GDPR
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Copper
provenance_date: '2026-11-09'
provider_name: Copper
provider_slug: copper
slug: copper-compliance
source_date: '2026-11-09'
source_filename: copper-compliance.yml
source_heading: Compliance
source_page: https://trust.copper.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Copper\naid: copper\nurl: https://trust.copper.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/copper-trust-center.yml\ntrust_center:\n  url: https://trust.copper.com/\nattestations:\n- framework: other\n  type: TRUSTe Data Privacy Framework Verification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: TRUSTe Data Privacy Framework Verification Compliant\n- framework: CCPA\n  type: CPRA compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CPRA (formerly CCPA) Compliant\n- framework: GDPR\n  type: GDPR compliance\n  scope:\
  \ null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR Compliant\n- framework: other\n  type: EU-U.S. Data Privacy Framework\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: EU-U.S. Data Privacy Framework (EU-U.S. DPF) Compliant\n- framework: other\n  type: UK Extension to the EU-U.S. Data Privacy Framework\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: UK Extension to the EU-U.S. Data Privacy Framework Compliant\n- framework: other\n  type: Swiss-U.S. Data Privacy Framework\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Swiss-U.S. Data Privacy Framework (Swiss-U.S. DPF) Compliant\n- framework: other\n  type: Virginia Consumer Data Protection Act\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Virginia Consumer Data Protection Act (VCDPA) Compliant\n- framework: other\n  type: Colorado Privacy Act\n  scope: null\n  period:\
  \ null\n  issuer: null\n  report_access: unstated\n  text: Colorado Privacy Act (ColoPA) Compliant\n- framework: other\n  type: PIPEDA\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PIPEDA Compliant\n"
source_yaml_url: https://artifacts.apis.io/copper/compliance/copper-compliance.yml
stated_fields:
- attestations
summary_line: 9 quoted statements, read from Copper's own page on 2026-11-09.
synthetic: false
tags:
- Activities
- Companies
- Contact Relationship Management
- Contacts
- CRM
- Google Workspace
- Leads
- Opportunities
- People
- Project
- Sales
- Task
---
