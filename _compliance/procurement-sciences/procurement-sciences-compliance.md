---
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Awarded AI platform
    text: SOC 2 Type II report
    type: SOC 2 Type 2
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Procurement Sciences platform
    text: maintaining CMMC Level 2 compliance
    type: CMMC Level 2 Assessed
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: Procurement Sciences platform
    text: FedRAMP® Moderate Authorization
    type: FedRAMP Moderate Authorization
  - framework: SOC2
    issuer: unstated
    period: '2025'
    report_access: on_request
    scope: unstated
    source: https://trust.procurementsciences.com/
    text: Request SOC 2 Type II 2025 Report
    type: SOC 2 Type II report
  - framework: FedRAMP
    issuer: unstated
    period: null
    report_access: on_request
    scope: unstated
    source: https://trust.procurementsciences.com/
    text: FedRAMP System Security Plan (SSP)
    type: FedRAMP System Security Plan (SSP)
  trust_center:
    url: https://www.procurementsciences.com/platform/security
frameworks:
- FedRAMP
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Procurement Sciences
provenance_date: '2026-11-10'
provider_name: Procurement Sciences
provider_slug: procurement-sciences
slug: procurement-sciences-compliance
source_date: '2026-11-10'
source_filename: procurement-sciences-compliance.yml
source_heading: Compliance
source_page: https://www.procurementsciences.com/platform/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Procurement Sciences\naid: procurement-sciences\nurl: https://www.procurementsciences.com/platform/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/procurement-sciences-trust-center.yml\n  sources:\n  - https://trust.procurementsciences.com/\n  - https://www.procurementsciences.com/platform/security\ntrust_center:\n  url: https://www.procurementsciences.com/platform/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2\n  scope: Awarded AI platform\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Type II report\n- framework: other\n  type: CMMC Level 2\
  \ Assessed\n  scope: Procurement Sciences platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: maintaining CMMC Level 2 compliance\n- framework: FedRAMP\n  type: FedRAMP Moderate Authorization\n  scope: Procurement Sciences platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: FedRAMP® Moderate Authorization\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: unstated\n  period: '2025'\n  issuer: unstated\n  report_access: on_request\n  text: Request SOC 2 Type II 2025 Report\n  source: https://trust.procurementsciences.com/\n- framework: FedRAMP\n  type: FedRAMP System Security Plan (SSP)\n  scope: unstated\n  period: null\n  issuer: unstated\n  report_access: on_request\n  text: FedRAMP System Security Plan (SSP)\n  source: https://trust.procurementsciences.com/\n"
source_yaml_url: https://artifacts.apis.io/procurement-sciences/compliance/procurement-sciences-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Procurement Sciences's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cloud Saas
- Artificial Intelligence
- Government
- GovTech
- GovCon
- Public Sector
- Procurement
- Proposal Automation
- Capture Management
---
