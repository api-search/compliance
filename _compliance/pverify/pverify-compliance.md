---
api_specs:
- filename: pverify-authentication-api-openapi.yml
  format: yaml
  label: pVerify Authentication API
  slug: pverify-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pverify/openapi/pverify-authentication-api-openapi.yml
- filename: pverify-eligibility-api-openapi.yml
  format: yaml
  label: pVerify Eligibility API
  slug: pverify-eligibility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pverify/openapi/pverify-eligibility-api-openapi.yml
- filename: pverify-dental-eligibility-api-openapi.yml
  format: yaml
  label: pVerify Dental Eligibility API
  slug: pverify-dental-eligibility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pverify/openapi/pverify-dental-eligibility-api-openapi.yml
- filename: pverify-insurance-discovery-api-openapi.yml
  format: yaml
  label: pVerify Insurance Discovery API
  slug: pverify-insurance-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pverify/openapi/pverify-insurance-discovery-api-openapi.yml
- filename: pverify-mbi-lookup-api-openapi.yml
  format: yaml
  label: pVerify MBI Lookup API
  slug: pverify-mbi-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pverify/openapi/pverify-mbi-lookup-api-openapi.yml
- filename: pverify-patient-demographic-validator-api-openapi.yml
  format: yaml
  label: pVerify Patient Demographic Validator API
  slug: pverify-patient-demographic-validator-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pverify/openapi/pverify-patient-demographic-validator-api-openapi.yml
- filename: pverify-claim-status-api-openapi.yml
  format: yaml
  label: pVerify Claim Status API
  slug: pverify-claim-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pverify/openapi/pverify-claim-status-api-openapi.yml
- filename: pverify-estimation-api-openapi.yml
  format: yaml
  label: pVerify Patient Cost Estimator API
  slug: pverify-estimation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pverify/openapi/pverify-estimation-api-openapi.yml
- filename: pverify-payers-api-openapi.yml
  format: yaml
  label: pVerify Payers API
  slug: pverify-payers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pverify/openapi/pverify-payers-api-openapi.yml
- filename: pverify-cgx-widget-api-openapi.yml
  format: yaml
  label: pVerify CGX Widget API
  slug: pverify-cgx-widget-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pverify/openapi/pverify-cgx-widget-api-openapi.yml
- filename: pverify-same-or-similar-api-openapi.yml
  format: yaml
  label: pVerify Same or Similar API (discontinued)
  slug: pverify-same-or-similar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pverify/openapi/pverify-same-or-similar-api-openapi.yml
- filename: pverify-cmn-api-openapi.yml
  format: yaml
  label: pVerify CMN API (discontinued)
  slug: pverify-cmn-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pverify/openapi/pverify-cmn-api-openapi.yml
- filename: pverify-snf-api-openapi.yml
  format: yaml
  label: pVerify SNF API (discontinued)
  slug: pverify-snf-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pverify/openapi/pverify-snf-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: HITRUST
    issuer: null
    period: '2026'
    report_access: unstated
    scope: DoseSpot & pVerify
    text: Interra Health has successfully completed its HITRUST i1 Certification renewal for 2026, covering both DoseSpot & pVerify.
    type: HITRUST i1 Validated Assessment / Certification
  - framework: SOC2
    issuer: null
    period: '2025'
    report_access: unstated
    scope: DoseSpot and pVerify
    text: DoseSpot and pVerify are proud to announce that we have successfully renewed our SOC 2 Type II certification for 2025!
    type: SOC 2 Type 2 renewal
  - framework: HIPAA
    issuer: null
    period: '2026'
    report_access: unstated
    scope: Interra Health
    text: HIPAA Interra Health | 2026 HIPAA SRA
    type: HIPAA SRA
  - framework: other
    issuer: null
    period: '2026'
    report_access: unstated
    scope: pVerify
    text: pVerify | 2026 Penetration Test Letter of Attestation (LoA)
    type: Penetration Test Letter of Attestation
  trust_center:
    url: https://trust.interrahealth.com/
frameworks:
- HIPAA
- HITRUST
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: pVerify
provenance_date: '2026-11-10'
provider_name: pVerify
provider_slug: pverify
slug: pverify-compliance
source_date: '2026-11-10'
source_filename: pverify-compliance.yml
source_heading: Compliance
source_page: https://trust.interrahealth.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: pVerify\naid: pverify\nurl: https://trust.interrahealth.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.interrahealth.com/\nattestations:\n- framework: HITRUST\n  type: HITRUST i1 Validated Assessment / Certification\n  scope: DoseSpot & pVerify\n  period: '2026'\n  issuer: null\n  report_access: unstated\n  text: Interra Health has successfully completed its HITRUST i1 Certification renewal for 2026, covering both DoseSpot\n    & pVerify.\n- framework: SOC2\n  type: SOC 2 Type 2 renewal\n  scope: DoseSpot and pVerify\n  period: '2025'\n  issuer: null\n  report_access: unstated\n  text: DoseSpot\
  \ and pVerify are proud to announce that we have successfully renewed our SOC 2 Type II certification\n    for 2025!\n- framework: HIPAA\n  type: HIPAA SRA\n  scope: Interra Health\n  period: '2026'\n  issuer: null\n  report_access: unstated\n  text: HIPAA Interra Health | 2026 HIPAA SRA\n- framework: other\n  type: Penetration Test Letter of Attestation\n  scope: pVerify\n  period: '2026'\n  issuer: null\n  report_access: unstated\n  text: pVerify | 2026 Penetration Test Letter of Attestation (LoA)\n"
source_yaml_url: https://artifacts.apis.io/pverify/compliance/pverify-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from pVerify's own page on 2026-11-10.
synthetic: false
tags:
- Healthcare
- Insurance
- Eligibility
- Claims
- EDI
- 270/271
- 276/277
- Revenue Cycle
- Medicare
- Payers
- Insurance Discovery
- Patient Estimation
- HIPAA
- Dental
- Health Insurance
---
