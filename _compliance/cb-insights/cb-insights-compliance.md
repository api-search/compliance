---
api_specs:
- filename: cb-insights-authorization-api-openapi.yml
  format: yaml
  label: CB Insights Authorization API
  slug: cb-insights-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cb-insights/openapi/cb-insights-authorization-api-openapi.yml
- filename: cb-insights-businessrelationships-api-openapi.yml
  format: yaml
  label: CB Insights Business Relationships API
  slug: cb-insights-businessrelationships-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cb-insights/openapi/cb-insights-businessrelationships-api-openapi.yml
- filename: cb-insights-chatcbi-api-openapi.yml
  format: yaml
  label: CB Insights Chat CBI API
  slug: cb-insights-chatcbi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cb-insights/openapi/cb-insights-chatcbi-api-openapi.yml
- filename: cb-insights-firmographics-api-openapi.yml
  format: yaml
  label: CB Insights Firmographics API
  slug: cb-insights-firmographics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cb-insights/openapi/cb-insights-firmographics-api-openapi.yml
- filename: cb-insights-managementandboard-api-openapi.yml
  format: yaml
  label: CB Insights Management And Board API
  slug: cb-insights-managementandboard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cb-insights/openapi/cb-insights-managementandboard-api-openapi.yml
- filename: cb-insights-organizations-api-openapi.yml
  format: yaml
  label: CB Insights Organizations API
  slug: cb-insights-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cb-insights/openapi/cb-insights-organizations-api-openapi.yml
- filename: cb-insights-outlook-api-openapi.yml
  format: yaml
  label: CB Insights Outlook API
  slug: cb-insights-outlook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cb-insights/openapi/cb-insights-outlook-api-openapi.yml
- filename: cb-insights-revenue-api-openapi.yml
  format: yaml
  label: CB Insights Revenue API
  slug: cb-insights-revenue-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cb-insights/openapi/cb-insights-revenue-api-openapi.yml
- filename: cb-insights-scoutingreports-api-openapi.yml
  format: yaml
  label: CB Insights Scouting Reports API
  slug: cb-insights-scoutingreports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cb-insights/openapi/cb-insights-scoutingreports-api-openapi.yml
- filename: cb-insights-strategymap-api-openapi.yml
  format: yaml
  label: CB Insights Strategy Map API
  slug: cb-insights-strategymap-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cb-insights/openapi/cb-insights-strategymap-api-openapi.yml
- filename: cb-insights-financial-transactions-api-openapi.yml
  format: yaml
  label: CB Insights Financial Transactions API
  slug: cb-insights-financial-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cb-insights/openapi/cb-insights-financial-transactions-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Request access CB Insights
    type: SOC 2 Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR Compliance Policy
    type: null
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA COMPLIANT
    type: null
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: infrastructure
    source: https://www.cbinsights.com/security-and-privacy/
    text: SOC 2 Type II–certified Our infrastructure is audited and certified to meet the most rigorous standards for data security.
    type: SOC 2 Type II certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: data privacy and protection
    source: https://www.cbinsights.com/security-and-privacy/
    text: GDPR compliant We meet the strict requirements of the General Data Protection Regulation for data privacy and protection.
    type: compliance
  trust_center:
    url: https://trust.cbinsights.com/
frameworks:
- CCPA
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: CB Insights
provenance_date: '2026-11-09'
provider_name: CB Insights
provider_slug: cb-insights
slug: cb-insights-compliance
source_date: '2026-11-09'
source_filename: cb-insights-compliance.yml
source_heading: Compliance
source_page: https://trust.cbinsights.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: CB Insights\naid: cb-insights\nurl: https://trust.cbinsights.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://trust.cbinsights.com/\n  - https://www.cbinsights.com/security-and-privacy/\ntrust_center:\n  url: https://trust.cbinsights.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Request access CB Insights\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR Compliance Policy\n- framework: CCPA\n  type: null\n  scope: null\n  period: null\n\
  \  issuer: null\n  report_access: unstated\n  text: CCPA COMPLIANT\n- framework: SOC2\n  type: SOC 2 Type II certification\n  scope: infrastructure\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II–certified Our infrastructure is audited and certified to meet the most rigorous standards\n    for data security.\n  source: https://www.cbinsights.com/security-and-privacy/\n- framework: GDPR\n  type: compliance\n  scope: data privacy and protection\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR compliant We meet the strict requirements of the General Data Protection Regulation for data privacy\n    and protection.\n  source: https://www.cbinsights.com/security-and-privacy/\n"
source_yaml_url: https://artifacts.apis.io/cb-insights/compliance/cb-insights-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from CB Insights's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Market Intelligence
- private-company-data
- Venture Capital
- Funding Data
- investor-data
- Company Data
- People Data
- BusinessRelationships
- predictive-scoring
- MCP
- Agent-Native
- Data Enrichment
- Snowflake
---
