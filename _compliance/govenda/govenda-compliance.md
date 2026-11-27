---
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Certified
    type: SOC 2 Type 2
  - framework: SOC1
    issuer: null
    period: null
    report_access: unstated
    scope: Financial Reporting Controls
    text: SOC 1 Type 2 Financial Reporting Controls
    type: SOC 1 Type 2
  - framework: SOC3
    issuer: null
    period: null
    report_access: unstated
    scope: Assurance for Service Organizer’s Controls
    text: SOC 3 Assurance for Service Organizer’s Controls
    type: SOC 3
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Controls for Information Risk Management
    text: ISO/IEC 27001:2013 Controls for Information Risk Management
    type: ISO/IEC 27001:2013
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA Compliant
    type: HIPAA
  trust_center:
    url: https://www.govenda.com/security/
frameworks:
- HIPAA
- ISO27001
- SOC1
- SOC2
- SOC3
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Govenda
provenance_date: '2026-11-09'
provider_name: Govenda
provider_slug: govenda
slug: govenda-compliance
source_date: '2026-11-09'
source_filename: govenda-compliance.yml
source_heading: Compliance
source_page: https://www.govenda.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Govenda\naid: govenda\nurl: https://www.govenda.com/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/govenda-trust-center.yml\ntrust_center:\n  url: https://www.govenda.com/security/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Certified\n- framework: SOC1\n  type: SOC 1 Type 2\n  scope: Financial Reporting Controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 1 Type 2 Financial Reporting Controls\n- framework: SOC3\n  type: SOC 3\n  scope: Assurance for Service Organizer’s\
  \ Controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 3 Assurance for Service Organizer’s Controls\n- framework: ISO27001\n  type: ISO/IEC 27001:2013\n  scope: Controls for Information Risk Management\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO/IEC 27001:2013 Controls for Information Risk Management\n- framework: HIPAA\n  type: HIPAA\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA Compliant\n"
source_yaml_url: https://artifacts.apis.io/govenda/compliance/govenda-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Govenda's own page on 2026-11-09.
synthetic: false
tags:
- Board Management
- Governance
- Meetings
- Documents
---
