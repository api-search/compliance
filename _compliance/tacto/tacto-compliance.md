---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: Proks Cert GmbH
    period: null
    report_access: unstated
    scope: Tacto's information security management system
    text: ISO/IEC 27001 Issued by Proks Cert GmbH. Certificate no. DE-IS-20260285.
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Data protection
    text: Fully GDPR compliant. DPA on request.
    type: compliance statement
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.tacto.ai/
    text: ISO 27001:2022 - Official Certificate (EN)
    type: certificate
  trust_center:
    url: https://www.tacto.ai/en/security
frameworks:
- GDPR
- ISO27001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Tacto
provenance_date: '2026-11-10'
provider_name: Tacto
provider_slug: tacto
slug: tacto-compliance
source_date: '2026-11-10'
source_filename: tacto-compliance.yml
source_heading: Compliance
source_page: https://www.tacto.ai/en/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Tacto\naid: tacto\nurl: https://www.tacto.ai/en/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://trust.tacto.ai/\n  - https://www.tacto.ai/en/security\ntrust_center:\n  url: https://www.tacto.ai/en/security\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: Tacto's information security management system\n  period: null\n  issuer: Proks Cert GmbH\n  report_access: unstated\n  text: ISO/IEC 27001 Issued by Proks Cert GmbH. Certificate no. DE-IS-20260285.\n- framework: GDPR\n  type: compliance statement\n  scope: Data protection\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: Fully GDPR compliant. DPA on request.\n- framework: ISO27001\n  type: certificate\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022 - Official Certificate (EN)\n  source: https://trust.tacto.ai/\n"
source_yaml_url: https://artifacts.apis.io/tacto/compliance/tacto-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Tacto's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Business Applications
- Procurement
- Supply Chain
- Manufacturing
- Artificial Intelligence
- Sourcing
- Compliance
- Germany
---
