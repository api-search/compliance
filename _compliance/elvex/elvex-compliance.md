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
    text: SOC2 Type2 and HIPAA reports on request
    type: SOC 2 Type 2 report
  - framework: HIPAA
    issuer: null
    period: null
    report_access: on_request
    scope: PHI safeguards
    text: HIPAA Report PHI safeguards · attestation
    type: HIPAA report (PHI safeguards attestation)
  trust_center:
    url: https://www.elvex.com/security
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: elvex
provenance_date: '2026-11-09'
provider_name: elvex
provider_slug: elvex
slug: elvex-compliance
source_date: '2026-11-09'
source_filename: elvex-compliance.yml
source_heading: Compliance
source_page: https://www.elvex.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: elvex\naid: elvex\nurl: https://www.elvex.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.elvex.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC2 Type2 and HIPAA reports on request\n- framework: HIPAA\n  type: HIPAA report (PHI safeguards attestation)\n  scope: PHI safeguards\n  period: null\n  issuer: null\n  report_access: on_request\n  text: HIPAA Report PHI safeguards · attestation\n"
source_yaml_url: https://artifacts.apis.io/elvex/compliance/elvex-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from elvex's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Enterprise
- Platform
- Automation
- Integration
- Company
---
