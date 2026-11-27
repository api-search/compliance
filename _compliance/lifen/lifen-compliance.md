---
api_specs:
- filename: lifen-communicationrequest-api-openapi.yml
  format: yaml
  label: Lifen CommunicationRequest API
  slug: lifen-communicationrequest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifen/openapi/lifen-communicationrequest-api-openapi.yml
- filename: lifen-coverage-api-openapi.yml
  format: yaml
  label: Lifen Coverage API
  slug: lifen-coverage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifen/openapi/lifen-coverage-api-openapi.yml
- filename: lifen-encounter-api-openapi.yml
  format: yaml
  label: Lifen Encounter API
  slug: lifen-encounter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifen/openapi/lifen-encounter-api-openapi.yml
- filename: lifen-organization-api-openapi.yml
  format: yaml
  label: Lifen Organization API
  slug: lifen-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifen/openapi/lifen-organization-api-openapi.yml
- filename: lifen-patient-api-openapi.yml
  format: yaml
  label: Lifen Patient API
  slug: lifen-patient-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifen/openapi/lifen-patient-api-openapi.yml
- filename: lifen-practitioner-api-openapi.yml
  format: yaml
  label: Lifen Practitioner API
  slug: lifen-practitioner-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifen/openapi/lifen-practitioner-api-openapi.yml
- filename: lifen-token-api-openapi.yml
  format: yaml
  label: Lifen Token API
  slug: lifen-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifen/openapi/lifen-token-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Solutions
    text: Nos solutions sont certifiées Hébergeur de Données de Santé (HDS)
    type: certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Lifen services
    text: nos certifications ISO 27001 et HDS
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Lifen practices
    text: vis-à-vis du Règlement Général sur la Protection des Données (RGPD)
    type: compliance
  trust_center:
    url: https://www.lifen.fr/nos-expertises/securite-des-donnees-de-sante
frameworks:
- GDPR
- HIPAA
- ISO27001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Lifen
provenance_date: '2026-11-09'
provider_name: Lifen
provider_slug: lifen
slug: lifen-compliance
source_date: '2026-11-09'
source_filename: lifen-compliance.yml
source_heading: Compliance
source_page: https://www.lifen.fr/nos-expertises/securite-des-donnees-de-sante
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Lifen\naid: lifen\nurl: https://www.lifen.fr/nos-expertises/securite-des-donnees-de-sante\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.lifen.fr/nos-expertises/securite-des-donnees-de-sante\nattestations:\n- framework: HIPAA\n  type: certification\n  scope: Solutions\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Nos solutions sont certifiées Hébergeur de Données de Santé (HDS)\n- framework: ISO27001\n  type: certification\n  scope: Lifen services\n  period: null\n  issuer: null\n  report_access: unstated\n  text: nos certifications ISO 27001 et HDS\n- framework: GDPR\n  type:\
  \ compliance\n  scope: Lifen practices\n  period: null\n  issuer: null\n  report_access: unstated\n  text: vis-à-vis du Règlement Général sur la Protection des Données (RGPD)\n"
source_yaml_url: https://artifacts.apis.io/lifen/compliance/lifen-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Lifen's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- FHIR
- Interoperability
- Health Data
- Electronic Health Records
- Medical Documents
- Secure Messaging
- France
- HL7
---
