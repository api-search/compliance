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
    text: backed by SOC 2 Type II
    type: SOC 2 Type II
  - framework: ISO42001
    issuer: null
    period: null
    report_access: unstated
    scope: Artificial Intelligence Management System
    text: ISO/IEC 42001-certified Artificial Intelligence Management System
    type: certification
  trust_center:
    url: https://www.augmentcode.com/security
frameworks:
- ISO42001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Augment Code
provenance_date: '2026-11-09'
provider_name: Augment Code
provider_slug: augment-code
slug: augment-code-compliance
source_date: '2026-11-09'
source_filename: augment-code-compliance.yml
source_heading: Compliance
source_page: https://www.augmentcode.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Augment Code\naid: augment-code\nurl: https://www.augmentcode.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/augment-code-trust-center.yml\ntrust_center:\n  url: https://www.augmentcode.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: backed by SOC 2 Type II\n- framework: ISO42001\n  type: certification\n  scope: Artificial Intelligence Management System\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO/IEC 42001-certified Artificial Intelligence Management System\n"
source_yaml_url: https://artifacts.apis.io/augment-code/compliance/augment-code-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Augment Code's own page on 2026-11-09.
synthetic: false
tags:
- AI Coding Agents
- Context Engine
- IDE Plugin
- Cosmos
- Auggie CLI
- Software Engineering
---
