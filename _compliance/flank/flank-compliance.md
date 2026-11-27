---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: ISO42001
    issuer: null
    period: null
    report_access: on_request
    scope: Artificial Intelligence Management System (AIMS)
    text: The ISO 42001 Certification validates that Flank implements a robust Artificial Intelligence Management System (AIMS).
    type: Certification
  - framework: SOC2
    issuer: null
    period: continuous period
    report_access: on_request
    scope: security controls
    text: The SOC 2 Type 2 Report provides independent validation of the design and operating effectiveness of Flank’s security controls over a continuous period.
    type: Type 2 report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: personal data processing via Data Processing Agreement
    text: The Data Processing Agreement (DPA) is our contractual commitment to meet stringent global data protection regulations, including the GDPR and CCPA.
    type: Regulation compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: personal data via Data Processing Agreement
    text: The Data Processing Agreement (DPA) is our contractual commitment to meet stringent global data protection regulations, including the GDPR and CCPA.
    type: Regulation compliance
  trust_center:
    url: https://trust.flank.ai/
frameworks:
- CCPA
- GDPR
- ISO42001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Flank
provenance_date: '2026-11-09'
provider_name: Flank
provider_slug: flank
slug: flank-compliance
source_date: '2026-11-09'
source_filename: flank-compliance.yml
source_heading: Compliance
source_page: https://trust.flank.ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Flank\naid: flank\nurl: https://trust.flank.ai/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.flank.ai/\nattestations:\n- framework: ISO42001\n  type: Certification\n  scope: Artificial Intelligence Management System (AIMS)\n  period: null\n  issuer: null\n  report_access: on_request\n  text: The ISO 42001 Certification validates that Flank implements a robust Artificial Intelligence Management\n    System (AIMS).\n- framework: SOC2\n  type: Type 2 report\n  scope: security controls\n  period: continuous period\n  issuer: null\n  report_access: on_request\n  text: The SOC 2 Type 2 Report provides\
  \ independent validation of the design and operating effectiveness of Flank’s\n    security controls over a continuous period.\n- framework: GDPR\n  type: Regulation compliance\n  scope: personal data processing via Data Processing Agreement\n  period: null\n  issuer: null\n  report_access: unstated\n  text: The Data Processing Agreement (DPA) is our contractual commitment to meet stringent global data protection\n    regulations, including the GDPR and CCPA.\n- framework: CCPA\n  type: Regulation compliance\n  scope: personal data via Data Processing Agreement\n  period: null\n  issuer: null\n  report_access: unstated\n  text: The Data Processing Agreement (DPA) is our contractual commitment to meet stringent global data protection\n    regulations, including the GDPR and CCPA.\n"
source_yaml_url: https://artifacts.apis.io/flank/compliance/flank-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Flank's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Ai Enterprise Software
- Legal Tech
- AI Agents
- Contract Management
- Legal Operations
---
