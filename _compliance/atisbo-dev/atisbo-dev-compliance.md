---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: Supabase and Vercel
    period: null
    report_access: unstated
    scope: Supabase and Vercel platforms, not Atisbo
    text: Atisbo has not completed an independent SOC 2 audit of its own.
    type: Type II report held by infrastructure providers
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Atisbo itself
    text: No independent SOC 2 audit of Atisbo itself.
    type: Independent audit of Atisbo
  trust_center:
    url: https://app.atisbo.dev/security
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: atisbo-dev
provenance_date: '2026-11-09'
provider_name: atisbo-dev
provider_slug: atisbo-dev
slug: atisbo-dev-compliance
source_date: '2026-11-09'
source_filename: atisbo-dev-compliance.yml
source_heading: Compliance
source_page: https://app.atisbo.dev/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: atisbo-dev\naid: atisbo-dev\nurl: https://app.atisbo.dev/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://app.atisbo.dev/security\nattestations:\n- framework: SOC2\n  type: Type II report held by infrastructure providers\n  scope: Supabase and Vercel platforms, not Atisbo\n  period: null\n  issuer: Supabase and Vercel\n  report_access: unstated\n  text: Atisbo has not completed an independent SOC 2 audit of its own.\n- framework: SOC2\n  type: Independent audit of Atisbo\n  scope: Atisbo itself\n  period: null\n  issuer: null\n  report_access: unstated\n  text: No independent SOC 2 audit of Atisbo\
  \ itself.\n"
source_yaml_url: https://artifacts.apis.io/atisbo-dev/compliance/atisbo-dev-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from atisbo-dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Product Management
- Evidence
- Decision Support
- Artificial Intelligence
---
