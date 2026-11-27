---
api_specs:
- filename: ezrentout-assets-api-openapi.yml
  format: yaml
  label: EZRentOut Assets API
  slug: ezrentout-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ezrentout/openapi/ezrentout-assets-api-openapi.yml
- filename: ezrentout-availability-api-openapi.yml
  format: yaml
  label: EZRentOut Availability API
  slug: ezrentout-availability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ezrentout/openapi/ezrentout-availability-api-openapi.yml
- filename: ezrentout-bundles-api-openapi.yml
  format: yaml
  label: EZRentOut Bundles API
  slug: ezrentout-bundles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ezrentout/openapi/ezrentout-bundles-api-openapi.yml
- filename: ezrentout-customers-api-openapi.yml
  format: yaml
  label: EZRentOut Customers API
  slug: ezrentout-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ezrentout/openapi/ezrentout-customers-api-openapi.yml
- filename: ezrentout-inventory-api-openapi.yml
  format: yaml
  label: EZRentOut Inventory API
  slug: ezrentout-inventory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ezrentout/openapi/ezrentout-inventory-api-openapi.yml
- filename: ezrentout-locations-api-openapi.yml
  format: yaml
  label: EZRentOut Locations API
  slug: ezrentout-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ezrentout/openapi/ezrentout-locations-api-openapi.yml
- filename: ezrentout-maintenance-api-openapi.yml
  format: yaml
  label: EZRentOut Maintenance API
  slug: ezrentout-maintenance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ezrentout/openapi/ezrentout-maintenance-api-openapi.yml
- filename: ezrentout-members-api-openapi.yml
  format: yaml
  label: EZRentOut Members API
  slug: ezrentout-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ezrentout/openapi/ezrentout-members-api-openapi.yml
- filename: ezrentout-orders-api-openapi.yml
  format: yaml
  label: EZRentOut Orders API
  slug: ezrentout-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ezrentout/openapi/ezrentout-orders-api-openapi.yml
- filename: ezrentout-payments-api-openapi.yml
  format: yaml
  label: EZRentOut Payments API
  slug: ezrentout-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ezrentout/openapi/ezrentout-payments-api-openapi.yml
- filename: ezrentout-purchase-orders-api-openapi.yml
  format: yaml
  label: EZRentOut Purchase Orders API
  slug: ezrentout-purchase-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ezrentout/openapi/ezrentout-purchase-orders-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: public
    scope: cloud computing offerings
    text: EZO is CSA STAR Level 1 certified.
    type: CSA STAR Level 1 certification
  - framework: SOC2
    issuer: AICPA
    period: null
    report_access: on_request
    scope: security, availability, processing integrity, confidentiality, and privacy of systems owned, managed and controlled by EZO
    text: To request EZO’s SOC 2 Type 2 report, please reach out to support@ezo.io .
    type: SOC 2 Type 2 report
  - framework: ISO27001
    issuer: Resource Inspection Canada Incorporated (RICI)
    period: null
    report_access: on_request
    scope: null
    text: EZO is certified by Resource Inspection Canada Incorporated (RICI) for ISO/IEC 27001 compliance.
    type: ISO/IEC 27001 certification
  - framework: other
    issuer: Texas Department of Information Resources
    period: null
    report_access: on_request
    scope: cloud services processing data of Texas state agencies
    text: EZO is certified by the Texas Department of Information Resources for TX RAMP Level 1 & 2.
    type: TX RAMP Level 1 & 2 certification
  trust_center:
    url: https://ezo.io/security/
frameworks:
- CSA-STAR
- ISO27001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: EZRentOut
provenance_date: '2026-11-09'
provider_name: EZRentOut
provider_slug: ezrentout
slug: ezrentout-compliance
source_date: '2026-11-09'
source_filename: ezrentout-compliance.yml
source_heading: Compliance
source_page: https://ezo.io/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: EZRentOut\naid: ezrentout\nurl: https://ezo.io/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/ezrentout-trust-center.yml\ntrust_center:\n  url: https://ezo.io/security/\nattestations:\n- framework: CSA-STAR\n  type: CSA STAR Level 1 certification\n  scope: cloud computing offerings\n  period: null\n  issuer: null\n  report_access: public\n  text: EZO is CSA STAR Level 1 certified.\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: security, availability, processing integrity, confidentiality, and privacy of systems owned, managed and\n    controlled by EZO\n  period: null\n  issuer:\
  \ AICPA\n  report_access: on_request\n  text: To request EZO’s SOC 2 Type 2 report, please reach out to support@ezo.io .\n- framework: ISO27001\n  type: ISO/IEC 27001 certification\n  scope: null\n  period: null\n  issuer: Resource Inspection Canada Incorporated (RICI)\n  report_access: on_request\n  text: EZO is certified by Resource Inspection Canada Incorporated (RICI) for ISO/IEC 27001 compliance.\n- framework: other\n  type: TX RAMP Level 1 & 2 certification\n  scope: cloud services processing data of Texas state agencies\n  period: null\n  issuer: Texas Department of Information Resources\n  report_access: on_request\n  text: EZO is certified by the Texas Department of Information Resources for TX RAMP Level 1 & 2.\n"
source_yaml_url: https://artifacts.apis.io/ezrentout/compliance/ezrentout-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from EZRentOut's own page on 2026-11-09.
synthetic: false
tags:
- Equipment Rental
- Rental Management
- Asset Tracking
- Inventory
- Order Management
- EZO
---
