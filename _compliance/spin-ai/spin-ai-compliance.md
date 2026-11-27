---
api_specs:
- filename: spin-ai-entities-api-openapi.yml
  format: yaml
  label: Spin.AI Entities API
  slug: spin-ai-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spin-ai/openapi/spin-ai-entities-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: SpinOne platform
    text: annual SOC 2 Type II audits
    type: SOC 2 Type II audit report
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: SpinOne platform
    text: Spin.AI supports GDPR, HIPAA, CCPA, and PCI-DSS compliance
    type: HIPAA compliance support
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: SpinOne platform
    text: Spin.AI supports GDPR, HIPAA, CCPA, and PCI-DSS compliance
    type: GDPR compliance support
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: unstated
    scope: SpinOne
    text: SpinOne CSA STAR Level 1 Certification
    type: CSA STAR Level 1 Certification
  trust_center:
    url: https://trust.spin.ai/
frameworks:
- CSA-STAR
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Spin.AI
provenance_date: '2026-11-10'
provider_name: Spin.AI
provider_slug: spin-ai
slug: spin-ai-compliance
source_date: '2026-11-10'
source_filename: spin-ai-compliance.yml
source_heading: Compliance
source_page: https://trust.spin.ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Spin.AI\naid: spin-ai\nurl: https://trust.spin.ai/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/spin-ai-trust-center.yml\ntrust_center:\n  url: https://trust.spin.ai/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II audit report\n  scope: SpinOne platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: annual SOC 2 Type II audits\n- framework: HIPAA\n  type: HIPAA compliance support\n  scope: SpinOne platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Spin.AI supports GDPR, HIPAA, CCPA, and PCI-DSS compliance\n- framework: GDPR\n  type: GDPR compliance\
  \ support\n  scope: SpinOne platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Spin.AI supports GDPR, HIPAA, CCPA, and PCI-DSS compliance\n- framework: CSA-STAR\n  type: CSA STAR Level 1 Certification\n  scope: SpinOne\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SpinOne CSA STAR Level 1 Certification\n"
source_yaml_url: https://artifacts.apis.io/spin-ai/compliance/spin-ai-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Spin.AI's own page on 2026-11-10.
synthetic: false
tags:
- Backup
- Compliance
- Data Protection
- Ransomware
- SaaS Security
---
