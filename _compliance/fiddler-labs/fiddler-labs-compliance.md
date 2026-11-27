---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: audited annually
    report_access: nda
    scope: trust services categories of security, confidentiality, and availability
    text: Fiddler’s SOC 2 Type II report covers the trust services categories of security, confidentiality, and availability and is audited annually.
    type: SOC 2 Type II report
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: protected health information
    text: Fiddler is in compliance with the U.S. Health Insurance and Accountability Act (HIPAA) .
    type: HIPAA compliance
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
name: Fiddler Labs
provenance_date: '2026-11-09'
provider_name: Fiddler Labs
provider_slug: fiddler-labs
slug: fiddler-labs-compliance
source_date: '2026-11-09'
source_filename: fiddler-labs-compliance.yml
source_heading: Compliance
source_page: https://www.fiddler.ai/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Fiddler Labs\naid: fiddler-labs\nurl: https://www.fiddler.ai/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.fiddler.ai/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: trust services categories of security, confidentiality, and availability\n  period: audited annually\n  issuer: null\n  report_access: nda\n  text: Fiddler’s SOC 2 Type II report covers the trust services categories of security, confidentiality, and availability\n    and is audited annually.\n- framework: HIPAA\n  type: HIPAA compliance\n  scope: protected health information\n  period: null\n\
  \  issuer: null\n  report_access: unstated\n  text: Fiddler is in compliance with the U.S. Health Insurance and Accountability Act (HIPAA) .\n"
source_yaml_url: https://artifacts.apis.io/fiddler-labs/compliance/fiddler-labs-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Fiddler Labs's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Observability
- ML Monitoring
- LLM Observability
- AI Agents
- AI Security
- AI Governance
- Model Monitoring
- Explainability
- Guardrails
---
