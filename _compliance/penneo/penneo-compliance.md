---
api_specs:
- filename: penneo-case-file-creation-api-openapi.yml
  format: yaml
  label: Penneo Case File Creation API
  slug: penneo-case-file-creation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/penneo/openapi/penneo-case-file-creation-api-openapi.yml
- filename: penneo-oauth-api-openapi.yml
  format: yaml
  label: Penneo OAuth API
  slug: penneo-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/penneo/openapi/penneo-oauth-api-openapi.yml
- filename: penneo-penneo-collect-api-api-openapi.yml
  format: yaml
  label: Penneo Penneo Collect API
  slug: penneo-penneo-collect-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/penneo/openapi/penneo-penneo-collect-api-api-openapi.yml
- filename: penneo-queue-status-check-api-openapi.yml
  format: yaml
  label: Penneo Queue Status Check API
  slug: penneo-queue-status-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/penneo/openapi/penneo-queue-status-check-api-openapi.yml
- filename: penneo-version-api-openapi.yml
  format: yaml
  label: Penneo Version API
  slug: penneo-version-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/penneo/openapi/penneo-version-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: Information Security Management System (ISMS)
    text: Certified under ISO/IEC 27001:2022 and ISO/IEC 27701:2019
    type: certification
  - framework: ISO27701
    issuer: null
    period: null
    report_access: on_request
    scope: Privacy Information Management System (PIMS)
    text: compliant with ISO/IEC 27001:2022 (Information Security) and ISO/IEC 27701:2019 (Privacy Management), respectively
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: EU-based data hosting & GDPR compliance
    text: EU-based data hosting & GDPR compliance
    type: stated compliance
  - framework: DORA
    issuer: null
    period: null
    report_access: unstated
    scope: ICT risk management and reporting obligations for financial entities
    text: Penneo supports financial entities’ ICT risk management and reporting obligations under DORA.
    type: stated support
  trust_center:
    url: https://penneo.com/trust-center/
frameworks:
- DORA
- GDPR
- ISO27001
- ISO27701
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Penneo
provenance_date: '2026-11-10'
provider_name: Penneo
provider_slug: penneo
slug: penneo-compliance
source_date: '2026-11-10'
source_filename: penneo-compliance.yml
source_heading: Compliance
source_page: https://penneo.com/trust-center/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Penneo\naid: penneo\nurl: https://penneo.com/trust-center/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://penneo.com/trust-center/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: Information Security Management System (ISMS)\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Certified under ISO/IEC 27001:2022 and ISO/IEC 27701:2019\n- framework: ISO27701\n  type: certification\n  scope: Privacy Information Management System (PIMS)\n  period: null\n  issuer: null\n  report_access: on_request\n  text: compliant with ISO/IEC 27001:2022 (Information Security) and\
  \ ISO/IEC 27701:2019 (Privacy Management), respectively\n- framework: GDPR\n  type: stated compliance\n  scope: EU-based data hosting & GDPR compliance\n  period: null\n  issuer: null\n  report_access: unstated\n  text: EU-based data hosting & GDPR compliance\n- framework: DORA\n  type: stated support\n  scope: ICT risk management and reporting obligations for financial entities\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Penneo supports financial entities’ ICT risk management and reporting obligations under DORA.\n"
source_yaml_url: https://artifacts.apis.io/penneo/compliance/penneo-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Penneo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Digital Signing
- eIDAS
- Compliance
---
