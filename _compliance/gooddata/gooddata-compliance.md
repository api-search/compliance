---
api_specs:
- filename: gooddata-dashboards-api-openapi.yml
  format: yaml
  label: GoodData Dashboards API
  slug: gooddata-dashboards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gooddata/openapi/gooddata-dashboards-api-openapi.yml
- filename: gooddata-data-sources-api-openapi.yml
  format: yaml
  label: GoodData Data Sources API
  slug: gooddata-data-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gooddata/openapi/gooddata-data-sources-api-openapi.yml
- filename: gooddata-execution-api-openapi.yml
  format: yaml
  label: GoodData Execution API
  slug: gooddata-execution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gooddata/openapi/gooddata-execution-api-openapi.yml
- filename: gooddata-logical-data-model-api-openapi.yml
  format: yaml
  label: GoodData Logical Data Model API
  slug: gooddata-logical-data-model-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gooddata/openapi/gooddata-logical-data-model-api-openapi.yml
- filename: gooddata-metrics-api-openapi.yml
  format: yaml
  label: GoodData Metrics API
  slug: gooddata-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gooddata/openapi/gooddata-metrics-api-openapi.yml
- filename: gooddata-permissions-api-openapi.yml
  format: yaml
  label: GoodData Permissions API
  slug: gooddata-permissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gooddata/openapi/gooddata-permissions-api-openapi.yml
- filename: gooddata-users-api-openapi.yml
  format: yaml
  label: GoodData Users API
  slug: gooddata-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gooddata/openapi/gooddata-users-api-openapi.yml
- filename: gooddata-visualizations-api-openapi.yml
  format: yaml
  label: GoodData Visualizations API
  slug: gooddata-visualizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gooddata/openapi/gooddata-visualizations-api-openapi.yml
- filename: gooddata-workspaces-api-openapi.yml
  format: yaml
  label: GoodData Workspaces API
  slug: gooddata-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gooddata/openapi/gooddata-workspaces-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: reputable third-party auditing company
    period: null
    report_access: unstated
    scope: Security, Availability, and Confidentiality principles
    text: GoodData is SOC 2 Type II certified since 2013 and is regularly audited by a reputable third-party auditing company on Security, Availability, and Confidentiality principles.
    type: SOC 2 Type II report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: all ISO 27001 Annex A controls implemented
    text: We comply with ISO 27002 code of practices and have implemented all ISO 27001 Annex A controls.
    type: ISO 27001 compliance
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: protection of health data; will sign BAA with customers
    text: We comply with U.S. HIPAA law for the protection of health data and will sign BAA with our customers.
    type: HIPAA compliance
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: business continuity
    text: Our business continuity plan follows ISO 22301 and incorporates daily off-site backups and annual disaster recovery tests.
    type: Business continuity plan follows ISO 22301
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: product accessibility
    text: Product accessibility WCAG 2.1 AA Compliance
    type: Accessibility conformance WCAG 2.1 AA
  trust_center:
    url: https://www.gooddata.ai/security/
frameworks:
- HIPAA
- ISO27001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: GoodData
provenance_date: '2026-11-09'
provider_name: GoodData
provider_slug: gooddata
slug: gooddata-compliance
source_date: '2026-11-09'
source_filename: gooddata-compliance.yml
source_heading: Compliance
source_page: https://www.gooddata.ai/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: GoodData\naid: gooddata\nurl: https://www.gooddata.ai/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/gooddata-trust-center.yml\ntrust_center:\n  url: https://www.gooddata.ai/security/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: Security, Availability, and Confidentiality principles\n  period: null\n  issuer: reputable third-party auditing company\n  report_access: unstated\n  text: GoodData is SOC 2 Type II certified since 2013 and is regularly audited by a reputable third-party auditing\n    company on Security, Availability, and Confidentiality principles.\n\
  - framework: ISO27001\n  type: ISO 27001 compliance\n  scope: all ISO 27001 Annex A controls implemented\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We comply with ISO 27002 code of practices and have implemented all ISO 27001 Annex A controls.\n- framework: HIPAA\n  type: HIPAA compliance\n  scope: protection of health data; will sign BAA with customers\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We comply with U.S. HIPAA law for the protection of health data and will sign BAA with our customers.\n- framework: ISO27001\n  type: Business continuity plan follows ISO 22301\n  scope: business continuity\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our business continuity plan follows ISO 22301 and incorporates daily off-site backups and annual disaster\n    recovery tests.\n- framework: other\n  type: Accessibility conformance WCAG 2.1 AA\n  scope: product accessibility\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: Product accessibility WCAG 2.1 AA Compliance\n"
source_yaml_url: https://artifacts.apis.io/gooddata/compliance/gooddata-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from GoodData's own page on 2026-11-09.
synthetic: false
tags:
- Analytics
- Business Intelligence
- Embedded Analytics
- Dashboards
- Data
---
