---
api_specs:
- filename: clevertap-campaigns-api-openapi.yml
  format: yaml
  label: CleverTap Campaigns API
  slug: clevertap-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clevertap/openapi/clevertap-campaigns-api-openapi.yml
- filename: clevertap-events-api-openapi.yml
  format: yaml
  label: CleverTap Events API
  slug: clevertap-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clevertap/openapi/clevertap-events-api-openapi.yml
- filename: clevertap-profiles-api-openapi.yml
  format: yaml
  label: CleverTap Profiles API
  slug: clevertap-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clevertap/openapi/clevertap-profiles-api-openapi.yml
- filename: clevertap-reports-api-openapi.yml
  format: yaml
  label: CleverTap Reports API
  slug: clevertap-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clevertap/openapi/clevertap-reports-api-openapi.yml
claim_count: 13
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: SOC 2 Compliant
    type: compliance
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: ISO 27001 Compliant
    type: compliance
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR Compliant
    type: compliance
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA Compliant
    type: compliance
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CSA Star Compliant
    type: compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CPRA (formerly CCPA) Compliant
    type: compliance
  - framework: ISO27017
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27017 Certified
    type: certification
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Digital Personal Data Protection Act (DPDPA) Compliance Framework Compliant
    type: compliance
  - framework: GDPR
    issuer: independent, third-party auditors
    period: null
    report_access: unstated
    scope: null
    source: https://clevertap.com/security/
    text: CleverTap currently is compliant with GDPR, CCPA, SOC 2 Type II, ISO 27001, and HIPAA.
    type: compliance statement
  - framework: CCPA
    issuer: independent, third-party auditors
    period: null
    report_access: unstated
    scope: null
    source: https://clevertap.com/security/
    text: CleverTap currently is compliant with GDPR, CCPA, SOC 2 Type II, ISO 27001, and HIPAA.
    type: compliance statement
  - framework: SOC2
    issuer: independent, third-party auditors
    period: null
    report_access: unstated
    scope: null
    source: https://clevertap.com/security/
    text: CleverTap currently is compliant with GDPR, CCPA, SOC 2 Type II, ISO 27001, and HIPAA.
    type: SOC 2 Type II
  - framework: ISO27001
    issuer: independent, third-party auditors
    period: null
    report_access: unstated
    scope: null
    source: https://clevertap.com/security/
    text: CleverTap currently is compliant with GDPR, CCPA, SOC 2 Type II, ISO 27001, and HIPAA.
    type: compliance statement
  - framework: HIPAA
    issuer: independent, third-party auditors
    period: null
    report_access: unstated
    scope: null
    source: https://clevertap.com/security/
    text: CleverTap currently is compliant with GDPR, CCPA, SOC 2 Type II, ISO 27001, and HIPAA.
    type: compliance statement
  trust_center:
    url: https://trust.clevertap.com/
frameworks:
- CCPA
- CSA-STAR
- GDPR
- HIPAA
- ISO27001
- ISO27017
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: CleverTap
provenance_date: '2026-11-09'
provider_name: CleverTap
provider_slug: clevertap
slug: clevertap-compliance
source_date: '2026-11-09'
source_filename: clevertap-compliance.yml
source_heading: Compliance
source_page: https://trust.clevertap.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: CleverTap\naid: clevertap\nurl: https://trust.clevertap.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/clevertap-trust-center.yml\n  sources:\n  - https://clevertap.com/security/\n  - https://trust.clevertap.com/\ntrust_center:\n  url: https://trust.clevertap.com/\nattestations:\n- framework: SOC2\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Compliant\n- framework: ISO27001\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: ISO 27001 Compliant\n- framework: GDPR\n  type: compliance\n\
  \  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR Compliant\n- framework: HIPAA\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA Compliant\n- framework: CSA-STAR\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CSA Star Compliant\n- framework: CCPA\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CPRA (formerly CCPA) Compliant\n- framework: ISO27017\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27017 Certified\n- framework: other\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Digital Personal Data Protection Act (DPDPA) Compliance Framework Compliant\n- framework: GDPR\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: independent, third-party auditors\n\
  \  report_access: unstated\n  text: CleverTap currently is compliant with GDPR, CCPA, SOC 2 Type II, ISO 27001, and HIPAA.\n  source: https://clevertap.com/security/\n- framework: CCPA\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: independent, third-party auditors\n  report_access: unstated\n  text: CleverTap currently is compliant with GDPR, CCPA, SOC 2 Type II, ISO 27001, and HIPAA.\n  source: https://clevertap.com/security/\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: null\n  issuer: independent, third-party auditors\n  report_access: unstated\n  text: CleverTap currently is compliant with GDPR, CCPA, SOC 2 Type II, ISO 27001, and HIPAA.\n  source: https://clevertap.com/security/\n- framework: ISO27001\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: independent, third-party auditors\n  report_access: unstated\n  text: CleverTap currently is compliant with GDPR, CCPA, SOC 2 Type II, ISO 27001, and HIPAA.\n  source:\
  \ https://clevertap.com/security/\n- framework: HIPAA\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: independent, third-party auditors\n  report_access: unstated\n  text: CleverTap currently is compliant with GDPR, CCPA, SOC 2 Type II, ISO 27001, and HIPAA.\n  source: https://clevertap.com/security/\n"
source_yaml_url: https://artifacts.apis.io/clevertap/compliance/clevertap-compliance.yml
stated_fields:
- attestations
summary_line: 13 quoted statements, read from CleverTap's own page on 2026-11-09.
synthetic: false
tags:
- Audiences
- Customer Engagement
- Customer Retention
- Marketing Automation
- Mobile Engagement
- Push Notifications
- User Behavior
---
