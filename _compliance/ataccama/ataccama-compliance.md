---
api_specs:
- filename: ataccama-ataccama-api-api-openapi.yml
  format: yaml
  label: Ataccama Ataccama API
  slug: ataccama-ataccama-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ataccama/openapi/ataccama-ataccama-api-api-openapi.yml
- filename: ataccama-catalog-api-openapi.yml
  format: yaml
  label: Ataccama Catalog API
  slug: ataccama-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ataccama/openapi/ataccama-catalog-api-openapi.yml
- filename: ataccama-data-quality-api-openapi.yml
  format: yaml
  label: Ataccama Data Quality API
  slug: ataccama-data-quality-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ataccama/openapi/ataccama-data-quality-api-openapi.yml
- filename: ataccama-reference-data-api-openapi.yml
  format: yaml
  label: Ataccama Reference Data API
  slug: ataccama-reference-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ataccama/openapi/ataccama-reference-data-api-openapi.yml
- filename: ataccama-rest-api-openapi.yml
  format: yaml
  label: Ataccama Rest API
  slug: ataccama-rest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ataccama/openapi/ataccama-rest-api-openapi.yml
claim_count: 8
description: ''
doc:
  attestations:
  - framework: SOC1
    issuer: independent third-party firm
    period: annual
    report_access: on_request
    scope: Ataccama ONE platform and associated services
    text: Ataccama undergoes an annual SOC 1 Type Il audit conducted by an independent third-party firm
    type: SOC 1 Type II audit
  - framework: SOC2
    issuer: independent third-party auditor
    period: annual
    report_access: on_request
    scope: Ataccama controls under AICPA Trust Services Criteria
    text: Ataccama undergoes an annual SOC 2 Type II audit, conducted by an independent third-party auditor
    type: SOC 2 Type II audit
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Protected Health Information controls mapped in SOC 2 Type II audit
    text: Ataccama aligns with HIPAA requirements to protect Personal Health Information (PHI) under US healthcare regulations.
    type: aligned with HIPAA requirements
  - framework: ISO27001
    issuer: null
    period: null
    report_access: public
    scope: Information Security Management System (ISMS)
    text: Ataccama’s Information Security Management System (ISMS) is certified to ISO 27001:2022
    type: ISO 27001:2022 certification
  - framework: ISO9001
    issuer: null
    period: null
    report_access: public
    scope: Quality Management System (QMS)
    text: Our Quality Management System (QMS) is certified to ISO 9001:2015
    type: ISO 9001:2015 certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: personal data of individuals in the European Union
    text: Ataccama adheres to the General Data Protection Regulation (GDPR)
    type: adheres to regulation
  - framework: DORA
    issuer: null
    period: null
    report_access: public
    scope: ICT risk management and operational resilience for financial institutions
    text: Ataccama aligns with the Digital Operational Resilience Act to support financial institutions
    type: aligns with regulation
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: personal information of California residents
    text: Ataccama complies with the California Consumer Privacy Act (CCPA)
    type: complies with regulation
  trust_center:
    url: https://www.ataccama.com/trust-center
frameworks:
- CCPA
- DORA
- GDPR
- HIPAA
- ISO27001
- ISO9001
- SOC1
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Ataccama
provenance_date: '2026-11-09'
provider_name: Ataccama
provider_slug: ataccama
slug: ataccama-compliance
source_date: '2026-11-09'
source_filename: ataccama-compliance.yml
source_heading: Compliance
source_page: https://www.ataccama.com/trust-center
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Ataccama\naid: ataccama\nurl: https://www.ataccama.com/trust-center\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.ataccama.com/trust-center\nattestations:\n- framework: SOC1\n  type: SOC 1 Type II audit\n  scope: Ataccama ONE platform and associated services\n  period: annual\n  issuer: independent third-party firm\n  report_access: on_request\n  text: Ataccama undergoes an annual SOC 1 Type Il audit conducted by an independent third-party firm\n- framework: SOC2\n  type: SOC 2 Type II audit\n  scope: Ataccama controls under AICPA Trust Services Criteria\n  period: annual\n  issuer: independent\
  \ third-party auditor\n  report_access: on_request\n  text: Ataccama undergoes an annual SOC 2 Type II audit, conducted by an independent third-party auditor\n- framework: HIPAA\n  type: aligned with HIPAA requirements\n  scope: Protected Health Information controls mapped in SOC 2 Type II audit\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Ataccama aligns with HIPAA requirements to protect Personal Health Information (PHI) under US healthcare\n    regulations.\n- framework: ISO27001\n  type: ISO 27001:2022 certification\n  scope: Information Security Management System (ISMS)\n  period: null\n  issuer: null\n  report_access: public\n  text: Ataccama’s Information Security Management System (ISMS) is certified to ISO 27001:2022\n- framework: ISO9001\n  type: ISO 9001:2015 certification\n  scope: Quality Management System (QMS)\n  period: null\n  issuer: null\n  report_access: public\n  text: Our Quality Management System (QMS) is certified to ISO 9001:2015\n- framework:\
  \ GDPR\n  type: adheres to regulation\n  scope: personal data of individuals in the European Union\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Ataccama adheres to the General Data Protection Regulation (GDPR)\n- framework: DORA\n  type: aligns with regulation\n  scope: ICT risk management and operational resilience for financial institutions\n  period: null\n  issuer: null\n  report_access: public\n  text: Ataccama aligns with the Digital Operational Resilience Act to support financial institutions\n- framework: CCPA\n  type: complies with regulation\n  scope: personal information of California residents\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Ataccama complies with the California Consumer Privacy Act (CCPA)\n"
source_yaml_url: https://artifacts.apis.io/ataccama/compliance/ataccama-compliance.yml
stated_fields:
- attestations
summary_line: 8 quoted statements, read from Ataccama's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Quality
- Data Governance
- Artificial Intelligence
- Enterprise
- Platform
---
