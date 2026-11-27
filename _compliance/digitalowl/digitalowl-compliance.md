---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: security, confidentiality, privacy and processing integrity
    text: SOC Type II Compliance standard based on security, confidentiality, privacy and processing integrity.
    type: SOC Type II
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: physical, network and process security measures to protect patient health information in the U.S.
    text: HIPAA Physical, network and process security measures to protect patient health information in the U.S.
    type: compliance
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: protection for European citizens
    text: GDPR Protection for European citizens from data loss due to cybercrime, terrorism, unethical business practices and more.
    type: compliance
  trust_center:
    url: https://www.digitalowl.com/trust
frameworks:
- GDPR
- HIPAA
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: DigitalOwl
provenance_date: '2026-11-09'
provider_name: DigitalOwl
provider_slug: digitalowl
slug: digitalowl-compliance
source_date: '2026-11-09'
source_filename: digitalowl-compliance.yml
source_heading: Compliance
source_page: https://www.digitalowl.com/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: DigitalOwl\naid: digitalowl\nurl: https://www.digitalowl.com/trust\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.digitalowl.com/trust\nattestations:\n- framework: other\n  type: SOC Type II\n  scope: security, confidentiality, privacy and processing integrity\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC Type II Compliance standard based on security, confidentiality, privacy and processing integrity.\n- framework: HIPAA\n  type: compliance\n  scope: physical, network and process security measures to protect patient health information in the U.S.\n  period: null\n  issuer:\
  \ null\n  report_access: unstated\n  text: HIPAA Physical, network and process security measures to protect patient health information in the U.S.\n- framework: GDPR\n  type: compliance\n  scope: protection for European citizens\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR Protection for European citizens from data loss due to cybercrime, terrorism, unethical business practices\n    and more.\n"
source_yaml_url: https://artifacts.apis.io/digitalowl/compliance/digitalowl-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from DigitalOwl's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Insurance
- Insurtech
- Medical Records
- Underwriting
- Claims
- Legal Tech
- Artificial Intelligence
- Data API
---
