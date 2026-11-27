---
api_specs:
- filename: checkmarx-applications-api-openapi.yml
  format: yaml
  label: Checkmarx Applications API
  slug: checkmarx-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkmarx/openapi/checkmarx-applications-api-openapi.yml
- filename: checkmarx-authentication-api-openapi.yml
  format: yaml
  label: Checkmarx Authentication API
  slug: checkmarx-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkmarx/openapi/checkmarx-authentication-api-openapi.yml
- filename: checkmarx-configuration-api-openapi.yml
  format: yaml
  label: Checkmarx Configuration API
  slug: checkmarx-configuration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkmarx/openapi/checkmarx-configuration-api-openapi.yml
- filename: checkmarx-engines-api-openapi.yml
  format: yaml
  label: Checkmarx Engines API
  slug: checkmarx-engines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkmarx/openapi/checkmarx-engines-api-openapi.yml
- filename: checkmarx-groups-api-openapi.yml
  format: yaml
  label: Checkmarx Groups API
  slug: checkmarx-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkmarx/openapi/checkmarx-groups-api-openapi.yml
- filename: checkmarx-packages-api-openapi.yml
  format: yaml
  label: Checkmarx Packages API
  slug: checkmarx-packages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkmarx/openapi/checkmarx-packages-api-openapi.yml
- filename: checkmarx-presets-api-openapi.yml
  format: yaml
  label: Checkmarx Presets API
  slug: checkmarx-presets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkmarx/openapi/checkmarx-presets-api-openapi.yml
- filename: checkmarx-projects-api-openapi.yml
  format: yaml
  label: Checkmarx Projects API
  slug: checkmarx-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkmarx/openapi/checkmarx-projects-api-openapi.yml
- filename: checkmarx-queries-api-openapi.yml
  format: yaml
  label: Checkmarx Queries API
  slug: checkmarx-queries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkmarx/openapi/checkmarx-queries-api-openapi.yml
- filename: checkmarx-reports-api-openapi.yml
  format: yaml
  label: Checkmarx Reports API
  slug: checkmarx-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkmarx/openapi/checkmarx-reports-api-openapi.yml
- filename: checkmarx-results-api-openapi.yml
  format: yaml
  label: Checkmarx Results API
  slug: checkmarx-results-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkmarx/openapi/checkmarx-results-api-openapi.yml
- filename: checkmarx-risk-reports-api-openapi.yml
  format: yaml
  label: Checkmarx Risk Reports API
  slug: checkmarx-risk-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkmarx/openapi/checkmarx-risk-reports-api-openapi.yml
- filename: checkmarx-scans-api-openapi.yml
  format: yaml
  label: Checkmarx Scans API
  slug: checkmarx-scans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkmarx/openapi/checkmarx-scans-api-openapi.yml
- filename: checkmarx-settings-api-openapi.yml
  format: yaml
  label: Checkmarx Settings API
  slug: checkmarx-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkmarx/openapi/checkmarx-settings-api-openapi.yml
- filename: checkmarx-teams-api-openapi.yml
  format: yaml
  label: Checkmarx Teams API
  slug: checkmarx-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkmarx/openapi/checkmarx-teams-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: information security management
    text: We’re certified to the latest and most recognized global standard for information security.
    type: certification
  - framework: SOC2
    issuer: null
    period: annually
    report_access: on_request
    scope: Checkmarx
    text: Checkmarx undergoes an independent SOC 2 Type II audit annually. Our report is available upon request.
    type: SOC 2 Type II audit
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: privacy program
    text: Our privacy program aligns with the stringent requirements of GDPR.
    type: aligned program
  - framework: other
    issuer: NIST
    period: null
    report_access: unstated
    scope: secure software development lifecycle
    text: We align with the NIST Secure Software Development Framework (SSDF) to integrate security at every stage of our software lifecycle.
    type: alignment with NIST Secure Software Development Framework (SSDF)
  trust_center:
    url: https://checkmarx.com/trust/
frameworks:
- GDPR
- ISO27001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Checkmarx
provenance_date: '2026-11-09'
provider_name: Checkmarx
provider_slug: checkmarx
slug: checkmarx-compliance
source_date: '2026-11-09'
source_filename: checkmarx-compliance.yml
source_heading: Compliance
source_page: https://checkmarx.com/trust/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Checkmarx\naid: checkmarx\nurl: https://checkmarx.com/trust/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://checkmarx.com/trust/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: information security management\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We’re certified to the latest and most recognized global standard for information security.\n- framework: SOC2\n  type: SOC 2 Type II audit\n  scope: Checkmarx\n  period: annually\n  issuer: null\n  report_access: on_request\n  text: Checkmarx undergoes an independent SOC 2 Type II audit annually. Our report\
  \ is available upon request.\n- framework: GDPR\n  type: aligned program\n  scope: privacy program\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our privacy program aligns with the stringent requirements of GDPR.\n- framework: other\n  type: alignment with NIST Secure Software Development Framework (SSDF)\n  scope: secure software development lifecycle\n  period: null\n  issuer: NIST\n  report_access: unstated\n  text: We align with the NIST Secure Software Development Framework (SSDF) to integrate security at every stage\n    of our software lifecycle.\n"
source_yaml_url: https://artifacts.apis.io/checkmarx/compliance/checkmarx-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Checkmarx's own page on 2026-11-09.
synthetic: false
tags:
- Application Security
- Code Analysis
- DevSecOps
- SAST
- Security Testing
- Vulnerability Scanning
---
