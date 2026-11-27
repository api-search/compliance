---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: unstated
    period: annual
    report_access: on_request
    scope: Mimic services (Security, Availability, Confidentiality trust criteria listed)
    text: We complete annual audits against SOC 2 security requirements.
    type: annual audit against SOC 2 security requirements
  trust_center:
    url: https://mimic.com/technical-and-organizational-measures
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Mimic
provenance_date: '2026-11-10'
provider_name: Mimic
provider_slug: mimic
slug: mimic-compliance
source_date: '2026-11-10'
source_filename: mimic-compliance.yml
source_heading: Compliance
source_page: https://mimic.com/technical-and-organizational-measures
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Mimic\naid: mimic\nurl: https://mimic.com/technical-and-organizational-measures\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://mimic.com/technical-and-organizational-measures\nattestations:\n- framework: SOC2\n  type: annual audit against SOC 2 security requirements\n  scope: Mimic services (Security, Availability, Confidentiality trust criteria listed)\n  period: annual\n  issuer: unstated\n  report_access: on_request\n  text: We complete annual audits against SOC 2 security requirements.\n"
source_yaml_url: https://artifacts.apis.io/mimic/compliance/mimic-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Mimic's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise
- Cybersecurity
- Ransomware Defense
- Endpoint Security
- Threat Detection
- AI Security
- Software-as-a-Service
---
