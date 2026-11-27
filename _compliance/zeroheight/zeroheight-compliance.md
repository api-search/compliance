---
api_specs:
- filename: zeroheight-pages-api-openapi.yml
  format: yaml
  label: Zeroheight Pages API
  slug: zeroheight-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zeroheight/openapi/zeroheight-pages-api-openapi.yml
- filename: zeroheight-styleguides-api-openapi.yml
  format: yaml
  label: Zeroheight Styleguides API
  slug: zeroheight-styleguides-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zeroheight/openapi/zeroheight-styleguides-api-openapi.yml
- filename: zeroheight-tokens-api-openapi.yml
  format: yaml
  label: Zeroheight Tokens API
  slug: zeroheight-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zeroheight/openapi/zeroheight-tokens-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: Dec 2025
    report_access: unstated
    scope: null
    text: SOC 2 Type II Report (Dec 2025)
    type: Type II
  - framework: ISO27001
    issuer: null
    period: 2026-2029
    report_access: unstated
    scope: null
    text: ISO 27001:2022 Certificate (2026-2029)
    type: ISO 27001:2022 certificate
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: compliance
  trust_center:
    url: https://trust.zeroheight.com/
frameworks:
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Zeroheight
provenance_date: '2026-11-10'
provider_name: Zeroheight
provider_slug: zeroheight
slug: zeroheight-compliance
source_date: '2026-11-10'
source_filename: zeroheight-compliance.yml
source_heading: Compliance
source_page: https://trust.zeroheight.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Zeroheight\naid: zeroheight\nurl: https://trust.zeroheight.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/zeroheight-trust-center.yml\ntrust_center:\n  url: https://trust.zeroheight.com/\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: Dec 2025\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II Report (Dec 2025)\n- framework: ISO27001\n  type: ISO 27001:2022 certificate\n  scope: null\n  period: 2026-2029\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022 Certificate (2026-2029)\n- framework: GDPR\n  type: compliance\n  scope: null\n\
  \  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n"
source_yaml_url: https://artifacts.apis.io/zeroheight/compliance/zeroheight-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Zeroheight's own page on 2026-11-10.
synthetic: false
tags:
- Design Systems
- Design Tokens
- Documentation
- MCP
- Agent Readiness
- Developer Tools
- Design
- Figma
- Storybook
- Design Operations
---
