---
api_specs:
- filename: userpilot-analytics-api-openapi.yml
  format: yaml
  label: Userpilot Analytics API
  slug: userpilot-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/userpilot/openapi/userpilot-analytics-api-openapi.yml
- filename: userpilot-background-jobs-api-openapi.yml
  format: yaml
  label: Userpilot Background Jobs API
  slug: userpilot-background-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/userpilot/openapi/userpilot-background-jobs-api-openapi.yml
- filename: userpilot-companies-api-openapi.yml
  format: yaml
  label: Userpilot Companies API
  slug: userpilot-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/userpilot/openapi/userpilot-companies-api-openapi.yml
- filename: userpilot-imports-api-openapi.yml
  format: yaml
  label: Userpilot Imports API
  slug: userpilot-imports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/userpilot/openapi/userpilot-imports-api-openapi.yml
- filename: userpilot-track-api-openapi.yml
  format: yaml
  label: Userpilot Track API
  slug: userpilot-track-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/userpilot/openapi/userpilot-track-api-openapi.yml
- filename: userpilot-realtime-api-openapi.yml
  format: yaml
  label: Userpilot Realtime API
  slug: userpilot-realtime-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/userpilot/openapi/userpilot-realtime-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent auditing body
    period: null
    report_access: on_request
    scope: security of client data processing
    text: SOC 2 report, available upon request from [email protected]
    type: SOC 2 Type II certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: customers who store and process PHI
    text: Userpilot ensures HIPAA compliance to demonstrate its commitment to providing the highest security standards for customers and potential prospects in the health industry.
    type: HIPAA compliance
  - framework: GDPR
    issuer: null
    period: null
    report_access: on_request
    scope: data protection rights
    text: Customers and Prospects can request our DPA which covers the mechanisms and measures implemented by Userpilot to reflect the Eight User Rights reflected within the EU’s GDPR framework.
    type: GDPR compliance
  trust_center:
    url: https://userpilot.com/security/
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Userpilot
provenance_date: '2026-11-10'
provider_name: Userpilot
provider_slug: userpilot
slug: userpilot-compliance
source_date: '2026-11-10'
source_filename: userpilot-compliance.yml
source_heading: Compliance
source_page: https://userpilot.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Userpilot\naid: userpilot\nurl: https://userpilot.com/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/userpilot-trust-center.yml\ntrust_center:\n  url: https://userpilot.com/security/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II certification\n  scope: security of client data processing\n  period: null\n  issuer: independent auditing body\n  report_access: on_request\n  text: SOC 2 report, available upon request from [email protected]\n- framework: HIPAA\n  type: HIPAA compliance\n  scope: customers who store and process PHI\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: Userpilot ensures HIPAA compliance to demonstrate its commitment to providing the highest security standards\n    for customers and potential prospects in the health industry.\n- framework: GDPR\n  type: GDPR compliance\n  scope: data protection rights\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Customers and Prospects can request our DPA which covers the mechanisms and measures implemented by Userpilot\n    to reflect the Eight User Rights reflected within the EU’s GDPR framework.\n"
source_yaml_url: https://artifacts.apis.io/userpilot/compliance/userpilot-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Userpilot's own page on 2026-11-10.
synthetic: false
tags:
- Product
- Onboarding
- In-App Guidance
- Analytics
- Customer Success
---
