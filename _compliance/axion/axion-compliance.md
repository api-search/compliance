---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Axion services
    text: We undergo regular penetration testing and security reviews designed to be SOC 2 compliant.
    type: SOC 2 compliance (designed to be)
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Information Security Program
    text: Our Information Security Program follows the criteria set forth by the SOC 2 Framework.
    type: Information security program following SOC 2 criteria
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Data centers hosting Axion data
    text: Data is hosted in ISO 27001 certified data centers with SOC 2 reports, physical safeguards, redundant networking and power, and 24/7 security staff.
    type: Hosting data center certification (AWS/GCP provider)
  trust_center:
    url: https://www.axion.com/security
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Axion
provenance_date: '2026-11-09'
provider_name: Axion
provider_slug: axion
slug: axion-compliance
source_date: '2026-11-09'
source_filename: axion-compliance.yml
source_heading: Compliance
source_page: https://www.axion.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Axion\naid: axion\nurl: https://www.axion.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.axion.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 compliance (designed to be)\n  scope: Axion services\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We undergo regular penetration testing and security reviews designed to be SOC 2 compliant.\n- framework: SOC2\n  type: Information security program following SOC 2 criteria\n  scope: Information Security Program\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our Information Security Program\
  \ follows the criteria set forth by the SOC 2 Framework.\n- framework: ISO27001\n  type: Hosting data center certification (AWS/GCP provider)\n  scope: Data centers hosting Axion data\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Data is hosted in ISO 27001 certified data centers with SOC 2 reports, physical safeguards, redundant networking\n    and power, and 24/7 security staff.\n"
source_yaml_url: https://artifacts.apis.io/axion/compliance/axion-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Axion's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Manufacturing
- Quality Management
- Warranty
- Root Cause Analysis
- Enterprise Saas
---
