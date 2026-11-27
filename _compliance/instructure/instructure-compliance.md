---
api_specs:
- filename: instructure-externaltool-api-openapi.yml
  format: yaml
  label: Instructure ExternalTool API
  slug: instructure-externaltool-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/instructure/openapi/instructure-externaltool-api-openapi.yml
- filename: instructure-lti-accountexternaltool-api-openapi.yml
  format: yaml
  label: Instructure Lti::AccountExternalTool API
  slug: instructure-lti-accountexternaltool-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/instructure/openapi/instructure-lti-accountexternaltool-api-openapi.yml
- filename: instructure-lti-accountlookup-api-openapi.yml
  format: yaml
  label: Instructure Lti::AccountLookup API
  slug: instructure-lti-accountlookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/instructure/openapi/instructure-lti-accountlookup-api-openapi.yml
- filename: instructure-lti-dataservice-api-openapi.yml
  format: yaml
  label: Instructure Lti::DataService API
  slug: instructure-lti-dataservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/instructure/openapi/instructure-lti-dataservice-api-openapi.yml
- filename: instructure-lti-ims-authentication-api-openapi.yml
  format: yaml
  label: Instructure Lti::IMS::Authentication API
  slug: instructure-lti-ims-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/instructure/openapi/instructure-lti-ims-authentication-api-openapi.yml
- filename: instructure-lti-ims-dynamicregistration-api-openapi.yml
  format: yaml
  label: Instructure Lti::IMS::DynamicRegistration API
  slug: instructure-lti-ims-dynamicregistration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/instructure/openapi/instructure-lti-ims-dynamicregistration-api-openapi.yml
- filename: instructure-lti-ims-lineitem-api-openapi.yml
  format: yaml
  label: Instructure Lti::IMS::LineItem API
  slug: instructure-lti-ims-lineitem-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/instructure/openapi/instructure-lti-ims-lineitem-api-openapi.yml
- filename: instructure-lti-ims-namesandrole-api-openapi.yml
  format: yaml
  label: Instructure Lti::IMS::NamesAndRole API
  slug: instructure-lti-ims-namesandrole-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/instructure/openapi/instructure-lti-ims-namesandrole-api-openapi.yml
- filename: instructure-lti-ims-result-api-openapi.yml
  format: yaml
  label: Instructure Lti::IMS::Result API
  slug: instructure-lti-ims-result-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/instructure/openapi/instructure-lti-ims-result-api-openapi.yml
- filename: instructure-lti-membershipservice-api-openapi.yml
  format: yaml
  label: Instructure Lti::MembershipService API
  slug: instructure-lti-membershipservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/instructure/openapi/instructure-lti-membershipservice-api-openapi.yml
- filename: instructure-lti-toolconfigurationsapi-api-openapi.yml
  format: yaml
  label: Instructure Lti::ToolConfigurationsApi API
  slug: instructure-lti-toolconfigurationsapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/instructure/openapi/instructure-lti-toolconfigurationsapi-api-openapi.yml
- filename: instructure-security-api-openapi.yml
  format: yaml
  label: Instructure Security API
  slug: instructure-security-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/instructure/openapi/instructure-security-api-openapi.yml
claim_count: 9
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II
    type: SOC 2 Type II badge
  - framework: SOC3
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 3
    type: SOC 3 badge
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Instructure ISO 27001 Compliance Certificate pdf
    type: ISO 27001 compliance certificate
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: Canvas Catalog and Parchment
    text: Both our Canvas Catalog PCI DSS and our Parchment PCI DSS have been refreshed!
    type: PCI DSS Attestation of Compliance
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: GDPR badge
  - framework: CyberEssentials
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CSA Cyber Essentials Plus
    type: Cyber Essentials Plus badge
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Canvas LMS
    text: We've just refreshed our Canvas LMS HECVAT to Version 4.
    type: HECVAT questionnaire
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: EU-US DPF
    type: EU-US DPF badge
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: TX-RAMP
    type: TX-RAMP badge
  trust_center:
    url: https://trust.instructure.com/
frameworks:
- CyberEssentials
- GDPR
- ISO27001
- PCI-DSS
- SOC2
- SOC3
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Instructure
provenance_date: '2026-11-09'
provider_name: Instructure
provider_slug: instructure
slug: instructure-compliance
source_date: '2026-11-09'
source_filename: instructure-compliance.yml
source_heading: Compliance
source_page: https://trust.instructure.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Instructure\naid: instructure\nurl: https://trust.instructure.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/instructure-trust-center.yml\ntrust_center:\n  url: https://trust.instructure.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II\n- framework: SOC3\n  type: SOC 3 badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 3\n- framework: ISO27001\n  type: ISO 27001 compliance certificate\n  scope: null\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: Instructure ISO 27001 Compliance Certificate pdf\n- framework: PCI-DSS\n  type: PCI DSS Attestation of Compliance\n  scope: Canvas Catalog and Parchment\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Both our Canvas Catalog PCI DSS and our Parchment PCI DSS have been refreshed!\n- framework: GDPR\n  type: GDPR badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: CyberEssentials\n  type: Cyber Essentials Plus badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CSA Cyber Essentials Plus\n- framework: other\n  type: HECVAT questionnaire\n  scope: Canvas LMS\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We've just refreshed our Canvas LMS HECVAT to Version 4.\n- framework: other\n  type: EU-US DPF badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: EU-US DPF\n- framework: other\n  type: TX-RAMP badge\n\
  \  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: TX-RAMP\n"
source_yaml_url: https://artifacts.apis.io/instructure/compliance/instructure-compliance.yml
stated_fields:
- attestations
summary_line: 9 quoted statements, read from Instructure's own page on 2026-11-09.
synthetic: false
tags:
- Enrollment
- Instructure
- EdTech
- Education
- LMS
- Canvas
- Courses
- Assignments
- Grades
- Discussions
- GraphQL
- LTI
---
