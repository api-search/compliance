---
api_specs:
- filename: invoca-messages-api-openapi.yml
  format: yaml
  label: Invoca Messages API
  slug: invoca-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/invoca/openapi/invoca-messages-api-openapi.yml
- filename: invoca-phone-numbers-api-openapi.yml
  format: yaml
  label: Invoca Phone Numbers API
  slug: invoca-phone-numbers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/invoca/openapi/invoca-phone-numbers-api-openapi.yml
claim_count: 12
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2
    type: null
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001:2022
    type: null
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PCI-DSS 4.0
    type: null
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: null
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA
    type: null
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA COMPLIANT
    type: null
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: FSQS
    type: FSQS
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Invoca Platform
    source: https://www.invoca.com/platform/security-governance
    text: SOC 2 Type 2 certified, ISO 27001, HIPAA, GDPR, and CCPA compliant.
    type: SOC 2 Type 2 certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Invoca Platform
    source: https://www.invoca.com/platform/security-governance
    text: SOC 2 Type 2 certified, ISO 27001, HIPAA, GDPR, and CCPA compliant.
    type: certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Invoca Platform
    source: https://www.invoca.com/platform/security-governance
    text: Business Associate Agreement (BAA) supported platform Invoca for all HIPAA-covered entities
    type: compliance
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Invoca Platform
    source: https://www.invoca.com/platform/security-governance
    text: SOC 2 Type 2 certified, ISO 27001, HIPAA, GDPR, and CCPA compliant.
    type: compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: Invoca Platform
    source: https://www.invoca.com/platform/security-governance
    text: SOC 2 Type 2 certified, ISO 27001, HIPAA, GDPR, and CCPA compliant.
    type: compliance
  trust_center:
    url: https://trust.invoca.com/
frameworks:
- CCPA
- GDPR
- HIPAA
- ISO27001
- PCI-DSS
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Invoca
provenance_date: '2026-11-09'
provider_name: Invoca
provider_slug: invoca
slug: invoca-compliance
source_date: '2026-11-09'
source_filename: invoca-compliance.yml
source_heading: Compliance
source_page: https://trust.invoca.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Invoca\naid: invoca\nurl: https://trust.invoca.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://trust.invoca.com/\n  - https://www.invoca.com/platform/security-governance\ntrust_center:\n  url: https://trust.invoca.com/\nattestations:\n- framework: SOC2\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2\n- framework: ISO27001\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022\n- framework: PCI-DSS\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text:\
  \ PCI-DSS 4.0\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: HIPAA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA\n- framework: CCPA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA COMPLIANT\n- framework: other\n  type: FSQS\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: FSQS\n- framework: SOC2\n  type: SOC 2 Type 2 certification\n  scope: Invoca Platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2 certified, ISO 27001, HIPAA, GDPR, and CCPA compliant.\n  source: https://www.invoca.com/platform/security-governance\n- framework: ISO27001\n  type: certification\n  scope: Invoca Platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2 certified, ISO 27001, HIPAA, GDPR, and CCPA compliant.\n\
  \  source: https://www.invoca.com/platform/security-governance\n- framework: HIPAA\n  type: compliance\n  scope: Invoca Platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Business Associate Agreement (BAA) supported platform Invoca for all HIPAA-covered entities\n  source: https://www.invoca.com/platform/security-governance\n- framework: GDPR\n  type: compliance\n  scope: Invoca Platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2 certified, ISO 27001, HIPAA, GDPR, and CCPA compliant.\n  source: https://www.invoca.com/platform/security-governance\n- framework: CCPA\n  type: compliance\n  scope: Invoca Platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2 certified, ISO 27001, HIPAA, GDPR, and CCPA compliant.\n  source: https://www.invoca.com/platform/security-governance\n"
source_yaml_url: https://artifacts.apis.io/invoca/compliance/invoca-compliance.yml
stated_fields:
- attestations
summary_line: 12 quoted statements, read from Invoca's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Call Tracking
- Conversation Intelligence
- Marketing
- Attribution
- Revenue
- Telephony
- Analytics
---
