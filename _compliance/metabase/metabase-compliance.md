---
api_specs:
- filename: metabase-cards-api-openapi.yml
  format: yaml
  label: Metabase Cards API
  slug: metabase-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metabase/openapi/metabase-cards-api-openapi.yml
- filename: metabase-collections-api-openapi.yml
  format: yaml
  label: Metabase Collections API
  slug: metabase-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metabase/openapi/metabase-collections-api-openapi.yml
- filename: metabase-dashboards-api-openapi.yml
  format: yaml
  label: Metabase Dashboards API
  slug: metabase-dashboards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metabase/openapi/metabase-dashboards-api-openapi.yml
- filename: metabase-databases-api-openapi.yml
  format: yaml
  label: Metabase Databases API
  slug: metabase-databases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metabase/openapi/metabase-databases-api-openapi.yml
- filename: metabase-datasets-api-openapi.yml
  format: yaml
  label: Metabase Datasets API
  slug: metabase-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metabase/openapi/metabase-datasets-api-openapi.yml
- filename: metabase-permissions-api-openapi.yml
  format: yaml
  label: Metabase Permissions API
  slug: metabase-permissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metabase/openapi/metabase-permissions-api-openapi.yml
- filename: metabase-search-api-openapi.yml
  format: yaml
  label: Metabase Search API
  slug: metabase-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metabase/openapi/metabase-search-api-openapi.yml
- filename: metabase-sessions-api-openapi.yml
  format: yaml
  label: Metabase Sessions API
  slug: metabase-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metabase/openapi/metabase-sessions-api-openapi.yml
- filename: metabase-settings-api-openapi.yml
  format: yaml
  label: Metabase Settings API
  slug: metabase-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metabase/openapi/metabase-settings-api-openapi.yml
- filename: metabase-users-api-openapi.yml
  format: yaml
  label: Metabase Users API
  slug: metabase-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metabase/openapi/metabase-users-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: Sensiba LLP
    period: null
    report_access: unstated
    scope: controls governing the security of customer data
    text: Our SOC 2 Type II report attests to the controls Metabase has in place governing the security of customer data.
    type: SOC 2 Type II report
  - framework: SOC1
    issuer: null
    period: null
    report_access: unstated
    scope: internal control over financial reporting
    text: Our SOC 1 Type II report provides assurances that Metabase has internal control over financial reporting.
    type: SOC 1 Type II report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: products, processes, and procedures
    text: At Metabase, we’ve worked to make our products, processes, and procedures GDPR-compliant.
    type: GDPR compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: customer data
    text: Metabase acts as a service provider to customers under the California Consumer Privacy Act (CCPA), and we support our customers’ compliance with the CCPA.
    type: service provider under CCPA
  trust_center:
    url: https://www.metabase.com/security
frameworks:
- CCPA
- GDPR
- SOC1
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Metabase
provenance_date: '2026-11-10'
provider_name: Metabase
provider_slug: metabase
slug: metabase-compliance
source_date: '2026-11-10'
source_filename: metabase-compliance.yml
source_heading: Compliance
source_page: https://www.metabase.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Metabase\naid: metabase\nurl: https://www.metabase.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/metabase-trust-center.yml\ntrust_center:\n  url: https://www.metabase.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: controls governing the security of customer data\n  period: null\n  issuer: Sensiba LLP\n  report_access: unstated\n  text: Our SOC 2 Type II report attests to the controls Metabase has in place governing the security of customer\n    data.\n- framework: SOC1\n  type: SOC 1 Type II report\n  scope: internal control over financial reporting\n\
  \  period: null\n  issuer: null\n  report_access: unstated\n  text: Our SOC 1 Type II report provides assurances that Metabase has internal control over financial reporting.\n- framework: GDPR\n  type: GDPR compliance\n  scope: products, processes, and procedures\n  period: null\n  issuer: null\n  report_access: unstated\n  text: At Metabase, we’ve worked to make our products, processes, and procedures GDPR-compliant.\n- framework: CCPA\n  type: service provider under CCPA\n  scope: customer data\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Metabase acts as a service provider to customers under the California Consumer Privacy Act (CCPA), and we\n    support our customers’ compliance with the CCPA.\n"
source_yaml_url: https://artifacts.apis.io/metabase/compliance/metabase-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Metabase's own page on 2026-11-10.
synthetic: false
tags:
- Metabase
- Analytics
- Business Intelligence
- Dashboards
- Data Visualization
- Open Source
- SQL
---
