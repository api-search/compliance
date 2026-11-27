---
api_specs:
- filename: digits-com-chart-of-accounts-api-openapi.yml
  format: yaml
  label: Digits Chart of Accounts API
  slug: digits-com-chart-of-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digits-com/openapi/digits-com-chart-of-accounts-api-openapi.yml
- filename: digits-com-connections-api-openapi.yml
  format: yaml
  label: Digits Connections API
  slug: digits-com-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digits-com/openapi/digits-com-connections-api-openapi.yml
- filename: digits-com-financial-statements-api-openapi.yml
  format: yaml
  label: Digits Financial Statements API
  slug: digits-com-financial-statements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digits-com/openapi/digits-com-financial-statements-api-openapi.yml
- filename: digits-com-organizations-api-openapi.yml
  format: yaml
  label: Digits Organizations API
  slug: digits-com-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digits-com/openapi/digits-com-organizations-api-openapi.yml
- filename: digits-com-parties-api-openapi.yml
  format: yaml
  label: Digits Parties API
  slug: digits-com-parties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digits-com/openapi/digits-com-parties-api-openapi.yml
- filename: digits-com-sources-api-openapi.yml
  format: yaml
  label: Digits Sources API
  slug: digits-com-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digits-com/openapi/digits-com-sources-api-openapi.yml
- filename: digits-com-transactions-api-openapi.yml
  format: yaml
  label: Digits Transactions API
  slug: digits-com-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digits-com/openapi/digits-com-transactions-api-openapi.yml
- filename: digits-com-webhooks-api-openapi.yml
  format: yaml
  label: Digits Webhooks API
  slug: digits-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digits-com/openapi/digits-com-webhooks-api-openapi.yml
- filename: digits-com-llms-txt-api-openapi.yml
  format: yaml
  label: Digits Llms.txt API
  slug: digits-com-llms-txt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digits-com/openapi/digits-com-llms-txt-api-openapi.yml
- filename: digits-com-sitemap-xml-api-openapi.yml
  format: yaml
  label: Digits Sitemap.xml API
  slug: digits-com-sitemap-xml-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digits-com/openapi/digits-com-sitemap-xml-api-openapi.yml
- filename: digits-com-well-known-api-openapi.yml
  format: yaml
  label: Digits .well Known API
  slug: digits-com-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digits-com/openapi/digits-com-well-known-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type 2 Report 2026
    type: SOC 2 Type 2 report
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type I
    type: SOC 2 Type I
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA COMPLIANT
    type: CCPA compliance
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Digits platform controls
    source: https://digits.com/security/
    text: Digits is SOC 2 Type II compliant, having met rigorous AICPA standards for security and data protection.
    type: Type II
  trust_center:
    url: https://trust.digits.com/
frameworks:
- CCPA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Digits
provenance_date: '2026-11-09'
provider_name: Digits
provider_slug: digits-com
slug: digits-com-compliance
source_date: '2026-11-09'
source_filename: digits-com-compliance.yml
source_heading: Compliance
source_page: https://trust.digits.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Digits\naid: digits-com\nurl: https://trust.digits.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/digits-com-trust-center.yml\n  sources:\n  - https://digits.com/security/\n  - https://trust.digits.com/\ntrust_center:\n  url: https://trust.digits.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2 Report 2026\n- framework: SOC2\n  type: SOC 2 Type I\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type I\n- framework: CCPA\n  type: CCPA compliance\n\
  \  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA COMPLIANT\n- framework: SOC2\n  type: Type II\n  scope: Digits platform controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Digits is SOC 2 Type II compliant, having met rigorous AICPA standards for security and data protection.\n  source: https://digits.com/security/\n"
source_yaml_url: https://artifacts.apis.io/digits-com/compliance/digits-com-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Digits's own page on 2026-11-09.
synthetic: false
tags:
- Accounting
- Bookkeeping
- Finance
- General Ledger
- Artificial Intelligence
- Fintech
---
