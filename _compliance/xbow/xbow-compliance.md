---
api_specs:
- filename: xbow-assessments-api-openapi.yml
  format: yaml
  label: Xbow Assessments API
  slug: xbow-assessments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xbow/openapi/xbow-assessments-api-openapi.yml
- filename: xbow-assets-api-openapi.yml
  format: yaml
  label: Xbow Assets API
  slug: xbow-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xbow/openapi/xbow-assets-api-openapi.yml
- filename: xbow-findings-api-openapi.yml
  format: yaml
  label: Xbow Findings API
  slug: xbow-findings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xbow/openapi/xbow-findings-api-openapi.yml
- filename: xbow-lightspeed-api-openapi.yml
  format: yaml
  label: Xbow Lightspeed API
  slug: xbow-lightspeed-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xbow/openapi/xbow-lightspeed-api-openapi.yml
- filename: xbow-meta-api-openapi.yml
  format: yaml
  label: Xbow Meta API
  slug: xbow-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xbow/openapi/xbow-meta-api-openapi.yml
- filename: xbow-organizations-api-openapi.yml
  format: yaml
  label: Xbow Organizations API
  slug: xbow-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xbow/openapi/xbow-organizations-api-openapi.yml
- filename: xbow-reports-api-openapi.yml
  format: yaml
  label: Xbow Reports API
  slug: xbow-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xbow/openapi/xbow-reports-api-openapi.yml
- filename: xbow-resources-api-openapi.yml
  format: yaml
  label: Xbow Resources API
  slug: xbow-resources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xbow/openapi/xbow-resources-api-openapi.yml
- filename: xbow-webhooks-api-openapi.yml
  format: yaml
  label: Xbow Webhooks API
  slug: xbow-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xbow/openapi/xbow-webhooks-api-openapi.yml
claim_count: 7
description: ''
doc:
  attestations:
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: XBOW is GDPR, SOC 2 Type 1, SOC 2 Type 2, and HIPAA compliant
    type: null
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: XBOW is GDPR, SOC 2 Type 1, SOC 2 Type 2, and HIPAA compliant
    type: Type 1
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: XBOW is GDPR, SOC 2 Type 1, SOC 2 Type 2, and HIPAA compliant
    type: Type 2
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: XBOW is GDPR, SOC 2 Type 1, SOC 2 Type 2, and HIPAA compliant
    type: null
  - framework: SOC2
    issuer: null
    period: 10.17.25
    report_access: unstated
    scope: null
    source: https://trust.xbow.com/
    text: SOC 2 Type 1 Report 10.17.25
    type: Type 1 report
  - framework: SOC2
    issuer: null
    period: 10.17.25 to 1.17.26
    report_access: unstated
    scope: null
    source: https://trust.xbow.com/
    text: SOC 2 Type 2 Report 10.17.25 to 1.17.26.pdf
    type: Type 2 report
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.xbow.com/
    text: HIPAA Compliance Audit Report 1.17.26.pdf
    type: Compliance audit report
  trust_center:
    url: https://docs.xbow.com/console/get-started/trust-and-safety/
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Xbow
provenance_date: '2026-11-10'
provider_name: Xbow
provider_slug: xbow
slug: xbow-compliance
source_date: '2026-11-10'
source_filename: xbow-compliance.yml
source_heading: Compliance
source_page: https://docs.xbow.com/console/get-started/trust-and-safety/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Xbow\naid: xbow\nurl: https://docs.xbow.com/console/get-started/trust-and-safety/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://docs.xbow.com/console/get-started/trust-and-safety/\n  - https://trust.xbow.com/\ntrust_center:\n  url: https://docs.xbow.com/console/get-started/trust-and-safety/\nattestations:\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: XBOW is GDPR, SOC 2 Type 1, SOC 2 Type 2, and HIPAA compliant\n- framework: SOC2\n  type: Type 1\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: XBOW is\
  \ GDPR, SOC 2 Type 1, SOC 2 Type 2, and HIPAA compliant\n- framework: SOC2\n  type: Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: XBOW is GDPR, SOC 2 Type 1, SOC 2 Type 2, and HIPAA compliant\n- framework: HIPAA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: XBOW is GDPR, SOC 2 Type 1, SOC 2 Type 2, and HIPAA compliant\n- framework: SOC2\n  type: Type 1 report\n  scope: null\n  period: 10.17.25\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 1 Report 10.17.25\n  source: https://trust.xbow.com/\n- framework: SOC2\n  type: Type 2 report\n  scope: null\n  period: 10.17.25 to 1.17.26\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2 Report 10.17.25 to 1.17.26.pdf\n  source: https://trust.xbow.com/\n- framework: HIPAA\n  type: Compliance audit report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA Compliance Audit Report 1.17.26.pdf\n\
  \  source: https://trust.xbow.com/\n"
source_yaml_url: https://artifacts.apis.io/xbow/compliance/xbow-compliance.yml
stated_fields:
- attestations
summary_line: 7 quoted statements, read from Xbow's own page on 2026-11-10.
synthetic: false
tags:
- Security
- Penetration Testing
- Offensive Security
- Artificial Intelligence
- Vulnerability Management
- Cybersecurity
- Application Security
---
