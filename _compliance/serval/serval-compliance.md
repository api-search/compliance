---
api_specs:
- filename: serval-auth-api-api-openapi.yml
  format: yaml
  label: Serval Auth API
  slug: serval-auth-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/serval/openapi/serval-auth-api-api-openapi.yml
claim_count: 10
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Serval platform
    text: Serval is SOC 2 Type II, ISO 27001, ISO 42001, HIPAA, and GDPR compliant.
    type: SOC 2 Type II report
  - framework: ISO27001
    issuer: Advantage Partners (MSCB-389)
    period: null
    report_access: on_request
    scope: AI-native IT service management platform delivered as cloud-hosted SaaS on AWS
    text: A copy of our ISO 27001:2022 certificate and Statement of Applicability (SoA) are available upon request via our Trust Center.
    type: ISO/IEC 27001:2022 certification
  - framework: ISO42001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO/IEC 42001:2023
    type: ISO/IEC 42001:2023 certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA
    type: HIPAA compliance
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR compliant.
    type: GDPR compliance
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Serval platform
    source: https://trust.serval.com/
    text: Serval is SOC 2 Type II, ISO 27001, ISO 42001, HIPAA, and GDPR compliant.
    type: SOC 2 Type II report
  - framework: ISO27001
    issuer: Advantage Partners (MSCB-389)
    period: null
    report_access: on_request
    scope: AI-native IT service management platform delivered as cloud-hosted SaaS on AWS
    source: https://trust.serval.com/
    text: A copy of our ISO 27001:2022 certificate and Statement of Applicability (SoA) are available upon request via our Trust Center.
    type: ISO/IEC 27001:2022 certification
  - framework: ISO42001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.serval.com/
    text: ISO/IEC 42001:2023
    type: ISO/IEC 42001:2023 certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.serval.com/
    text: Serval is SOC 2 Type II, ISO 27001, ISO 42001, HIPAA, and GDPR compliant.
    type: compliance
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.serval.com/
    text: Serval is SOC 2 Type II, ISO 27001, ISO 42001, HIPAA, and GDPR compliant.
    type: compliance
  trust_center:
    url: https://trust.serval.com/
frameworks:
- GDPR
- HIPAA
- ISO27001
- ISO42001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Serval
provenance_date: '2026-11-10'
provider_name: Serval
provider_slug: serval
slug: serval-compliance
source_date: '2026-11-10'
source_filename: serval-compliance.yml
source_heading: Compliance
source_page: https://trust.serval.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Serval\naid: serval\nurl: https://trust.serval.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/serval-trust-center.yml\n  sources:\n  - https://trust.serval.com/\ntrust_center:\n  url: https://trust.serval.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: Serval platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Serval is SOC 2 Type II, ISO 27001, ISO 42001, HIPAA, and GDPR compliant.\n- framework: ISO27001\n  type: ISO/IEC 27001:2022 certification\n  scope: AI-native IT service management platform delivered as cloud-hosted SaaS on AWS\n \
  \ period: null\n  issuer: Advantage Partners (MSCB-389)\n  report_access: on_request\n  text: A copy of our ISO 27001:2022 certificate and Statement of Applicability (SoA) are available upon request\n    via our Trust Center.\n- framework: ISO42001\n  type: ISO/IEC 42001:2023 certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO/IEC 42001:2023\n- framework: HIPAA\n  type: HIPAA compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA\n- framework: GDPR\n  type: GDPR compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR compliant.\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: Serval platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Serval is SOC 2 Type II, ISO 27001, ISO 42001, HIPAA, and GDPR compliant.\n  source: https://trust.serval.com/\n- framework: ISO27001\n  type: ISO/IEC 27001:2022 certification\n  scope:\
  \ AI-native IT service management platform delivered as cloud-hosted SaaS on AWS\n  period: null\n  issuer: Advantage Partners (MSCB-389)\n  report_access: on_request\n  text: A copy of our ISO 27001:2022 certificate and Statement of Applicability (SoA) are available upon request\n    via our Trust Center.\n  source: https://trust.serval.com/\n- framework: ISO42001\n  type: ISO/IEC 42001:2023 certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO/IEC 42001:2023\n  source: https://trust.serval.com/\n- framework: HIPAA\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Serval is SOC 2 Type II, ISO 27001, ISO 42001, HIPAA, and GDPR compliant.\n  source: https://trust.serval.com/\n- framework: GDPR\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Serval is SOC 2 Type II, ISO 27001, ISO 42001, HIPAA, and GDPR compliant.\n  source: https://trust.serval.com/\n"
source_yaml_url: https://artifacts.apis.io/serval/compliance/serval-compliance.yml
stated_fields:
- attestations
summary_line: 10 quoted statements, read from Serval's own page on 2026-11-10.
synthetic: false
tags:
- Company
- ITSM
- Help Desk
- Workflow Automation
- AI Agents
- Identity and Access Management
- Employee Support
- Ticketing
---
