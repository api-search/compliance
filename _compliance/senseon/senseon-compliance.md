---
api_specs:
- filename: senseon-openapi-generated.yml
  format: yaml
  label: SenseOn API
  slug: senseon-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/senseon/openapi/_ae-authored/senseon-openapi-generated.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001:2022
    type: certification
  - framework: CyberEssentials
    issuer: null
    period: null
    report_access: unstated
    scope: Cyber Essentials Plus
    text: UK Cyber Essentials Plus
    type: certification
  trust_center:
    url: https://trust.senseon.io/
frameworks:
- CyberEssentials
- ISO27001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: SenseOn
provenance_date: '2026-11-10'
provider_name: SenseOn
provider_slug: senseon
slug: senseon-compliance
source_date: '2026-11-10'
source_filename: senseon-compliance.yml
source_heading: Compliance
source_page: https://trust.senseon.io/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: SenseOn\naid: senseon\nurl: https://trust.senseon.io/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.senseon.io/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022\n- framework: CyberEssentials\n  type: certification\n  scope: Cyber Essentials Plus\n  period: null\n  issuer: null\n  report_access: unstated\n  text: UK Cyber Essentials Plus\n"
source_yaml_url: https://artifacts.apis.io/senseon/compliance/senseon-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from SenseOn's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Artificial Intelligence
- Platform
- Incident Response
---
