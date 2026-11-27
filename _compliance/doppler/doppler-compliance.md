---
api_specs:
- filename: doppler-workplace-api-openapi.yml
  format: yaml
  label: Doppler Workplace API
  slug: doppler-workplace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doppler/openapi/doppler-workplace-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Doppler is SOC 2 certified, ensuring your API keys, credentials, and secrets are stored with industry-leading security standards.
    type: certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We’ve achieved ISO 27001 certification to align with the highest security standards
    type: certification
  trust_center:
    url: https://www.doppler.com/security
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Doppler
provenance_date: '2026-11-09'
provider_name: Doppler
provider_slug: doppler
slug: doppler-compliance
source_date: '2026-11-09'
source_filename: doppler-compliance.yml
source_heading: Compliance
source_page: https://www.doppler.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Doppler\naid: doppler\nurl: https://www.doppler.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/doppler-trust-center.yml\ntrust_center:\n  url: https://www.doppler.com/security\nattestations:\n- framework: SOC2\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Doppler is SOC 2 certified, ensuring your API keys, credentials, and secrets are stored with industry-leading\n    security standards.\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We’ve achieved\
  \ ISO 27001 certification to align with the highest security standards\n"
source_yaml_url: https://artifacts.apis.io/doppler/compliance/doppler-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Doppler's own page on 2026-11-09.
synthetic: false
tags:
- Secrets Management
- SecretOps
- DevOps
- Configuration Management
- Security
- CI/CD
- Developer Tools
---
