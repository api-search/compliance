---
api_specs:
- filename: moneygram-accounts-api-openapi.yml
  format: yaml
  label: MoneyGram Accounts API
  slug: moneygram-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moneygram/openapi/moneygram-accounts-api-openapi.yml
- filename: moneygram-amend-api-openapi.yml
  format: yaml
  label: MoneyGram Amend API
  slug: moneygram-amend-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moneygram/openapi/moneygram-amend-api-openapi.yml
- filename: moneygram-fx-rate-api-openapi.yml
  format: yaml
  label: MoneyGram Fx Rate API
  slug: moneygram-fx-rate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moneygram/openapi/moneygram-fx-rate-api-openapi.yml
- filename: moneygram-oauth-api-openapi.yml
  format: yaml
  label: MoneyGram OAuth API
  slug: moneygram-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moneygram/openapi/moneygram-oauth-api-openapi.yml
- filename: moneygram-partnerconnect-api-openapi.yml
  format: yaml
  label: MoneyGram Partnerconnect API
  slug: moneygram-partnerconnect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moneygram/openapi/moneygram-partnerconnect-api-openapi.yml
- filename: moneygram-reference-data-api-openapi.yml
  format: yaml
  label: MoneyGram Reference Data API
  slug: moneygram-reference-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moneygram/openapi/moneygram-reference-data-api-openapi.yml
- filename: moneygram-transactions-api-openapi.yml
  format: yaml
  label: MoneyGram Transactions API
  slug: moneygram-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moneygram/openapi/moneygram-transactions-api-openapi.yml
- filename: moneygram-transfer-api-openapi.yml
  format: yaml
  label: MoneyGram Transfer API
  slug: moneygram-transfer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moneygram/openapi/moneygram-transfer-api-openapi.yml
- filename: moneygram-transfers-api-openapi.yml
  format: yaml
  label: MoneyGram Transfers API
  slug: moneygram-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moneygram/openapi/moneygram-transfers-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PCI Attestation of Compliance (AOC)
    type: Attestation of Compliance (AOC)
  - framework: SOC1
    issuer: null
    period: '2025'
    report_access: unstated
    scope: GCC
    text: MoneyGram 2025 GCC SOC 1 Type 2
    type: SOC 1 Type II
  - framework: NIST-CSF
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: NIST Cybersecurity Framework NIST CSF 2.0
    type: Cybersecurity Framework
  - framework: NIST-800-53
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: NIST 800-53
    type: Framework
  trust_center:
    url: https://trust.moneygram.com/
frameworks:
- NIST-800-53
- NIST-CSF
- PCI-DSS
- SOC1
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: MoneyGram
provenance_date: '2026-11-10'
provider_name: MoneyGram
provider_slug: moneygram
slug: moneygram-compliance
source_date: '2026-11-10'
source_filename: moneygram-compliance.yml
source_heading: Compliance
source_page: https://trust.moneygram.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: MoneyGram\naid: moneygram\nurl: https://trust.moneygram.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.moneygram.com/\nattestations:\n- framework: PCI-DSS\n  type: Attestation of Compliance (AOC)\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI Attestation of Compliance (AOC)\n- framework: SOC1\n  type: SOC 1 Type II\n  scope: GCC\n  period: '2025'\n  issuer: null\n  report_access: unstated\n  text: MoneyGram 2025 GCC SOC 1 Type 2\n- framework: NIST-CSF\n  type: Cybersecurity Framework\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: NIST Cybersecurity Framework NIST CSF 2.0\n- framework: NIST-800-53\n  type: Framework\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: NIST 800-53\n"
source_yaml_url: https://artifacts.apis.io/moneygram/compliance/moneygram-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from MoneyGram's own page on 2026-11-10.
synthetic: false
tags:
- Money
- Payments
- Transfer
- Fintech
- Global
---
