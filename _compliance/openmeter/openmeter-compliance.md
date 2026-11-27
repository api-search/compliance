---
api_specs:
- filename: openmeter-billing-api-openapi.yml
  format: yaml
  label: OpenMeter Billing API
  slug: openmeter-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openmeter/openapi/openmeter-billing-api-openapi.yml
- filename: openmeter-customers-api-openapi.yml
  format: yaml
  label: OpenMeter Customers API
  slug: openmeter-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openmeter/openapi/openmeter-customers-api-openapi.yml
- filename: openmeter-entitlements-api-openapi.yml
  format: yaml
  label: OpenMeter Entitlements API
  slug: openmeter-entitlements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openmeter/openapi/openmeter-entitlements-api-openapi.yml
- filename: openmeter-events-api-openapi.yml
  format: yaml
  label: OpenMeter Events API
  slug: openmeter-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openmeter/openapi/openmeter-events-api-openapi.yml
- filename: openmeter-features-api-openapi.yml
  format: yaml
  label: OpenMeter Features API
  slug: openmeter-features-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openmeter/openapi/openmeter-features-api-openapi.yml
- filename: openmeter-grants-api-openapi.yml
  format: yaml
  label: OpenMeter Grants API
  slug: openmeter-grants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openmeter/openapi/openmeter-grants-api-openapi.yml
- filename: openmeter-meters-api-openapi.yml
  format: yaml
  label: OpenMeter Meters API
  slug: openmeter-meters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openmeter/openapi/openmeter-meters-api-openapi.yml
- filename: openmeter-notifications-api-openapi.yml
  format: yaml
  label: OpenMeter Notifications API
  slug: openmeter-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openmeter/openapi/openmeter-notifications-api-openapi.yml
- filename: openmeter-plans-api-openapi.yml
  format: yaml
  label: OpenMeter Plans API
  slug: openmeter-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openmeter/openapi/openmeter-plans-api-openapi.yml
- filename: openmeter-subjects-api-openapi.yml
  format: yaml
  label: OpenMeter Subjects API
  slug: openmeter-subjects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openmeter/openapi/openmeter-subjects-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: OpenMeter Cloud
    text: Visit the Trust Center to access reports.
    type: Type 2
  trust_center:
    url: https://openmeter.io/security
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: OpenMeter
provenance_date: '2026-11-10'
provider_name: OpenMeter
provider_slug: openmeter
slug: openmeter-compliance
source_date: '2026-11-10'
source_filename: openmeter-compliance.yml
source_heading: Compliance
source_page: https://openmeter.io/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: OpenMeter\naid: openmeter\nurl: https://openmeter.io/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/openmeter-trust-center.yml\ntrust_center:\n  url: https://openmeter.io/security\nattestations:\n- framework: SOC2\n  type: Type 2\n  scope: OpenMeter Cloud\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Visit the Trust Center to access reports.\n"
source_yaml_url: https://artifacts.apis.io/openmeter/compliance/openmeter-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from OpenMeter's own page on 2026-11-10.
synthetic: false
tags:
- Usage Metering
- Billing
- Entitlements
- CloudEvents
- Open Source
- Artificial Intelligence
- Usage-Based Billing
---
