---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Embeddable platform
    text: Embeddable is SOC 2 Type II certified. Our SOC 2 report and independent penetration-test reports are available via trust.embeddable.com
    type: Type II certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Embeddable
    text: Embeddable is fully GDPR compliant.
    type: compliance statement
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.embeddable.com/
    text: SOC 2 Compliant
    type: compliance
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.embeddable.com/
    text: GDPR Compliant
    type: compliance
  trust_center:
    url: https://embeddable.com/security
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Embeddable
provenance_date: '2026-11-09'
provider_name: Embeddable
provider_slug: embeddable
slug: embeddable-compliance
source_date: '2026-11-09'
source_filename: embeddable-compliance.yml
source_heading: Compliance
source_page: https://embeddable.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Embeddable\naid: embeddable\nurl: https://embeddable.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/embeddable-trust-center.yml\n  sources:\n  - https://embeddable.com/security\n  - https://trust.embeddable.com/\ntrust_center:\n  url: https://embeddable.com/security\nattestations:\n- framework: SOC2\n  type: Type II certification\n  scope: Embeddable platform\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Embeddable is SOC 2 Type II certified. Our SOC 2 report and independent penetration-test reports are available\n    via trust.embeddable.com\n- framework: GDPR\n\
  \  type: compliance statement\n  scope: Embeddable\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Embeddable is fully GDPR compliant.\n- framework: SOC2\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Compliant\n  source: https://trust.embeddable.com/\n- framework: GDPR\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR Compliant\n  source: https://trust.embeddable.com/\n"
source_yaml_url: https://artifacts.apis.io/embeddable/compliance/embeddable-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Embeddable's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Analytics
- Embedded Analytics
- Business Intelligence
- Dashboards
- Data Visualization
- Semantic Layer
- Developer Tools
- Software-as-a-Service
---
