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
    text: Compliance SOC 2 6 documents
    type: SOC 2 documents
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Compliance GDPR 1 document
    type: GDPR documents
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Compliance HIPAA SOC 2 GDPR CCPA
    type: compliance tag
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Compliance HIPAA SOC 2 GDPR CCPA
    type: compliance tag
  trust_center:
    url: https://trust.zight.com/
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
name: CloudApp
provenance_date: '2026-11-09'
provider_name: CloudApp
provider_slug: cloudapp
slug: cloudapp-compliance
source_date: '2026-11-09'
source_filename: cloudapp-compliance.yml
source_heading: Compliance
source_page: https://trust.zight.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: CloudApp\naid: cloudapp\nurl: https://trust.zight.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.zight.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 documents\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliance SOC 2 6 documents\n- framework: GDPR\n  type: GDPR documents\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliance GDPR 1 document\n- framework: HIPAA\n  type: compliance tag\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliance HIPAA SOC 2 GDPR CCPA\n-\
  \ framework: CCPA\n  type: compliance tag\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliance HIPAA SOC 2 GDPR CCPA\n"
source_yaml_url: https://artifacts.apis.io/cloudapp/compliance/cloudapp-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from CloudApp's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
