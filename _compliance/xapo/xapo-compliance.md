---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: other
    issuer: Big 4 firm (unnamed)
    period: null
    report_access: unstated
    scope: Financial statements of the entire balance sheet
    text: We partner with a Big 4 firm to conduct audits of our financial statements
    type: Financial statement audit
  - framework: other
    issuer: Gibraltar Financial Services Commission
    period: null
    report_access: unstated
    scope: Xapo Bank Limited, credit institution
    text: Xapo Bank is regulated by the Gibraltar Financial Services Commission (GFSC).
    type: Financial services regulation (GFSC)
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Global compliance
    text: 'Global Compliance: Adherence to strict AML (Anti-Money Laundering) and KYC (Know Your Customer) protocols.'
    type: AML and KYC protocols
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: personal data privacy
    source: https://www.xapobank.com/en/company/our-security-system
    text: Xapo Bank is legally bound to the highest global standards for data privacy, including GDPR
    type: regulatory obligation
  trust_center:
    url: https://www.xapobank.com/en/company/compliance
frameworks:
- GDPR
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Xapo
provenance_date: '2026-11-10'
provider_name: Xapo
provider_slug: xapo
slug: xapo-compliance
source_date: '2026-11-10'
source_filename: xapo-compliance.yml
source_heading: Compliance
source_page: https://www.xapobank.com/en/company/compliance
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Xapo\naid: xapo\nurl: https://www.xapobank.com/en/company/compliance\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/xapo-trust-center.yml\n  sources:\n  - https://www.xapobank.com/en/company/compliance\n  - https://www.xapobank.com/en/company/our-security-system\ntrust_center:\n  url: https://www.xapobank.com/en/company/compliance\nattestations:\n- framework: other\n  type: Financial statement audit\n  scope: Financial statements of the entire balance sheet\n  period: null\n  issuer: Big 4 firm (unnamed)\n  report_access: unstated\n  text: We partner with a Big 4 firm to conduct audits of our financial\
  \ statements\n- framework: other\n  type: Financial services regulation (GFSC)\n  scope: Xapo Bank Limited, credit institution\n  period: null\n  issuer: Gibraltar Financial Services Commission\n  report_access: unstated\n  text: Xapo Bank is regulated by the Gibraltar Financial Services Commission (GFSC).\n- framework: other\n  type: AML and KYC protocols\n  scope: Global compliance\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'Global Compliance: Adherence to strict AML (Anti-Money Laundering) and KYC (Know Your Customer) protocols.'\n- framework: GDPR\n  type: regulatory obligation\n  scope: personal data privacy\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Xapo Bank is legally bound to the highest global standards for data privacy, including GDPR\n  source: https://www.xapobank.com/en/company/our-security-system\n"
source_yaml_url: https://artifacts.apis.io/xapo/compliance/xapo-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Xapo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cryptocurrency
- Bitcoin
- Banking
- Custody
- Payments
- Wealth Management
- Fintech
---
