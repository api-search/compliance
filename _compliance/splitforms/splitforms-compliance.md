---
api_specs:
- filename: splitforms-openapi.json
  format: json
  label: Form Submission API
  slug: form-submission-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/splitforms/openapi/splitforms-openapi.json
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: splitforms itself
    text: Not yet. splitforms has not undergone a SOC 2 Type I or Type II audit.
    type: Not held
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: splitforms
    text: No. splitforms is not HIPAA compliant and we do not sign Business Associate Agreements (BAAs).
    type: Not held
  - framework: GDPR
    issuer: null
    period: null
    report_access: on_request
    scope: form submissions collected by customers; splitforms as processor
    text: splitforms helps you meet GDPR for the form submissions you collect.
    type: Self-described support for customer compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: data held about splitforms account holders
    text: Yes for the data we hold about you as a splitforms account holder.
    type: Self-described compliance
  trust_center:
    url: https://splitforms.com/security
frameworks:
- CCPA
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Split Forms
provenance_date: '2026-11-10'
provider_name: Split Forms
provider_slug: splitforms
slug: splitforms-compliance
source_date: '2026-11-10'
source_filename: splitforms-compliance.yml
source_heading: Compliance
source_page: https://splitforms.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Split Forms\naid: splitforms\nurl: https://splitforms.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://splitforms.com/security\nattestations:\n- framework: SOC2\n  type: Not held\n  scope: splitforms itself\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Not yet. splitforms has not undergone a SOC 2 Type I or Type II audit.\n- framework: HIPAA\n  type: Not held\n  scope: splitforms\n  period: null\n  issuer: null\n  report_access: unstated\n  text: No. splitforms is not HIPAA compliant and we do not sign Business Associate Agreements (BAAs).\n- framework: GDPR\n  type:\
  \ Self-described support for customer compliance\n  scope: form submissions collected by customers; splitforms as processor\n  period: null\n  issuer: null\n  report_access: on_request\n  text: splitforms helps you meet GDPR for the form submissions you collect.\n- framework: CCPA\n  type: Self-described compliance\n  scope: data held about splitforms account holders\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Yes for the data we hold about you as a splitforms account holder.\n"
source_yaml_url: https://artifacts.apis.io/splitforms/compliance/splitforms-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Split Forms's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Form Backend
- Developer Tools
- Free Tier
- Webhook
---
