---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: provider policies, procedures and controls
    text: we have implemented policies, procedures, and controls that align with SOC 2, ISO 27001, and the BITS Voluntary Guidelines for Financial Services
    type: aligned controls
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: provider policies, procedures and controls
    text: we have implemented policies, procedures, and controls that align with SOC 2, ISO 27001, and the BITS Voluntary Guidelines for Financial Services
    type: aligned controls
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: server-instances hosted on AWS
    text: Our server-instances are located in multiple AWS high-security availability zones and are compliant with the requirements outlined in SOC 2 and PCI.
    type: compliance claim
  trust_center:
    url: https://www.blueleaf.com/security/
frameworks:
- ISO27001
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: BlueLeaf
provenance_date: '2026-11-09'
provider_name: BlueLeaf
provider_slug: blueleaf
slug: blueleaf-compliance
source_date: '2026-11-09'
source_filename: blueleaf-compliance.yml
source_heading: Compliance
source_page: https://www.blueleaf.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: BlueLeaf\naid: blueleaf\nurl: https://www.blueleaf.com/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.blueleaf.com/security/\nattestations:\n- framework: SOC2\n  type: aligned controls\n  scope: provider policies, procedures and controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: we have implemented policies, procedures, and controls that align with SOC 2, ISO 27001, and the BITS Voluntary\n    Guidelines for Financial Services\n- framework: ISO27001\n  type: aligned controls\n  scope: provider policies, procedures and controls\n  period: null\n  issuer: null\n\
  \  report_access: unstated\n  text: we have implemented policies, procedures, and controls that align with SOC 2, ISO 27001, and the BITS Voluntary\n    Guidelines for Financial Services\n- framework: PCI-DSS\n  type: compliance claim\n  scope: server-instances hosted on AWS\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our server-instances are located in multiple AWS high-security availability zones and are compliant with\n    the requirements outlined in SOC 2 and PCI.\n"
source_yaml_url: https://artifacts.apis.io/blueleaf/compliance/blueleaf-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from BlueLeaf's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Wealth Management
- Fintech
- Financial Advisors
- Investment Reporting
- Account Aggregation
- Client Portal
- OAuth
- Authentication
---
