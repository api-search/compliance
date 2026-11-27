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
    text: We’re SOC2 and HIPAA compliant
    type: compliance attestation
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We’re SOC2 and HIPAA compliant
    type: compliance attestation
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    source: https://trust.jellyvision.com/
    text: request access to our security documentation
    type: SOC 2
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.jellyvision.com/
    text: HIPAA
    type: HIPAA
  trust_center:
    url: https://www.jellyvision.com/security/
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Jellyvision
provenance_date: '2026-11-09'
provider_name: Jellyvision
provider_slug: jellyvision
slug: jellyvision-compliance
source_date: '2026-11-09'
source_filename: jellyvision-compliance.yml
source_heading: Compliance
source_page: https://www.jellyvision.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Jellyvision\naid: jellyvision\nurl: https://www.jellyvision.com/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/jellyvision-trust-center.yml\n  sources:\n  - https://trust.jellyvision.com/\n  - https://www.jellyvision.com/security/\ntrust_center:\n  url: https://www.jellyvision.com/security/\nattestations:\n- framework: SOC2\n  type: compliance attestation\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We’re SOC2 and HIPAA compliant\n- framework: HIPAA\n  type: compliance attestation\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: We’re SOC2 and HIPAA compliant\n- framework: SOC2\n  type: SOC 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: request access to our security documentation\n  source: https://trust.jellyvision.com/\n- framework: HIPAA\n  type: HIPAA\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA\n  source: https://trust.jellyvision.com/\n"
source_yaml_url: https://artifacts.apis.io/jellyvision/compliance/jellyvision-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Jellyvision's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Employee Benefits
- Human Resources
- Benefits Administration
- Benefits Enrollment
- Health Insurance
- Decision Support
- HR Technology
- Insurance
- Employee Engagement
---
