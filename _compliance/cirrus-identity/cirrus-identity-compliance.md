---
api_specs:
- filename: cirrus-identity-endpoints-api-openapi.yml
  format: yaml
  label: Cirrus Identity Endpoints API
  slug: cirrus-identity-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cirrus-identity/openapi/cirrus-identity-endpoints-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: To obtain the full report, please contact Cirrus Support by sending an email to support@cirrusidentity.com .
    type: SOC 2 Type 2 audit
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Cirrus Identity has received Texas Risk and Authorization Management Program (TX-RAMP) Level 1 certification.
    type: TX-RAMP Level 1 certification
  trust_center:
    url: https://www.cirrusidentity.com/resources/trust-and-compliance-center
frameworks:
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Cirrus Identity
provenance_date: '2026-11-09'
provider_name: Cirrus Identity
provider_slug: cirrus-identity
slug: cirrus-identity-compliance
source_date: '2026-11-09'
source_filename: cirrus-identity-compliance.yml
source_heading: Compliance
source_page: https://www.cirrusidentity.com/resources/trust-and-compliance-center
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Cirrus Identity\naid: cirrus-identity\nurl: https://www.cirrusidentity.com/resources/trust-and-compliance-center\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.cirrusidentity.com/resources/trust-and-compliance-center\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 audit\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: To obtain the full report, please contact Cirrus Support by sending an email to support@cirrusidentity.com\n    .\n- framework: other\n  type: TX-RAMP Level 1 certification\n  scope: null\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: Cirrus Identity has received Texas Risk and Authorization Management Program (TX-RAMP) Level 1 certification.\n"
source_yaml_url: https://artifacts.apis.io/cirrus-identity/compliance/cirrus-identity-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Cirrus Identity's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Identity
- Authentication
- SSO
- SAML
- OpenID Connect
- Higher Education
- Identity and Access Management
- Federation
- Logs
- Identity Federation
---
