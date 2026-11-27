---
api_specs:
- filename: nifty-authentication-api-openapi.yml
  format: yaml
  label: Nifty Authentication API
  slug: nifty-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nifty/openapi/nifty-authentication-api-openapi.yml
- filename: nifty-documents-api-openapi.yml
  format: yaml
  label: Nifty Documents API
  slug: nifty-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nifty/openapi/nifty-documents-api-openapi.yml
- filename: nifty-files-api-openapi.yml
  format: yaml
  label: Nifty Files API
  slug: nifty-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nifty/openapi/nifty-files-api-openapi.yml
- filename: nifty-folders-api-openapi.yml
  format: yaml
  label: Nifty Folders API
  slug: nifty-folders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nifty/openapi/nifty-folders-api-openapi.yml
- filename: nifty-members-api-openapi.yml
  format: yaml
  label: Nifty Members API
  slug: nifty-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nifty/openapi/nifty-members-api-openapi.yml
- filename: nifty-milestones-api-openapi.yml
  format: yaml
  label: Nifty Milestones API
  slug: nifty-milestones-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nifty/openapi/nifty-milestones-api-openapi.yml
- filename: nifty-projects-api-openapi.yml
  format: yaml
  label: Nifty Projects API
  slug: nifty-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nifty/openapi/nifty-projects-api-openapi.yml
- filename: nifty-tasks-api-openapi.yml
  format: yaml
  label: Nifty Tasks API
  slug: nifty-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nifty/openapi/nifty-tasks-api-openapi.yml
- filename: nifty-webhooks-api-openapi.yml
  format: yaml
  label: Nifty Webhooks API
  slug: nifty-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nifty/openapi/nifty-webhooks-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Nifty platform
    text: Nifty is compliant with the General Data Protection Regulation (GDPR)
    type: compliance statement
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Nifty organizational and technology controls
    text: For the latest SOC 2 report, reach out to team@niftypm.com.
    type: certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: information security management
    text: Nifty has achieved ISO 27001:2022 certification, a globally recognized standard for information security management.
    type: certification
  - framework: other
    issuer: null
    period: null
    report_access: on_request
    scope: Cloud Application Security Assessment
    text: For the latest CASA security report, reach out to team@niftypm.com.
    type: certification (CASA)
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: credit card storage and processing
    text: Nifty maintains ongoing Level 1 PCI compliance
    type: compliance statement
  trust_center:
    url: https://niftypm.com/security/
frameworks:
- GDPR
- ISO27001
- PCI-DSS
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Nifty
provenance_date: '2026-11-10'
provider_name: Nifty
provider_slug: nifty
slug: nifty-compliance
source_date: '2026-11-10'
source_filename: nifty-compliance.yml
source_heading: Compliance
source_page: https://niftypm.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Nifty\naid: nifty\nurl: https://niftypm.com/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/nifty-trust-center.yml\ntrust_center:\n  url: https://niftypm.com/security/\nattestations:\n- framework: GDPR\n  type: compliance statement\n  scope: Nifty platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Nifty is compliant with the General Data Protection Regulation (GDPR)\n- framework: SOC2\n  type: certification\n  scope: Nifty organizational and technology controls\n  period: null\n  issuer: null\n  report_access: on_request\n  text: For the latest SOC 2 report, reach\
  \ out to team@niftypm.com.\n- framework: ISO27001\n  type: certification\n  scope: information security management\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Nifty has achieved ISO 27001:2022 certification, a globally recognized standard for information security\n    management.\n- framework: other\n  type: certification (CASA)\n  scope: Cloud Application Security Assessment\n  period: null\n  issuer: null\n  report_access: on_request\n  text: For the latest CASA security report, reach out to team@niftypm.com.\n- framework: PCI-DSS\n  type: compliance statement\n  scope: credit card storage and processing\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Nifty maintains ongoing Level 1 PCI compliance\n"
source_yaml_url: https://artifacts.apis.io/nifty/compliance/nifty-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Nifty's own page on 2026-11-10.
synthetic: false
tags:
- Project Management
- Task Management
- Collaboration
- Productivity
- Roadmaps
- Team Workspace
---
