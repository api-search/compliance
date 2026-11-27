---
api_specs:
- filename: doximity-openid-connect-api-openapi.yml
  format: yaml
  label: Doximity OpenID Connect API
  slug: doximity-openid-connect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doximity/openapi/doximity-openid-connect-api-openapi.yml
- filename: doximity-oauth-api-openapi.yml
  format: yaml
  label: Doximity O Auth API
  slug: doximity-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doximity/openapi/doximity-oauth-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: platforms and data
    text: being SOC 2 Type 2 and HIPAA/HITECH certified
    type: SOC 2 Type 2 certification
  - framework: SOC3
    issuer: null
    period: null
    report_access: public
    scope: null
    text: Doximity SOC 3 Report
    type: SOC 3 report
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: platform healthcare communications
    text: maintaining compliance with the Health Insurance Portability and Accountability Act of 1996 (HIPAA)
    type: HIPAA compliance
  trust_center:
    url: https://www.doximity.com/about/security
frameworks:
- HIPAA
- SOC2
- SOC3
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Doximity
provenance_date: '2026-11-09'
provider_name: Doximity
provider_slug: doximity
slug: doximity-compliance
source_date: '2026-11-09'
source_filename: doximity-compliance.yml
source_heading: Compliance
source_page: https://www.doximity.com/about/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Doximity\naid: doximity\nurl: https://www.doximity.com/about/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.doximity.com/about/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 certification\n  scope: platforms and data\n  period: null\n  issuer: null\n  report_access: unstated\n  text: being SOC 2 Type 2 and HIPAA/HITECH certified\n- framework: SOC3\n  type: SOC 3 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: public\n  text: Doximity SOC 3 Report\n- framework: HIPAA\n  type: HIPAA compliance\n  scope: platform healthcare communications\n  period:\
  \ null\n  issuer: null\n  report_access: unstated\n  text: maintaining compliance with the Health Insurance Portability and Accountability Act of 1996 (HIPAA)\n"
source_yaml_url: https://artifacts.apis.io/doximity/compliance/doximity-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Doximity's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health Tech
- Identity
- OAuth
- OpenID Connect
- Authentication
- Physician Network
- Healthcare
- SSO
- Verification
---
