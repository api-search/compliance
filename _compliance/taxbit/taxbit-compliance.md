---
claim_count: 6
description: ''
doc:
  attestations:
  - framework: SOC1
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 1 Type 2
    type: Type 2
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type 2
    type: Type 2
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001:2022
    type: null
  - framework: ISO27701
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001, 27701, and 27017
    type: null
  - framework: ISO27017
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001, 27701, and 27017
    type: null
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: null
  trust_center:
    url: https://trust.taxbit.com/
frameworks:
- GDPR
- ISO27001
- ISO27017
- ISO27701
- SOC1
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: TaxBit
provenance_date: '2026-11-10'
provider_name: TaxBit
provider_slug: taxbit
slug: taxbit-compliance
source_date: '2026-11-10'
source_filename: taxbit-compliance.yml
source_heading: Compliance
source_page: https://trust.taxbit.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: TaxBit\naid: taxbit\nurl: https://trust.taxbit.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/taxbit-trust-center.yml\ntrust_center:\n  url: https://trust.taxbit.com/\nattestations:\n- framework: SOC1\n  type: Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 1 Type 2\n- framework: SOC2\n  type: Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2\n- framework: ISO27001\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022\n- framework: ISO27701\n\
  \  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001, 27701, and 27017\n- framework: ISO27017\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001, 27701, and 27017\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n"
source_yaml_url: https://artifacts.apis.io/taxbit/compliance/taxbit-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from TaxBit's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Tax
- Tax Compliance
- Information Reporting
- Digital Assets
- Cryptocurrency
- Accounting
- RegTech
---
