---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: 'AICPA TSPs: Security, Availability, Processing Integrity, Confidentiality, and Privacy'
    text: 'Quartet is within the reporting period of its SOC-2 certification for the following AICPA TSPs: Security, Availability, Processing Integrity, Confidentiality, and Privacy.'
    type: SOC 2 Type report
  - framework: HIPAA
    issuer: external audit firm
    period: null
    report_access: unstated
    scope: null
    text: Quartet has undergone a HIPAA Risk Assessment conducted by an external audit firm.
    type: HIPAA Risk Assessment
  trust_center:
    url: https://www.quartethealth.com/security/
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Quartet Health
provenance_date: '2026-11-10'
provider_name: Quartet Health
provider_slug: quartet
slug: quartet-compliance
source_date: '2026-11-10'
source_filename: quartet-compliance.yml
source_heading: Compliance
source_page: https://www.quartethealth.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Quartet Health\naid: quartet\nurl: https://www.quartethealth.com/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.quartethealth.com/security/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type report\n  scope: 'AICPA TSPs: Security, Availability, Processing Integrity, Confidentiality, and Privacy'\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'Quartet is within the reporting period of its SOC-2 certification for the following AICPA TSPs: Security,\n    Availability, Processing Integrity, Confidentiality, and Privacy.'\n- framework: HIPAA\n  type: HIPAA Risk Assessment\n\
  \  scope: null\n  period: null\n  issuer: external audit firm\n  report_access: unstated\n  text: Quartet has undergone a HIPAA Risk Assessment conducted by an external audit firm.\n"
source_yaml_url: https://artifacts.apis.io/quartet/compliance/quartet-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Quartet Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Life Sciences
- Behavioral Health
- Mental Health
- Healthcare
- Care Coordination
- Value-Based Care
- Digital Health
---
