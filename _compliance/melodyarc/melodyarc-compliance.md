---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: SOC 2 Type 2 Audited annually to ensure our systems meet strict trust and security standards.
    type: SOC 2 Type 2 audit
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We safeguard health data per HIPAA’s privacy and security requirements.
    type: HIPAA compliance
  trust_center:
    url: https://melodyarc.secureframetrust.com/
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: MelodyArc
provenance_date: '2026-11-10'
provider_name: MelodyArc
provider_slug: melodyarc
slug: melodyarc-compliance
source_date: '2026-11-10'
source_filename: melodyarc-compliance.yml
source_heading: Compliance
source_page: https://melodyarc.secureframetrust.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: MelodyArc\naid: melodyarc\nurl: https://melodyarc.secureframetrust.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://melodyarc.secureframetrust.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 audit\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Type 2 Audited annually to ensure our systems meet strict trust and security standards.\n- framework: HIPAA\n  type: HIPAA compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We safeguard health data per HIPAA’s privacy and security requirements.\n"
source_yaml_url: https://artifacts.apis.io/melodyarc/compliance/melodyarc-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from MelodyArc's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Workflow Automation
- Orchestration
- AI Agents
- Governance
- Enterprise
- Human-in-the-Loop
---
