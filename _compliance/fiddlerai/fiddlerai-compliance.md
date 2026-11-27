---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: audited annually
    report_access: nda
    scope: security, confidentiality, and availability trust services categories
    text: Fiddler’s SOC 2 Type II report covers the trust services categories of security, confidentiality, and availability and is audited annually.
    type: SOC 2 Type II report
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: protected health information
    text: Fiddler is in compliance with the U.S. Health Insurance and Accountability Act (HIPAA) .
    type: HIPAA compliance
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust-center.fiddler.ai/
    text: Compliance SOC 2 HIPAA
    type: null
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust-center.fiddler.ai/
    text: Compliance SOC 2 HIPAA
    type: null
  trust_center:
    url: https://www.fiddler.ai/security
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: fiddler.ai
provenance_date: '2026-11-09'
provider_name: fiddler.ai
provider_slug: fiddlerai
slug: fiddlerai-compliance
source_date: '2026-11-09'
source_filename: fiddlerai-compliance.yml
source_heading: Compliance
source_page: https://www.fiddler.ai/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: fiddler.ai\naid: fiddlerai\nurl: https://www.fiddler.ai/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://trust-center.fiddler.ai/\n  - https://www.fiddler.ai/security\ntrust_center:\n  url: https://www.fiddler.ai/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: security, confidentiality, and availability trust services categories\n  period: audited annually\n  issuer: null\n  report_access: nda\n  text: Fiddler’s SOC 2 Type II report covers the trust services categories of security, confidentiality, and availability\n    and is audited annually.\n- framework: HIPAA\n\
  \  type: HIPAA compliance\n  scope: protected health information\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Fiddler is in compliance with the U.S. Health Insurance and Accountability Act (HIPAA) .\n- framework: SOC2\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliance SOC 2 HIPAA\n  source: https://trust-center.fiddler.ai/\n- framework: HIPAA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliance SOC 2 HIPAA\n  source: https://trust-center.fiddler.ai/\n"
source_yaml_url: https://artifacts.apis.io/fiddlerai/compliance/fiddlerai-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from fiddler.ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Observability
- Machine Learning
- LLM
- Model Monitoring
- Guardrails
- MLOps
- AI Governance
- Explainability
- Agent Observability
- AI Security
---
