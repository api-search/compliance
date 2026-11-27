---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Compliant
    type: null
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA Compliant
    type: null
  trust_center:
    url: https://trust.simplehealthkit.com/
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Simple HealthKit
provenance_date: '2026-11-10'
provider_name: Simple HealthKit
provider_slug: simple-healthkit
slug: simple-healthkit-compliance
source_date: '2026-11-10'
source_filename: simple-healthkit-compliance.yml
source_heading: Compliance
source_page: https://trust.simplehealthkit.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Simple HealthKit\naid: simple-healthkit\nurl: https://trust.simplehealthkit.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/simple-healthkit-trust-center.yml\ntrust_center:\n  url: https://trust.simplehealthkit.com/\nattestations:\n- framework: SOC2\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Compliant\n- framework: HIPAA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA Compliant\n"
source_yaml_url: https://artifacts.apis.io/simple-healthkit/compliance/simple-healthkit-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Simple HealthKit's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
---
