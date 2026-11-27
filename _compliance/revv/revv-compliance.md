---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: AWS data centers hosting Revv
    text: AWS DCs are ISO 27001:2013, SAS 70/SSAE 16 and PCI DSS certified.
    type: certification of hosting provider (AWS data centers)
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: Stripe payment processing for Revv
    text: It is certified with Payment Card Industry Data Security Standard or PCI DSS standards.
    type: certification of payment processor (Stripe)
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: AWS data centers hosting Revv
    text: AWS DCs are EU GDPR compliant.
    type: compliance statement for hosting provider (AWS data centers)
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: AWS Cognito User Pools authentication
    text: Amazon Cognito is HIPAA eligible and PCI DSS, SOC, ISO/EIC 27001, ISO/EIC 27017, ISO/ EIC 27018, and ISO 9001 compliant.
    type: eligibility of AWS Cognito
  trust_center:
    url: https://www.revv.so/trust/security.html
frameworks:
- GDPR
- HIPAA
- ISO27001
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Revv
provenance_date: '2026-11-10'
provider_name: Revv
provider_slug: revv
slug: revv-compliance
source_date: '2026-11-10'
source_filename: revv-compliance.yml
source_heading: Compliance
source_page: https://www.revv.so/trust/security.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Revv\naid: revv\nurl: https://www.revv.so/trust/security.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.revv.so/trust/security.html\nattestations:\n- framework: ISO27001\n  type: certification of hosting provider (AWS data centers)\n  scope: AWS data centers hosting Revv\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS DCs are ISO 27001:2013, SAS 70/SSAE 16 and PCI DSS certified.\n- framework: PCI-DSS\n  type: certification of payment processor (Stripe)\n  scope: Stripe payment processing for Revv\n  period: null\n  issuer: null\n  report_access: unstated\n  text: It\
  \ is certified with Payment Card Industry Data Security Standard or PCI DSS standards.\n- framework: GDPR\n  type: compliance statement for hosting provider (AWS data centers)\n  scope: AWS data centers hosting Revv\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AWS DCs are EU GDPR compliant.\n- framework: HIPAA\n  type: eligibility of AWS Cognito\n  scope: AWS Cognito User Pools authentication\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Amazon Cognito is HIPAA eligible and PCI DSS, SOC, ISO/EIC 27001, ISO/EIC 27017, ISO/ EIC 27018, and ISO\n    9001 compliant.\n"
source_yaml_url: https://artifacts.apis.io/revv/compliance/revv-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Revv's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Document Automation
- E-Signature
- Contract Management
- Sales Enablement
- Workflow Automation
- Software-as-a-Service
---
