---
api_specs:
- filename: hiver-conversations-api-openapi.yml
  format: yaml
  label: Hiver Conversations API
  slug: hiver-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hiver/openapi/hiver-conversations-api-openapi.yml
- filename: hiver-inbox-api-openapi.yml
  format: yaml
  label: Hiver Inbox API
  slug: hiver-inbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hiver/openapi/hiver-inbox-api-openapi.yml
claim_count: 9
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: An independent auditor
    period: null
    report_access: on_request
    scope: The platform
    text: The platform is covered by our SOC 2 Type II report.
    type: Type II report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We are also ISO 27001:2022 certified and fully GDPR compliant.
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We are also ISO 27001:2022 certified and fully GDPR compliant.
    type: compliance
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA Compliant
    type: compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CPRA (formerly CCPA) Compliant
    type: compliance
  - framework: ISO27001
    issuer: accredited certification body
    period: null
    report_access: unstated
    scope: Hiver information security management
    source: https://hiverhq.com/security-center
    text: You can view our ISO27001 certification here.
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: security, availability, processing integrity, confidentiality, and privacy of customer data
    source: https://hiverhq.com/security-center
    text: The complete SOC 2 Type II report will be available upon a request sent to security@hiverhq.com under a non-disclosure commitment.
    type: SOC 2 Type II report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: GDPR obligations
    source: https://hiverhq.com/security-center
    text: We’ve now completed our GDPR readiness program and you can find more information about our compliance here .
    type: readiness program
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: California residents' personal information
    source: https://hiverhq.com/security-center
    text: Hiver does not sell (as the term is defined in the CCPA) the personal information we collect.
    type: statement of compliance with consumer rights
  trust_center:
    url: https://trustcenter.hiverhq.com/
frameworks:
- CCPA
- GDPR
- HIPAA
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Hiver
provenance_date: '2026-11-09'
provider_name: Hiver
provider_slug: hiver
slug: hiver-compliance
source_date: '2026-11-09'
source_filename: hiver-compliance.yml
source_heading: Compliance
source_page: https://trustcenter.hiverhq.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Hiver\naid: hiver\nurl: https://trustcenter.hiverhq.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://hiverhq.com/security-center\n  - https://trustcenter.hiverhq.com/\ntrust_center:\n  url: https://trustcenter.hiverhq.com/\nattestations:\n- framework: SOC2\n  type: Type II report\n  scope: The platform\n  period: null\n  issuer: An independent auditor\n  report_access: on_request\n  text: The platform is covered by our SOC 2 Type II report.\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We are also ISO 27001:2022 certified\
  \ and fully GDPR compliant.\n- framework: GDPR\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We are also ISO 27001:2022 certified and fully GDPR compliant.\n- framework: HIPAA\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA Compliant\n- framework: CCPA\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CPRA (formerly CCPA) Compliant\n- framework: ISO27001\n  type: certification\n  scope: Hiver information security management\n  period: null\n  issuer: accredited certification body\n  report_access: unstated\n  text: You can view our ISO27001 certification here.\n  source: https://hiverhq.com/security-center\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: security, availability, processing integrity, confidentiality, and privacy of customer data\n  period: null\n  issuer: null\n  report_access: nda\n  text: The\
  \ complete SOC 2 Type II report will be available upon a request sent to security@hiverhq.com under a\n    non-disclosure commitment.\n  source: https://hiverhq.com/security-center\n- framework: GDPR\n  type: readiness program\n  scope: GDPR obligations\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We’ve now completed our GDPR readiness program and you can find more information about our compliance here\n    .\n  source: https://hiverhq.com/security-center\n- framework: CCPA\n  type: statement of compliance with consumer rights\n  scope: California residents' personal information\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Hiver does not sell (as the term is defined in the CCPA) the personal information we collect.\n  source: https://hiverhq.com/security-center\n"
source_yaml_url: https://artifacts.apis.io/hiver/compliance/hiver-compliance.yml
stated_fields:
- attestations
summary_line: 9 quoted statements, read from Hiver's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Customer Service
- Help Desk
- Shared Inbox
- Email
- Ticketing
- Collaboration
- Gmail
- Google Workspace
- Omnichannel
- Live Chat
- Software-as-a-Service
- Artificial Intelligence
---
