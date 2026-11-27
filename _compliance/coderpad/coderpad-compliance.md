---
api_specs:
- filename: coderpad-account-api-openapi.yml
  format: yaml
  label: CoderPad Account API
  slug: coderpad-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coderpad/openapi/coderpad-account-api-openapi.yml
- filename: coderpad-campaigns-api-openapi.yml
  format: yaml
  label: CoderPad Campaigns API
  slug: coderpad-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coderpad/openapi/coderpad-campaigns-api-openapi.yml
- filename: coderpad-me-api-openapi.yml
  format: yaml
  label: CoderPad Me API
  slug: coderpad-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coderpad/openapi/coderpad-me-api-openapi.yml
- filename: coderpad-organization-api-openapi.yml
  format: yaml
  label: CoderPad Organization API
  slug: coderpad-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coderpad/openapi/coderpad-organization-api-openapi.yml
- filename: coderpad-pad-environments-api-openapi.yml
  format: yaml
  label: CoderPad Pad environments API
  slug: coderpad-pad-environments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coderpad/openapi/coderpad-pad-environments-api-openapi.yml
- filename: coderpad-pads-api-openapi.yml
  format: yaml
  label: CoderPad Pads API
  slug: coderpad-pads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coderpad/openapi/coderpad-pads-api-openapi.yml
- filename: coderpad-question-variants-api-openapi.yml
  format: yaml
  label: CoderPad Question variants API
  slug: coderpad-question-variants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coderpad/openapi/coderpad-question-variants-api-openapi.yml
- filename: coderpad-questions-api-openapi.yml
  format: yaml
  label: CoderPad Questions API
  slug: coderpad-questions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coderpad/openapi/coderpad-questions-api-openapi.yml
- filename: coderpad-temporaryfile-api-openapi.yml
  format: yaml
  label: CoderPad Temporary File API
  slug: coderpad-temporaryfile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coderpad/openapi/coderpad-temporaryfile-api-openapi.yml
- filename: coderpad-tests-api-openapi.yml
  format: yaml
  label: CoderPad Tests API
  slug: coderpad-tests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coderpad/openapi/coderpad-tests-api-openapi.yml
- filename: coderpad-webhook-api-openapi.yml
  format: yaml
  label: CoderPad Webhook API
  slug: coderpad-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coderpad/openapi/coderpad-webhook-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: Insight Assurance
    period: null
    report_access: on_request
    scope: CoderPad information security policies and procedures
    text: Our SOC2 Type 2 report , issued by Insight Assurance as per the American Institute of CPAs (AICPA) framework, shows our commitment to our strict information security policies and procedures
    type: SOC 2 Type 2 report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: privacy regulations
    text: We follow privacy regulations and are GDPR and CCPA compliant
    type: compliance statement
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: privacy regulations
    text: We follow privacy regulations and are GDPR and CCPA compliant
    type: compliance statement
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: full set of internal cybersecurity policies
    text: We have and abide by a full set of internal cybersecurity policies (based on the ISO 27000 framework)
    type: internal policies based on framework
  trust_center:
    url: https://coderpad.io/security/
frameworks:
- CCPA
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: CoderPad
provenance_date: '2026-11-09'
provider_name: CoderPad
provider_slug: coderpad
slug: coderpad-compliance
source_date: '2026-11-09'
source_filename: coderpad-compliance.yml
source_heading: Compliance
source_page: https://coderpad.io/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: CoderPad\naid: coderpad\nurl: https://coderpad.io/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://coderpad.io/security/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: CoderPad information security policies and procedures\n  period: null\n  issuer: Insight Assurance\n  report_access: on_request\n  text: Our SOC2 Type 2 report , issued by Insight Assurance as per the American Institute of CPAs (AICPA) framework,\n    shows our commitment to our strict information security policies and procedures\n- framework: GDPR\n  type: compliance statement\n  scope: privacy regulations\n\
  \  period: null\n  issuer: null\n  report_access: unstated\n  text: We follow privacy regulations and are GDPR and CCPA compliant\n- framework: CCPA\n  type: compliance statement\n  scope: privacy regulations\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We follow privacy regulations and are GDPR and CCPA compliant\n- framework: ISO27001\n  type: internal policies based on framework\n  scope: full set of internal cybersecurity policies\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We have and abide by a full set of internal cybersecurity policies (based on the ISO 27000 framework)\n"
source_yaml_url: https://artifacts.apis.io/coderpad/compliance/coderpad-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from CoderPad's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Hiring
- Technical Assessment
- InterviewPlatform
---
