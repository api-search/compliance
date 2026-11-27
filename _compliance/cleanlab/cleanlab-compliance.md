---
api_specs:
- filename: cleanlab-codex-api-openapi.yml
  format: yaml
  label: Cleanlab Codex API
  slug: cleanlab-codex-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cleanlab/openapi/cleanlab-codex-api-openapi.yml
- filename: cleanlab-studio-api-openapi.yml
  format: yaml
  label: Cleanlab Studio API
  slug: cleanlab-studio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cleanlab/openapi/cleanlab-studio-api-openapi.yml
- filename: cleanlab-tlm-api-openapi.yml
  format: yaml
  label: Cleanlab TLM API
  slug: cleanlab-tlm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cleanlab/openapi/cleanlab-tlm-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We are SOC 2 certified and undergo regular independent penetration testing.
    type: certification
  trust_center:
    url: https://cleanlab.ai/trust/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Cleanlab
provenance_date: '2026-11-09'
provider_name: Cleanlab
provider_slug: cleanlab
slug: cleanlab-compliance
source_date: '2026-11-09'
source_filename: cleanlab-compliance.yml
source_heading: Compliance
source_page: https://cleanlab.ai/trust/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Cleanlab\naid: cleanlab\nurl: https://cleanlab.ai/trust/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/cleanlab-trust-center.yml\ntrust_center:\n  url: https://cleanlab.ai/trust/\nattestations:\n- framework: SOC2\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We are SOC 2 certified and undergo regular independent penetration testing.\n"
source_yaml_url: https://artifacts.apis.io/cleanlab/compliance/cleanlab-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Cleanlab's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- LLM
- Trustworthiness
- Data Quality
- Guardrails
- Real-Time
---
