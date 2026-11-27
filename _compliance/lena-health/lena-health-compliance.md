---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: 2025_SOC 2 Type I_Lena Health_Final Report
    type: SOC 2 Type I
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II report
    type: SOC 2 Type II
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://lena.io/llms.txt
    text: SOC 2 Type II Certified
    type: SOC 2 Type II certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://lena.io/llms.txt
    text: HIPAA Compliant
    type: HIPAA compliance
  trust_center:
    url: https://trust.lenaconnect.com/
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Lena Health
provenance_date: '2026-11-09'
provider_name: Lena Health
provider_slug: lena-health
slug: lena-health-compliance
source_date: '2026-11-09'
source_filename: lena-health-compliance.yml
source_heading: Compliance
source_page: https://trust.lenaconnect.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Lena Health\naid: lena-health\nurl: https://trust.lenaconnect.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/lena-health-trust-center.yml\n  sources:\n  - https://lena.io/llms.txt\n  - https://trust.lenaconnect.com/\ntrust_center:\n  url: https://trust.lenaconnect.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type I\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 2025_SOC 2 Type I_Lena Health_Final Report\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II report\n\
  - framework: SOC2\n  type: SOC 2 Type II certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II Certified\n  source: https://lena.io/llms.txt\n- framework: HIPAA\n  type: HIPAA compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA Compliant\n  source: https://lena.io/llms.txt\n"
source_yaml_url: https://artifacts.apis.io/lena-health/compliance/lena-health-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Lena Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Health Care Coordination
- Care Navigation
- Artificial Intelligence
- Patient Engagement
- Chronic Care Management
- Health Plans
- Digital Health
- HIPAA
---
