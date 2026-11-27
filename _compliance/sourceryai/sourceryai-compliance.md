---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: SOC 2 Type 2 Report March 02, 2026
    type: SOC 2 Type 2 report
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: SOC 2 Type 1 Report March 02, 2026
    type: SOC 2 Type 1 report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR Compliant
    type: compliance statement
  - framework: SOC2
    issuer: independent auditor
    period: null
    report_access: unstated
    scope: security controls
    source: https://www.sourcery.ai/security
    text: SOC 2 Type II compliant An independent auditor verifies our security controls.
    type: SOC 2 Type II
  trust_center:
    url: https://trust.mycroft.io/sourcery
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Sourcery.AI
provenance_date: '2026-11-10'
provider_name: Sourcery.AI
provider_slug: sourceryai
slug: sourceryai-compliance
source_date: '2026-11-10'
source_filename: sourceryai-compliance.yml
source_heading: Compliance
source_page: https://trust.mycroft.io/sourcery
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Sourcery.AI\naid: sourceryai\nurl: https://trust.mycroft.io/sourcery\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/sourceryai-trust-center.yml\n  sources:\n  - https://trust.mycroft.io/sourcery\n  - https://www.sourcery.ai/security\ntrust_center:\n  url: https://trust.mycroft.io/sourcery\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Type 2 Report March 02, 2026\n- framework: SOC2\n  type: SOC 2 Type 1 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text:\
  \ SOC 2 Type 1 Report March 02, 2026\n- framework: GDPR\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR Compliant\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: security controls\n  period: null\n  issuer: independent auditor\n  report_access: unstated\n  text: SOC 2 Type II compliant An independent auditor verifies our security controls.\n  source: https://www.sourcery.ai/security\n"
source_yaml_url: https://artifacts.apis.io/sourceryai/compliance/sourceryai-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Sourcery.AI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Code Review
- Developer Tools
- Static Analysis
- Security Scanning
- Code Quality
- Artificial Intelligence
- DevOps
---
