---
api_specs:
- filename: moxe-health-claims-api-openapi.yml
  format: yaml
  label: Moxe Health Claims API
  slug: moxe-health-claims-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moxe-health/openapi/moxe-health-claims-api-openapi.yml
- filename: moxe-health-patient-api-openapi.yml
  format: yaml
  label: Moxe Health Patient API
  slug: moxe-health-patient-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moxe-health/openapi/moxe-health-patient-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: audited annually
    report_access: unstated
    scope: Moxe practices including review against HIPAA Security Rule
    text: Moxe is audited annually with an SSAE 16 SOC 2 Type 2 Report that also includes a review of its practices as it relates to the HIPAA Security Rule
    type: SSAE 16 SOC 2 Type 2 Report
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Moxe practices as included in SOC 2 Type 2 report
    text: 'SOC2 and HIPAA Compliance: Moxe is committed to following industry best practices when it comes to protecting your data.'
    type: HIPAA Security Rule review
  - framework: SOC2
    issuer: null
    period: annually
    report_access: unstated
    scope: Moxe practices
    source: https://moxehealth.com/security
    text: Moxe is audited annually with an SSAE 16 SOC 2 Type 2 Report
    type: SOC 2 Type 2 report
  - framework: HIPAA
    issuer: null
    period: annually
    report_access: unstated
    scope: review of its practices as it relates to the HIPAA Security Rule
    source: https://moxehealth.com/security
    text: Moxe is audited annually with an SSAE 16 SOC 2 Type 2 Report that also includes a review of its practices as it relates to the HIPAA Security Rule
    type: HIPAA Security Rule review
  trust_center:
    url: https://moxehealth.com/security/
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Moxe Health
provenance_date: '2026-11-10'
provider_name: Moxe Health
provider_slug: moxe-health
slug: moxe-health-compliance
source_date: '2026-11-10'
source_filename: moxe-health-compliance.yml
source_heading: Compliance
source_page: https://moxehealth.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Moxe Health\naid: moxe-health\nurl: https://moxehealth.com/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/moxe-health-trust-center.yml\n  sources:\n  - https://moxehealth.com/security\n  - https://moxehealth.com/security/\ntrust_center:\n  url: https://moxehealth.com/security/\nattestations:\n- framework: SOC2\n  type: SSAE 16 SOC 2 Type 2 Report\n  scope: Moxe practices including review against HIPAA Security Rule\n  period: audited annually\n  issuer: null\n  report_access: unstated\n  text: Moxe is audited annually with an SSAE 16 SOC 2 Type 2 Report that also includes a review of its\
  \ practices\n    as it relates to the HIPAA Security Rule\n- framework: HIPAA\n  type: HIPAA Security Rule review\n  scope: Moxe practices as included in SOC 2 Type 2 report\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'SOC2 and HIPAA Compliance: Moxe is committed to following industry best practices when it comes to protecting\n    your data.'\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: Moxe practices\n  period: annually\n  issuer: null\n  report_access: unstated\n  text: Moxe is audited annually with an SSAE 16 SOC 2 Type 2 Report\n  source: https://moxehealth.com/security\n- framework: HIPAA\n  type: HIPAA Security Rule review\n  scope: review of its practices as it relates to the HIPAA Security Rule\n  period: annually\n  issuer: null\n  report_access: unstated\n  text: Moxe is audited annually with an SSAE 16 SOC 2 Type 2 Report that also includes a review of its practices\n    as it relates to the HIPAA Security Rule\n  source: https://moxehealth.com/security\n"
source_yaml_url: https://artifacts.apis.io/moxe-health/compliance/moxe-health-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Moxe Health's own page on 2026-11-10.
synthetic: false
tags:
- Healthcare
- United States
- Interoperability
- Clinical Data
- Payers
- Providers
- Electronic Health Records
- Health Data Exchange
- Claims
- Risk Adjustment
---
