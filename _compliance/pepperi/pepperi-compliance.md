---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: Pepperi
    text: 'Pepperi is ISO/IEC 27001: 2013 certified, an international information security standard.'
    type: certification
  - framework: other
    issuer: null
    period: null
    report_access: on_request
    scope: Pepperi services to companies under SOC regulation
    text: Pepperi is also ISAE 3402 compliant, providing the necessary assurances that Pepperi follows the applicable controls and standards to provide services to companies who are under SOC regulation, including Sarbanes-Oxley.
    type: ISAE 3402 compliance
  - framework: ISO9001
    issuer: null
    period: null
    report_access: unstated
    scope: Cloud infrastructure section
    text: ISO 9001-2008 is the International Standard for Quality Management Systems (QMS).
    type: certification reference
  trust_center:
    url: https://www.pepperi.com/security
frameworks:
- ISO27001
- ISO9001
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Pepperi
provenance_date: '2026-11-10'
provider_name: Pepperi
provider_slug: pepperi
slug: pepperi-compliance
source_date: '2026-11-10'
source_filename: pepperi-compliance.yml
source_heading: Compliance
source_page: https://www.pepperi.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Pepperi\naid: pepperi\nurl: https://www.pepperi.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.pepperi.com/security\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: Pepperi\n  period: null\n  issuer: null\n  report_access: on_request\n  text: 'Pepperi is ISO/IEC 27001: 2013 certified, an international information security standard.'\n- framework: other\n  type: ISAE 3402 compliance\n  scope: Pepperi services to companies under SOC regulation\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Pepperi is also ISAE 3402 compliant, providing the\
  \ necessary assurances that Pepperi follows the applicable\n    controls and standards to provide services to companies who are under SOC regulation, including Sarbanes-Oxley.\n- framework: ISO9001\n  type: certification reference\n  scope: Cloud infrastructure section\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 9001-2008 is the International Standard for Quality Management Systems (QMS).\n"
source_yaml_url: https://artifacts.apis.io/pepperi/compliance/pepperi-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Pepperi's own page on 2026-11-10.
synthetic: false
tags:
- Company
- B2B
- Commerce
- Retail
- Automation
---
