---
api_specs:
- filename: nightfall-ai-scan-api-openapi.yml
  format: yaml
  label: Nightfall AI Scan API
  slug: nightfall-ai-scan-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nightfall-ai/openapi/nightfall-ai-scan-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Nightfall security practices
    text: Nightfall is SOC 2 Type 2 certified and is used commonly for HIPAA compliance.
    type: SOC 2 Type 2 certification
  trust_center:
    url: https://www.nightfall.ai/security
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Nightfall AI
provenance_date: '2026-11-10'
provider_name: Nightfall AI
provider_slug: nightfall-ai
slug: nightfall-ai-compliance
source_date: '2026-11-10'
source_filename: nightfall-ai-compliance.yml
source_heading: Compliance
source_page: https://www.nightfall.ai/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Nightfall AI\naid: nightfall-ai\nurl: https://www.nightfall.ai/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/nightfall-ai-trust-center.yml\ntrust_center:\n  url: https://www.nightfall.ai/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 certification\n  scope: Nightfall security practices\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Nightfall is SOC 2 Type 2 certified and is used commonly for HIPAA compliance.\n"
source_yaml_url: https://artifacts.apis.io/nightfall-ai/compliance/nightfall-ai-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Nightfall AI's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Privacy
- Sensitive Data
---
