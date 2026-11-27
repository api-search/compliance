---
api_specs:
- filename: loon-finance-attestations-api-openapi.yml
  format: yaml
  label: Loon Finance Attestations API
  slug: loon-finance-attestations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loon-finance/openapi/loon-finance-attestations-api-openapi.yml
- filename: loon-finance-issuances-api-openapi.yml
  format: yaml
  label: Loon Finance Issuances API
  slug: loon-finance-issuances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loon-finance/openapi/loon-finance-issuances-api-openapi.yml
- filename: loon-finance-supply-api-openapi.yml
  format: yaml
  label: Loon Finance Supply API
  slug: loon-finance-supply-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loon-finance/openapi/loon-finance-supply-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: other
    issuer: Independent third party (not named on page)
    period: null
    report_access: public
    scope: CADC in circulation fully backed by Canadian dollars at ATB Financial
    text: Every month, our reserves are independently attested and published here.
    type: Monthly reserve attestation
  trust_center:
    url: https://loon.finance/transparency/
frameworks:
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Loon Finance
provenance_date: '2026-11-09'
provider_name: Loon Finance
provider_slug: loon-finance
slug: loon-finance-compliance
source_date: '2026-11-09'
source_filename: loon-finance-compliance.yml
source_heading: Compliance
source_page: https://loon.finance/transparency/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Loon Finance\naid: loon-finance\nurl: https://loon.finance/transparency/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://loon.finance/transparency/\nattestations:\n- framework: other\n  type: Monthly reserve attestation\n  scope: CADC in circulation fully backed by Canadian dollars at ATB Financial\n  period: null\n  issuer: Independent third party (not named on page)\n  report_access: public\n  text: Every month, our reserves are independently attested and published here.\n"
source_yaml_url: https://artifacts.apis.io/loon-finance/compliance/loon-finance-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Loon Finance's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Stablecoins
- Cryptocurrency
- Payments
- Canada
- Digital Dollar
- Blockchain
- Transparency
- Stablecoin Issuance
---
