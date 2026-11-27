---
api_specs:
- filename: planning-center-calendar-api-openapi.yml
  format: yaml
  label: Planning Center Calendar API
  slug: planning-center-calendar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/planning-center/openapi/planning-center-calendar-api-openapi.yml
- filename: planning-center-check-ins-api-openapi.yml
  format: yaml
  label: Planning Center Check-Ins API
  slug: planning-center-check-ins-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/planning-center/openapi/planning-center-check-ins-api-openapi.yml
- filename: planning-center-giving-api-openapi.yml
  format: yaml
  label: Planning Center Giving API
  slug: planning-center-giving-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/planning-center/openapi/planning-center-giving-api-openapi.yml
- filename: planning-center-groups-api-openapi.yml
  format: yaml
  label: Planning Center Groups API
  slug: planning-center-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/planning-center/openapi/planning-center-groups-api-openapi.yml
- filename: planning-center-people-api-openapi.yml
  format: yaml
  label: Planning Center People API
  slug: planning-center-people-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/planning-center/openapi/planning-center-people-api-openapi.yml
- filename: planning-center-publishing-api-openapi.yml
  format: yaml
  label: Planning Center Publishing API
  slug: planning-center-publishing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/planning-center/openapi/planning-center-publishing-api-openapi.yml
- filename: planning-center-registrations-api-openapi.yml
  format: yaml
  label: Planning Center Registrations API
  slug: planning-center-registrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/planning-center/openapi/planning-center-registrations-api-openapi.yml
- filename: planning-center-services-api-openapi.yml
  format: yaml
  label: Planning Center Services API
  slug: planning-center-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/planning-center/openapi/planning-center-services-api-openapi.yml
- filename: planning-center-webhooks-api-openapi.yml
  format: yaml
  label: Planning Center Webhooks API
  slug: planning-center-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/planning-center/openapi/planning-center-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: Johanson Group
    period: null
    report_access: on_request
    scope: security, availability, processing integrity, confidentiality, and privacy
    text: Planning Center is SOC 2 Type 2 certified.
    type: SOC 2 Type 2 audit report
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: cardholder data
    text: Planning Center is a PCI Level One compliant merchant.
    type: PCI compliance
  trust_center:
    url: https://www.planningcenter.com/security
frameworks:
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Planning Center
provenance_date: '2026-11-10'
provider_name: Planning Center
provider_slug: planning-center
slug: planning-center-compliance
source_date: '2026-11-10'
source_filename: planning-center-compliance.yml
source_heading: Compliance
source_page: https://www.planningcenter.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Planning Center\naid: planning-center\nurl: https://www.planningcenter.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/planning-center-trust-center.yml\ntrust_center:\n  url: https://www.planningcenter.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 audit report\n  scope: security, availability, processing integrity, confidentiality, and privacy\n  period: null\n  issuer: Johanson Group\n  report_access: on_request\n  text: Planning Center is SOC 2 Type 2 certified.\n- framework: PCI-DSS\n  type: PCI compliance\n  scope: cardholder data\n  period: null\n  issuer: null\n\
  \  report_access: unstated\n  text: Planning Center is a PCI Level One compliant merchant.\n"
source_yaml_url: https://artifacts.apis.io/planning-center/compliance/planning-center-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Planning Center's own page on 2026-11-10.
synthetic: false
tags:
- Church Management
- ChMS
- Faith
- Giving
- Event
- Scheduling
- People
- Non-Profit
---
