---
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: PagerTree policies align with SOC 2 (page wording)
    text: These policies are reviewed at least annually and align with SOC 2, ISO 27001, and industry best practices.
    type: unstated
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: PagerTree policies align with ISO 27001 (page wording)
    text: These policies are reviewed at least annually and align with SOC 2, ISO 27001, and industry best practices.
    type: unstated
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: Stripe payments provider certified to PCI Service Provider Level 1 (third party, not PagerTree)
    text: Our payments provider, Stripe, has been audited by a PCI-certified auditor and is certified to PCI Service Provider Level 1.
    type: unstated
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Fly.io data centers demonstrate compliance with SOC2 Type 1 (hosting provider, not PagerTree)
    text: The data centers we use demonstrate ongoing compliance with rigorous international standards, such as SOC2 Type 1.
    type: unstated
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: PagerTree states it is GDPR compliant
    text: GDPR Compliant
    type: unstated
  trust_center:
    url: https://pagertree.com/security
frameworks:
- GDPR
- ISO27001
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: PagerTree
provenance_date: '2026-11-10'
provider_name: PagerTree
provider_slug: pagertree
slug: pagertree-compliance
source_date: '2026-11-10'
source_filename: pagertree-compliance.yml
source_heading: Compliance
source_page: https://pagertree.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: PagerTree\naid: pagertree\nurl: https://pagertree.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://pagertree.com/security\nattestations:\n- framework: SOC2\n  type: unstated\n  scope: PagerTree policies align with SOC 2 (page wording)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: These policies are reviewed at least annually and align with SOC 2, ISO 27001, and industry best practices.\n- framework: ISO27001\n  type: unstated\n  scope: PagerTree policies align with ISO 27001 (page wording)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: These policies\
  \ are reviewed at least annually and align with SOC 2, ISO 27001, and industry best practices.\n- framework: PCI-DSS\n  type: unstated\n  scope: Stripe payments provider certified to PCI Service Provider Level 1 (third party, not PagerTree)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our payments provider, Stripe, has been audited by a PCI-certified auditor and is certified to PCI Service\n    Provider Level 1.\n- framework: SOC2\n  type: unstated\n  scope: Fly.io data centers demonstrate compliance with SOC2 Type 1 (hosting provider, not PagerTree)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: The data centers we use demonstrate ongoing compliance with rigorous international standards, such as SOC2\n    Type 1.\n- framework: GDPR\n  type: unstated\n  scope: PagerTree states it is GDPR compliant\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR Compliant\n"
source_yaml_url: https://artifacts.apis.io/pagertree/compliance/pagertree-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from PagerTree's own page on 2026-11-10.
synthetic: false
tags:
- Company
---
