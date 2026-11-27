---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: third-party auditor
    period: Annual third-party audits
    report_access: nda
    scope: platform
    text: Annual third-party audits with continuous control monitoring. Full reports and letters of attestation available under NDA.
    type: SOC 2 Type II
  trust_center:
    url: https://nextmatter.com/security
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Next Matter
provenance_date: '2026-11-10'
provider_name: Next Matter
provider_slug: next-matter
slug: next-matter-compliance
source_date: '2026-11-10'
source_filename: next-matter-compliance.yml
source_heading: Compliance
source_page: https://nextmatter.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Next Matter\naid: next-matter\nurl: https://nextmatter.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://nextmatter.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: platform\n  period: Annual third-party audits\n  issuer: third-party auditor\n  report_access: nda\n  text: Annual third-party audits with continuous control monitoring. Full reports and letters of attestation available\n    under NDA.\n"
source_yaml_url: https://artifacts.apis.io/next-matter/compliance/next-matter-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Next Matter's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Automation
- Workflows
- Integration
- Software-as-a-Service
---
