---
api_specs:
- filename: riot-awareness-api-openapi.yml
  format: yaml
  label: Riot Awareness API
  slug: riot-awareness-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riot/openapi/riot-awareness-api-openapi.yml
- filename: riot-breaches-api-openapi.yml
  format: yaml
  label: Riot Breaches API
  slug: riot-breaches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riot/openapi/riot-breaches-api-openapi.yml
- filename: riot-general-api-openapi.yml
  format: yaml
  label: Riot General API
  slug: riot-general-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riot/openapi/riot-general-api-openapi.yml
- filename: riot-groups-api-openapi.yml
  format: yaml
  label: Riot Groups API
  slug: riot-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riot/openapi/riot-groups-api-openapi.yml
- filename: riot-inbox-api-openapi.yml
  format: yaml
  label: Riot Inbox API
  slug: riot-inbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riot/openapi/riot-inbox-api-openapi.yml
- filename: riot-scim-api-openapi.yml
  format: yaml
  label: Riot SCIM API
  slug: riot-scim-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riot/openapi/riot-scim-api-openapi.yml
- filename: riot-simulation-api-openapi.yml
  format: yaml
  label: Riot Simulation API
  slug: riot-simulation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riot/openapi/riot-simulation-api-openapi.yml
- filename: riot-slash-api-openapi.yml
  format: yaml
  label: Riot Slash API
  slug: riot-slash-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riot/openapi/riot-slash-api-openapi.yml
- filename: riot-sonar-api-openapi.yml
  format: yaml
  label: Riot Sonar API
  slug: riot-sonar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riot/openapi/riot-sonar-api-openapi.yml
claim_count: 7
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Information Security Management System
    text: We're pleased to announce that Riot is now ISO/IEC 27001 certified
    type: certification
  - framework: ISO27017
    issuer: null
    period: null
    report_access: unstated
    scope: Cloud security
    text: including the ISO/IEC 27017 (cloud security) and ISO/IEC 27018 (protection of PII in the cloud) extensions
    type: certification extension
  - framework: ISO27018
    issuer: null
    period: null
    report_access: unstated
    scope: Protection of PII in the cloud
    text: including the ISO/IEC 27017 (cloud security) and ISO/IEC 27018 (protection of PII in the cloud) extensions
    type: certification extension
  - framework: SOC2
    issuer: null
    period: '2025'
    report_access: nda
    scope: Security controls
    text: The 2025 report is now available to customers and prospects under NDA via our Trust Center
    type: Type II audit report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: This certification complements our existing SOC 2 and GDPR compliance
    type: compliance
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    source: https://tryriot.com/security/
    text: Riot complies with the requirements of AICPA SOC 2 Type II and GDPR
    type: SOC 2 Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://tryriot.com/security/
    text: Riot complies with the requirements of AICPA SOC 2 Type II and GDPR
    type: GDPR compliance
  trust_center:
    url: https://trust.tryriot.com/
frameworks:
- GDPR
- ISO27001
- ISO27017
- ISO27018
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Riot
provenance_date: '2026-11-10'
provider_name: Riot
provider_slug: riot
slug: riot-compliance
source_date: '2026-11-10'
source_filename: riot-compliance.yml
source_heading: Compliance
source_page: https://trust.tryriot.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Riot\naid: riot\nurl: https://trust.tryriot.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/riot-trust-center.yml\n  sources:\n  - https://trust.tryriot.com/\n  - https://tryriot.com/security/\ntrust_center:\n  url: https://trust.tryriot.com/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: Information Security Management System\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We're pleased to announce that Riot is now ISO/IEC 27001 certified\n- framework: ISO27017\n  type: certification extension\n  scope: Cloud security\n  period: null\n  issuer: null\n\
  \  report_access: unstated\n  text: including the ISO/IEC 27017 (cloud security) and ISO/IEC 27018 (protection of PII in the cloud) extensions\n- framework: ISO27018\n  type: certification extension\n  scope: Protection of PII in the cloud\n  period: null\n  issuer: null\n  report_access: unstated\n  text: including the ISO/IEC 27017 (cloud security) and ISO/IEC 27018 (protection of PII in the cloud) extensions\n- framework: SOC2\n  type: Type II audit report\n  scope: Security controls\n  period: '2025'\n  issuer: null\n  report_access: nda\n  text: The 2025 report is now available to customers and prospects under NDA via our Trust Center\n- framework: GDPR\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: This certification complements our existing SOC 2 and GDPR compliance\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Riot complies with the requirements\
  \ of AICPA SOC 2 Type II and GDPR\n  source: https://tryriot.com/security/\n- framework: GDPR\n  type: GDPR compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Riot complies with the requirements of AICPA SOC 2 Type II and GDPR\n  source: https://tryriot.com/security/\n"
source_yaml_url: https://artifacts.apis.io/riot/compliance/riot-compliance.yml
stated_fields:
- attestations
summary_line: 7 quoted statements, read from Riot's own page on 2026-11-10.
synthetic: false
tags:
- Cybersecurity
- Security Awareness
- Human Risk Management
- Phishing Simulation
- employee-security
- Security Posture Management
- breach-detection
- Email Security
- SaaS Security
- SCIM
- Webhook
- OCSF
- France
---
