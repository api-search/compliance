---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: third-party independent auditors
    period: null
    report_access: unstated
    scope: cloud services security, availability, and confidentiality controls
    text: Fiix is subject to third-party, independent audits to meet SOC 2 Type 2 compliance standards
    type: Type 2 audit by third-party independent auditors
  - framework: ISO27001
    issuer: AWS
    period: null
    report_access: unstated
    scope: AWS infrastructure hosting Fiix servers
    text: AWS has achieved best-in-class security credentials, including ISO 27001 and SOC 2 Type 2.
    type: certification held by AWS hosting provider
  trust_center:
    url: https://fiixsoftware.com/security/
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Fiix Software
provenance_date: '2026-11-09'
provider_name: Fiix Software
provider_slug: fiix-software
slug: fiix-software-compliance
source_date: '2026-11-09'
source_filename: fiix-software-compliance.yml
source_heading: Compliance
source_page: https://fiixsoftware.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Fiix Software\naid: fiix-software\nurl: https://fiixsoftware.com/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://fiixsoftware.com/security/\nattestations:\n- framework: SOC2\n  type: Type 2 audit by third-party independent auditors\n  scope: cloud services security, availability, and confidentiality controls\n  period: null\n  issuer: third-party independent auditors\n  report_access: unstated\n  text: Fiix is subject to third-party, independent audits to meet SOC 2 Type 2 compliance standards\n- framework: ISO27001\n  type: certification held by AWS hosting provider\n  scope: AWS infrastructure\
  \ hosting Fiix servers\n  period: null\n  issuer: AWS\n  report_access: unstated\n  text: AWS has achieved best-in-class security credentials, including ISO 27001 and SOC 2 Type 2.\n"
source_yaml_url: https://artifacts.apis.io/fiix-software/compliance/fiix-software-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Fiix Software's own page on 2026-11-09.
synthetic: false
tags:
- CMMS
- Maintenance Management
- Asset Management
- Manufacturing
- Reliability
- Work Orders
- Software-as-a-Service
---
