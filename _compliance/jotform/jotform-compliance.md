---
api_specs:
- filename: jotform-folder-api-openapi.yml
  format: yaml
  label: Jotform Folder API
  slug: jotform-folder-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jotform/openapi/jotform-folder-api-openapi.yml
- filename: jotform-form-api-openapi.yml
  format: yaml
  label: Jotform Form API
  slug: jotform-form-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jotform/openapi/jotform-form-api-openapi.yml
- filename: jotform-label-api-openapi.yml
  format: yaml
  label: Jotform Label API
  slug: jotform-label-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jotform/openapi/jotform-label-api-openapi.yml
- filename: jotform-report-api-openapi.yml
  format: yaml
  label: Jotform Report API
  slug: jotform-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jotform/openapi/jotform-report-api-openapi.yml
- filename: jotform-submission-api-openapi.yml
  format: yaml
  label: Jotform Submission API
  slug: jotform-submission-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jotform/openapi/jotform-submission-api-openapi.yml
- filename: jotform-system-api-openapi.yml
  format: yaml
  label: Jotform System API
  slug: jotform-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jotform/openapi/jotform-system-api-openapi.yml
- filename: jotform-user-api-openapi.yml
  format: yaml
  label: Jotform User API
  slug: jotform-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jotform/openapi/jotform-user-api-openapi.yml
- filename: jotform-webhook-api-openapi.yml
  format: yaml
  label: Jotform Webhook API
  slug: jotform-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jotform/openapi/jotform-webhook-api-openapi.yml
claim_count: 8
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: Jotform payment processing and form services
    text: Jotform is PCI DSS Service Provider Level 1 compliant, the highest security attainment you can have as a business that collects payments from and integrates with credit cards.
    type: PCI DSS Service Provider Level 1 compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: Jotform services
    text: Jotform is compliant with the California Consumer Privacy Act (CCPA)
    type: compliance statement
  - framework: HIPAA
    issuer: null
    period: null
    report_access: on_request
    scope: HIPAA features for healthcare providers, Business Associate Agreement available upon request
    text: A Business Associate Agreement (BAA) is also available upon request.
    type: HIPAA-enabled forms
  - framework: StateRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: Jotform Government
    text: Jotform is currently in the security snapshot Program of StateRAMP.
    type: security snapshot program participation
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: Jotform Government built to security controls common to FedRAMP and StateRAMP
    text: Jotform Government has been built and is being managed according to security controls common to both FedRAMP and StateRAMP
    type: controls alignment
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Google Cloud primary platform
    text: Our primary platform is Google Cloud, which complies with SSAE16 / ISAE 3402 Type II, SOC 1, SOC 2, SOC 3, ISO 27001, ISO 27017 (Cloud Security), ISO 27018 (Cloud Privacy), and PCI DSS v3.2.
    type: cloud provider certification
  - framework: ISO27017
    issuer: null
    period: null
    report_access: unstated
    scope: Google Cloud primary platform
    text: ISO 27017 (Cloud Security), ISO 27018 (Cloud Privacy), and PCI DSS v3.2.
    type: cloud provider certification
  - framework: ISO27018
    issuer: null
    period: null
    report_access: unstated
    scope: Google Cloud primary platform
    text: ISO 27018 (Cloud Privacy)
    type: cloud provider certification
  trust_center:
    url: https://www.jotform.com/security/
frameworks:
- CCPA
- FedRAMP
- HIPAA
- ISO27001
- ISO27017
- ISO27018
- PCI-DSS
- StateRAMP
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Jotform
provenance_date: '2026-11-09'
provider_name: Jotform
provider_slug: jotform
slug: jotform-compliance
source_date: '2026-11-09'
source_filename: jotform-compliance.yml
source_heading: Compliance
source_page: https://www.jotform.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Jotform\naid: jotform\nurl: https://www.jotform.com/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.jotform.com/security/\nattestations:\n- framework: PCI-DSS\n  type: PCI DSS Service Provider Level 1 compliance\n  scope: Jotform payment processing and form services\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Jotform is PCI DSS Service Provider Level 1 compliant, the highest security attainment you can have as a\n    business that collects payments from and integrates with credit cards.\n- framework: CCPA\n  type: compliance statement\n  scope: Jotform services\n\
  \  period: null\n  issuer: null\n  report_access: unstated\n  text: Jotform is compliant with the California Consumer Privacy Act (CCPA)\n- framework: HIPAA\n  type: HIPAA-enabled forms\n  scope: HIPAA features for healthcare providers, Business Associate Agreement available upon request\n  period: null\n  issuer: null\n  report_access: on_request\n  text: A Business Associate Agreement (BAA) is also available upon request.\n- framework: StateRAMP\n  type: security snapshot program participation\n  scope: Jotform Government\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Jotform is currently in the security snapshot Program of StateRAMP.\n- framework: FedRAMP\n  type: controls alignment\n  scope: Jotform Government built to security controls common to FedRAMP and StateRAMP\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Jotform Government has been built and is being managed according to security controls common to both FedRAMP\n    and StateRAMP\n\
  - framework: ISO27001\n  type: cloud provider certification\n  scope: Google Cloud primary platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our primary platform is Google Cloud, which complies with SSAE16 / ISAE 3402 Type II, SOC 1, SOC 2, SOC\n    3, ISO 27001, ISO 27017 (Cloud Security), ISO 27018 (Cloud Privacy), and PCI DSS v3.2.\n- framework: ISO27017\n  type: cloud provider certification\n  scope: Google Cloud primary platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27017 (Cloud Security), ISO 27018 (Cloud Privacy), and PCI DSS v3.2.\n- framework: ISO27018\n  type: cloud provider certification\n  scope: Google Cloud primary platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27018 (Cloud Privacy)\n"
source_yaml_url: https://artifacts.apis.io/jotform/compliance/jotform-compliance.yml
stated_fields:
- attestations
summary_line: 8 quoted statements, read from Jotform's own page on 2026-11-09.
synthetic: false
tags:
- Forms
- Surveys
- No-Code
- Data Collection
- Workflows
- HIPAA
- EU
- MCP
- E-Signature
- Webhook
- Online Payments
---
