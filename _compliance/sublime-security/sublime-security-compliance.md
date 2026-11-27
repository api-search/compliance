---
api_specs:
- filename: sublime-security-binexplode-api-openapi.yml
  format: yaml
  label: Sublime Security BinExplode API
  slug: sublime-security-binexplode-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sublime-security/openapi/sublime-security-binexplode-api-openapi.yml
- filename: sublime-security-email-bombs-api-openapi.yml
  format: yaml
  label: Sublime Security Email Bombs API
  slug: sublime-security-email-bombs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sublime-security/openapi/sublime-security-email-bombs-api-openapi.yml
- filename: sublime-security-enrichment-api-openapi.yml
  format: yaml
  label: Sublime Security Enrichment API
  slug: sublime-security-enrichment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sublime-security/openapi/sublime-security-enrichment-api-openapi.yml
- filename: sublime-security-events-in-the-audit-log-api-openapi.yml
  format: yaml
  label: Sublime Security Events in the audit log API
  slug: sublime-security-events-in-the-audit-log-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sublime-security/openapi/sublime-security-events-in-the-audit-log-api-openapi.yml
- filename: sublime-security-hunt-jobs-api-openapi.yml
  format: yaml
  label: Sublime Security Hunt Jobs API
  slug: sublime-security-hunt-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sublime-security/openapi/sublime-security-hunt-jobs-api-openapi.yml
- filename: sublime-security-lists-api-openapi.yml
  format: yaml
  label: Sublime Security Lists API
  slug: sublime-security-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sublime-security/openapi/sublime-security-lists-api-openapi.yml
- filename: sublime-security-live-flow-api-openapi.yml
  format: yaml
  label: Sublime Security Live flow API
  slug: sublime-security-live-flow-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sublime-security/openapi/sublime-security-live-flow-api-openapi.yml
- filename: sublime-security-mailboxes-api-openapi.yml
  format: yaml
  label: Sublime Security Mailboxes API
  slug: sublime-security-mailboxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sublime-security/openapi/sublime-security-mailboxes-api-openapi.yml
- filename: sublime-security-message-groups-api-openapi.yml
  format: yaml
  label: Sublime Security Message Groups API
  slug: sublime-security-message-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sublime-security/openapi/sublime-security-message-groups-api-openapi.yml
- filename: sublime-security-messages-api-openapi.yml
  format: yaml
  label: Sublime Security Messages API
  slug: sublime-security-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sublime-security/openapi/sublime-security-messages-api-openapi.yml
- filename: sublime-security-organizations-api-openapi.yml
  format: yaml
  label: Sublime Security Organizations API
  slug: sublime-security-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sublime-security/openapi/sublime-security-organizations-api-openapi.yml
- filename: sublime-security-roles-api-openapi.yml
  format: yaml
  label: Sublime Security Roles API
  slug: sublime-security-roles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sublime-security/openapi/sublime-security-roles-api-openapi.yml
- filename: sublime-security-rules-api-openapi.yml
  format: yaml
  label: Sublime Security Rules API
  slug: sublime-security-rules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sublime-security/openapi/sublime-security-rules-api-openapi.yml
- filename: sublime-security-scim-api-openapi.yml
  format: yaml
  label: Sublime Security SCIM API
  slug: sublime-security-scim-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sublime-security/openapi/sublime-security-scim-api-openapi.yml
- filename: sublime-security-tasks-api-openapi.yml
  format: yaml
  label: Sublime Security Tasks API
  slug: sublime-security-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sublime-security/openapi/sublime-security-tasks-api-openapi.yml
- filename: sublime-security-user-reports-api-openapi.yml
  format: yaml
  label: Sublime Security User Reports API
  slug: sublime-security-user-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sublime-security/openapi/sublime-security-user-reports-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: 5 Trust Criteria (Security, Availability, Confidentiality, Privacy, and Process Integrity)
    text: SOC 2 Type 2 for 5 Trust Criteria (Security, Availability, Confidentiality, Privacy, and Process Integrity)
    type: SOC 2 Type II report
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Sublime Security - HIPAA Type 1 Report
    type: HIPAA Type 1 Report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: EU-U.S. Data Privacy Framework + UK Extension, and Swiss-U.S. DPF
    text: Sublime Security is an Active Participant of the Data Privacy Framework
    type: EU-U.S. Data Privacy Framework participation
  trust_center:
    url: https://trust.sublime.security/
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Sublime Security
provenance_date: '2026-11-10'
provider_name: Sublime Security
provider_slug: sublime-security
slug: sublime-security-compliance
source_date: '2026-11-10'
source_filename: sublime-security-compliance.yml
source_heading: Compliance
source_page: https://trust.sublime.security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Sublime Security\naid: sublime-security\nurl: https://trust.sublime.security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.sublime.security/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: 5 Trust Criteria (Security, Availability, Confidentiality, Privacy, and Process Integrity)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2 for 5 Trust Criteria (Security, Availability, Confidentiality, Privacy, and Process Integrity)\n- framework: HIPAA\n  type: HIPAA Type 1 Report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: Sublime Security - HIPAA Type 1 Report\n- framework: GDPR\n  type: EU-U.S. Data Privacy Framework participation\n  scope: EU-U.S. Data Privacy Framework + UK Extension, and Swiss-U.S. DPF\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Sublime Security is an Active Participant of the Data Privacy Framework\n"
source_yaml_url: https://artifacts.apis.io/sublime-security/compliance/sublime-security-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Sublime Security's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Email Security
- Phishing
- Detection as Code
- Threat Detection
- Cloud Email Security
- SCIM
---
