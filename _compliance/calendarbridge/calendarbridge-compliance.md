---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: null
    text: SOC 2 Type 2 Compliant
    type: Type 2
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type 1 Compliant
    type: Type 1
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR Compliant
    type: null
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA Compliant
    type: null
  trust_center:
    url: https://trust.calendarbridge.com/
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: CalendarBridge
provenance_date: '2026-11-09'
provider_name: CalendarBridge
provider_slug: calendarbridge
slug: calendarbridge-compliance
source_date: '2026-11-09'
source_filename: calendarbridge-compliance.yml
source_heading: Compliance
source_page: https://trust.calendarbridge.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: CalendarBridge\naid: calendarbridge\nurl: https://trust.calendarbridge.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.calendarbridge.com/\nattestations:\n- framework: SOC2\n  type: Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: SOC 2 Type 2 Compliant\n- framework: SOC2\n  type: Type 1\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 1 Compliant\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR Compliant\n- framework: HIPAA\n  type: null\n\
  \  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA Compliant\n"
source_yaml_url: https://artifacts.apis.io/calendarbridge/compliance/calendarbridge-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from CalendarBridge's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Calendar
- Scheduling
- Integration
---
