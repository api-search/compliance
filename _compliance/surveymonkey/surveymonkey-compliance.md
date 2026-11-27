---
api_specs:
- filename: surveymonkey-collectors-api-openapi.yml
  format: yaml
  label: SurveyMonkey Collectors API
  slug: surveymonkey-collectors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/surveymonkey/openapi/surveymonkey-collectors-api-openapi.yml
- filename: surveymonkey-contacts-api-openapi.yml
  format: yaml
  label: SurveyMonkey Contacts API
  slug: surveymonkey-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/surveymonkey/openapi/surveymonkey-contacts-api-openapi.yml
- filename: surveymonkey-groups-api-openapi.yml
  format: yaml
  label: SurveyMonkey Groups API
  slug: surveymonkey-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/surveymonkey/openapi/surveymonkey-groups-api-openapi.yml
- filename: surveymonkey-responses-api-openapi.yml
  format: yaml
  label: SurveyMonkey Responses API
  slug: surveymonkey-responses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/surveymonkey/openapi/surveymonkey-responses-api-openapi.yml
- filename: surveymonkey-survey-structure-api-openapi.yml
  format: yaml
  label: SurveyMonkey Survey Structure API
  slug: surveymonkey-survey-structure-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/surveymonkey/openapi/surveymonkey-survey-structure-api-openapi.yml
- filename: surveymonkey-surveys-api-openapi.yml
  format: yaml
  label: SurveyMonkey Surveys API
  slug: surveymonkey-surveys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/surveymonkey/openapi/surveymonkey-surveys-api-openapi.yml
- filename: surveymonkey-users-api-openapi.yml
  format: yaml
  label: SurveyMonkey Users API
  slug: surveymonkey-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/surveymonkey/openapi/surveymonkey-users-api-openapi.yml
- filename: surveymonkey-work-groups-api-openapi.yml
  format: yaml
  label: SurveyMonkey Work Groups API
  slug: surveymonkey-work-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/surveymonkey/openapi/surveymonkey-work-groups-api-openapi.yml
claim_count: 8
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO - 27001
    type: certification
  - framework: ISO27701
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO - 27701
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type 2
    type: Type 2
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: regime
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PCI DSS
    type: certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA
    type: regime
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA
    type: regime
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: TX-RAMP
    type: certification
  trust_center:
    url: https://trust.surveymonkey.com/
frameworks:
- CCPA
- GDPR
- HIPAA
- ISO27001
- ISO27701
- PCI-DSS
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: SurveyMonkey
provenance_date: '2026-11-10'
provider_name: SurveyMonkey
provider_slug: surveymonkey
slug: surveymonkey-compliance
source_date: '2026-11-10'
source_filename: surveymonkey-compliance.yml
source_heading: Compliance
source_page: https://trust.surveymonkey.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: SurveyMonkey\naid: surveymonkey\nurl: https://trust.surveymonkey.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/surveymonkey-trust-center.yml\ntrust_center:\n  url: https://trust.surveymonkey.com/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO - 27001\n- framework: ISO27701\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO - 27701\n- framework: SOC2\n  type: Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: SOC 2 Type 2\n- framework: GDPR\n  type: regime\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: PCI-DSS\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI DSS\n- framework: HIPAA\n  type: regime\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA\n- framework: CCPA\n  type: regime\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA\n- framework: other\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: TX-RAMP\n"
source_yaml_url: https://artifacts.apis.io/surveymonkey/compliance/surveymonkey-compliance.yml
stated_fields:
- attestations
summary_line: 8 quoted statements, read from SurveyMonkey's own page on 2026-11-10.
synthetic: false
tags:
- Surveys
- Market Research
- Feedback
- NPS
- Forms
- OAuth
- Authentication
---
