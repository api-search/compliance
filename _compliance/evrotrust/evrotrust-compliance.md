---
api_specs:
- filename: evrotrust-all-signing-api-openapi.yml
  format: yaml
  label: Evrotrust All Signing API
  slug: evrotrust-all-signing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evrotrust/openapi/evrotrust-all-signing-api-openapi.yml
- filename: evrotrust-e-authentication-api-openapi.yml
  format: yaml
  label: Evrotrust E Authentication API
  slug: evrotrust-e-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evrotrust/openapi/evrotrust-e-authentication-api-openapi.yml
- filename: evrotrust-e-delivery-api-openapi.yml
  format: yaml
  label: Evrotrust E Delivery API
  slug: evrotrust-e-delivery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evrotrust/openapi/evrotrust-e-delivery-api-openapi.yml
- filename: evrotrust-e-signatures-api-openapi.yml
  format: yaml
  label: Evrotrust E Signatures API
  slug: evrotrust-e-signatures-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evrotrust/openapi/evrotrust-e-signatures-api-openapi.yml
- filename: evrotrust-evrotrust-eid-registered-users-api-openapi.yml
  format: yaml
  label: Evrotrust Evrotrust eID (Registered Users) API
  slug: evrotrust-evrotrust-eid-registered-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evrotrust/openapi/evrotrust-evrotrust-eid-registered-users-api-openapi.yml
- filename: evrotrust-ident-lite-advanced-basic-api-openapi.yml
  format: yaml
  label: Evrotrust Ident Lite (Advanced, Basic) API
  slug: evrotrust-ident-lite-advanced-basic-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evrotrust/openapi/evrotrust-ident-lite-advanced-basic-api-openapi.yml
- filename: evrotrust-one-time-signatures-documents-api-openapi.yml
  format: yaml
  label: Evrotrust One-time Signatures (Documents) API
  slug: evrotrust-one-time-signatures-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evrotrust/openapi/evrotrust-one-time-signatures-documents-api-openapi.yml
- filename: evrotrust-one-time-signatures-hash-api-openapi.yml
  format: yaml
  label: Evrotrust One-time Signatures (Hash) API
  slug: evrotrust-one-time-signatures-hash-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evrotrust/openapi/evrotrust-one-time-signatures-hash-api-openapi.yml
- filename: evrotrust-signing-via-app-sdk-documents-api-openapi.yml
  format: yaml
  label: Evrotrust Signing via App/SDK (Documents) API
  slug: evrotrust-signing-via-app-sdk-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evrotrust/openapi/evrotrust-signing-via-app-sdk-documents-api-openapi.yml
- filename: evrotrust-signing-via-app-sdk-hash-api-openapi.yml
  format: yaml
  label: Evrotrust Signing via App/SDK (Hash) API
  slug: evrotrust-signing-via-app-sdk-hash-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evrotrust/openapi/evrotrust-signing-via-app-sdk-hash-api-openapi.yml
claim_count: 8
description: ''
doc:
  attestations:
  - framework: ISO9001
    issuer: null
    period: null
    report_access: unstated
    scope: Evrotrust technology, services and infrastructure
    text: ISO 9001:2015
    type: certificate
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Evrotrust technology, services and infrastructure
    text: ISO/IEC 27001:2022
    type: certificate
  - framework: ISO27701
    issuer: null
    period: null
    report_access: unstated
    scope: Privacy Information Management System
    text: The company is certified under the international standard ISO/IEC 27701, which extends ISO/IEC 27001 and ISO/IEC 27002 with guidelines and requirements for managing Personally Identifiable Information (PII).
    type: certificate
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: ISO/IEC 20000-1 IT service management
    text: ISO/IEC 20000-1:2018
    type: certification
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: ISO 22301 business continuity
    text: ISO 22301:2019
    type: certification
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Qualified Trust Service Provider under eIDAS Regulation (EC) 910/2014
    text: Evrotrust is а Qualified Trust Service Provider.
    type: regulatory compliance
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Personal data processing as controller
    text: Evrotrust, as a personal data controller responsible for processing its clients’ personal data, continuously improves its Privacy Information Management System (PIMS).
    type: regulatory compliance
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Strong Customer Authentication under PSD2
    text: Evrotrust’s solution is fully compliant with Directive 2015/2366 (PSD2) and specifically meets the requirements for Strong Customer Authentication (SCA).
    type: regulatory compliance
  trust_center:
    url: https://evrotrust.com/compliance/
frameworks:
- GDPR
- ISO27001
- ISO27701
- ISO9001
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Evrotrust
provenance_date: '2026-11-09'
provider_name: Evrotrust
provider_slug: evrotrust
slug: evrotrust-compliance
source_date: '2026-11-09'
source_filename: evrotrust-compliance.yml
source_heading: Compliance
source_page: https://evrotrust.com/compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Evrotrust\naid: evrotrust\nurl: https://evrotrust.com/compliance/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://evrotrust.com/compliance/\nattestations:\n- framework: ISO9001\n  type: certificate\n  scope: Evrotrust technology, services and infrastructure\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 9001:2015\n- framework: ISO27001\n  type: certificate\n  scope: Evrotrust technology, services and infrastructure\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO/IEC 27001:2022\n- framework: ISO27701\n  type: certificate\n  scope: Privacy Information Management\
  \ System\n  period: null\n  issuer: null\n  report_access: unstated\n  text: The company is certified under the international standard ISO/IEC 27701, which extends ISO/IEC 27001 and\n    ISO/IEC 27002 with guidelines and requirements for managing Personally Identifiable Information (PII).\n- framework: other\n  type: certification\n  scope: ISO/IEC 20000-1 IT service management\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO/IEC 20000-1:2018\n- framework: other\n  type: certification\n  scope: ISO 22301 business continuity\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 22301:2019\n- framework: other\n  type: regulatory compliance\n  scope: Qualified Trust Service Provider under eIDAS Regulation (EC) 910/2014\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Evrotrust is а Qualified Trust Service Provider.\n- framework: GDPR\n  type: regulatory compliance\n  scope: Personal data processing as controller\n  period: null\n\
  \  issuer: null\n  report_access: unstated\n  text: Evrotrust, as a personal data controller responsible for processing its clients’ personal data, continuously\n    improves its Privacy Information Management System (PIMS).\n- framework: other\n  type: regulatory compliance\n  scope: Strong Customer Authentication under PSD2\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Evrotrust’s solution is fully compliant with Directive 2015/2366 (PSD2) and specifically meets the requirements\n    for Strong Customer Authentication (SCA).\n"
source_yaml_url: https://artifacts.apis.io/evrotrust/compliance/evrotrust-compliance.yml
stated_fields:
- attestations
summary_line: 8 quoted statements, read from Evrotrust's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Trust Services
- E-Signature
- Digital Identity
- eIDAS
- KYC
- Identity Verification
- Timestamping
- Compliance
---
