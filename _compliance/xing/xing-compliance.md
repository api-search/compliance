---
api_specs:
- filename: xing-openapi-generated.yml
  format: yaml
  label: XING API
  slug: xing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xing/openapi/_ae-authored/xing-openapi-generated.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Information Security Management System
    text: Our "Information Security Management System" is VdS 10000 certified.
    type: certification (VdS 10000)
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: IT systems
    text: Our IT systems have been checked according to the "Payment Card Industry Data Security Standard" ( PCI DSS ).
    type: check against standard
  trust_center:
    url: https://privacy.xing.com/en/your-security
frameworks:
- PCI-DSS
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: XING
provenance_date: '2026-11-10'
provider_name: XING
provider_slug: xing
slug: xing-compliance
source_date: '2026-11-10'
source_filename: xing-compliance.yml
source_heading: Compliance
source_page: https://privacy.xing.com/en/your-security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: XING\naid: xing\nurl: https://privacy.xing.com/en/your-security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://privacy.xing.com/en/your-security\nattestations:\n- framework: other\n  type: certification (VdS 10000)\n  scope: Information Security Management System\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our \"Information Security Management System\" is VdS 10000 certified.\n- framework: PCI-DSS\n  type: check against standard\n  scope: IT systems\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our IT systems have been checked according to the \"Payment\
  \ Card Industry Data Security Standard\" ( PCI DSS\n    ).\n"
source_yaml_url: https://artifacts.apis.io/xing/compliance/xing-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from XING's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Networking
- Job
- Recruiters
- Europe
---
