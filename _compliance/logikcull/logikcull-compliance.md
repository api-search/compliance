---
api_specs:
- filename: logikcull
  format: yaml
  label: Logikcull API
  slug: logikcull-api
  spec_type: OpenAPI
  url: https://docs.revealdata.com/logikcull
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: data centers hosting customer files
    text: Your files live in SOC 2, HIPAA, and ISO 27001-compliant US and EU data centers with multiple availability zones and daily backups.
    type: compliance claim
  - framework: HIPAA
    issuer: null
    period: null
    report_access: on_request
    scope: data centers hosting customer files
    text: Your files live in SOC 2, HIPAA, and ISO 27001-compliant US and EU data centers with multiple availability zones and daily backups.
    type: compliance claim
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: data centers hosting customer files
    text: Your files live in SOC 2, HIPAA, and ISO 27001-compliant US and EU data centers with multiple availability zones and daily backups.
    type: compliance claim
  trust_center:
    url: https://www.logikcull.com/company/security
frameworks:
- HIPAA
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Logikcull
provenance_date: '2026-11-09'
provider_name: Logikcull
provider_slug: logikcull
slug: logikcull-compliance
source_date: '2026-11-09'
source_filename: logikcull-compliance.yml
source_heading: Compliance
source_page: https://www.logikcull.com/company/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Logikcull\naid: logikcull\nurl: https://www.logikcull.com/company/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/logikcull-trust-center.yml\ntrust_center:\n  url: https://www.logikcull.com/company/security\nattestations:\n- framework: SOC2\n  type: compliance claim\n  scope: data centers hosting customer files\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Your files live in SOC 2, HIPAA, and ISO 27001-compliant US and EU data centers with multiple availability\n    zones and daily backups.\n- framework: HIPAA\n  type: compliance claim\n  scope: data centers hosting\
  \ customer files\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Your files live in SOC 2, HIPAA, and ISO 27001-compliant US and EU data centers with multiple availability\n    zones and daily backups.\n- framework: ISO27001\n  type: compliance claim\n  scope: data centers hosting customer files\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Your files live in SOC 2, HIPAA, and ISO 27001-compliant US and EU data centers with multiple availability\n    zones and daily backups.\n"
source_yaml_url: https://artifacts.apis.io/logikcull/compliance/logikcull-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Logikcull's own page on 2026-11-09.
synthetic: false
tags:
- eDiscovery
- Legal
- Document Management
- Legal Hold
- Redaction
- Production Sets
- Cloud
---
