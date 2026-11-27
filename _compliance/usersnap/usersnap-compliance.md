---
api_specs:
- filename: usersnap-feedback-api-openapi.yml
  format: yaml
  label: Usersnap Feedback API
  slug: usersnap-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usersnap/openapi/usersnap-feedback-api-openapi.yml
- filename: usersnap-pre-submit-api-openapi.yml
  format: yaml
  label: Usersnap Pre Submit API
  slug: usersnap-pre-submit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usersnap/openapi/usersnap-pre-submit-api-openapi.yml
- filename: usersnap-project-api-openapi.yml
  format: yaml
  label: Usersnap Project API
  slug: usersnap-project-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usersnap/openapi/usersnap-project-api-openapi.yml
- filename: usersnap-submit-api-openapi.yml
  format: yaml
  label: Usersnap Submit API
  slug: usersnap-submit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usersnap/openapi/usersnap-submit-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: personal data processing
    text: We are compliant with the EU General Data Protection Regulation (GDPR)
    type: self-stated compliance
  trust_center:
    url: https://usersnap.com/security
frameworks:
- GDPR
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Usersnap
provenance_date: '2026-11-10'
provider_name: Usersnap
provider_slug: usersnap
slug: usersnap-compliance
source_date: '2026-11-10'
source_filename: usersnap-compliance.yml
source_heading: Compliance
source_page: https://usersnap.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Usersnap\naid: usersnap\nurl: https://usersnap.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://usersnap.com/security\nattestations:\n- framework: GDPR\n  type: self-stated compliance\n  scope: personal data processing\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We are compliant with the EU General Data Protection Regulation (GDPR)\n"
source_yaml_url: https://artifacts.apis.io/usersnap/compliance/usersnap-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Usersnap's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Feedback
- Bug Tracking
- Customer Experience
- Product Management
- Surveys
- Software-as-a-Service
---
