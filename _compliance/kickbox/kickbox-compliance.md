---
api_specs:
- filename: kickbox-account-api-openapi.yml
  format: yaml
  label: Kickbox Account API
  slug: kickbox-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kickbox/openapi/kickbox-account-api-openapi.yml
- filename: kickbox-batch-api-openapi.yml
  format: yaml
  label: Kickbox Batch API
  slug: kickbox-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kickbox/openapi/kickbox-batch-api-openapi.yml
- filename: kickbox-open-api-openapi.yml
  format: yaml
  label: Kickbox Open API
  slug: kickbox-open-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kickbox/openapi/kickbox-open-api-openapi.yml
- filename: kickbox-verification-api-openapi.yml
  format: yaml
  label: Kickbox Verification API
  slug: kickbox-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kickbox/openapi/kickbox-verification-api-openapi.yml
- filename: kickbox-disposable-api-openapi.yml
  format: yaml
  label: Kickbox Disposable API
  slug: kickbox-disposable-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kickbox/openapi/kickbox-disposable-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: EU customers data protection
    text: We are GDPR compliant , following all of the EU's regulations for data protection for our EU customers.
    type: self-stated compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: company
    text: We are members of anti-abuse organizations like M3WAGG, are CCPA and GDPR ready, and value email security above all.
    type: self-stated readiness
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: company
    text: To view our current progress towards SOC2 compliance , as well as a comprehensive list of Kickbox's security, check out our trust center .
    type: in progress
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: null
    source: https://trust.kickbox.com/
    text: accessing our SOC2 Report and any other available resources will require a signed NDA
    type: SOC 2 Type 1 and Type II reports
  trust_center:
    url: https://docs.kickbox.com/docs/security-and-compliance
frameworks:
- CCPA
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Kickbox
provenance_date: '2026-11-09'
provider_name: Kickbox
provider_slug: kickbox
slug: kickbox-compliance
source_date: '2026-11-09'
source_filename: kickbox-compliance.yml
source_heading: Compliance
source_page: https://docs.kickbox.com/docs/security-and-compliance
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Kickbox\naid: kickbox\nurl: https://docs.kickbox.com/docs/security-and-compliance\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://docs.kickbox.com/docs/security-and-compliance\n  - https://trust.kickbox.com/\ntrust_center:\n  url: https://docs.kickbox.com/docs/security-and-compliance\nattestations:\n- framework: GDPR\n  type: self-stated compliance\n  scope: EU customers data protection\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We are GDPR compliant , following all of the EU's regulations for data protection for our EU customers.\n- framework: CCPA\n  type: self-stated readiness\n\
  \  scope: company\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We are members of anti-abuse organizations like M3WAGG, are CCPA and GDPR ready, and value email security\n    above all.\n- framework: SOC2\n  type: in progress\n  scope: company\n  period: null\n  issuer: null\n  report_access: on_request\n  text: To view our current progress towards SOC2 compliance , as well as a comprehensive list of Kickbox's security,\n    check out our trust center .\n- framework: SOC2\n  type: SOC 2 Type 1 and Type II reports\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: accessing our SOC2 Report and any other available resources will require a signed NDA\n  source: https://trust.kickbox.com/\n"
source_yaml_url: https://artifacts.apis.io/kickbox/compliance/kickbox-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Kickbox's own page on 2026-11-09.
synthetic: false
tags:
- Email Verification
- Deliverability
- Data Quality
- Email
---
