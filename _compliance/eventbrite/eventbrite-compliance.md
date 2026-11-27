---
api_specs:
- filename: eventbrite-attendees-api-openapi.yml
  format: yaml
  label: Eventbrite Attendees API
  slug: eventbrite-attendees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventbrite/openapi/eventbrite-attendees-api-openapi.yml
- filename: eventbrite-categories-api-openapi.yml
  format: yaml
  label: Eventbrite Categories API
  slug: eventbrite-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventbrite/openapi/eventbrite-categories-api-openapi.yml
- filename: eventbrite-events-api-openapi.yml
  format: yaml
  label: Eventbrite Events API
  slug: eventbrite-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventbrite/openapi/eventbrite-events-api-openapi.yml
- filename: eventbrite-orders-api-openapi.yml
  format: yaml
  label: Eventbrite Orders API
  slug: eventbrite-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventbrite/openapi/eventbrite-orders-api-openapi.yml
- filename: eventbrite-organizations-api-openapi.yml
  format: yaml
  label: Eventbrite Organizations API
  slug: eventbrite-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventbrite/openapi/eventbrite-organizations-api-openapi.yml
- filename: eventbrite-ticket-classes-api-openapi.yml
  format: yaml
  label: Eventbrite Ticket Classes API
  slug: eventbrite-ticket-classes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventbrite/openapi/eventbrite-ticket-classes-api-openapi.yml
- filename: eventbrite-users-api-openapi.yml
  format: yaml
  label: Eventbrite Users API
  slug: eventbrite-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventbrite/openapi/eventbrite-users-api-openapi.yml
- filename: eventbrite-venues-api-openapi.yml
  format: yaml
  label: Eventbrite Venues API
  slug: eventbrite-venues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventbrite/openapi/eventbrite-venues-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: Qualified Security Assessor (Coalfire, Inc.)
    period: null
    report_access: public
    scope: Eventbrite as Merchant and Service Provider
    text: Eventbrite complies with PCI-DSS 4.0.1 Level 1 as both a Merchant and a Service Provider.
    type: Attestation of Compliance (Level 1, Merchant and Service Provider)
  - framework: SOC2
    issuer: null
    period: null
    report_access: public
    scope: Eventbrite Systems and Organization Controls
    text: Eventbrite Latest SOC2 Report
    type: SOC report
  - framework: SOC3
    issuer: null
    period: null
    report_access: public
    scope: Security, Availability & Confidentiality
    text: Eventbrite SOC 3 Security, Availability & Confidentiality Report, available for Download.
    type: SOC 3 Security, Availability & Confidentiality Report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Amazon EC2 hosting environment referenced on page
    text: ISO 27001 certified
    type: ISO 27001 certification
  trust_center:
    url: https://www.eventbrite.com/security/
frameworks:
- ISO27001
- PCI-DSS
- SOC2
- SOC3
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Eventbrite
provenance_date: '2026-11-09'
provider_name: Eventbrite
provider_slug: eventbrite
slug: eventbrite-compliance
source_date: '2026-11-09'
source_filename: eventbrite-compliance.yml
source_heading: Compliance
source_page: https://www.eventbrite.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Eventbrite\naid: eventbrite\nurl: https://www.eventbrite.com/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/eventbrite-trust-center.yml\ntrust_center:\n  url: https://www.eventbrite.com/security/\nattestations:\n- framework: PCI-DSS\n  type: Attestation of Compliance (Level 1, Merchant and Service Provider)\n  scope: Eventbrite as Merchant and Service Provider\n  period: null\n  issuer: Qualified Security Assessor (Coalfire, Inc.)\n  report_access: public\n  text: Eventbrite complies with PCI-DSS 4.0.1 Level 1 as both a Merchant and a Service Provider.\n- framework: SOC2\n  type: SOC report\n\
  \  scope: Eventbrite Systems and Organization Controls\n  period: null\n  issuer: null\n  report_access: public\n  text: Eventbrite Latest SOC2 Report\n- framework: SOC3\n  type: SOC 3 Security, Availability & Confidentiality Report\n  scope: Security, Availability & Confidentiality\n  period: null\n  issuer: null\n  report_access: public\n  text: Eventbrite SOC 3 Security, Availability & Confidentiality Report, available for Download.\n- framework: ISO27001\n  type: ISO 27001 certification\n  scope: Amazon EC2 hosting environment referenced on page\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001 certified\n"
source_yaml_url: https://artifacts.apis.io/eventbrite/compliance/eventbrite-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Eventbrite's own page on 2026-11-09.
synthetic: false
tags:
- Event
- Event Technology
- Ticketing
- Marketplace
---
