---
api_specs:
- filename: matillion-dpc-agents-api-openapi.yml
  format: yaml
  label: Matillion DPC Agents API
  slug: matillion-dpc-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/matillion/openapi/matillion-dpc-agents-api-openapi.yml
- filename: matillion-dpc-environments-api-openapi.yml
  format: yaml
  label: Matillion DPC Environments API
  slug: matillion-dpc-environments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/matillion/openapi/matillion-dpc-environments-api-openapi.yml
- filename: matillion-dpc-pipeline-executions-api-openapi.yml
  format: yaml
  label: Matillion DPC Pipeline Executions API
  slug: matillion-dpc-pipeline-executions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/matillion/openapi/matillion-dpc-pipeline-executions-api-openapi.yml
- filename: matillion-dpc-projects-api-openapi.yml
  format: yaml
  label: Matillion DPC Projects API
  slug: matillion-dpc-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/matillion/openapi/matillion-dpc-projects-api-openapi.yml
- filename: matillion-dpc-schedules-api-openapi.yml
  format: yaml
  label: Matillion DPC Schedules API
  slug: matillion-dpc-schedules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/matillion/openapi/matillion-dpc-schedules-api-openapi.yml
- filename: matillion-etl-groups-projects-api-openapi.yml
  format: yaml
  label: Matillion ETL Groups & Projects API
  slug: matillion-etl-groups-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/matillion/openapi/matillion-etl-groups-projects-api-openapi.yml
- filename: matillion-etl-jobs-runs-api-openapi.yml
  format: yaml
  label: Matillion ETL Jobs & Runs API
  slug: matillion-etl-jobs-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/matillion/openapi/matillion-etl-jobs-runs-api-openapi.yml
- filename: matillion-etl-schedules-api-openapi.yml
  format: yaml
  label: Matillion ETL Schedules API
  slug: matillion-etl-schedules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/matillion/openapi/matillion-etl-schedules-api-openapi.yml
- filename: matillion-etl-tasks-api-openapi.yml
  format: yaml
  label: Matillion ETL Tasks API
  slug: matillion-etl-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/matillion/openapi/matillion-etl-tasks-api-openapi.yml
claim_count: 6
description: ''
doc:
  attestations:
  - framework: SOC1
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC1 Type 2 accreditation demonstrates the commitment from Matillion to create, implement and maintain security policies and practices that address and adhere to AICPA principles.
    type: SOC1 Type 2 report
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Matillion undergoes SOC2 external audit once a year to demonstrate the continuous monitoring of controls
    type: SOC2 Type 2 report
  - framework: SOC3
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC3 Report demonstrates the commitment from Matillion to Customers that company's security controls are trustworthy.
    type: SOC3 report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: 'Matillion is now ISO 27001 : 2022 compliant.'
    type: ISO 27001:2022 certification
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Matillion is now PCI DSS 4.0.1 certified, providing an extra layer of security and assurance for businesses handling payment card data.
    type: PCI DSS 4.0.1 certification (ROC AOC)
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Protected Health Information
    text: Matillion complies with HIPAA requirements for Protected Health Information (PHI) and will sign an appropriate Business Associate Agreement (BAA) with customers who are subject to HIPAA.
    type: HIPAA compliance with BAA
  trust_center:
    url: https://www.matillion.com/trust-center
frameworks:
- HIPAA
- ISO27001
- PCI-DSS
- SOC1
- SOC2
- SOC3
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Matillion
provenance_date: '2026-11-10'
provider_name: Matillion
provider_slug: matillion
slug: matillion-compliance
source_date: '2026-11-10'
source_filename: matillion-compliance.yml
source_heading: Compliance
source_page: https://www.matillion.com/trust-center
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Matillion\naid: matillion\nurl: https://www.matillion.com/trust-center\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.matillion.com/trust-center\nattestations:\n- framework: SOC1\n  type: SOC1 Type 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC1 Type 2 accreditation demonstrates the commitment from Matillion to create, implement and maintain security\n    policies and practices that address and adhere to AICPA principles.\n- framework: SOC2\n  type: SOC2 Type 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text:\
  \ Matillion undergoes SOC2 external audit once a year to demonstrate the continuous monitoring of controls\n- framework: SOC3\n  type: SOC3 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC3 Report demonstrates the commitment from Matillion to Customers that company's security controls are\n    trustworthy.\n- framework: ISO27001\n  type: ISO 27001:2022 certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'Matillion is now ISO 27001 : 2022 compliant.'\n- framework: PCI-DSS\n  type: PCI DSS 4.0.1 certification (ROC AOC)\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Matillion is now PCI DSS 4.0.1 certified, providing an extra layer of security and assurance for businesses\n    handling payment card data.\n- framework: HIPAA\n  type: HIPAA compliance with BAA\n  scope: Protected Health Information\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Matillion\
  \ complies with HIPAA requirements for Protected Health Information (PHI) and will sign an appropriate\n    Business Associate Agreement (BAA) with customers who are subject to HIPAA.\n"
source_yaml_url: https://artifacts.apis.io/matillion/compliance/matillion-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from Matillion's own page on 2026-11-10.
synthetic: false
tags:
- Data Integration
- ETL
- ELT
- Data Pipeline
- Cloud Data Warehouse
---
