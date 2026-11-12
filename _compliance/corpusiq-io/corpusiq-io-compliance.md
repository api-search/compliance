---
api_specs:
- filename: corpusiq-io-authentication-api-openapi.yml
  format: yaml
  label: CorpusIQ Authentication API
  slug: corpusiq-io-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpusiq-io/openapi/corpusiq-io-authentication-api-openapi.yml
- filename: corpusiq-io-discovery-api-openapi.yml
  format: yaml
  label: CorpusIQ Discovery API
  slug: corpusiq-io-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpusiq-io/openapi/corpusiq-io-discovery-api-openapi.yml
- filename: corpusiq-io-mcp-api-openapi.yml
  format: yaml
  label: CorpusIQ MCP API
  slug: corpusiq-io-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpusiq-io/openapi/corpusiq-io-mcp-api-openapi.yml
- filename: corpusiq-io-usage-api-openapi.yml
  format: yaml
  label: CorpusIQ Usage API
  slug: corpusiq-io-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpusiq-io/openapi/corpusiq-io-usage-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: other
    issuer: DEKRA
    period: valid through March 5, 2027
    report_access: unstated
    scope: null
    text: CorpusIQ is CASA Tier 2 certified by DEKRA (certification ID 151c1b05, valid through March 5, 2027)
    type: CASA Tier 2 certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: maintains a SOC 2 aligned security posture
    type: aligned posture (not stated as an audit)
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR Aligned
    type: aligned (not stated as an attestation)
  trust_center:
    url: https://www.corpusiq.io/security
frameworks:
- GDPR
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: CorpusIQ
provenance_date: '2026-11-09'
provider_name: CorpusIQ
provider_slug: corpusiq-io
slug: corpusiq-io-compliance
source_date: '2026-11-09'
source_filename: corpusiq-io-compliance.yml
source_heading: Compliance
source_page: https://www.corpusiq.io/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: CorpusIQ\naid: corpusiq-io\nurl: https://www.corpusiq.io/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.corpusiq.io/security\nattestations:\n- framework: other\n  type: CASA Tier 2 certification\n  scope: null\n  period: valid through March 5, 2027\n  issuer: DEKRA\n  report_access: unstated\n  text: CorpusIQ is CASA Tier 2 certified by DEKRA (certification ID 151c1b05, valid through March 5, 2027)\n- framework: SOC2\n  type: aligned posture (not stated as an audit)\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: maintains a SOC 2 aligned security posture\n\
  - framework: GDPR\n  type: aligned (not stated as an attestation)\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR Aligned\n"
source_yaml_url: https://artifacts.apis.io/corpusiq-io/compliance/corpusiq-io-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from CorpusIQ's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- MCP
- Business Intelligence
- Small Business
- Integrations
- ChatGPT
- Analytics
---
