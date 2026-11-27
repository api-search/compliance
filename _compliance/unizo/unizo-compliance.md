---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Unizo API Fabric; exposure management product
    text: The exposure management product is in audit, with independent penetration testing as part of that work.
    type: SOC 2 Type II
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Designed and operated in alignment with ISO 27001 practices.
    type: Practices aligned
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Built to support EU and California data protection requirements.
    type: Built to support
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Built to support EU and California data protection requirements.
    type: Built to support
  trust_center:
    url: https://unizo.ai/trust/
frameworks:
- CCPA
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Unizo
provenance_date: '2026-11-10'
provider_name: Unizo
provider_slug: unizo
slug: unizo-compliance
source_date: '2026-11-10'
source_filename: unizo-compliance.yml
source_heading: Compliance
source_page: https://unizo.ai/trust/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Unizo\naid: unizo\nurl: https://unizo.ai/trust/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://unizo.ai/trust/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: Unizo API Fabric; exposure management product\n  period: null\n  issuer: null\n  report_access: unstated\n  text: The exposure management product is in audit, with independent penetration testing as part of that work.\n- framework: ISO27001\n  type: Practices aligned\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Designed and operated in alignment with ISO 27001 practices.\n- framework: GDPR\n\
  \  type: Built to support\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Built to support EU and California data protection requirements.\n- framework: CCPA\n  type: Built to support\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Built to support EU and California data protection requirements.\n"
source_yaml_url: https://artifacts.apis.io/unizo/compliance/unizo-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Unizo's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Security
- Exposure Management
- Platform
- Company
---
