---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: our controls are certified via a SOC-2 Type 2 assessment and ISO/IEC 27001:2022 assessment
    type: SOC-2 Type 2 assessment
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: You can request a copy of our SOC-2 Type 2 certified report, ISO 27001 certificate, Information Security Management System (ISMS) Policy, or any other security-related documentation by contacting security@chalk.ai .
    type: ISO/IEC 27001:2022 assessment
  trust_center:
    url: https://docs.chalk.ai/docs/security
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Chalk
provenance_date: '2026-11-09'
provider_name: Chalk
provider_slug: chalk
slug: chalk-compliance
source_date: '2026-11-09'
source_filename: chalk-compliance.yml
source_heading: Compliance
source_page: https://docs.chalk.ai/docs/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Chalk\naid: chalk\nurl: https://docs.chalk.ai/docs/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://docs.chalk.ai/docs/security\nattestations:\n- framework: SOC2\n  type: SOC-2 Type 2 assessment\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: our controls are certified via a SOC-2 Type 2 assessment and ISO/IEC 27001:2022 assessment\n- framework: ISO27001\n  type: ISO/IEC 27001:2022 assessment\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: You can request a copy of our SOC-2 Type 2 certified report, ISO 27001 certificate,\
  \ Information Security\n    Management System (ISMS) Policy, or any other security-related documentation by contacting security@chalk.ai\n    .\n"
source_yaml_url: https://artifacts.apis.io/chalk/compliance/chalk-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Chalk's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Machine Learning
- Feature Store
- Artificial Intelligence
- Data Platform
- MLOps
- Real-Time Data
- LLM
- Agents
- Feature Engineering
---
