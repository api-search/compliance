---
api_specs:
- filename: weave-contacts-api-openapi.yml
  format: yaml
  label: Weave Contacts API
  slug: weave-hq-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weave/openapi/weave-contacts-api-openapi.yml
- filename: weave-events-api-openapi.yml
  format: yaml
  label: Weave Events API
  slug: weave-hq-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weave/openapi/weave-events-api-openapi.yml
- filename: weave-forms-api-openapi.yml
  format: yaml
  label: Weave Forms API
  slug: weave-hq-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weave/openapi/weave-forms-api-openapi.yml
- filename: weave-messaging-api-openapi.yml
  format: yaml
  label: Weave Messaging API
  slug: weave-hq-messaging-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weave/openapi/weave-messaging-api-openapi.yml
- filename: weave-payments-api-openapi.yml
  format: yaml
  label: Weave Payments API
  slug: weave-hq-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weave/openapi/weave-payments-api-openapi.yml
- filename: weave-phone-calls-api-openapi.yml
  format: yaml
  label: Weave Phone & Calls API
  slug: weave-hq-phone-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weave/openapi/weave-phone-calls-api-openapi.yml
- filename: weave-reviews-api-openapi.yml
  format: yaml
  label: Weave Reviews API
  slug: weave-hq-reviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weave/openapi/weave-reviews-api-openapi.yml
- filename: weave-scheduling-api-openapi.yml
  format: yaml
  label: Weave Scheduling API
  slug: weave-hq-scheduling-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weave/openapi/weave-scheduling-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Google Cloud Platform infrastructure hosting the Weave platform
    text: GCP undergoes regular independent verification of its security, privacy, and compliance controls, including ISO 27001 and SOC2 Type 2 assessments.
    type: third-party assessment of hosting provider
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Google Cloud Platform infrastructure hosting the Weave platform
    text: GCP undergoes regular independent verification of its security, privacy, and compliance controls, including ISO 27001 and SOC2 Type 2 assessments.
    type: third-party assessment of hosting provider
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Weave features designed to support customers in complying with HIPAA
    text: Weave has been designed with features to support you in complying with HIPAA, while also enabling you to make the most of your communications with patients.
    type: compliance support
  trust_center:
    url: https://www.getweave.com/security/
frameworks:
- HIPAA
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Weave
provenance_date: '2026-11-10'
provider_name: Weave
provider_slug: weave
slug: weave-compliance
source_date: '2026-11-10'
source_filename: weave-compliance.yml
source_heading: Compliance
source_page: https://www.getweave.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Weave\naid: weave\nurl: https://www.getweave.com/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.getweave.com/security/\nattestations:\n- framework: ISO27001\n  type: third-party assessment of hosting provider\n  scope: Google Cloud Platform infrastructure hosting the Weave platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GCP undergoes regular independent verification of its security, privacy, and compliance controls, including\n    ISO 27001 and SOC2 Type 2 assessments.\n- framework: SOC2\n  type: third-party assessment of hosting provider\n  scope: Google Cloud\
  \ Platform infrastructure hosting the Weave platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GCP undergoes regular independent verification of its security, privacy, and compliance controls, including\n    ISO 27001 and SOC2 Type 2 assessments.\n- framework: HIPAA\n  type: compliance support\n  scope: Weave features designed to support customers in complying with HIPAA\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Weave has been designed with features to support you in complying with HIPAA, while also enabling you to\n    make the most of your communications with patients.\n"
source_yaml_url: https://artifacts.apis.io/weave/compliance/weave-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Weave's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Communications
- Messaging
- Payments
- Healthcare
- VoIP
- Telephony
- Reviews
- Scheduling
- Small Business
- Developer Platform
- OAuth
- Authentication
---
