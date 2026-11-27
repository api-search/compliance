---
api_specs:
- filename: kaiko-canton-oracle-api-openapi.yml
  format: yaml
  label: Kaiko Canton Oracle API
  slug: kaiko-canton-oracle-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kaiko/openapi/kaiko-canton-oracle-api-openapi.yml
- filename: kaiko-index-reference-data-api-openapi.yml
  format: yaml
  label: Kaiko Index Reference Data API
  slug: kaiko-index-reference-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kaiko/openapi/kaiko-index-reference-data-api-openapi.yml
- filename: kaiko-indices-api-openapi.yml
  format: yaml
  label: Kaiko Indices API
  slug: kaiko-indices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kaiko/openapi/kaiko-indices-api-openapi.yml
- filename: kaiko-supply-api-openapi.yml
  format: yaml
  label: Kaiko Supply API
  slug: kaiko-supply-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kaiko/openapi/kaiko-supply-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: Big 4 firm
    period: null
    report_access: unstated
    scope: Kaiko data controls
    text: Kaiko underwent a rigorous assessment process that involved an independent audit of its controls and processes by a ‘Big 4’ firm.
    type: SOC 2 Type II examination
  - framework: SOC1
    issuer: Big 4 firm
    period: null
    report_access: unstated
    scope: internal controls over financial reporting
    text: Kaiko successfully completed this audit, with its financial controls and processes independently reviewed and validated by a ‘Big 4’ firm.
    type: SOC 1 Type II examination
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Kaiko Indices
    text: Kaiko Indices are administered in accordance with the IOSCO Principles for Financial Benchmarks.
    type: IOSCO Principles for Financial Benchmarks alignment
  trust_center:
    url: https://www.kaiko.com/compliance
frameworks:
- SOC1
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Kaiko
provenance_date: '2026-11-09'
provider_name: Kaiko
provider_slug: kaiko
slug: kaiko-compliance
source_date: '2026-11-09'
source_filename: kaiko-compliance.yml
source_heading: Compliance
source_page: https://www.kaiko.com/compliance
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Kaiko\naid: kaiko\nurl: https://www.kaiko.com/compliance\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.kaiko.com/compliance\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II examination\n  scope: Kaiko data controls\n  period: null\n  issuer: Big 4 firm\n  report_access: unstated\n  text: Kaiko underwent a rigorous assessment process that involved an independent audit of its controls and processes\n    by a ‘Big 4’ firm.\n- framework: SOC1\n  type: SOC 1 Type II examination\n  scope: internal controls over financial reporting\n  period: null\n  issuer: Big 4 firm\n  report_access: unstated\n\
  \  text: Kaiko successfully completed this audit, with its financial controls and processes independently reviewed\n    and validated by a ‘Big 4’ firm.\n- framework: other\n  type: IOSCO Principles for Financial Benchmarks alignment\n  scope: Kaiko Indices\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Kaiko Indices are administered in accordance with the IOSCO Principles for Financial Benchmarks.\n"
source_yaml_url: https://artifacts.apis.io/kaiko/compliance/kaiko-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Kaiko's own page on 2026-11-09.
synthetic: false
tags:
- Web3
- Cryptocurrency
- Market Data
- Institutional
- Foreign Exchange
- Indices
- Onchain
- Streaming
---
