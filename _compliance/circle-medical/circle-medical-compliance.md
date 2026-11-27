---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Patient names in reviews
    text: Full names have been changed in compliance with federal patient privacy laws.
    type: Compliance statement on patient-name changes
  trust_center:
    url: https://www.circlemedical.com/legal/notice-of-hipaa-privacy-practices
frameworks:
- HIPAA
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Circle Medical
provenance_date: '2026-11-09'
provider_name: Circle Medical
provider_slug: circle-medical
slug: circle-medical-compliance
source_date: '2026-11-09'
source_filename: circle-medical-compliance.yml
source_heading: Compliance
source_page: https://www.circlemedical.com/legal/notice-of-hipaa-privacy-practices
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Circle Medical\naid: circle-medical\nurl: https://www.circlemedical.com/legal/notice-of-hipaa-privacy-practices\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.circlemedical.com/legal/notice-of-hipaa-privacy-practices\nattestations:\n- framework: HIPAA\n  type: Compliance statement on patient-name changes\n  scope: Patient names in reviews\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Full names have been changed in compliance with federal patient privacy laws.\n"
source_yaml_url: https://artifacts.apis.io/circle-medical/compliance/circle-medical-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Circle Medical's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Telehealth
- Primary Care
- Digital Health
- HIPAA
---
