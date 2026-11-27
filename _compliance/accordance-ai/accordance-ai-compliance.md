---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent auditors
    period: annually
    report_access: unstated
    scope: restricted access to customer data
    text: Restricted access to your data is verified annually by independent auditors under SOC 2 standards.
    type: independent audit
  trust_center:
    url: https://accordance.com/security
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Accordance Ai
provenance_date: '2026-11-09'
provider_name: Accordance Ai
provider_slug: accordance-ai
slug: accordance-ai-compliance
source_date: '2026-11-09'
source_filename: accordance-ai-compliance.yml
source_heading: Compliance
source_page: https://accordance.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Accordance Ai\naid: accordance-ai\nurl: https://accordance.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/accordance-ai-trust-center.yml\ntrust_center:\n  url: https://accordance.com/security\nattestations:\n- framework: SOC2\n  type: independent audit\n  scope: restricted access to customer data\n  period: annually\n  issuer: independent auditors\n  report_access: unstated\n  text: Restricted access to your data is verified annually by independent auditors under SOC 2 standards.\n"
source_yaml_url: https://artifacts.apis.io/accordance-ai/compliance/accordance-ai-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Accordance Ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Tax
- Accounting
- Audit
- Agents
- Compliance
- Professional Services
---
