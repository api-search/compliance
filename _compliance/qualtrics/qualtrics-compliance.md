---
api_specs:
- filename: qualtrics-automations-api-openapi.yml
  format: yaml
  label: Qualtrics Automations API
  slug: qualtrics-automations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualtrics/openapi/qualtrics-automations-api-openapi.yml
- filename: qualtrics-directories-api-openapi.yml
  format: yaml
  label: Qualtrics Directories API
  slug: qualtrics-directories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualtrics/openapi/qualtrics-directories-api-openapi.yml
- filename: qualtrics-distributions-api-openapi.yml
  format: yaml
  label: Qualtrics Distributions API
  slug: qualtrics-distributions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualtrics/openapi/qualtrics-distributions-api-openapi.yml
- filename: qualtrics-file-api-openapi.yml
  format: yaml
  label: Qualtrics File API
  slug: qualtrics-file-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualtrics/openapi/qualtrics-file-api-openapi.yml
- filename: qualtrics-files-api-openapi.yml
  format: yaml
  label: Qualtrics Files API
  slug: qualtrics-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualtrics/openapi/qualtrics-files-api-openapi.yml
- filename: qualtrics-survey-definitions-api-openapi.yml
  format: yaml
  label: Qualtrics Survey Definitions API
  slug: qualtrics-survey-definitions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualtrics/openapi/qualtrics-survey-definitions-api-openapi.yml
- filename: qualtrics-event-subscriptions-api-openapi.yml
  format: yaml
  label: Qualtrics Event Subscriptions API
  slug: qualtrics-event-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualtrics/openapi/qualtrics-event-subscriptions-api-openapi.yml
claim_count: 15
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: '2024'
    report_access: nda
    scope: Qualtrics XM platform
    text: Qualtrics' SOC 2 Type II report for 2024 is now available to approved users within our Trust Center.
    type: SOC 2 Type II report
  - framework: ISO42001
    issuer: null
    period: null
    report_access: public
    scope: AI management systems
    text: Qualtrics is pleased to announce that we have officially achieved the ISO 42001 certification for our AI management systems.
    type: ISO 42001 certification
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: on_request
    scope: Qualtrics XM platform
    text: Access is limited to eligible government agencies and is subject to verification. Public sector customers may request access to the Qualtrics FedRAMP High security package here
    type: FedRAMP High authorization
  - framework: other
    issuer: Defense Information Systems Agency (DISA)
    period: null
    report_access: unstated
    scope: Qualtrics XM platform
    text: Qualtrics has secured Impact Level 4 (IL4) Provisional Authorization from the Defense Information Systems Agency (DISA) for the Qualtrics XM platform.
    type: DISA IL4 Provisional Authorization
  - framework: other
    issuer: GovRAMP Program Management Office (PMO)
    period: FY2026
    report_access: on_request
    scope: Qualtrics XM Platform, High security impact level
    text: Qualtrics is pleased to announce our GovRAMP Authorized status for FY2026, granted by the GovRAMP Program Management Office (PMO) and the GovRAMP Approvals Committee
    type: GovRAMP Authorized status
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001 Cert - 2030 Expiry pdf
    type: ISO 27001 certificate
  - framework: ISO27017
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27017 Cert - 2030 Expiry pdf
    type: ISO 27017 certificate
  - framework: ISO27018
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27018 Cert - 2030 Expiry pdf
    type: ISO 27018 certificate
  - framework: ISO27701
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27701 Cert - 2028 Expiry pdf
    type: ISO 27701 certificate
  - framework: PCI-DSS
    issuer: null
    period: '''25'
    report_access: unstated
    scope: null
    text: PCI DSS AOC '25
    type: PCI DSS Attestation of Compliance
  - framework: HITRUST
    issuer: null
    period: '''25'
    report_access: unstated
    scope: null
    text: HITRUST Certification Letter '25 pdf
    type: HITRUST certification letter
  - framework: TISAX
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Qualtrics TISAX Certification SIG Core '25
    type: TISAX certification
  - framework: CyberEssentials
    issuer: null
    period: Dec. '25
    report_access: unstated
    scope: null
    text: Cyber Essentials Certificate Dec. '25
    type: Cyber Essentials certificate
  - framework: IRAP
    issuer: null
    period: null
    report_access: unstated
    scope: Qualtrics XM
    text: Qualtrics XM IRAP Compliance Letter
    type: IRAP compliance letter
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Certifications & Compliance SOC 2 Type II GDPR PCI CCPA Cyber Essentials HITRUST TISAX TX-RAMP GovRAMP FedRAMP High ISO 42001
    type: GDPR certification listed
  trust_center:
    url: https://trust.qualtrics.com/
