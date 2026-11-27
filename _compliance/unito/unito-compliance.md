---
api_specs:
- filename: unito-reports-api-openapi.yml
  format: yaml
  label: Unito Reports API
  slug: unito-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unito/openapi/unito-reports-api-openapi.yml
- filename: unito-server-api-openapi.yml
  format: yaml
  label: Unito Server API
  slug: unito-server-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unito/openapi/unito-server-api-openapi.yml
- filename: unito-workspaces-api-openapi.yml
  format: yaml
  label: Unito Workspaces API
  slug: unito-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unito/openapi/unito-workspaces-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Unito is SOC 2 Type 2 Certified.
    type: SOC 2 Type 2
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: We comply with PCI DSS requirements.
    type: self-assessment questionnaire (SAQ)
  - framework: other
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: We have completed the CAIQ self-assessment questionnaire from the Cloud Security Alliance.
    type: CAIQ self-assessment questionnaire (Cloud Security Alliance)
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: 'Unito complies with worldwide privacy laws: European GDPR, California CCPA, Québec Loi 25.'
    type: privacy law compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: 'Unito complies with worldwide privacy laws: European GDPR, California CCPA, Québec Loi 25.'
    type: privacy law compliance
  trust_center:
    url: https://unito.io/security/
frameworks:
- CCPA
- GDPR
- PCI-DSS
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Unito
provenance_date: '2026-11-10'
provider_name: Unito
provider_slug: unito
slug: unito-compliance
source_date: '2026-11-10'
source_filename: unito-compliance.yml
source_heading: Compliance
source_page: https://unito.io/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Unito\naid: unito\nurl: https://unito.io/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://unito.io/security/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Unito is SOC 2 Type 2 Certified.\n- framework: PCI-DSS\n  type: self-assessment questionnaire (SAQ)\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: We comply with PCI DSS requirements.\n- framework: other\n  type: CAIQ self-assessment questionnaire (Cloud Security Alliance)\n  scope: null\n  period: null\n  issuer:\
  \ null\n  report_access: on_request\n  text: We have completed the CAIQ self-assessment questionnaire from the Cloud Security Alliance.\n- framework: GDPR\n  type: privacy law compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'Unito complies with worldwide privacy laws: European GDPR, California CCPA, Québec Loi 25.'\n- framework: CCPA\n  type: privacy law compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'Unito complies with worldwide privacy laws: European GDPR, California CCPA, Québec Loi 25.'\n"
source_yaml_url: https://artifacts.apis.io/unito/compliance/unito-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Unito's own page on 2026-11-10.
synthetic: false
tags:
- Integration
- Two-Way Sync
- Workflow Automation
- Project Management
- Collaboration
- Embedded Integrations
- Software-as-a-Service
---
