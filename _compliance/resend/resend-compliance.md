---
api_specs:
- filename: resend-audiences-api-openapi.yml
  format: yaml
  label: Resend Audiences API
  slug: resend-audiences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/resend/openapi/resend-audiences-api-openapi.yml
- filename: resend-broadcasts-api-openapi.yml
  format: yaml
  label: Resend Broadcasts API
  slug: resend-broadcasts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/resend/openapi/resend-broadcasts-api-openapi.yml
- filename: resend-domains-api-openapi.yml
  format: yaml
  label: Resend Domains API
  slug: resend-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/resend/openapi/resend-domains-api-openapi.yml
- filename: resend-emails-api-openapi.yml
  format: yaml
  label: Resend Emails API
  slug: resend-emails-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/resend/openapi/resend-emails-api-openapi.yml
- filename: resend-send-api-openapi.yml
  format: yaml
  label: Resend Send API
  slug: resend-send-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/resend/openapi/resend-send-api-openapi.yml
- filename: resend-apis-api-openapi.yml
  format: yaml
  label: Resend APIS API
  slug: resend-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/resend/openapi/resend-apis-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: Vanta & Advantage Partners
    period: null
    report_access: unstated
    scope: null
    text: Yes, Resend is SOC 2 Type II compliant. The audit was completed by Vanta & Advantage Partners.
    type: SOC 2 Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Yes, Resend complies with all articles of GDPR.
    type: GDPR compliance
  trust_center:
    url: https://resend.com/security
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Resend
provenance_date: '2026-11-10'
provider_name: Resend
provider_slug: resend
slug: resend-compliance
source_date: '2026-11-10'
source_filename: resend-compliance.yml
source_heading: Compliance
source_page: https://resend.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Resend\naid: resend\nurl: https://resend.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/resend-trust-center.yml\ntrust_center:\n  url: https://resend.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: null\n  issuer: Vanta & Advantage Partners\n  report_access: unstated\n  text: Yes, Resend is SOC 2 Type II compliant. The audit was completed by Vanta & Advantage Partners.\n- framework: GDPR\n  type: GDPR compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Yes, Resend complies with all articles of GDPR.\n"
source_yaml_url: https://artifacts.apis.io/resend/compliance/resend-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Resend's own page on 2026-11-10.
synthetic: false
tags:
- Email
- Developer Tools
- Transactional Email
- Marketing Email
---
