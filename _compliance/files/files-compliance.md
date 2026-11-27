---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: These include the independent SOC 2 Type II examination and our FedRAMP certification .
    type: SOC 2 Type II examination
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: These include the independent SOC 2 Type II examination and our FedRAMP certification .
    type: FedRAMP certification
  trust_center:
    url: https://www.files.com/compliance
frameworks:
- FedRAMP
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Files.com
provenance_date: '2026-11-09'
provider_name: Files.com
provider_slug: files
slug: files-compliance
source_date: '2026-11-09'
source_filename: files-compliance.yml
source_heading: Compliance
source_page: https://www.files.com/compliance
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Files.com\naid: files\nurl: https://www.files.com/compliance\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.files.com/compliance\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II examination\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: These include the independent SOC 2 Type II examination and our FedRAMP certification .\n- framework: FedRAMP\n  type: FedRAMP certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: These include the independent SOC 2 Type II examination and our FedRAMP certification .\n"
source_yaml_url: https://artifacts.apis.io/files/compliance/files-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Files.com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- File Transfer
- Cloud Storage
- Automation
- Security
---
