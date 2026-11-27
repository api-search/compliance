---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: security, availability, and confidentiality
    text: Independently audited controls for security, availability, and confidentiality.
    type: Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR compliant with all processing in the European Union
    type: null
  trust_center:
    url: https://www.vesence.com/security
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Vesence
provenance_date: '2026-11-10'
provider_name: Vesence
provider_slug: vesence
slug: vesence-compliance
source_date: '2026-11-10'
source_filename: vesence-compliance.yml
source_heading: Compliance
source_page: https://www.vesence.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Vesence\naid: vesence\nurl: https://www.vesence.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/vesence-trust-center.yml\ntrust_center:\n  url: https://www.vesence.com/security\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: security, availability, and confidentiality\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Independently audited controls for security, availability, and confidentiality.\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR compliant with all processing in the European\
  \ Union\n"
source_yaml_url: https://artifacts.apis.io/vesence/compliance/vesence-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Vesence's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Legal Tech
- Professional Services
- Microsoft Office
- Document Automation
---
