---
api_specs:
- filename: metaplane-connections-api-openapi.yml
  format: yaml
  label: Metaplane Connections API
  slug: metaplane-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metaplane/openapi/metaplane-connections-api-openapi.yml
- filename: metaplane-monitors-api-openapi.yml
  format: yaml
  label: Metaplane Monitors API
  slug: metaplane-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metaplane/openapi/metaplane-monitors-api-openapi.yml
- filename: metaplane-tags-api-openapi.yml
  format: yaml
  label: Metaplane Tags API
  slug: metaplane-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metaplane/openapi/metaplane-tags-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Metaplane service
    text: SOC 2 report and Data Process Addendum available upon request.
    type: report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Metaplane service
    text: Compliant with SOC 2, GDPR, and HIPAA
    type: compliance claim
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Metaplane service
    text: Compliant with SOC 2, GDPR, and HIPAA
    type: compliance claim
  trust_center:
    url: https://www.metaplane.dev/security
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Metaplane
provenance_date: '2026-11-10'
provider_name: Metaplane
provider_slug: metaplane
slug: metaplane-compliance
source_date: '2026-11-10'
source_filename: metaplane-compliance.yml
source_heading: Compliance
source_page: https://www.metaplane.dev/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Metaplane\naid: metaplane\nurl: https://www.metaplane.dev/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/metaplane-trust-center.yml\ntrust_center:\n  url: https://www.metaplane.dev/security\nattestations:\n- framework: SOC2\n  type: report\n  scope: Metaplane service\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 2 report and Data Process Addendum available upon request.\n- framework: GDPR\n  type: compliance claim\n  scope: Metaplane service\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliant with SOC 2, GDPR, and HIPAA\n- framework: HIPAA\n\
  \  type: compliance claim\n  scope: Metaplane service\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliant with SOC 2, GDPR, and HIPAA\n"
source_yaml_url: https://artifacts.apis.io/metaplane/compliance/metaplane-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Metaplane's own page on 2026-11-10.
synthetic: false
tags:
- AIOps
- Data Observability
- Data Quality
- Anomaly Detection
- Data Lineage
- Monitoring
- Analytics
- Data Engineering
- dbt
- Snowflake
---
