---
api_specs:
- filename: usertesting-clip-api-openapi.yml
  format: yaml
  label: UserTesting Clip API
  slug: usertesting-clip-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usertesting/openapi/usertesting-clip-api-openapi.yml
- filename: usertesting-general-session-data-api-openapi.yml
  format: yaml
  label: UserTesting General Session Data API
  slug: usertesting-general-session-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usertesting/openapi/usertesting-general-session-data-api-openapi.yml
- filename: usertesting-highlightreel-api-openapi.yml
  format: yaml
  label: UserTesting Highlightreel API
  slug: usertesting-highlightreel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usertesting/openapi/usertesting-highlightreel-api-openapi.yml
- filename: usertesting-qxscore-data-api-openapi.yml
  format: yaml
  label: UserTesting QXscore Data API
  slug: usertesting-qxscore-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usertesting/openapi/usertesting-qxscore-data-api-openapi.yml
- filename: usertesting-session-api-openapi.yml
  format: yaml
  label: UserTesting Session API
  slug: usertesting-session-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usertesting/openapi/usertesting-session-api-openapi.yml
- filename: usertesting-studies-api-openapi.yml
  format: yaml
  label: UserTesting Studies API
  slug: usertesting-studies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usertesting/openapi/usertesting-studies-api-openapi.yml
- filename: usertesting-video-data-api-openapi.yml
  format: yaml
  label: UserTesting Video Data API
  slug: usertesting-video-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usertesting/openapi/usertesting-video-data-api-openapi.yml
- filename: usertesting-workspaces-api-openapi.yml
  format: yaml
  label: UserTesting Workspaces API
  slug: usertesting-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usertesting/openapi/usertesting-workspaces-api-openapi.yml
claim_count: 8
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: '2025'
    report_access: unstated
    scope: UserTesting
    text: UserTesting SOC 2 Type II (2025)
    type: Type II
  - framework: ISO27001
    issuer: null
    period: '2022'
    report_access: unstated
    scope: UserTesting
    text: UserTesting ISO 27001:2022 Certificate
    type: certificate
  - framework: ISO27701
    issuer: null
    period: '2019'
    report_access: unstated
    scope: UserTesting
    text: UserTesting ISO 27701:2019 Certificate
    type: certificate
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA COMPLIANT CCPA
    type: compliance
  - framework: CyberEssentials
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: UK Cyber Essentials 3.3
    type: UK Cyber Essentials 3.3
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Trusted Cloud Provider (CSA)
    type: Trusted Cloud Provider
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: EU-U.S. Data Privacy Framework
    type: EU-U.S. Data Privacy Framework
  trust_center:
    url: https://trust.usertesting.com/
frameworks:
- CCPA
- CSA-STAR
- CyberEssentials
- GDPR
- ISO27001
- ISO27701
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: UserTesting
provenance_date: '2026-11-10'
provider_name: UserTesting
provider_slug: usertesting
slug: usertesting-compliance
source_date: '2026-11-10'
source_filename: usertesting-compliance.yml
source_heading: Compliance
source_page: https://trust.usertesting.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: UserTesting\naid: usertesting\nurl: https://trust.usertesting.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.usertesting.com/\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: UserTesting\n  period: '2025'\n  issuer: null\n  report_access: unstated\n  text: UserTesting SOC 2 Type II (2025)\n- framework: ISO27001\n  type: certificate\n  scope: UserTesting\n  period: '2022'\n  issuer: null\n  report_access: unstated\n  text: UserTesting ISO 27001:2022 Certificate\n- framework: ISO27701\n  type: certificate\n  scope: UserTesting\n  period: '2019'\n  issuer: null\n  report_access:\
  \ unstated\n  text: UserTesting ISO 27701:2019 Certificate\n- framework: GDPR\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: CCPA\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA COMPLIANT CCPA\n- framework: CyberEssentials\n  type: UK Cyber Essentials 3.3\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: UK Cyber Essentials 3.3\n- framework: CSA-STAR\n  type: Trusted Cloud Provider\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Trusted Cloud Provider (CSA)\n- framework: other\n  type: EU-U.S. Data Privacy Framework\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: EU-U.S. Data Privacy Framework\n"
source_yaml_url: https://artifacts.apis.io/usertesting/compliance/usertesting-compliance.yml
stated_fields:
- attestations
summary_line: 8 quoted statements, read from UserTesting's own page on 2026-11-10.
synthetic: false
tags:
- Company
- User Research
- Usability Testing
- Human Insight
- Customer Experience
- Surveys
- Video
- Transcripts
- Experience Metrics
---
