---
api_specs:
- filename: certik-security-score-api-openapi.yml
  format: yaml
  label: CertiK Security Score API
  slug: certik-security-score-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certik/openapi/certik-security-score-api-openapi.yml
- filename: certik-token-scan-api-openapi.yml
  format: yaml
  label: CertiK Token Scan API
  slug: certik-token-scan-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certik/openapi/certik-token-scan-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: platform hosting our services (Skyharbor)
    text: We completed ISO 27001, SOC 2 Type 1 and 2 examinations with regards to the platform hosting our services (i.e. Skyharbor).
    type: examination
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: platform hosting our services (Skyharbor)
    text: We completed ISO 27001, SOC 2 Type 1 and 2 examinations with regards to the platform hosting our services (i.e. Skyharbor).
    type: certification
  trust_center:
    url: https://www.certik.com/company/trust-and-security
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: CertiK
provenance_date: '2026-11-09'
provider_name: CertiK
provider_slug: certik
slug: certik-compliance
source_date: '2026-11-09'
source_filename: certik-compliance.yml
source_heading: Compliance
source_page: https://www.certik.com/company/trust-and-security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: CertiK\naid: certik\nurl: https://www.certik.com/company/trust-and-security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.certik.com/company/trust-and-security\nattestations:\n- framework: SOC2\n  type: examination\n  scope: platform hosting our services (Skyharbor)\n  period: null\n  issuer: null\n  report_access: on_request\n  text: We completed ISO 27001, SOC 2 Type 1 and 2 examinations with regards to the platform hosting our services\n    (i.e. Skyharbor).\n- framework: ISO27001\n  type: certification\n  scope: platform hosting our services (Skyharbor)\n  period: null\n  issuer: null\n  report_access:\
  \ on_request\n  text: We completed ISO 27001, SOC 2 Type 1 and 2 examinations with regards to the platform hosting our services\n    (i.e. Skyharbor).\n"
source_yaml_url: https://artifacts.apis.io/certik/compliance/certik-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from CertiK's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- Web3
- Blockchain
- Smart Contract Security
- Security Auditing
- Threat Intelligence
---
