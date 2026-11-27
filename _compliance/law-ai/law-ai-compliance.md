---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: null
    text: SOC 2 report (under NDA)
    type: SOC 2 report
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA/CPRA compliant
    type: compliance statement
  trust_center:
    url: https://law.ai/security
frameworks:
- CCPA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: law-ai
provenance_date: '2026-11-09'
provider_name: law-ai
provider_slug: law-ai
slug: law-ai-compliance
source_date: '2026-11-09'
source_filename: law-ai-compliance.yml
source_heading: Compliance
source_page: https://law.ai/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: law-ai\naid: law-ai\nurl: https://law.ai/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://law.ai/security\nattestations:\n- framework: SOC2\n  type: SOC 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: SOC 2 report (under NDA)\n- framework: CCPA\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA/CPRA compliant\n"
source_yaml_url: https://artifacts.apis.io/law-ai/compliance/law-ai-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from law-ai's own page on 2026-11-09.
synthetic: false
tags:
- Legal Tech
- Artificial Intelligence
- Law
- Directory
- Marketplace
---