frameworks:
- CyberEssentials
- FedRAMP
- GDPR
- HITRUST
- IRAP
- ISO27001
- ISO27017
- ISO27018
- ISO27701
- ISO42001
- PCI-DSS
- SOC2
- TISAX
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Qualtrics
provenance_date: '2026-11-10'
provider_name: Qualtrics
provider_slug: qualtrics
slug: qualtrics-compliance
source_date: '2026-11-10'
source_filename: qualtrics-compliance.yml
source_heading: Compliance
source_page: https://trust.qualtrics.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Qualtrics\naid: qualtrics\nurl: https://trust.qualtrics.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/qualtrics-trust-center.yml\ntrust_center:\n  url: https://trust.qualtrics.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: Qualtrics XM platform\n  period: '2024'\n  issuer: null\n  report_access: nda\n  text: Qualtrics' SOC 2 Type II report for 2024 is now available to approved users within our Trust Center.\n- framework: ISO42001\n  type: ISO 42001 certification\n  scope: AI management systems\n  period: null\n  issuer: null\n  report_access: public\n  text: Qualtrics\
  \ is pleased to announce that we have officially achieved the ISO 42001 certification for our AI\n    management systems.\n- framework: FedRAMP\n  type: FedRAMP High authorization\n  scope: Qualtrics XM platform\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Access is limited to eligible government agencies and is subject to verification. Public sector customers\n    may request access to the Qualtrics FedRAMP High security package here\n- framework: other\n  type: DISA IL4 Provisional Authorization\n  scope: Qualtrics XM platform\n  period: null\n  issuer: Defense Information Systems Agency (DISA)\n  report_access: unstated\n  text: Qualtrics has secured Impact Level 4 (IL4) Provisional Authorization from the Defense Information Systems\n    Agency (DISA) for the Qualtrics XM platform.\n- framework: other\n  type: GovRAMP Authorized status\n  scope: Qualtrics XM Platform, High security impact level\n  period: FY2026\n  issuer: GovRAMP Program Management Office (PMO)\n\
  \  report_access: on_request\n  text: Qualtrics is pleased to announce our GovRAMP Authorized status for FY2026, granted by the GovRAMP Program\n    Management Office (PMO) and the GovRAMP Approvals Committee\n- framework: ISO27001\n  type: ISO 27001 certificate\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001 Cert - 2030 Expiry pdf\n- framework: ISO27017\n  type: ISO 27017 certificate\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27017 Cert - 2030 Expiry pdf\n- framework: ISO27018\n  type: ISO 27018 certificate\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27018 Cert - 2030 Expiry pdf\n- framework: ISO27701\n  type: ISO 27701 certificate\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27701 Cert - 2028 Expiry pdf\n- framework: PCI-DSS\n  type: PCI DSS Attestation of Compliance\n  scope: null\n  period: '''25'\n  issuer: null\n\
  \  report_access: unstated\n  text: PCI DSS AOC '25\n- framework: HITRUST\n  type: HITRUST certification letter\n  scope: null\n  period: '''25'\n  issuer: null\n  report_access: unstated\n  text: HITRUST Certification Letter '25 pdf\n- framework: TISAX\n  type: TISAX certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Qualtrics TISAX Certification SIG Core '25\n- framework: CyberEssentials\n  type: Cyber Essentials certificate\n  scope: null\n  period: Dec. '25\n  issuer: null\n  report_access: unstated\n  text: Cyber Essentials Certificate Dec. '25\n- framework: IRAP\n  type: IRAP compliance letter\n  scope: Qualtrics XM\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Qualtrics XM IRAP Compliance Letter\n- framework: GDPR\n  type: GDPR certification listed\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Certifications & Compliance SOC 2 Type II GDPR PCI CCPA Cyber Essentials HITRUST TISAX\
  \ TX-RAMP GovRAMP FedRAMP\n    High ISO 42001\n"
source_yaml_url: https://artifacts.apis.io/qualtrics/compliance/qualtrics-compliance.yml
stated_fields:
- attestations
summary_line: 15 quoted statements, read from Qualtrics's own page on 2026-11-10.
synthetic: false
tags:
- Experience Management
- Surveys
- Customer Experience
- Employee Experience
- Market Research
- XM
- REST API
---
