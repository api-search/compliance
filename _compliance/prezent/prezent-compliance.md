---
api_specs:
- filename: prezent-audiences-api-openapi.yml
  format: yaml
  label: Prezent Audiences API
  slug: prezent-audiences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prezent/openapi/prezent-audiences-api-openapi.yml
- filename: prezent-autogenerator-api-openapi.yml
  format: yaml
  label: Prezent AutoGenerator API
  slug: prezent-autogenerator-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prezent/openapi/prezent-autogenerator-api-openapi.yml
- filename: prezent-file-access-api-openapi.yml
  format: yaml
  label: Prezent File Access API
  slug: prezent-file-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prezent/openapi/prezent-file-access-api-openapi.yml
- filename: prezent-health-api-openapi.yml
  format: yaml
  label: Prezent Health API
  slug: prezent-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prezent/openapi/prezent-health-api-openapi.yml
- filename: prezent-streaming-api-openapi.yml
  format: yaml
  label: Prezent Streaming API
  slug: prezent-streaming-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prezent/openapi/prezent-streaming-api-openapi.yml
- filename: prezent-template-converter-api-openapi.yml
  format: yaml
  label: Prezent Template Converter API
  slug: prezent-template-converter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prezent/openapi/prezent-template-converter-api-openapi.yml
- filename: prezent-themes-api-openapi.yml
  format: yaml
  label: Prezent Themes API
  slug: prezent-themes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prezent/openapi/prezent-themes-api-openapi.yml
- filename: prezent-upload-api-openapi.yml
  format: yaml
  label: Prezent Upload API
  slug: prezent-upload-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prezent/openapi/prezent-upload-api-openapi.yml
- filename: prezent-webhooks-api-openapi.yml
  format: yaml
  label: Prezent Webhooks API
  slug: prezent-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prezent/openapi/prezent-webhooks-api-openapi.yml
claim_count: 9
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Data privacy is protected by ISO 27001 and SOC 2 Type II certified ISMS.
    type: certified ISMS
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Data privacy is protected by ISO 27001 and SOC 2 Type II certified ISMS.
    type: Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Prezent supports full customer control with GDPR and CCPA-aligned policies.
    type: policies aligned with GDPR
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Prezent supports full customer control with GDPR and CCPA-aligned policies.
    type: policies aligned with CCPA
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Our policies are continuously updated to stay aligned with evolving laws and standards, including ISO/IEC 27001:2022, GDPR, CCPA, and SOX compliance requirements.
    type: SOX compliance requirements
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: ISMS
    source: https://www.prezent.ai/security-compliance
    text: Data privacy is protected by ISO 27001 and SOC 2 Type II certified ISMS.
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://www.prezent.ai/security-compliance
    text: Data privacy is protected by ISO 27001 and SOC 2 Type II certified ISMS.
    type: Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://www.prezent.ai/security-compliance
    text: Prezent supports full customer control with GDPR and CCPA-aligned policies.
    type: aligned policies
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://www.prezent.ai/security-compliance
    text: Prezent supports full customer control with GDPR and CCPA-aligned policies.
    type: aligned policies
  trust_center:
    url: https://www.prezent.ai/security-compliance
frameworks:
- CCPA
- GDPR
- ISO27001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Prezent
provenance_date: '2026-11-10'
provider_name: Prezent
provider_slug: prezent
slug: prezent-compliance
source_date: '2026-11-10'
source_filename: prezent-compliance.yml
source_heading: Compliance
source_page: https://www.prezent.ai/security-compliance
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Prezent\naid: prezent\nurl: https://www.prezent.ai/security-compliance\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/prezent-trust-center.yml\n  sources:\n  - https://www.prezent.ai/security-compliance\ntrust_center:\n  url: https://www.prezent.ai/security-compliance\nattestations:\n- framework: ISO27001\n  type: certified ISMS\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Data privacy is protected by ISO 27001 and SOC 2 Type II certified ISMS.\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text:\
  \ Data privacy is protected by ISO 27001 and SOC 2 Type II certified ISMS.\n- framework: GDPR\n  type: policies aligned with GDPR\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Prezent supports full customer control with GDPR and CCPA-aligned policies.\n- framework: CCPA\n  type: policies aligned with CCPA\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Prezent supports full customer control with GDPR and CCPA-aligned policies.\n- framework: other\n  type: SOX compliance requirements\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our policies are continuously updated to stay aligned with evolving laws and standards, including ISO/IEC\n    27001:2022, GDPR, CCPA, and SOX compliance requirements.\n- framework: ISO27001\n  type: certification\n  scope: ISMS\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Data privacy is protected by ISO 27001 and SOC 2 Type II certified\
  \ ISMS.\n  source: https://www.prezent.ai/security-compliance\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Data privacy is protected by ISO 27001 and SOC 2 Type II certified ISMS.\n  source: https://www.prezent.ai/security-compliance\n- framework: GDPR\n  type: aligned policies\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Prezent supports full customer control with GDPR and CCPA-aligned policies.\n  source: https://www.prezent.ai/security-compliance\n- framework: CCPA\n  type: aligned policies\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Prezent supports full customer control with GDPR and CCPA-aligned policies.\n  source: https://www.prezent.ai/security-compliance\n"
source_yaml_url: https://artifacts.apis.io/prezent/compliance/prezent-compliance.yml
stated_fields:
- attestations
summary_line: 9 quoted statements, read from Prezent's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Presentations
- Generative AI
- AI Agents
- Life Sciences
- Content Generation
- Enterprise
- MCP
- Productivity
---
