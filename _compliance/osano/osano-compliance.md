---
api_specs:
- filename: osano-cmp-api-openapi.yml
  format: yaml
  label: Osano Cmp API
  slug: osano-cmp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osano/openapi/osano-cmp-api-openapi.yml
- filename: osano-cmprules-api-openapi.yml
  format: yaml
  label: Osano Cmp Rules API
  slug: osano-cmprules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osano/openapi/osano-cmprules-api-openapi.yml
- filename: osano-collections-api-openapi.yml
  format: yaml
  label: Osano Collections API
  slug: osano-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osano/openapi/osano-collections-api-openapi.yml
- filename: osano-config-api-openapi.yml
  format: yaml
  label: Osano Config API
  slug: osano-config-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osano/openapi/osano-config-api-openapi.yml
- filename: osano-connectors-api-openapi.yml
  format: yaml
  label: Osano Connectors API
  slug: osano-connectors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osano/openapi/osano-connectors-api-openapi.yml
- filename: osano-consent-profiles-api-openapi.yml
  format: yaml
  label: Osano Consent Profiles API
  slug: osano-consent-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osano/openapi/osano-consent-profiles-api-openapi.yml
- filename: osano-consents-api-openapi.yml
  format: yaml
  label: Osano Consents API
  slug: osano-consents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osano/openapi/osano-consents-api-openapi.yml
- filename: osano-customerinsights-api-openapi.yml
  format: yaml
  label: Osano Customer Insights API
  slug: osano-customerinsights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osano/openapi/osano-customerinsights-api-openapi.yml
- filename: osano-dsar-api-openapi.yml
  format: yaml
  label: Osano Dsar API
  slug: osano-dsar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osano/openapi/osano-dsar-api-openapi.yml
- filename: osano-dsaractionitems-api-openapi.yml
  format: yaml
  label: Osano Dsar Action Items API
  slug: osano-dsaractionitems-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osano/openapi/osano-dsaractionitems-api-openapi.yml
- filename: osano-sessions-api-openapi.yml
  format: yaml
  label: Osano Sessions API
  slug: osano-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osano/openapi/osano-sessions-api-openapi.yml
- filename: osano-subjectrightsportal-api-openapi.yml
  format: yaml
  label: Osano Subject Rights Portal API
  slug: osano-subjectrightsportal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osano/openapi/osano-subjectrightsportal-api-openapi.yml
- filename: osano-subjects-api-openapi.yml
  format: yaml
  label: Osano Subjects API
  slug: osano-subjects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osano/openapi/osano-subjects-api-openapi.yml
- filename: osano-token-api-openapi.yml
  format: yaml
  label: Osano Token API
  slug: osano-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osano/openapi/osano-token-api-openapi.yml
- filename: osano-unified-consent-core-api-api-openapi.yml
  format: yaml
  label: Osano Unified Consent Core API
  slug: osano-unified-consent-core-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osano/openapi/osano-unified-consent-core-api-api-openapi.yml
- filename: osano-data-discovery-api-openapi.yml
  format: yaml
  label: Osano Data Discovery API
  slug: osano-data-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osano/openapi/osano-data-discovery-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: not stated
    text: We recently updated our SOC 2 Type II Report!
    type: Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: null
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    source: https://trust.osano.com/
    text: We recently updated our SOC 2 Type II Report!
    type: SOC 2 Type II Report
  trust_center:
    url: https://trust.osano.com/
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Osano
provenance_date: '2026-11-10'
provider_name: Osano
provider_slug: osano
slug: osano-compliance
source_date: '2026-11-10'
source_filename: osano-compliance.yml
source_heading: Compliance
source_page: https://trust.osano.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Osano\naid: osano\nurl: https://trust.osano.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/osano-trust-center.yml\n  sources:\n  - https://trust.osano.com/\ntrust_center:\n  url: https://trust.osano.com/\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: not stated\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We recently updated our SOC 2 Type II Report!\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: SOC2\n  type: SOC 2 Type II Report\n  scope: null\n  period: null\n  issuer:\
  \ null\n  report_access: on_request\n  text: We recently updated our SOC 2 Type II Report!\n  source: https://trust.osano.com/\n"
source_yaml_url: https://artifacts.apis.io/osano/compliance/osano-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Osano's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Privacy
- Consent Management
- Compliance
- GDPR
- CCPA
- Cookie Consent
- Subject Rights
- Data Mapping
- Vendor Risk
- Privacy Assessments
- Governance Risk Compliance
---
