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
    text: Get the vendor-review packet. SOC 2 report, DPA template, BAA template, security architecture doc, and a pre-filled CAIQ.
    type: SOC 2 Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: GDPR DPA available
    type: DPA available
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA Compliant
    type: Compliant
  - framework: HIPAA
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: HIPAA BAA available
    type: BAA available
  trust_center:
    url: https://contently.com/trust/security/
frameworks:
- CCPA
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Contently
provenance_date: '2026-11-09'
provider_name: Contently
provider_slug: contently
slug: contently-compliance
source_date: '2026-11-09'
source_filename: contently-compliance.yml
source_heading: Compliance
source_page: https://contently.com/trust/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Contently\naid: contently\nurl: https://contently.com/trust/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://contently.com/trust/security/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: Get the vendor-review packet. SOC 2 report, DPA template, BAA template, security architecture doc, and a\n    pre-filled CAIQ.\n- framework: GDPR\n  type: DPA available\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: GDPR DPA available\n- framework: CCPA\n  type: Compliant\n  scope: null\n\
  \  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA Compliant\n- framework: HIPAA\n  type: BAA available\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: HIPAA BAA available\n"
source_yaml_url: https://artifacts.apis.io/contently/compliance/contently-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Contently's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Content Marketing
- Talent Marketplace
- Freelance
- Content Creation
- Publishing
- Editorial Workflow
- Regulated Content
- Compliance
---
