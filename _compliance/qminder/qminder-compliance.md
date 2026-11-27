---
api_specs:
- filename: qminder-appointments-api-openapi.yml
  format: yaml
  label: Qminder Appointments API
  slug: qminder-appointments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qminder/openapi/qminder-appointments-api-openapi.yml
- filename: qminder-input-fields-api-openapi.yml
  format: yaml
  label: Qminder Input Fields API
  slug: qminder-input-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qminder/openapi/qminder-input-fields-api-openapi.yml
- filename: qminder-lines-api-openapi.yml
  format: yaml
  label: Qminder Lines API
  slug: qminder-lines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qminder/openapi/qminder-lines-api-openapi.yml
- filename: qminder-locations-api-openapi.yml
  format: yaml
  label: Qminder Locations API
  slug: qminder-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qminder/openapi/qminder-locations-api-openapi.yml
- filename: qminder-tickets-api-openapi.yml
  format: yaml
  label: Qminder Tickets API
  slug: qminder-tickets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qminder/openapi/qminder-tickets-api-openapi.yml
- filename: qminder-users-api-openapi.yml
  format: yaml
  label: Qminder Users API
  slug: qminder-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qminder/openapi/qminder-users-api-openapi.yml
- filename: qminder-webhooks-api-openapi.yml
  format: yaml
  label: Qminder Webhooks API
  slug: qminder-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qminder/openapi/qminder-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent third-party auditor
    period: null
    report_access: on_request
    scope: Qminder service controls based on Trust Services Criteria
    text: If you'd like to access the compliance reports, please contact team@qminder.com
    type: SOC 2 Type II audit report
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: businesses subject to HIPAA can process PHI within their Qminder account
    text: Businesses subject to HIPAA can process PHI within their Qminder account, provided they sign Qminder’s Business Associate Agreement.
    type: HIPAA compliance with Business Associate Agreement
  - framework: other
    issuer: Texas Department of Information Resources
    period: null
    report_access: unstated
    scope: security controls for cloud services used by Texas state agencies and higher education
    text: Qminder has achieved TX-RAMP Level 2 certification, demonstrating that our security controls meet the rigorous standards required for handling sensitive government data.
    type: TX-RAMP Level 2 certification
  trust_center:
    url: https://www.qminder.com/security/
frameworks:
- HIPAA
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Qminder
provenance_date: '2026-11-10'
provider_name: Qminder
provider_slug: qminder
slug: qminder-compliance
source_date: '2026-11-10'
source_filename: qminder-compliance.yml
source_heading: Compliance
source_page: https://www.qminder.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Qminder\naid: qminder\nurl: https://www.qminder.com/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.qminder.com/security/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II audit report\n  scope: Qminder service controls based on Trust Services Criteria\n  period: null\n  issuer: independent third-party auditor\n  report_access: on_request\n  text: If you'd like to access the compliance reports, please contact team@qminder.com\n- framework: HIPAA\n  type: HIPAA compliance with Business Associate Agreement\n  scope: businesses subject to HIPAA can process PHI within their Qminder account\n\
  \  period: null\n  issuer: null\n  report_access: unstated\n  text: Businesses subject to HIPAA can process PHI within their Qminder account, provided they sign Qminder’s Business\n    Associate Agreement.\n- framework: other\n  type: TX-RAMP Level 2 certification\n  scope: security controls for cloud services used by Texas state agencies and higher education\n  period: null\n  issuer: Texas Department of Information Resources\n  report_access: unstated\n  text: Qminder has achieved TX-RAMP Level 2 certification, demonstrating that our security controls meet the rigorous\n    standards required for handling sensitive government data.\n"
source_yaml_url: https://artifacts.apis.io/qminder/compliance/qminder-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Qminder's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Queue Management
- Appointment Scheduling
- Visitor Management
- Customer Experience
- REST
- GraphQL
- Webhook
- Software-as-a-Service
- Scheduling
---
