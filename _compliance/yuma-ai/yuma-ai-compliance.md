---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: Johanson Group LLP
    period: null
    report_access: on_request
    scope: Security Trust Services Criteria
    text: A SOC 2 Type II report covering the Security Trust Services Criteria, issued by independent auditors Johanson Group LLP. Request the report
    type: SOC 2 Type II report
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Yuma AI is certified under the EU-U.S. Data Privacy Framework.
    type: EU-U.S. Data Privacy Framework certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Yuma acts as a processor on your behalf, under a Data Processing Agreement.
    type: processor under Data Processing Agreement
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Yuma is a service provider. We never sell or share customer personal data.
    type: service provider
  trust_center:
    url: https://yuma.ai/security
frameworks:
- CCPA
- GDPR
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Yuma AI
provenance_date: '2026-11-10'
provider_name: Yuma AI
provider_slug: yuma-ai
slug: yuma-ai-compliance
source_date: '2026-11-10'
source_filename: yuma-ai-compliance.yml
source_heading: Compliance
source_page: https://yuma.ai/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Yuma AI\naid: yuma-ai\nurl: https://yuma.ai/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://yuma.ai/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: Security Trust Services Criteria\n  period: null\n  issuer: Johanson Group LLP\n  report_access: on_request\n  text: A SOC 2 Type II report covering the Security Trust Services Criteria, issued by independent auditors Johanson\n    Group LLP. Request the report\n- framework: other\n  type: EU-U.S. Data Privacy Framework certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text:\
  \ Yuma AI is certified under the EU-U.S. Data Privacy Framework.\n- framework: GDPR\n  type: processor under Data Processing Agreement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Yuma acts as a processor on your behalf, under a Data Processing Agreement.\n- framework: CCPA\n  type: service provider\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Yuma is a service provider. We never sell or share customer personal data.\n"
source_yaml_url: https://artifacts.apis.io/yuma-ai/compliance/yuma-ai-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Yuma AI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- Automation
- Data Analysis
---
