---
api_specs:
- filename: formstack-asyncapi.yml
  format: yaml
  label: Formstack Webhooks API
  slug: webhooks
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/formstack/openapi/formstack-asyncapi.yml
- filename: formstack-partnerapi-api-openapi.yml
  format: yaml
  label: Formstack Partner API
  slug: formstack-partnerapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/formstack/openapi/formstack-partnerapi-api-openapi.yml
claim_count: 6
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II
    type: SOC 2 Type II badge
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: Formstack Forms
    text: Formstack Forms - PCI-DSS AOC
    type: PCI-DSS AOC document
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001 Engagement Summary Letter
    type: ISO 27001 engagement summary letter
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Formstack
    text: Formstack HIPAA Audit
    type: HIPAA audit document
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: TX-RAMP
    type: TX-RAMP badge
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: GDPR badge
  trust_center:
    url: https://trust.intellistack.com/
frameworks:
- GDPR
- HIPAA
- ISO27001
- PCI-DSS
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Formstack
provenance_date: '2026-11-09'
provider_name: Formstack
provider_slug: formstack
slug: formstack-compliance
source_date: '2026-11-09'
source_filename: formstack-compliance.yml
source_heading: Compliance
source_page: https://trust.intellistack.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Formstack\naid: formstack\nurl: https://trust.intellistack.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/formstack-trust-center.yml\ntrust_center:\n  url: https://trust.intellistack.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II\n- framework: PCI-DSS\n  type: PCI-DSS AOC document\n  scope: Formstack Forms\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Formstack Forms - PCI-DSS AOC\n- framework: ISO27001\n  type: ISO 27001 engagement summary letter\n  scope:\
  \ null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001 Engagement Summary Letter\n- framework: HIPAA\n  type: HIPAA audit document\n  scope: Formstack\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Formstack HIPAA Audit\n- framework: other\n  type: TX-RAMP badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: TX-RAMP\n- framework: GDPR\n  type: GDPR badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n"
source_yaml_url: https://artifacts.apis.io/formstack/compliance/formstack-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from Formstack's own page on 2026-11-09.
synthetic: false
tags:
- Forms
- Documents
- E-Signature
- Workflow Automation
- No-Code
- OAuth
- Authentication
---
