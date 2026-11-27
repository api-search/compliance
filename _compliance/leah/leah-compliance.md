---
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC3
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC Type 3 report
    type: SOC Type 3 report
  - framework: HIPAA
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: HIPAA/HITECH report (upon request)
    type: HIPAA/HITECH report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR report
    type: GDPR report
  - framework: TISAX
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: TISAX Report
    type: TISAX Report
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO Certificate
    type: ISO certificate
  trust_center:
    url: https://leahai.com/trust-portal
frameworks:
- GDPR
- HIPAA
- SOC3
- TISAX
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Leah
provenance_date: '2026-11-09'
provider_name: Leah
provider_slug: leah
slug: leah-compliance
source_date: '2026-11-09'
source_filename: leah-compliance.yml
source_heading: Compliance
source_page: https://leahai.com/trust-portal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Leah\naid: leah\nurl: https://leahai.com/trust-portal\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/leah-trust-center.yml\ntrust_center:\n  url: https://leahai.com/trust-portal\nattestations:\n- framework: SOC3\n  type: SOC Type 3 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC Type 3 report\n- framework: HIPAA\n  type: HIPAA/HITECH report\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: HIPAA/HITECH report (upon request)\n- framework: GDPR\n  type: GDPR report\n  scope: null\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: GDPR report\n- framework: TISAX\n  type: TISAX Report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: TISAX Report\n- framework: other\n  type: ISO certificate\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO Certificate\n"
source_yaml_url: https://artifacts.apis.io/leah/compliance/leah-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Leah's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Contract Lifecycle Management
- Legal
- Legal Tech
- Procurement
- Source-to-Pay
- Finance
- Enterprise Software
---
