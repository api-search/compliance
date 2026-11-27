---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Feroot Security
    text: SOC 2 Type II
    type: Type II report
  - framework: PCI-DSS
    issuer: null
    period: '2026'
    report_access: unstated
    scope: Feroot Security
    text: PCI-DSS-v4-0-1-SAQ-D AoC 2026
    type: SAQ D attestation of compliance
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: unstated
    source: https://www.feroot.com/llms.txt
    text: SOC 2 Type 2 certified
    type: Type 2 certification
  trust_center:
    url: https://trust.feroot.com/
frameworks:
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Feroot
provenance_date: '2026-11-09'
provider_name: Feroot
provider_slug: feroot
slug: feroot-compliance
source_date: '2026-11-09'
source_filename: feroot-compliance.yml
source_heading: Compliance
source_page: https://trust.feroot.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Feroot\naid: feroot\nurl: https://trust.feroot.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/feroot-trust-center.yml\n  sources:\n  - https://trust.feroot.com/\n  - https://www.feroot.com/llms.txt\ntrust_center:\n  url: https://trust.feroot.com/\nattestations:\n- framework: SOC2\n  type: Type II report\n  scope: Feroot Security\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II\n- framework: PCI-DSS\n  type: SAQ D attestation of compliance\n  scope: Feroot Security\n  period: '2026'\n  issuer: null\n  report_access: unstated\n  text: PCI-DSS-v4-0-1-SAQ-D AoC 2026\n\
  - framework: SOC2\n  type: Type 2 certification\n  scope: unstated\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2 certified\n  source: https://www.feroot.com/llms.txt\n"
source_yaml_url: https://artifacts.apis.io/feroot/compliance/feroot-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Feroot's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Client-Side Security
- Application Security
- Compliance
- PCI DSS
- Privacy
- JavaScript Security
---
