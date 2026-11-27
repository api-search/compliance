---
api_specs:
- filename: tradingview-account-api-openapi.yml
  format: yaml
  label: TradingView Account API
  slug: tradingview-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradingview/openapi/tradingview-account-api-openapi.yml
- filename: tradingview-authorization-api-openapi.yml
  format: yaml
  label: TradingView Authorization API
  slug: tradingview-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradingview/openapi/tradingview-authorization-api-openapi.yml
- filename: tradingview-broker-configuration-api-openapi.yml
  format: yaml
  label: TradingView Broker Configuration API
  slug: tradingview-broker-configuration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradingview/openapi/tradingview-broker-configuration-api-openapi.yml
- filename: tradingview-data-integration-api-openapi.yml
  format: yaml
  label: TradingView Data Integration API
  slug: tradingview-data-integration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradingview/openapi/tradingview-data-integration-api-openapi.yml
- filename: tradingview-data-permissions-api-openapi.yml
  format: yaml
  label: TradingView Data Permissions API
  slug: tradingview-data-permissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradingview/openapi/tradingview-data-permissions-api-openapi.yml
- filename: tradingview-market-data-api-openapi.yml
  format: yaml
  label: TradingView Market Data API
  slug: tradingview-market-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradingview/openapi/tradingview-market-data-api-openapi.yml
- filename: tradingview-trading-api-openapi.yml
  format: yaml
  label: TradingView Trading API
  slug: tradingview-trading-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradingview/openapi/tradingview-trading-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: '2026'
    report_access: unstated
    scope: null
    text: SOC 2 Type 2 Report 2026
    type: SOC 2 Type 2 report
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PCI DSS Level 1 Merchant AOC
    type: Merchant AOC
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PCI DSS 4.0.1
    type: compliance listing
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: compliance listing
  - framework: DORA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Digital Operational Resilience Act
    type: compliance listing
  trust_center:
    url: https://trust.tradingview.com/
frameworks:
- DORA
- GDPR
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: TradingView
provenance_date: '2026-11-10'
provider_name: TradingView
provider_slug: tradingview
slug: tradingview-compliance
source_date: '2026-11-10'
source_filename: tradingview-compliance.yml
source_heading: Compliance
source_page: https://trust.tradingview.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: TradingView\naid: tradingview\nurl: https://trust.tradingview.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.tradingview.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: null\n  period: '2026'\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2 Report 2026\n- framework: PCI-DSS\n  type: Merchant AOC\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI DSS Level 1 Merchant AOC\n- framework: PCI-DSS\n  type: compliance listing\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI DSS\
  \ 4.0.1\n- framework: GDPR\n  type: compliance listing\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: DORA\n  type: compliance listing\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Digital Operational Resilience Act\n"
source_yaml_url: https://artifacts.apis.io/tradingview/compliance/tradingview-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from TradingView's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Charts
- Charting Library
- Financial Data
- Market Data
- Widgets
- Trading
- Fintech
- Embeddable Components
---
