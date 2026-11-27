---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Steno data and products covered by security controls
    text: If you would like to access our SOC 2 Type II or HIPAA report, please select the document you would like, and we can grant you access to download it.
    type: Type II report
  - framework: HIPAA
    issuer: null
    period: null
    report_access: on_request
    scope: Steno data and products covered by security controls
    text: Both are covered by the same security controls as all other data within Steno, including our SOC 2 Type II and HIPAA compliance.
    type: HIPAA compliance
  - framework: SOC2
    issuer: Linford & Company LLP
    period: null
    report_access: unstated
    scope: Steno Connect, the Firm Dashboard, and Ops
    source: https://brief.steno.com/soc2-hipaa-compliance
    text: we have been audited and demonstrated compliance with System and Organization Controls (SOC) 2 Type II and the Health Insurance Portability and Accountability Act of 1996 (HIPAA)
    type: SOC 2 Type II audit
  - framework: HIPAA
    issuer: Linford & Company LLP
    period: null
    report_access: unstated
    scope: Steno Connect, the Firm Dashboard, and Ops
    source: https://brief.steno.com/soc2-hipaa-compliance
    text: Steno’s technology offerings were found to be in compliance with SOC 2 Type II and HIPAA requirements.
    type: HIPAA compliance assessment
  trust_center:
    url: https://trust.steno.com/
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Steno
provenance_date: '2026-11-10'
provider_name: Steno
provider_slug: steno
slug: steno-compliance
source_date: '2026-11-10'
source_filename: steno-compliance.yml
source_heading: Compliance
source_page: https://trust.steno.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Steno\naid: steno\nurl: https://trust.steno.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://brief.steno.com/soc2-hipaa-compliance\n  - https://trust.steno.com/\ntrust_center:\n  url: https://trust.steno.com/\nattestations:\n- framework: SOC2\n  type: Type II report\n  scope: Steno data and products covered by security controls\n  period: null\n  issuer: null\n  report_access: on_request\n  text: If you would like to access our SOC 2 Type II or HIPAA report, please select the document you would like,\n    and we can grant you access to download it.\n- framework: HIPAA\n  type: HIPAA compliance\n  scope:\
  \ Steno data and products covered by security controls\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Both are covered by the same security controls as all other data within Steno, including our SOC 2 Type\n    II and HIPAA compliance.\n- framework: SOC2\n  type: SOC 2 Type II audit\n  scope: Steno Connect, the Firm Dashboard, and Ops\n  period: null\n  issuer: Linford & Company LLP\n  report_access: unstated\n  text: we have been audited and demonstrated compliance with System and Organization Controls (SOC) 2 Type II and\n    the Health Insurance Portability and Accountability Act of 1996 (HIPAA)\n  source: https://brief.steno.com/soc2-hipaa-compliance\n- framework: HIPAA\n  type: HIPAA compliance assessment\n  scope: Steno Connect, the Firm Dashboard, and Ops\n  period: null\n  issuer: Linford & Company LLP\n  report_access: unstated\n  text: Steno’s technology offerings were found to be in compliance with SOC 2 Type II and HIPAA requirements.\n  source: https://brief.steno.com/soc2-hipaa-compliance\n"
source_yaml_url: https://artifacts.apis.io/steno/compliance/steno-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Steno's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Legal
- Legal Tech
- Court Reporting
- Depositions
- Litigation Support
- Transcription
- Video
- Artificial Intelligence
- Salesforce
---
