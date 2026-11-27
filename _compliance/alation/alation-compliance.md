---
api_specs:
- filename: alation-aggregated-context-api-openapi.yml
  format: yaml
  label: Alation Aggregated Context API
  slug: alation-aggregated-context-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alation/openapi/alation-aggregated-context-api-openapi.yml
- filename: alation-columns-api-openapi.yml
  format: yaml
  label: Alation Columns API
  slug: alation-columns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alation/openapi/alation-columns-api-openapi.yml
- filename: alation-custom-fields-api-openapi.yml
  format: yaml
  label: Alation Custom Fields API
  slug: alation-custom-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alation/openapi/alation-custom-fields-api-openapi.yml
- filename: alation-data-quality-api-openapi.yml
  format: yaml
  label: Alation Data Quality API
  slug: alation-data-quality-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alation/openapi/alation-data-quality-api-openapi.yml
- filename: alation-data-sources-api-openapi.yml
  format: yaml
  label: Alation Data Sources API
  slug: alation-data-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alation/openapi/alation-data-sources-api-openapi.yml
- filename: alation-dataflows-api-openapi.yml
  format: yaml
  label: Alation Dataflows API
  slug: alation-dataflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alation/openapi/alation-dataflows-api-openapi.yml
- filename: alation-glossary-terms-api-openapi.yml
  format: yaml
  label: Alation Glossary Terms API
  slug: alation-glossary-terms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alation/openapi/alation-glossary-terms-api-openapi.yml
- filename: alation-lineage-api-openapi.yml
  format: yaml
  label: Alation Lineage API
  slug: alation-lineage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alation/openapi/alation-lineage-api-openapi.yml
- filename: alation-policies-api-openapi.yml
  format: yaml
  label: Alation Policies API
  slug: alation-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alation/openapi/alation-policies-api-openapi.yml
- filename: alation-schemas-api-openapi.yml
  format: yaml
  label: Alation Schemas API
  slug: alation-schemas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alation/openapi/alation-schemas-api-openapi.yml
- filename: alation-search-api-openapi.yml
  format: yaml
  label: Alation Search API
  slug: alation-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alation/openapi/alation-search-api-openapi.yml
- filename: alation-tables-api-openapi.yml
  format: yaml
  label: Alation Tables API
  slug: alation-tables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alation/openapi/alation-tables-api-openapi.yml
claim_count: 6
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: as of January 29, 2020
    report_access: unstated
    scope: entire company and development and maintenance of products
    text: ISO 27001:2022 certified as of January 29, 2020.
    type: certification
  - framework: ISO27017
    issuer: null
    period: as of February 24, 2026
    report_access: unstated
    scope: null
    text: ISO 27017:2015 certified as of February 24, 2026.
    type: certification
  - framework: ISO27018
    issuer: null
    period: as of February 24, 2026
    report_access: unstated
    scope: null
    text: ISO 27018:2019 certified as of February 24, 2026.
    type: certification
  - framework: ISO27701
    issuer: null
    period: as of January 12, 2022
    report_access: unstated
    scope: null
    text: ISO 27701:2019 certified as of January 12, 2022.
    type: certification
  - framework: SOC2
    issuer: American Institute of CPAs (AICPA)
    period: null
    report_access: unstated
    scope: null
    text: Alation maintains an American Institute of CPAs (AICPA) Service Organization Control (SOC) 2 report.
    type: SOC 2 Type 2 report
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Alation has attained an attestation of compliance with the Health Insurance Portability and Accountability Act (HIPAA) and the Health Information Technology for Economic and Clinical Health Act (HITECH).
    type: attestation of compliance
  trust_center:
    url: https://www.alation.com/legal/security/
frameworks:
- HIPAA
- ISO27001
- ISO27017
- ISO27018
- ISO27701
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Alation
provenance_date: '2026-11-09'
provider_name: Alation
provider_slug: alation
slug: alation-compliance
source_date: '2026-11-09'
source_filename: alation-compliance.yml
source_heading: Compliance
source_page: https://www.alation.com/legal/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Alation\naid: alation\nurl: https://www.alation.com/legal/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/alation-trust-center.yml\ntrust_center:\n  url: https://www.alation.com/legal/security/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: entire company and development and maintenance of products\n  period: as of January 29, 2020\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022 certified as of January 29, 2020.\n- framework: ISO27017\n  type: certification\n  scope: null\n  period: as of February 24, 2026\n  issuer: null\n  report_access: unstated\n\
  \  text: ISO 27017:2015 certified as of February 24, 2026.\n- framework: ISO27018\n  type: certification\n  scope: null\n  period: as of February 24, 2026\n  issuer: null\n  report_access: unstated\n  text: ISO 27018:2019 certified as of February 24, 2026.\n- framework: ISO27701\n  type: certification\n  scope: null\n  period: as of January 12, 2022\n  issuer: null\n  report_access: unstated\n  text: ISO 27701:2019 certified as of January 12, 2022.\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: null\n  period: null\n  issuer: American Institute of CPAs (AICPA)\n  report_access: unstated\n  text: Alation maintains an American Institute of CPAs (AICPA) Service Organization Control (SOC) 2 report.\n- framework: HIPAA\n  type: attestation of compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Alation has attained an attestation of compliance with the Health Insurance Portability and Accountability\n    Act (HIPAA) and the Health Information\
  \ Technology for Economic and Clinical Health Act (HITECH).\n"
source_yaml_url: https://artifacts.apis.io/alation/compliance/alation-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from Alation's own page on 2026-11-09.
synthetic: false
tags:
- Data Catalog
- Data Governance
- Data Intelligence
- Data Lineage
- Data Quality
- Business Glossary
- Metadata Management
- Artificial Intelligence
---
