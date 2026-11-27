---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: third-party auditor
    period: null
    report_access: on_request
    scope: platform security, confidentiality and availability controls
    text: Rewst has achieved SOC 2 Type 2 compliance.
    type: SOC 2 Type 2
  - framework: GDPR
    issuer: third-party auditor
    period: null
    report_access: unstated
    scope: data protection and privacy regulations
    text: Rewst is GDPR compliant and has been audited by a third-party to verify our compliance with these data protection and privacy regulations.
    type: GDPR compliance audit
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: null
    source: https://rewst.io/trust-center
    text: After signing an NDA, you will be able to access our SOC 2 Report and additional information security program resources.
    type: SOC 2 report
  trust_center:
    url: https://rewst.io/security
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Rewst
provenance_date: '2026-11-10'
provider_name: Rewst
provider_slug: rewst
slug: rewst-compliance
source_date: '2026-11-10'
source_filename: rewst-compliance.yml
source_heading: Compliance
source_page: https://rewst.io/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Rewst\naid: rewst\nurl: https://rewst.io/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/rewst-trust-center.yml\n  sources:\n  - https://rewst.io/security\n  - https://rewst.io/trust-center\ntrust_center:\n  url: https://rewst.io/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2\n  scope: platform security, confidentiality and availability controls\n  period: null\n  issuer: third-party auditor\n  report_access: on_request\n  text: Rewst has achieved SOC 2 Type 2 compliance.\n- framework: GDPR\n  type: GDPR compliance audit\n  scope: data protection and privacy regulations\n\
  \  period: null\n  issuer: third-party auditor\n  report_access: unstated\n  text: Rewst is GDPR compliant and has been audited by a third-party to verify our compliance with these data protection\n    and privacy regulations.\n- framework: SOC2\n  type: SOC 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: After signing an NDA, you will be able to access our SOC 2 Report and additional information security program\n    resources.\n  source: https://rewst.io/trust-center\n"
source_yaml_url: https://artifacts.apis.io/rewst/compliance/rewst-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Rewst's own page on 2026-11-10.
synthetic: false
tags:
- Company
- DevOps
- Automation
- iPaaS
- RPA
- Workflow Automation
- MSP
- Integration
- Webhook
---
