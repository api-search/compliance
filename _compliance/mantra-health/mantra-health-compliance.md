---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: handling of Protected Health Information related to student health records, medical research collaborations and other university-related healthcare data
    text: We adhere to the national standard for handling Protected Health Information (PHI) related to student health records
    type: regulatory adherence
  - framework: SOC1
    issuer: null
    period: null
    report_access: unstated
    scope: security, availability, processing integrity, confidentiality, and privacy controls
    text: SOC-I & SOC-II
    type: external audit
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: security, availability, processing integrity, confidentiality, and privacy controls
    text: Mantra has undergone a rigorous external audit, in which our security, availability, processing integrity, confidentiality, and privacy controls have been assessed and approved.
    type: external audit
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: state-specific security requirements for higher education institutions and state agencies in Texas
    text: including the TX RMP security framework which is mandated for higher education institutions and state agencies in Texas
    type: state security framework alignment (TX-RAMP)
  trust_center:
    url: https://mantrahealth.com/security-and-privacy/
frameworks:
- HIPAA
- SOC1
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Mantra Health
provenance_date: '2026-11-10'
provider_name: Mantra Health
provider_slug: mantra-health
slug: mantra-health-compliance
source_date: '2026-11-10'
source_filename: mantra-health-compliance.yml
source_heading: Compliance
source_page: https://mantrahealth.com/security-and-privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Mantra Health\naid: mantra-health\nurl: https://mantrahealth.com/security-and-privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/mantra-health-trust-center.yml\ntrust_center:\n  url: https://mantrahealth.com/security-and-privacy/\nattestations:\n- framework: HIPAA\n  type: regulatory adherence\n  scope: handling of Protected Health Information related to student health records, medical research collaborations\n    and other university-related healthcare data\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We adhere to the national standard for handling Protected Health Information\
  \ (PHI) related to student health\n    records\n- framework: SOC1\n  type: external audit\n  scope: security, availability, processing integrity, confidentiality, and privacy controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC-I & SOC-II\n- framework: SOC2\n  type: external audit\n  scope: security, availability, processing integrity, confidentiality, and privacy controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Mantra has undergone a rigorous external audit, in which our security, availability, processing integrity,\n    confidentiality, and privacy controls have been assessed and approved.\n- framework: other\n  type: state security framework alignment (TX-RAMP)\n  scope: state-specific security requirements for higher education institutions and state agencies in Texas\n  period: null\n  issuer: null\n  report_access: unstated\n  text: including the TX RMP security framework which is mandated for higher education institutions and\
  \ state agencies\n    in Texas\n"
source_yaml_url: https://artifacts.apis.io/mantra-health/compliance/mantra-health-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Mantra Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Mental Health
- Telehealth
- Higher Education
- Digital Health
- Patient Engagement
- HIPAA
- GraphQL
---
