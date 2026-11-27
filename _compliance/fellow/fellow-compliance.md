---
api_specs:
- filename: fellow-action-items-api-openapi.yml
  format: yaml
  label: Fellow Action Items API
  slug: fellow-action-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fellow/openapi/fellow-action-items-api-openapi.yml
- filename: fellow-notes-api-openapi.yml
  format: yaml
  label: Fellow Notes API
  slug: fellow-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fellow/openapi/fellow-notes-api-openapi.yml
- filename: fellow-recordings-api-openapi.yml
  format: yaml
  label: Fellow Recordings API
  slug: fellow-recordings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fellow/openapi/fellow-recordings-api-openapi.yml
- filename: fellow-users-api-openapi.yml
  format: yaml
  label: Fellow Users API
  slug: fellow-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fellow/openapi/fellow-users-api-openapi.yml
- filename: fellow-webhooks-api-openapi.yml
  format: yaml
  label: Fellow Webhooks API
  slug: fellow-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fellow/openapi/fellow-webhooks-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: AICPA accredited third parties
    period: valid for 12 months
    report_access: on_request
    scope: Security and Confidentiality criteria
    text: Our latest SOC 2 Type II report covers the Security and Confidentiality criteria and is valid for 12 months.
    type: SOC 2 Type II report
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Protected Health Information
    text: Fellow provides Business Associate Agreements (BAAs) for organizations that require compliance with the Health Insurance Portability and Accountability Act (HIPAA).
    type: HIPAA compliance with Business Associate Agreements
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR compliant data processing agreements, Fellow has an on staff Data Protection Officer
    type: GDPR compliant data processing agreements
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: Customer personal information rights
    text: Fellow is committed to transparency and user privacy in accordance with the California Consumer Privacy Act (CCPA).
    type: CCPA compliance commitment
  - framework: SOC2
    issuer: null
    period: '2025'
    report_access: unstated
    scope: null
    source: https://trust.fellow.ai/
    text: SOC 2 Type II - 2025
    type: Type II
  trust_center:
    url: https://help.fellow.ai/en/articles/4302231-security-and-compliance
frameworks:
- CCPA
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Fellow
provenance_date: '2026-11-09'
provider_name: Fellow
provider_slug: fellow
slug: fellow-compliance
source_date: '2026-11-09'
source_filename: fellow-compliance.yml
source_heading: Compliance
source_page: https://help.fellow.ai/en/articles/4302231-security-and-compliance
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Fellow\naid: fellow\nurl: https://help.fellow.ai/en/articles/4302231-security-and-compliance\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://help.fellow.ai/en/articles/4302231-security-and-compliance\n  - https://trust.fellow.ai/\ntrust_center:\n  url: https://help.fellow.ai/en/articles/4302231-security-and-compliance\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: Security and Confidentiality criteria\n  period: valid for 12 months\n  issuer: AICPA accredited third parties\n  report_access: on_request\n  text: Our latest SOC 2 Type II report covers the Security and Confidentiality\
  \ criteria and is valid for 12 months.\n- framework: HIPAA\n  type: HIPAA compliance with Business Associate Agreements\n  scope: Protected Health Information\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Fellow provides Business Associate Agreements (BAAs) for organizations that require compliance with the\n    Health Insurance Portability and Accountability Act (HIPAA).\n- framework: GDPR\n  type: GDPR compliant data processing agreements\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR compliant data processing agreements, Fellow has an on staff Data Protection Officer\n- framework: CCPA\n  type: CCPA compliance commitment\n  scope: Customer personal information rights\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Fellow is committed to transparency and user privacy in accordance with the California Consumer Privacy\n    Act (CCPA).\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: '2025'\n\
  \  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II - 2025\n  source: https://trust.fellow.ai/\n"
source_yaml_url: https://artifacts.apis.io/fellow/compliance/fellow-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Fellow's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Software-as-a-Service
- Meetings
- Artificial Intelligence
- Meeting Notes
- Transcription
- Productivity
- Action Items
- Webhook
- MCP
---
