---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Brain Corp’s successful SOC 2 Type II examination validates our ongoing commitment to data protection.
    type: SOC 2 Type II examination
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Brain Corp integrates 'security by design' principles throughout its AI and software development, aligning with ISO 27001 standards.
    type: alignment
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Brain Corp is committed to helping customers understand their rights and obligations under the General Data Protection Regulation (GDPR).
    type: commitment
  trust_center:
    url: https://www.braincorp.com/security
frameworks:
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Brain Corp
provenance_date: '2026-11-09'
provider_name: Brain Corp
provider_slug: brain-corp
slug: brain-corp-compliance
source_date: '2026-11-09'
source_filename: brain-corp-compliance.yml
source_heading: Compliance
source_page: https://www.braincorp.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Brain Corp\naid: brain-corp\nurl: https://www.braincorp.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/brain-corp-trust-center.yml\ntrust_center:\n  url: https://www.braincorp.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II examination\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Brain Corp’s successful SOC 2 Type II examination validates our ongoing commitment to data protection.\n- framework: ISO27001\n  type: alignment\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Brain Corp integrates\
  \ 'security by design' principles throughout its AI and software development, aligning\n    with ISO 27001 standards.\n- framework: GDPR\n  type: commitment\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Brain Corp is committed to helping customers understand their rights and obligations under the General Data\n    Protection Regulation (GDPR).\n"
source_yaml_url: https://artifacts.apis.io/brain-corp/compliance/brain-corp-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Brain Corp's own page on 2026-11-09.
synthetic: false
tags:
- Autonomous Mobile Robots
- Autonomy
- BrainOS
- Cleaning Robots
- Floor Care
- Inventory
- RFID
- Retail Robotics
- Robotics
- Scanning as a Service
---
