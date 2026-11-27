---
api_specs:
- filename: contrast-security-applications-api-openapi.yml
  format: yaml
  label: Contrast Security Applications API
  slug: contrast-security-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contrast-security/openapi/contrast-security-applications-api-openapi.yml
- filename: contrast-security-organizations-api-openapi.yml
  format: yaml
  label: Contrast Security Organizations API
  slug: contrast-security-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contrast-security/openapi/contrast-security-organizations-api-openapi.yml
- filename: contrast-security-rules-api-openapi.yml
  format: yaml
  label: Contrast Security Rules API
  slug: contrast-security-rules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contrast-security/openapi/contrast-security-rules-api-openapi.yml
- filename: contrast-security-vulnerabilities-api-openapi.yml
  format: yaml
  label: Contrast Security Vulnerabilities API
  slug: contrast-security-vulnerabilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contrast-security/openapi/contrast-security-vulnerabilities-api-openapi.yml
claim_count: 6
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: unstated
    period: '2025'
    report_access: unstated
    scope: unstated
    text: SOC2 Type II 2025
    type: Type II report
  - framework: SOC3
    issuer: unstated
    period: '2026'
    report_access: unstated
    scope: unstated
    text: 2026 SOC3 Type II
    type: Type II report
  - framework: CCPA
    issuer: unstated
    period: null
    report_access: unstated
    scope: unstated
    text: CCPA COMPLIANT
    type: compliance
  - framework: GDPR
    issuer: unstated
    period: null
    report_access: unstated
    scope: unstated
    text: GDPR
    type: compliance
  - framework: other
    issuer: unstated
    period: null
    report_access: unstated
    scope: unstated
    text: TX-RAMP
    type: TX-RAMP
  - framework: NIST-CSF
    issuer: unstated
    period: null
    report_access: unstated
    scope: unstated
    text: NIST CSF 2.0
    type: NIST CSF 2.0 compliance
  trust_center:
    url: https://trust.contrastsecurity.com/
frameworks:
- CCPA
- GDPR
- NIST-CSF
- SOC2
- SOC3
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Contrast Security
provenance_date: '2026-11-09'
provider_name: Contrast Security
provider_slug: contrast-security
slug: contrast-security-compliance
source_date: '2026-11-09'
source_filename: contrast-security-compliance.yml
source_heading: Compliance
source_page: https://trust.contrastsecurity.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Contrast Security\naid: contrast-security\nurl: https://trust.contrastsecurity.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.contrastsecurity.com/\nattestations:\n- framework: SOC2\n  type: Type II report\n  scope: unstated\n  period: '2025'\n  issuer: unstated\n  report_access: unstated\n  text: SOC2 Type II 2025\n- framework: SOC3\n  type: Type II report\n  scope: unstated\n  period: '2026'\n  issuer: unstated\n  report_access: unstated\n  text: 2026 SOC3 Type II\n- framework: CCPA\n  type: compliance\n  scope: unstated\n  period: null\n  issuer: unstated\n  report_access: unstated\n \
  \ text: CCPA COMPLIANT\n- framework: GDPR\n  type: compliance\n  scope: unstated\n  period: null\n  issuer: unstated\n  report_access: unstated\n  text: GDPR\n- framework: other\n  type: TX-RAMP\n  scope: unstated\n  period: null\n  issuer: unstated\n  report_access: unstated\n  text: TX-RAMP\n- framework: NIST-CSF\n  type: NIST CSF 2.0 compliance\n  scope: unstated\n  period: null\n  issuer: unstated\n  report_access: unstated\n  text: NIST CSF 2.0\n"
source_yaml_url: https://artifacts.apis.io/contrast-security/compliance/contrast-security-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from Contrast Security's own page on 2026-11-09.
synthetic: false
tags:
- Application Security
- AppSec
- IAST
- RASP
- Software Composition Analysis
- DevSecOps
- Runtime Protection
---
