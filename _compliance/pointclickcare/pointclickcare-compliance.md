---
api_specs:
- filename: pointclickcare-assessments-api-openapi.yml
  format: yaml
  label: PointClickCare Assessments API
  slug: pointclickcare-assessments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pointclickcare/openapi/pointclickcare-assessments-api-openapi.yml
- filename: pointclickcare-diagnoses-api-openapi.yml
  format: yaml
  label: PointClickCare Diagnoses API
  slug: pointclickcare-diagnoses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pointclickcare/openapi/pointclickcare-diagnoses-api-openapi.yml
- filename: pointclickcare-facilities-api-openapi.yml
  format: yaml
  label: PointClickCare Facilities API
  slug: pointclickcare-facilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pointclickcare/openapi/pointclickcare-facilities-api-openapi.yml
- filename: pointclickcare-medications-api-openapi.yml
  format: yaml
  label: PointClickCare Medications API
  slug: pointclickcare-medications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pointclickcare/openapi/pointclickcare-medications-api-openapi.yml
- filename: pointclickcare-patients-api-openapi.yml
  format: yaml
  label: PointClickCare Patients API
  slug: pointclickcare-patients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pointclickcare/openapi/pointclickcare-patients-api-openapi.yml
- filename: pointclickcare-vitals-api-openapi.yml
  format: yaml
  label: PointClickCare Vitals API
  slug: pointclickcare-vitals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pointclickcare/openapi/pointclickcare-vitals-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: '2025'
    report_access: unstated
    scope: Senior Care EHR Solution - Core Platform
    text: PointClickCare - 2025 SOC 2 Type 2 - Report
    type: Type 2
  - framework: SOC1
    issuer: null
    period: '2025'
    report_access: unstated
    scope: Senior Care EHR Solution - Core Platform
    text: PointClickCare - 2025 SOC 1 Type 2 - Report
    type: Type 2
  - framework: HITRUST
    issuer: null
    period: null
    report_access: unstated
    scope: Collective Platform (A&P)
    text: 'Certifications: HITRUST'
    type: null
  - framework: NIST-CSF
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Badges SOC 2 Type II HITRUST NIST CSF
    type: badge
  trust_center:
    url: https://trust.pointclickcare.com/
frameworks:
- HITRUST
- NIST-CSF
- SOC1
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: PointClickCare
provenance_date: '2026-11-10'
provider_name: PointClickCare
provider_slug: pointclickcare
slug: pointclickcare-compliance
source_date: '2026-11-10'
source_filename: pointclickcare-compliance.yml
source_heading: Compliance
source_page: https://trust.pointclickcare.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: PointClickCare\naid: pointclickcare\nurl: https://trust.pointclickcare.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/pointclickcare-trust-center.yml\ntrust_center:\n  url: https://trust.pointclickcare.com/\nattestations:\n- framework: SOC2\n  type: Type 2\n  scope: Senior Care EHR Solution - Core Platform\n  period: '2025'\n  issuer: null\n  report_access: unstated\n  text: PointClickCare - 2025 SOC 2 Type 2 - Report\n- framework: SOC1\n  type: Type 2\n  scope: Senior Care EHR Solution - Core Platform\n  period: '2025'\n  issuer: null\n  report_access: unstated\n  text: PointClickCare - 2025\
  \ SOC 1 Type 2 - Report\n- framework: HITRUST\n  type: null\n  scope: Collective Platform (A&P)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'Certifications: HITRUST'\n- framework: NIST-CSF\n  type: badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Badges SOC 2 Type II HITRUST NIST CSF\n"
source_yaml_url: https://artifacts.apis.io/pointclickcare/compliance/pointclickcare-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from PointClickCare's own page on 2026-11-10.
synthetic: false
tags:
- Healthcare
- Long-Term Care
- Post-Acute Care
- Electronic Health Records
- FHIR
- Senior Care
- Interoperability
---
