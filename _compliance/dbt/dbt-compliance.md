---
api_specs:
- filename: dbt-accounts-api-openapi.yml
  format: yaml
  label: dbt Accounts API
  slug: dbt-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dbt/openapi/dbt-accounts-api-openapi.yml
- filename: dbt-environments-api-openapi.yml
  format: yaml
  label: dbt Environments API
  slug: dbt-environments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dbt/openapi/dbt-environments-api-openapi.yml
- filename: dbt-jobs-api-openapi.yml
  format: yaml
  label: dbt Jobs API
  slug: dbt-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dbt/openapi/dbt-jobs-api-openapi.yml
- filename: dbt-metrics-api-openapi.yml
  format: yaml
  label: dbt Metrics API
  slug: dbt-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dbt/openapi/dbt-metrics-api-openapi.yml
- filename: dbt-projects-api-openapi.yml
  format: yaml
  label: dbt Projects API
  slug: dbt-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dbt/openapi/dbt-projects-api-openapi.yml
- filename: dbt-runs-api-openapi.yml
  format: yaml
  label: dbt Runs API
  slug: dbt-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dbt/openapi/dbt-runs-api-openapi.yml
- filename: dbt-fastapi-api-openapi.yml
  format: yaml
  label: dbt Fast API
  slug: dbt-fastapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dbt/openapi/dbt-fastapi-api-openapi.yml
- filename: dbt-private-api-openapi.yml
  format: yaml
  label: dbt Private API
  slug: dbt-private-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dbt/openapi/dbt-private-api-openapi.yml
- filename: dbt-ready-api-openapi.yml
  format: yaml
  label: dbt Ready API
  slug: dbt-ready-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dbt/openapi/dbt-ready-api-openapi.yml
- filename: dbt-graph-ql-api-openapi.yml
  format: yaml
  label: dbt Graph QL API
  slug: dbt-graph-ql-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dbt/openapi/dbt-graph-ql-api-openapi.yml
claim_count: 9
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: 'We maintain these certifications: SOC 2 Type 2, GDPR, CCPA, ISO 27701, ISO 27001:2022, ISO 42001.'
    type: SOC 2 Type 2
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001:2022
    type: ISO 27001:2022
  - framework: ISO27017
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27017
    type: ISO 27017
  - framework: ISO27018
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27018:2019
    type: ISO 27018:2019
  - framework: ISO42001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 42001:2023
    type: ISO 42001:2023
  - framework: ISO27701
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27701
    type: ISO 27701
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: GDPR
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA
    type: CCPA
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We align with OWASP, NIST, and HIPAA Security standards.
    type: HIPAA Security standards alignment
  trust_center:
    url: https://trust.getdbt.com/
frameworks:
- CCPA
- GDPR
- HIPAA
- ISO27001
- ISO27017
- ISO27018
- ISO27701
- ISO42001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: dbt
provenance_date: '2026-11-09'
provider_name: dbt
provider_slug: dbt
slug: dbt-compliance
source_date: '2026-11-09'
source_filename: dbt-compliance.yml
source_heading: Compliance
source_page: https://trust.getdbt.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: dbt\naid: dbt\nurl: https://trust.getdbt.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/dbt-trust-center.yml\ntrust_center:\n  url: https://trust.getdbt.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'We maintain these certifications: SOC 2 Type 2, GDPR, CCPA, ISO 27701, ISO 27001:2022, ISO 42001.'\n- framework: ISO27001\n  type: ISO 27001:2022\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022\n- framework: ISO27017\n  type: ISO 27017\n  scope: null\n\
  \  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27017\n- framework: ISO27018\n  type: ISO 27018:2019\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27018:2019\n- framework: ISO42001\n  type: ISO 42001:2023\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 42001:2023\n- framework: ISO27701\n  type: ISO 27701\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27701\n- framework: GDPR\n  type: GDPR\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: CCPA\n  type: CCPA\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA\n- framework: HIPAA\n  type: HIPAA Security standards alignment\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We align with OWASP, NIST, and HIPAA Security standards.\n"
source_yaml_url: https://artifacts.apis.io/dbt/compliance/dbt-compliance.yml
stated_fields:
- attestations
summary_line: 9 quoted statements, read from dbt's own page on 2026-11-09.
synthetic: false
tags:
- Analytics Engineering
- Data
- ELT
- Metrics
- Project
- SQL
- Transformation
---
