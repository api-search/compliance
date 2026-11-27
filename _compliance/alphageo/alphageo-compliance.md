---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent auditors
    period: null
    report_access: on_request
    scope: Security, Availability and Confidentiality Trust Principles
    text: AlphaGeo produces Service Organization Control (SOC 2) reports based on independent audits of its cloud-based data processing system.
    type: SOC 2 report based on independent audit
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: active controls
    text: GDPR 80 active controls
    type: active controls count
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: active controls
    text: CCPA 34 active controls
    type: active controls count
  trust_center:
    url: https://alphageo.ai/security/
frameworks:
- CCPA
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Alphageo
provenance_date: '2026-11-09'
provider_name: Alphageo
provider_slug: alphageo
slug: alphageo-compliance
source_date: '2026-11-09'
source_filename: alphageo-compliance.yml
source_heading: Compliance
source_page: https://alphageo.ai/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Alphageo\naid: alphageo\nurl: https://alphageo.ai/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://alphageo.ai/security/\nattestations:\n- framework: SOC2\n  type: SOC 2 report based on independent audit\n  scope: Security, Availability and Confidentiality Trust Principles\n  period: null\n  issuer: independent auditors\n  report_access: on_request\n  text: AlphaGeo produces Service Organization Control (SOC 2) reports based on independent audits of its cloud-based\n    data processing system.\n- framework: GDPR\n  type: active controls count\n  scope: active controls\n  period: null\n  issuer:\
  \ null\n  report_access: unstated\n  text: GDPR 80 active controls\n- framework: CCPA\n  type: active controls count\n  scope: active controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA 34 active controls\n"
source_yaml_url: https://artifacts.apis.io/alphageo/compliance/alphageo-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Alphageo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Climate
- Climate Risk
- Geospatial
- Analytics
- Risk Management
- Real Estate
- ESG
- Data
- Machine Learning
---
