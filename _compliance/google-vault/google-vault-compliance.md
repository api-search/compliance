---
api_specs:
- filename: google-vault-matters-api-openapi.yml
  format: yaml
  label: Google Vault Matters API
  slug: google-vault-matters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-vault/openapi/google-vault-matters-api-openapi.yml
- filename: google-vault-operations-api-openapi.yml
  format: yaml
  label: Google Vault Operations API
  slug: google-vault-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-vault/openapi/google-vault-operations-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Google Workspace
    text: Meet compliance standards like HIPAA, FINRA, FedRAMP High, and DoD IL4.
    type: compliance standard mentioned
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: Google Workspace
    text: Meet compliance standards like HIPAA, FINRA, FedRAMP High, and DoD IL4.
    type: compliance standard mentioned
  trust_center:
    url: https://workspace.google.com/security/
frameworks:
- FedRAMP
- HIPAA
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Google Vault
provenance_date: '2026-11-09'
provider_name: Google Vault
provider_slug: google-vault
slug: google-vault-compliance
source_date: '2026-11-09'
source_filename: google-vault-compliance.yml
source_heading: Compliance
source_page: https://workspace.google.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Google Vault\naid: google-vault\nurl: https://workspace.google.com/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/google-vault-trust-center.yml\ntrust_center:\n  url: https://workspace.google.com/security/\nattestations:\n- framework: HIPAA\n  type: compliance standard mentioned\n  scope: Google Workspace\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Meet compliance standards like HIPAA, FINRA, FedRAMP High, and DoD IL4.\n- framework: FedRAMP\n  type: compliance standard mentioned\n  scope: Google Workspace\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: Meet compliance standards like HIPAA, FINRA, FedRAMP High, and DoD IL4.\n"
source_yaml_url: https://artifacts.apis.io/google-vault/compliance/google-vault-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Google Vault's own page on 2026-11-09.
synthetic: false
tags:
- eDiscovery
- Legal Hold
- Information Governance
- Compliance
- Archiving
- Retention
- Google Workspace
- Audit
---
