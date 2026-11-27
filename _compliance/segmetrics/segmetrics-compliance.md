---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Platform
    text: SegMetrics is not currently operating as a HIPAA Business Associate and does not have any active Business Associate Agreements (BAAs) in place.
    type: not certified
  - framework: other
    issuer: infrastructure providers
    period: null
    report_access: unstated
    scope: key infrastructure providers
    text: We rely on the attestations of our key infrastructure providers — the certifications each holds are listed alongside them in our subprocessor list at segmetrics.io/subprocessors/ .
    type: subprocessor attestations
  trust_center:
    url: https://segmetrics.io/security/
frameworks:
- HIPAA
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: SegMetrics
provenance_date: '2026-11-10'
provider_name: SegMetrics
provider_slug: segmetrics
slug: segmetrics-compliance
source_date: '2026-11-10'
source_filename: segmetrics-compliance.yml
source_heading: Compliance
source_page: https://segmetrics.io/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: SegMetrics\naid: segmetrics\nurl: https://segmetrics.io/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://segmetrics.io/security/\nattestations:\n- framework: HIPAA\n  type: not certified\n  scope: Platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SegMetrics is not currently operating as a HIPAA Business Associate and does not have any active Business\n    Associate Agreements (BAAs) in place.\n- framework: other\n  type: subprocessor attestations\n  scope: key infrastructure providers\n  period: null\n  issuer: infrastructure providers\n  report_access: unstated\n\
  \  text: We rely on the attestations of our key infrastructure providers — the certifications each holds are listed\n    alongside them in our subprocessor list at segmetrics.io/subprocessors/ .\n"
source_yaml_url: https://artifacts.apis.io/segmetrics/compliance/segmetrics-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from SegMetrics's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketing
- Analytics
- Attribution
- Marketing Analytics
- Reporting
- Business Intelligence
- Advertising
- Software-as-a-Service
- MCP
---
