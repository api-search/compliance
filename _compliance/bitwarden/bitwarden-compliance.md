---
api_specs:
- filename: bitwarden-collections-api-openapi.yml
  format: yaml
  label: Bitwarden Collections API
  slug: bitwarden-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitwarden/openapi/bitwarden-collections-api-openapi.yml
- filename: bitwarden-events-api-openapi.yml
  format: yaml
  label: Bitwarden Events API
  slug: bitwarden-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitwarden/openapi/bitwarden-events-api-openapi.yml
- filename: bitwarden-groups-api-openapi.yml
  format: yaml
  label: Bitwarden Groups API
  slug: bitwarden-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitwarden/openapi/bitwarden-groups-api-openapi.yml
- filename: bitwarden-members-api-openapi.yml
  format: yaml
  label: Bitwarden Members API
  slug: bitwarden-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitwarden/openapi/bitwarden-members-api-openapi.yml
- filename: bitwarden-organization-api-openapi.yml
  format: yaml
  label: Bitwarden Organization API
  slug: bitwarden-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitwarden/openapi/bitwarden-organization-api-openapi.yml
- filename: bitwarden-policies-api-openapi.yml
  format: yaml
  label: Bitwarden Policies API
  slug: bitwarden-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitwarden/openapi/bitwarden-policies-api-openapi.yml
claim_count: 7
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Bitwarden is ISO 27001 certified and in compliance with ISO 27001 control sets surrounding data security.
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Bitwarden is SOC2 Type II and SOC3 certified. SOC2 Reports available upon request.
    type: certification
  - framework: SOC3
    issuer: null
    period: null
    report_access: public
    scope: null
    text: Read the SOC3 report
    type: certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Bitwarden is HIPAA compliant and undergoes annual third-party audits for HIPAA Security Rule compliance.
    type: compliance
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Bitwarden complies with GDPR, current EU data protection rules, and EU Standard Contractual Clauses (SCCs).
    type: compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Bitwarden is compliant with the California Consumer Privacy Act (CCPA) and the California Privacy Rights Act (CPRA).
    type: compliance
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Bitwarden complies with the Data Privacy Framework (DPF), previously called Privacy Shield, which defines the safe transfer of personal data.
    type: compliance
  trust_center:
    url: https://bitwarden.com/compliance/
frameworks:
- CCPA
- GDPR
- HIPAA
- ISO27001
- SOC2
- SOC3
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Bitwarden
provenance_date: '2026-11-09'
provider_name: Bitwarden
provider_slug: bitwarden
slug: bitwarden-compliance
source_date: '2026-11-09'
source_filename: bitwarden-compliance.yml
source_heading: Compliance
source_page: https://bitwarden.com/compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Bitwarden\naid: bitwarden\nurl: https://bitwarden.com/compliance/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/bitwarden-trust-center.yml\ntrust_center:\n  url: https://bitwarden.com/compliance/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Bitwarden is ISO 27001 certified and in compliance with ISO 27001 control sets surrounding data security.\n- framework: SOC2\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Bitwarden is SOC2 Type II and\
  \ SOC3 certified. SOC2 Reports available upon request.\n- framework: SOC3\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: public\n  text: Read the SOC3 report\n- framework: HIPAA\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Bitwarden is HIPAA compliant and undergoes annual third-party audits for HIPAA Security Rule compliance.\n- framework: GDPR\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Bitwarden complies with GDPR, current EU data protection rules, and EU Standard Contractual Clauses (SCCs).\n- framework: CCPA\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Bitwarden is compliant with the California Consumer Privacy Act (CCPA) and the California Privacy Rights\n    Act (CPRA).\n- framework: other\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: Bitwarden complies with the Data Privacy Framework (DPF), previously called Privacy Shield, which defines\n    the safe transfer of personal data.\n"
source_yaml_url: https://artifacts.apis.io/bitwarden/compliance/bitwarden-compliance.yml
stated_fields:
- attestations
summary_line: 7 quoted statements, read from Bitwarden's own page on 2026-11-09.
synthetic: false
tags:
- Security
- Password Manager
- Open Source
- Vault
- Identity
- SCIM
---
