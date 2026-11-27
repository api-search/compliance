---
api_specs:
- filename: docs.ziphq.com
  format: yaml
  label: Zip Procurement API
  slug: zip-procurement-api
  spec_type: OpenAPI
  url: https://docs.ziphq.com
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC1
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Zip has undergone a Service Organization Controls audit (SOC 1 Type 2). Please contact your account manager or Security Resource Center to request Zip's most recent report.
    type: SOC 1 Type 2
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Zip has undergone a Service Organization Controls audit (SOC 2 Type 2). Please contact your account manager or Security Resource Center to request Zip's most recent report.
    type: SOC 2 Type 2
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO/IEC 27001:2022 is a specification for an information security management system (ISMS)
    type: ISO/IEC 27001:2022 certificate
  trust_center:
    url: https://zip.com/trust
frameworks:
- ISO27001
- SOC1
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Zip
provenance_date: '2026-11-10'
provider_name: Zip
provider_slug: zip
slug: zip-compliance
source_date: '2026-11-10'
source_filename: zip-compliance.yml
source_heading: Compliance
source_page: https://zip.com/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Zip\naid: zip\nurl: https://zip.com/trust\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/zip-trust-center.yml\ntrust_center:\n  url: https://zip.com/trust\nattestations:\n- framework: SOC1\n  type: SOC 1 Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Zip has undergone a Service Organization Controls audit (SOC 1 Type 2). Please contact your account manager\n    or Security Resource Center to request Zip's most recent report.\n- framework: SOC2\n  type: SOC 2 Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Zip\
  \ has undergone a Service Organization Controls audit (SOC 2 Type 2). Please contact your account manager\n    or Security Resource Center to request Zip's most recent report.\n- framework: ISO27001\n  type: ISO/IEC 27001:2022 certificate\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO/IEC 27001:2022 is a specification for an information security management system (ISMS)\n"
source_yaml_url: https://artifacts.apis.io/zip/compliance/zip-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Zip's own page on 2026-11-10.
synthetic: false
tags:
- Procurement
- Spend Management
- Intake to Pay
- Approval Workflows
- Vendor Management
- Contract Management
- Enterprise Software
- Fintech
---
