---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: protected health information
    text: We safeguard protected health information with HIPAA-compliant processes, policies, and technical controls, backed by a formal compliance program and a signed BAA before any PHI is exchanged.
    type: compliance program with BAA
  - framework: SOC2
    issuer: third-party auditor
    period: null
    report_access: unstated
    scope: security, availability, and confidentiality
    text: Independently audited controls covering security, availability, and confidentiality, with annual third-party penetration testing and continuous vulnerability scanning.
    type: SOC 2 Type II audit
  trust_center:
    url: https://www.cofactorai.com/security-compliance
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Cofactor AI
provenance_date: '2026-11-09'
provider_name: Cofactor AI
provider_slug: cofactor-ai
slug: cofactor-ai-compliance
source_date: '2026-11-09'
source_filename: cofactor-ai-compliance.yml
source_heading: Compliance
source_page: https://www.cofactorai.com/security-compliance
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Cofactor AI\naid: cofactor-ai\nurl: https://www.cofactorai.com/security-compliance\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.cofactorai.com/security-compliance\nattestations:\n- framework: HIPAA\n  type: compliance program with BAA\n  scope: protected health information\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We safeguard protected health information with HIPAA-compliant processes, policies, and technical controls,\n    backed by a formal compliance program and a signed BAA before any PHI is exchanged.\n- framework: SOC2\n  type: SOC 2 Type II audit\n  scope: security,\
  \ availability, and confidentiality\n  period: null\n  issuer: third-party auditor\n  report_access: unstated\n  text: Independently audited controls covering security, availability, and confidentiality, with annual third-party\n    penetration testing and continuous vulnerability scanning.\n"
source_yaml_url: https://artifacts.apis.io/cofactor-ai/compliance/cofactor-ai-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Cofactor AI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Artificial Intelligence
- Platform
- Analytics
---
