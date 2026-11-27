---
api_specs:
- filename: mongodb-atlas-clusters-api-openapi.yml
  format: yaml
  label: MongoDB Atlas Clusters API
  slug: mongodb-atlas-clusters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mongodb-atlas/openapi/mongodb-atlas-clusters-api-openapi.yml
- filename: mongodb-atlas-database-users-api-openapi.yml
  format: yaml
  label: MongoDB Atlas Database Users API
  slug: mongodb-atlas-database-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mongodb-atlas/openapi/mongodb-atlas-database-users-api-openapi.yml
- filename: mongodb-atlas-organizations-api-openapi.yml
  format: yaml
  label: MongoDB Atlas Organizations API
  slug: mongodb-atlas-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mongodb-atlas/openapi/mongodb-atlas-organizations-api-openapi.yml
- filename: mongodb-atlas-projects-api-openapi.yml
  format: yaml
  label: MongoDB Atlas Projects API
  slug: mongodb-atlas-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mongodb-atlas/openapi/mongodb-atlas-projects-api-openapi.yml
claim_count: 12
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: unstated
    period: Oct 2025 - Mar 2026
    report_access: unstated
    scope: unstated
    text: SOC2 + HITRUST Mapping Report Oct 2025 - Mar 2026
    type: SOC 2 Type II report
  - framework: ISO27001
    issuer: unstated
    period: null
    report_access: unstated
    scope: unstated
    text: ISO 27001:2022
    type: ISO 27001:2022 certificate
  - framework: ISO27017
    issuer: unstated
    period: null
    report_access: unstated
    scope: unstated
    text: ISO 27017
    type: certification badge
  - framework: ISO27018
    issuer: unstated
    period: null
    report_access: unstated
    scope: unstated
    text: ISO 27018
    type: certification badge
  - framework: ISO9001
    issuer: unstated
    period: null
    report_access: unstated
    scope: unstated
    text: ISO 9001
    type: certification badge
  - framework: CSA-STAR
    issuer: unstated
    period: null
    report_access: unstated
    scope: unstated
    text: CSA CAIQ v4 xlsx
    type: CSA CAIQ v4 document
  - framework: PCI-DSS
    issuer: unstated
    period: null
    report_access: unstated
    scope: unstated
    text: PCI Attestation of Compliance (AoC)
    type: PCI Attestation of Compliance (AoC)
  - framework: HIPAA
    issuer: unstated
    period: null
    report_access: unstated
    scope: unstated
    text: HIPAA Attestation
    type: HIPAA attestation
  - framework: HITRUST
    issuer: unstated
    period: Apr 2025 - Sep 2025
    report_access: unstated
    scope: unstated
    text: SOC 2 + HITRUST Mapping Report Apr 2025 - Sep 2025
    type: SOC 2 + HITRUST mapping report
  - framework: FedRAMP
    issuer: unstated
    period: null
    report_access: unstated
    scope: unstated
    text: FedRAMP
    type: certification badge
  - framework: GDPR
    issuer: unstated
    period: null
    report_access: unstated
    scope: unstated
    text: GDPR
    type: certification badge
  - framework: TISAX
    issuer: unstated
    period: null
    report_access: unstated
    scope: unstated
    text: TISAX
    type: certification badge
  trust_center:
    url: https://trust.mongodb.com/
frameworks:
- CSA-STAR
- FedRAMP
- GDPR
- HIPAA
- HITRUST
- ISO27001
- ISO27017
- ISO27018
- ISO9001
- PCI-DSS
- SOC2
- TISAX
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: MongoDB Atlas
provenance_date: '2026-11-10'
provider_name: MongoDB Atlas
provider_slug: mongodb-atlas
slug: mongodb-atlas-compliance
source_date: '2026-11-10'
source_filename: mongodb-atlas-compliance.yml
source_heading: Compliance
source_page: https://trust.mongodb.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: MongoDB Atlas\naid: mongodb-atlas\nurl: https://trust.mongodb.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/mongodb-atlas-trust-center.yml\ntrust_center:\n  url: https://trust.mongodb.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: unstated\n  period: Oct 2025 - Mar 2026\n  issuer: unstated\n  report_access: unstated\n  text: SOC2 + HITRUST Mapping Report Oct 2025 - Mar 2026\n- framework: ISO27001\n  type: ISO 27001:2022 certificate\n  scope: unstated\n  period: null\n  issuer: unstated\n  report_access: unstated\n  text: ISO 27001:2022\n- framework: ISO27017\n\
  \  type: certification badge\n  scope: unstated\n  period: null\n  issuer: unstated\n  report_access: unstated\n  text: ISO 27017\n- framework: ISO27018\n  type: certification badge\n  scope: unstated\n  period: null\n  issuer: unstated\n  report_access: unstated\n  text: ISO 27018\n- framework: ISO9001\n  type: certification badge\n  scope: unstated\n  period: null\n  issuer: unstated\n  report_access: unstated\n  text: ISO 9001\n- framework: CSA-STAR\n  type: CSA CAIQ v4 document\n  scope: unstated\n  period: null\n  issuer: unstated\n  report_access: unstated\n  text: CSA CAIQ v4 xlsx\n- framework: PCI-DSS\n  type: PCI Attestation of Compliance (AoC)\n  scope: unstated\n  period: null\n  issuer: unstated\n  report_access: unstated\n  text: PCI Attestation of Compliance (AoC)\n- framework: HIPAA\n  type: HIPAA attestation\n  scope: unstated\n  period: null\n  issuer: unstated\n  report_access: unstated\n  text: HIPAA Attestation\n- framework: HITRUST\n  type: SOC 2 + HITRUST mapping\
  \ report\n  scope: unstated\n  period: Apr 2025 - Sep 2025\n  issuer: unstated\n  report_access: unstated\n  text: SOC 2 + HITRUST Mapping Report Apr 2025 - Sep 2025\n- framework: FedRAMP\n  type: certification badge\n  scope: unstated\n  period: null\n  issuer: unstated\n  report_access: unstated\n  text: FedRAMP\n- framework: GDPR\n  type: certification badge\n  scope: unstated\n  period: null\n  issuer: unstated\n  report_access: unstated\n  text: GDPR\n- framework: TISAX\n  type: certification badge\n  scope: unstated\n  period: null\n  issuer: unstated\n  report_access: unstated\n  text: TISAX\n"
source_yaml_url: https://artifacts.apis.io/mongodb-atlas/compliance/mongodb-atlas-compliance.yml
stated_fields:
- attestations
summary_line: 12 quoted statements, read from MongoDB Atlas's own page on 2026-11-10.
synthetic: false
tags:
- Database
- Document Database
- NoSQL
- MongoDB
- Cloud Database
- Database-as-a-Service
- Vector Search
- Atlas
---
