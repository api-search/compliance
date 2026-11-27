---
api_specs:
- filename: black-duck-black-duck-api-api-openapi.yml
  format: yaml
  label: Black Duck Black Duck API
  slug: black-duck-black-duck-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/black-duck/openapi/black-duck-black-duck-api-api-openapi.yml
- filename: black-duck-issues-api-openapi.yml
  format: yaml
  label: Black Duck Issues API
  slug: black-duck-issues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/black-duck/openapi/black-duck-issues-api-openapi.yml
- filename: black-duck-projects-api-openapi.yml
  format: yaml
  label: Black Duck Projects API
  slug: black-duck-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/black-duck/openapi/black-duck-projects-api-openapi.yml
- filename: black-duck-search-api-openapi.yml
  format: yaml
  label: Black Duck Search API
  slug: black-duck-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/black-duck/openapi/black-duck-search-api-openapi.yml
- filename: black-duck-users-api-openapi.yml
  format: yaml
  label: Black Duck Users API
  slug: black-duck-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/black-duck/openapi/black-duck-users-api-openapi.yml
claim_count: 8
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Security, availability, and confidentiality
    text: SOC 2 Type 2 Covering security, availability, and confidentiality
    type: SOC 2 Type 2
  - framework: SOC3
    issuer: null
    period: null
    report_access: unstated
    scope: Security, availability, and confidentiality
    text: SOC 3 Type 2 Covering security, availability, and confidentiality
    type: SOC 3 Type 2
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Download ISO 27001 Certification
    type: ISO 27001 Certification
  - framework: ISO27017
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Download ISO 27017 Certification
    type: ISO 27017 Certification
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Download ISO 26262 Functional Safety
    type: ISO 26262 Functional Safety
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CSA STAR Self-Assessment based on CAIQ
    type: CSA STAR Self-Assessment based on CAIQ
  - framework: TISAX
    issuer: null
    period: 'Valid Until: 02/17/2028'
    report_access: unstated
    scope: Assessment Level 2
    text: 'TISAX Certification Scope ID: SW4K5R Location ID: L174MH Assessment Level: 2 Valid Until: 02/17/2028'
    type: TISAX Certification
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Covering Polaris
    text: TX-RAMP Certification – Level 2 Covering Polaris
    type: TX-RAMP Certification Level 2
  trust_center:
    url: https://www.blackduck.com/company/legal/security-commitments.html
frameworks:
- CSA-STAR
- ISO27001
- ISO27017
- SOC2
- SOC3
- TISAX
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Black Duck
provenance_date: '2026-11-09'
provider_name: Black Duck
provider_slug: black-duck
slug: black-duck-compliance
source_date: '2026-11-09'
source_filename: black-duck-compliance.yml
source_heading: Compliance
source_page: https://www.blackduck.com/company/legal/security-commitments.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Black Duck\naid: black-duck\nurl: https://www.blackduck.com/company/legal/security-commitments.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.blackduck.com/company/legal/security-commitments.html\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2\n  scope: Security, availability, and confidentiality\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2 Covering security, availability, and confidentiality\n- framework: SOC3\n  type: SOC 3 Type 2\n  scope: Security, availability, and confidentiality\n  period: null\n  issuer: null\n  report_access: unstated\n \
  \ text: SOC 3 Type 2 Covering security, availability, and confidentiality\n- framework: ISO27001\n  type: ISO 27001 Certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Download ISO 27001 Certification\n- framework: ISO27017\n  type: ISO 27017 Certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Download ISO 27017 Certification\n- framework: other\n  type: ISO 26262 Functional Safety\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Download ISO 26262 Functional Safety\n- framework: CSA-STAR\n  type: CSA STAR Self-Assessment based on CAIQ\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CSA STAR Self-Assessment based on CAIQ\n- framework: TISAX\n  type: TISAX Certification\n  scope: Assessment Level 2\n  period: 'Valid Until: 02/17/2028'\n  issuer: null\n  report_access: unstated\n  text: 'TISAX Certification Scope ID: SW4K5R Location\
  \ ID: L174MH Assessment Level: 2 Valid Until: 02/17/2028'\n- framework: other\n  type: TX-RAMP Certification Level 2\n  scope: Covering Polaris\n  period: null\n  issuer: null\n  report_access: unstated\n  text: TX-RAMP Certification – Level 2 Covering Polaris\n"
source_yaml_url: https://artifacts.apis.io/black-duck/compliance/black-duck-compliance.yml
stated_fields:
- attestations
summary_line: 8 quoted statements, read from Black Duck's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Enterprise
- Application Security
- Software Composition Analysis
- SAST
- DAST
- Open Source Security
- DevSecOps
- Vulnerability Management
---
