---
api_specs:
- filename: particle-health-authentication-api-openapi.yml
  format: yaml
  label: Particle Health Authentication API
  slug: particle-health-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/particle-health/openapi/particle-health-authentication-api-openapi.yml
- filename: particle-health-batches-api-openapi.yml
  format: yaml
  label: Particle Health Batches API
  slug: particle-health-batches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/particle-health/openapi/particle-health-batches-api-openapi.yml
- filename: particle-health-ccda-api-openapi.yml
  format: yaml
  label: Particle Health CCDA API
  slug: particle-health-ccda-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/particle-health/openapi/particle-health-ccda-api-openapi.yml
- filename: particle-health-deltas-api-openapi.yml
  format: yaml
  label: Particle Health Deltas API
  slug: particle-health-deltas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/particle-health/openapi/particle-health-deltas-api-openapi.yml
- filename: particle-health-documents-api-openapi.yml
  format: yaml
  label: Particle Health Documents API
  slug: particle-health-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/particle-health/openapi/particle-health-documents-api-openapi.yml
- filename: particle-health-fhir-api-openapi.yml
  format: yaml
  label: Particle Health FHIR API
  slug: particle-health-fhir-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/particle-health/openapi/particle-health-fhir-api-openapi.yml
- filename: particle-health-files-api-openapi.yml
  format: yaml
  label: Particle Health Files API
  slug: particle-health-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/particle-health/openapi/particle-health-files-api-openapi.yml
- filename: particle-health-flat-api-openapi.yml
  format: yaml
  label: Particle Health Flat API
  slug: particle-health-flat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/particle-health/openapi/particle-health-flat-api-openapi.yml
- filename: particle-health-hl7v2-api-openapi.yml
  format: yaml
  label: Particle Health HL7v2 API
  slug: particle-health-hl7v2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/particle-health/openapi/particle-health-hl7v2-api-openapi.yml
- filename: particle-health-networkparticipants-api-openapi.yml
  format: yaml
  label: Particle Health NetworkParticipants API
  slug: particle-health-networkparticipants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/particle-health/openapi/particle-health-networkparticipants-api-openapi.yml
- filename: particle-health-notifications-api-openapi.yml
  format: yaml
  label: Particle Health Notifications API
  slug: particle-health-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/particle-health/openapi/particle-health-notifications-api-openapi.yml
- filename: particle-health-patients-api-openapi.yml
  format: yaml
  label: Particle Health Patients API
  slug: particle-health-patients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/particle-health/openapi/particle-health-patients-api-openapi.yml
- filename: particle-health-projects-api-openapi.yml
  format: yaml
  label: Particle Health Projects API
  slug: particle-health-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/particle-health/openapi/particle-health-projects-api-openapi.yml
- filename: particle-health-providermap-api-openapi.yml
  format: yaml
  label: Particle Health ProviderMap API
  slug: particle-health-providermap-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/particle-health/openapi/particle-health-providermap-api-openapi.yml
- filename: particle-health-queries-api-openapi.yml
  format: yaml
  label: Particle Health Queries API
  slug: particle-health-queries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/particle-health/openapi/particle-health-queries-api-openapi.yml
- filename: particle-health-signal-api-openapi.yml
  format: yaml
  label: Particle Health Signal API
  slug: particle-health-signal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/particle-health/openapi/particle-health-signal-api-openapi.yml
- filename: particle-health-subscriptions-api-openapi.yml
  format: yaml
  label: Particle Health Subscriptions API
  slug: particle-health-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/particle-health/openapi/particle-health-subscriptions-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: HITRUST
    issuer: null
    period: null
    report_access: unstated
    scope: Particle Health platform
    text: 'The Particle Health platform includes: HITRUST Certification:'
    type: Certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: API platform
    text: 'SOC 2 Compliance: This ensures that our API platform, which provides digital healthcare providers with access to more than 300 million patient electronic health records (EHRs), is operating with industry-leading data security standards.'
    type: SOC 2 Compliance
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Personal health information handling
    text: By complying with HIPAA, we can help ensure that your personal health information is kept private and secure.
    type: Compliance
  trust_center:
    url: https://particlehealth.com/security
frameworks:
- HIPAA
- HITRUST
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Particle Health
provenance_date: '2026-11-10'
provider_name: Particle Health
provider_slug: particle-health
slug: particle-health-compliance
source_date: '2026-11-10'
source_filename: particle-health-compliance.yml
source_heading: Compliance
source_page: https://particlehealth.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Particle Health\naid: particle-health\nurl: https://particlehealth.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/particle-health-trust-center.yml\ntrust_center:\n  url: https://particlehealth.com/security\nattestations:\n- framework: HITRUST\n  type: Certification\n  scope: Particle Health platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'The Particle Health platform includes: HITRUST Certification:'\n- framework: SOC2\n  type: SOC 2 Compliance\n  scope: API platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'SOC 2 Compliance: This\
  \ ensures that our API platform, which provides digital healthcare providers with\n    access to more than 300 million patient electronic health records (EHRs), is operating with industry-leading\n    data security standards.'\n- framework: HIPAA\n  type: Compliance\n  scope: Personal health information handling\n  period: null\n  issuer: null\n  report_access: unstated\n  text: By complying with HIPAA, we can help ensure that your personal health information is kept private and secure.\n"
source_yaml_url: https://artifacts.apis.io/particle-health/compliance/particle-health-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Particle Health's own page on 2026-11-10.
synthetic: false
tags:
- ADT
- C-CDA
- Care Coordination
- Carequality
- Clinical Data
- CommonWell
- Deltas
- eHealth Exchange
- Electronic Health Records
- FHIR
- Health Data
- Health Information Exchange
- Healthcare
- HIE
- HL7
- HL7v2
- Interoperability
- Medical Records
- Patients
- Pharmacy
- QHIN
- Surescripts
- TEFCA
- USCDI
---
