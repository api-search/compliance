---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: a third party
    period: null
    report_access: unstated
    scope: information security management
    text: Cycode is ISO27001 certified by a third party
    type: third-party certification
  - framework: ISO42001
    issuer: a third party
    period: null
    report_access: unstated
    scope: AI development and deployment approaches
    text: Cycode is ISO/IEC 42001 certified by a third party
    type: third-party certification
  - framework: SOC2
    issuer: an independent auditor
    period: null
    report_access: unstated
    scope: product, infrastructure, and policies
    text: Cycode has completed a full third-party SOC 2 Type II audit.
    type: SOC 2 Type II audit
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: unstated
    scope: self-assessment of security controls
    text: Cycode has completed a CSA STAR Level 1 attestation.
    type: CSA STAR Level 1 attestation
  trust_center:
    url: https://cycode.com/trust/
frameworks:
- CSA-STAR
- ISO27001
- ISO42001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Cycode
provenance_date: '2026-11-09'
provider_name: Cycode
provider_slug: cycode
slug: cycode-compliance
source_date: '2026-11-09'
source_filename: cycode-compliance.yml
source_heading: Compliance
source_page: https://cycode.com/trust/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Cycode\naid: cycode\nurl: https://cycode.com/trust/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://cycode.com/trust/\nattestations:\n- framework: ISO27001\n  type: third-party certification\n  scope: information security management\n  period: null\n  issuer: a third party\n  report_access: unstated\n  text: Cycode is ISO27001 certified by a third party\n- framework: ISO42001\n  type: third-party certification\n  scope: AI development and deployment approaches\n  period: null\n  issuer: a third party\n  report_access: unstated\n  text: Cycode is ISO/IEC 42001 certified by a third party\n- framework:\
  \ SOC2\n  type: SOC 2 Type II audit\n  scope: product, infrastructure, and policies\n  period: null\n  issuer: an independent auditor\n  report_access: unstated\n  text: Cycode has completed a full third-party SOC 2 Type II audit.\n- framework: CSA-STAR\n  type: CSA STAR Level 1 attestation\n  scope: self-assessment of security controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Cycode has completed a CSA STAR Level 1 attestation.\n"
source_yaml_url: https://artifacts.apis.io/cycode/compliance/cycode-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Cycode's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- Application Security
- Software Supply Chain Security
- ASPM
- DevSecOps
- Secrets Scanning
- SAST
- Software Composition Analysis
- Developer Tools
- MCP
- CLI
---
