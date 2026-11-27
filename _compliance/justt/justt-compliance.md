---
api_specs:
- filename: justt-chargebacks-api-openapi.yml
  format: yaml
  label: Justt Chargebacks API
  slug: justt-chargebacks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/justt/openapi/justt-chargebacks-api-openapi.yml
- filename: justt-data-subjects-api-openapi.yml
  format: yaml
  label: Justt Data Subjects API
  slug: justt-data-subjects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/justt/openapi/justt-data-subjects-api-openapi.yml
- filename: justt-evidence-api-openapi.yml
  format: yaml
  label: Justt Evidence API
  slug: justt-evidence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/justt/openapi/justt-evidence-api-openapi.yml
- filename: justt-files-api-openapi.yml
  format: yaml
  label: Justt Files API
  slug: justt-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/justt/openapi/justt-files-api-openapi.yml
- filename: justt-integrations-api-openapi.yml
  format: yaml
  label: Justt Integrations API
  slug: justt-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/justt/openapi/justt-integrations-api-openapi.yml
- filename: justt-merchants-api-openapi.yml
  format: yaml
  label: Justt Merchants API
  slug: justt-merchants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/justt/openapi/justt-merchants-api-openapi.yml
- filename: justt-pre-chargeback-alerts-api-openapi.yml
  format: yaml
  label: Justt Pre-chargeback Alerts API
  slug: justt-pre-chargeback-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/justt/openapi/justt-pre-chargeback-alerts-api-openapi.yml
- filename: justt-sandbox-api-openapi.yml
  format: yaml
  label: Justt Sandbox API
  slug: justt-sandbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/justt/openapi/justt-sandbox-api-openapi.yml
- filename: justt-transactions-api-openapi.yml
  format: yaml
  label: Justt Transactions API
  slug: justt-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/justt/openapi/justt-transactions-api-openapi.yml
claim_count: 9
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001:2022
    type: certification
  - framework: ISO27017
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27017 Certificate
    type: certification
  - framework: ISO27018
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27018 Certificate
    type: certification
  - framework: ISO27701
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27701 Certificate
    type: certification
  - framework: ISO42001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO/IEC 42001:2023
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA COMPLIANT
    type: compliance
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: PCI DSS 4.0.1
    type: report
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: SOC 2 Type II Report
    type: report
  trust_center:
    url: https://trust.justt.ai/
frameworks:
- CCPA
- GDPR
- ISO27001
- ISO27017
- ISO27018
- ISO27701
- ISO42001
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Justt
provenance_date: '2026-11-09'
provider_name: Justt
provider_slug: justt
slug: justt-compliance
source_date: '2026-11-09'
source_filename: justt-compliance.yml
source_heading: Compliance
source_page: https://trust.justt.ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Justt\naid: justt\nurl: https://trust.justt.ai/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.justt.ai/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022\n- framework: ISO27017\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27017 Certificate\n- framework: ISO27018\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27018 Certificate\n- framework: ISO27701\n  type: certification\n\
  \  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27701 Certificate\n- framework: ISO42001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO/IEC 42001:2023\n- framework: GDPR\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: CCPA\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA COMPLIANT\n- framework: PCI-DSS\n  type: report\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: PCI DSS 4.0.1\n- framework: SOC2\n  type: report\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Type II Report\n"
source_yaml_url: https://artifacts.apis.io/justt/compliance/justt-compliance.yml
stated_fields:
- attestations
summary_line: 9 quoted statements, read from Justt's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Chargebacks
- Disputes
- Fraud Prevention
- Risk Management
- Financial Services
- E-Commerce
- Artificial Intelligence
- Webhook
---
