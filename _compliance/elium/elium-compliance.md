---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: ISO/IEC 27001:2022
    type: certification
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: SecNumCloud
    text: SecNumCloud
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: design, development, management, and support of the Elium solution
    source: https://elium.com/trust/controls
    text: Whatever S.A. is ISO/IEC 27001:2022 certified, covering the design, development, management, and support of the Elium solution.
    type: certification
  trust_center:
    url: https://elium.com/trust
frameworks:
- GDPR
- ISO27001
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Elium
provenance_date: '2026-11-09'
provider_name: Elium
provider_slug: elium
slug: elium-compliance
source_date: '2026-11-09'
source_filename: elium-compliance.yml
source_heading: Compliance
source_page: https://elium.com/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Elium\naid: elium\nurl: https://elium.com/trust\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://elium.com/trust\n  - https://elium.com/trust/controls\ntrust_center:\n  url: https://elium.com/trust\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: ISO/IEC 27001:2022\n- framework: other\n  type: certification\n  scope: SecNumCloud\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SecNumCloud\n- framework: GDPR\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: GDPR\n- framework: ISO27001\n  type: certification\n  scope: design, development, management, and support of the Elium solution\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Whatever S.A. is ISO/IEC 27001:2022 certified, covering the design, development, management, and support\n    of the Elium solution.\n  source: https://elium.com/trust/controls\n"
source_yaml_url: https://artifacts.apis.io/elium/compliance/elium-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Elium's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Software-as-a-Service
- Knowledge Management
- Knowledge Base
- Enterprise Search
- AI Search
- GraphQL
- MCP
- Collaboration
- Documentation
- RAG
- Europe
---
