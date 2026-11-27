---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: Thoropass Assurance
    period: null
    report_access: nda
    scope: Design of controls against Trust Services Criteria for Security and Confidentiality
    text: The report was issued on October 27, 2026 by Thoropass Assurance, an AICPA-registered CPA firm, with an unqualified opinion.
    type: SOC 2 Type 1
  - framework: SOC2
    issuer: null
    period: October 1, 2026 to March 31, 2027
    report_access: unstated
    scope: Same scope as Type 1
    text: The observation period runs from October 1, 2026 to March 31, 2027, with the same scope.
    type: SOC 2 Type 2
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Calven as processor for customer data; Data Processing Addendum incorporated into Terms of Use
    text: For your data, you are the controller and Calven is the processor.
    type: GDPR processor compliance
  trust_center:
    url: https://calven.ai/security
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Calven AI
provenance_date: '2026-11-09'
provider_name: Calven AI
provider_slug: calven-ai
slug: calven-ai-compliance
source_date: '2026-11-09'
source_filename: calven-ai-compliance.yml
source_heading: Compliance
source_page: https://calven.ai/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Calven AI\naid: calven-ai\nurl: https://calven.ai/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://calven.ai/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 1\n  scope: Design of controls against Trust Services Criteria for Security and Confidentiality\n  period: null\n  issuer: Thoropass Assurance\n  report_access: nda\n  text: The report was issued on October 27, 2026 by Thoropass Assurance, an AICPA-registered CPA firm, with an\n    unqualified opinion.\n- framework: SOC2\n  type: SOC 2 Type 2\n  scope: Same scope as Type 1\n  period: October 1, 2026 to March 31, 2027\n  issuer:\
  \ null\n  report_access: unstated\n  text: The observation period runs from October 1, 2026 to March 31, 2027, with the same scope.\n- framework: GDPR\n  type: GDPR processor compliance\n  scope: Calven as processor for customer data; Data Processing Addendum incorporated into Terms of Use\n  period: null\n  issuer: null\n  report_access: unstated\n  text: For your data, you are the controller and Calven is the processor.\n"
source_yaml_url: https://artifacts.apis.io/calven-ai/compliance/calven-ai-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Calven AI's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Marketing
- Platform
- B2B
- Automation
---
