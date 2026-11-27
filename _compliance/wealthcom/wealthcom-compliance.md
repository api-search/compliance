---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent CPA
    period: null
    report_access: unstated
    scope: security
    text: We have undergone a Service Organization Control 2 (SOC 2) Type 2 audit, resulting in an independent CPA’s report and certification.
    type: SOC 2 Type 2 audit
  - framework: SOC2
    issuer: null
    period: yearly
    report_access: unstated
    scope: security, availability, confidentiality, privacy and processing integrity
    text: Our SOC 2 compliance means that Wealth is audited against five Trust Services Criteria yearly, comprising security, availability, confidentiality, privacy and processing integrity.
    type: SOC 2 Type 2
  trust_center:
    url: https://www.wealth.com/privacy-and-security/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Wealth.com
provenance_date: '2026-11-10'
provider_name: Wealth.com
provider_slug: wealthcom
slug: wealthcom-compliance
source_date: '2026-11-10'
source_filename: wealthcom-compliance.yml
source_heading: Compliance
source_page: https://www.wealth.com/privacy-and-security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Wealth.com\naid: wealthcom\nurl: https://www.wealth.com/privacy-and-security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/wealthcom-trust-center.yml\ntrust_center:\n  url: https://www.wealth.com/privacy-and-security/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 audit\n  scope: security\n  period: null\n  issuer: independent CPA\n  report_access: unstated\n  text: We have undergone a Service Organization Control 2 (SOC 2) Type 2 audit, resulting in an independent CPA’s\n    report and certification.\n- framework: SOC2\n  type: SOC 2 Type 2\n  scope: security, availability, confidentiality,\
  \ privacy and processing integrity\n  period: yearly\n  issuer: null\n  report_access: unstated\n  text: Our SOC 2 compliance means that Wealth is audited against five Trust Services Criteria yearly, comprising\n    security, availability, confidentiality, privacy and processing integrity.\n"
source_yaml_url: https://artifacts.apis.io/wealthcom/compliance/wealthcom-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Wealth.com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise
- Estate Planning
- Tax Planning
- Wealth Management
- Financial Advisors
- Fintech
- Artificial Intelligence
---
