---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Trisotech
    text: Trisotech has achieved SOC 2 Type II compliance in accordance with American Institute of Certified Public Accountants (AICPA) standards
    type: SOC 2 Type II
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: data center infrastructure where customer data is stored
    text: Trisotech guarantees the data center infrastructure where customer data is stored complies with International standards and is certified for ISO/IEC 27001:2013
    type: ISO/IEC 27001:2013 certification of data center provider
  - framework: SOC3
    issuer: null
    period: null
    report_access: public
    scope: data center provider controls relevant to security
    text: Download the SOC 3 report
    type: SOC 3 report of data center provider
  trust_center:
    url: https://www.trisotech.com/security/
frameworks:
- ISO27001
- SOC2
- SOC3
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Trisotech
provenance_date: '2026-11-10'
provider_name: Trisotech
provider_slug: trisotech
slug: trisotech-compliance
source_date: '2026-11-10'
source_filename: trisotech-compliance.yml
source_heading: Compliance
source_page: https://www.trisotech.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Trisotech\naid: trisotech\nurl: https://www.trisotech.com/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/trisotech-trust-center.yml\ntrust_center:\n  url: https://www.trisotech.com/security/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: Trisotech\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Trisotech has achieved SOC 2 Type II compliance in accordance with American Institute of Certified Public\n    Accountants (AICPA) standards\n- framework: ISO27001\n  type: ISO/IEC 27001:2013 certification of data center provider\n  scope: data center infrastructure\
  \ where customer data is stored\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Trisotech guarantees the data center infrastructure where customer data is stored complies with International\n    standards and is certified for ISO/IEC 27001:2013\n- framework: SOC3\n  type: SOC 3 report of data center provider\n  scope: data center provider controls relevant to security\n  period: null\n  issuer: null\n  report_access: public\n  text: Download the SOC 3 report\n"
source_yaml_url: https://artifacts.apis.io/trisotech/compliance/trisotech-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Trisotech's own page on 2026-11-10.
synthetic: false
tags:
- Business Process Management
- Decision Management
- Workflow Automation
- Low-Code
- BPMN
- DMN
- CMMN
- Healthcare
- FHIR
- Clinical Decision Support
- Standards
- AI Agents
- MCP
- Enterprise Architecture
---
