---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: null
    text: SOC 2 Type II Independently audited; report (scope and period) available via the Trust Center under NDA.
    type: Type II audit
  - framework: ISO42001
    issuer: null
    period: null
    report_access: nda
    scope: AI Management System (AIMS)
    text: ISO/IEC 42001:2023 Certified (Nov 2025) — AI Management System (AIMS).
    type: Certification
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: Runs on Google Cloud's FedRAMP-authorized platform
    text: Runs on Google Cloud's FedRAMP-authorized platform.
    type: Platform inheritance
  trust_center:
    url: https://behavox.com/security-compliance
frameworks:
- FedRAMP
- ISO42001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Behavox
provenance_date: '2026-11-09'
provider_name: Behavox
provider_slug: behavox
slug: behavox-compliance
source_date: '2026-11-09'
source_filename: behavox-compliance.yml
source_heading: Compliance
source_page: https://behavox.com/security-compliance
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Behavox\naid: behavox\nurl: https://behavox.com/security-compliance\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://behavox.com/security-compliance\nattestations:\n- framework: SOC2\n  type: Type II audit\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: SOC 2 Type II Independently audited; report (scope and period) available via the Trust Center under NDA.\n- framework: ISO42001\n  type: Certification\n  scope: AI Management System (AIMS)\n  period: null\n  issuer: null\n  report_access: nda\n  text: ISO/IEC 42001:2023 Certified (Nov 2025) — AI Management System (AIMS).\n\
  - framework: FedRAMP\n  type: Platform inheritance\n  scope: Runs on Google Cloud's FedRAMP-authorized platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Runs on Google Cloud's FedRAMP-authorized platform.\n"
source_yaml_url: https://artifacts.apis.io/behavox/compliance/behavox-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Behavox's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Compliance
- RegTech
- Artificial Intelligence
- Financial Services
- Security
- Trade Surveillance
---
