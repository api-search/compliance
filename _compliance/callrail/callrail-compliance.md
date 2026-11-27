---
api_specs:
- filename: callrail-accounts-api-openapi.yml
  format: yaml
  label: CallRail Accounts API
  slug: callrail-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callrail/openapi/callrail-accounts-api-openapi.yml
- filename: callrail-calls-api-openapi.yml
  format: yaml
  label: CallRail Calls API
  slug: callrail-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callrail/openapi/callrail-calls-api-openapi.yml
claim_count: 10
description: ''
doc:
  attestations:
  - framework: ISO42001
    issuer: null
    period: null
    report_access: unstated
    scope: AI Management Systems
    text: CallRail is proud to be the first in the lead intelligence industry to achieve this certification.
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: security processes and practices
    text: SOC 2 (Type II)
    type: compliance standard
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: end-to-end solution for health care providers and covered entities
    text: we’ve not only created an end-to-end solution for health care providers, ensuring covered entities and the agencies that serve them maintain compliance with the regulations of HIPAA and HITECH.
    type: compliance
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: PII redaction feature for payment information
    text: CallRail’s PII redaction feature was built to help businesses uphold security standards and protect their customer’s personal and financial data
    type: feature
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: personal data
    text: GDPR (General Data Protection Regulation) is the latest set of rules in the European Union governing how personal data can be used and stored.
    type: compliance regulation
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: personal information of California residents
    text: CCPA (California Consumer Protection Act) is California's groundbreaking privacy law that provides data protection of any personal information to California residents.
    type: compliance regulation
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.callrail.com/
    text: HIPAA
    type: null
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.callrail.com/
    text: SOC 2 Type II
    type: Type II
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.callrail.com/
    text: PCI
    type: null
  - framework: ISO42001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.callrail.com/
    text: ISO 42001
    type: null
  trust_center:
    url: https://www.callrail.com/security
frameworks:
- CCPA
- GDPR
- HIPAA
- ISO42001
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: CallRail
provenance_date: '2026-11-09'
provider_name: CallRail
provider_slug: callrail
slug: callrail-compliance
source_date: '2026-11-09'
source_filename: callrail-compliance.yml
source_heading: Compliance
source_page: https://www.callrail.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: CallRail\naid: callrail\nurl: https://www.callrail.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/callrail-trust-center.yml\n  sources:\n  - https://trust.callrail.com/\n  - https://www.callrail.com/security\ntrust_center:\n  url: https://www.callrail.com/security\nattestations:\n- framework: ISO42001\n  type: certification\n  scope: AI Management Systems\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CallRail is proud to be the first in the lead intelligence industry to achieve this certification.\n- framework: SOC2\n  type: compliance standard\n  scope: security\
  \ processes and practices\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 (Type II)\n- framework: HIPAA\n  type: compliance\n  scope: end-to-end solution for health care providers and covered entities\n  period: null\n  issuer: null\n  report_access: unstated\n  text: we’ve not only created an end-to-end solution for health care providers, ensuring covered entities and the\n    agencies that serve them maintain compliance with the regulations of HIPAA and HITECH.\n- framework: PCI-DSS\n  type: feature\n  scope: PII redaction feature for payment information\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CallRail’s PII redaction feature was built to help businesses uphold security standards and protect their\n    customer’s personal and financial data\n- framework: GDPR\n  type: compliance regulation\n  scope: personal data\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR (General Data Protection Regulation) is the latest\
  \ set of rules in the European Union governing how\n    personal data can be used and stored.\n- framework: CCPA\n  type: compliance regulation\n  scope: personal information of California residents\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA (California Consumer Protection Act) is California's groundbreaking privacy law that provides data\n    protection of any personal information to California residents.\n- framework: HIPAA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA\n  source: https://trust.callrail.com/\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II\n  source: https://trust.callrail.com/\n- framework: PCI-DSS\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI\n  source: https://trust.callrail.com/\n- framework: ISO42001\n  type: null\n  scope: null\n  period: null\n\
  \  issuer: null\n  report_access: unstated\n  text: ISO 42001\n  source: https://trust.callrail.com/\n"
source_yaml_url: https://artifacts.apis.io/callrail/compliance/callrail-compliance.yml
stated_fields:
- attestations
summary_line: 10 quoted statements, read from CallRail's own page on 2026-11-09.
synthetic: false
tags:
- Call Tracking
- Conversation Intelligence
- Marketing Attribution
- Lead Tracking
- Telephony
- Analytics
- Form Tracking
- Attribution
---
