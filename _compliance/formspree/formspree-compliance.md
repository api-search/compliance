---
api_specs:
- filename: formspree-forms-api-openapi.yml
  format: yaml
  label: Formspree Forms API
  slug: formspree-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/formspree/openapi/formspree-forms-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent third-party auditor
    period: null
    report_access: on_request
    scope: null
    text: Formspree has achieved SOC 2 Type 2 compliance and been audited by an independent third-party auditor.
    type: SOC 2 Type 2
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Formspree is fully GDPR compliant and believes in the mission of advancing privacy worldwide.
    type: compliance statement
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We ensure California consumers can exercise their rights under CCPA.
    type: compliance statement
  trust_center:
    url: https://formspree.io/security/
frameworks:
- CCPA
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Formspree
provenance_date: '2026-11-09'
provider_name: Formspree
provider_slug: formspree
slug: formspree-compliance
source_date: '2026-11-09'
source_filename: formspree-compliance.yml
source_heading: Compliance
source_page: https://formspree.io/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Formspree\naid: formspree\nurl: https://formspree.io/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/formspree-trust-center.yml\ntrust_center:\n  url: https://formspree.io/security/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2\n  scope: null\n  period: null\n  issuer: independent third-party auditor\n  report_access: on_request\n  text: Formspree has achieved SOC 2 Type 2 compliance and been audited by an independent third-party auditor.\n- framework: GDPR\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Formspree\
  \ is fully GDPR compliant and believes in the mission of advancing privacy worldwide.\n- framework: CCPA\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We ensure California consumers can exercise their rights under CCPA.\n"
source_yaml_url: https://artifacts.apis.io/formspree/compliance/formspree-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Formspree's own page on 2026-11-09.
synthetic: false
tags:
- Forms
- Backend
- Static Sites
- Email
- Webhook
- JAMstack
- CLI
---
