---
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent CPA firm
    period: Dec 22, 2025 to Mar 22, 2026
    report_access: on_request
    scope: Security
    text: Independent SOC 2 Type 2 examination (Security) covering Dec 22, 2025 to Mar 22, 2026.
    type: SOC 2 Type 2 examination
  - framework: SOC2
    issuer: independent CPA firm
    period: December 22, 2025
    report_access: on_request
    scope: null
    text: SOC 2 Type 1 report as of December 22, 2025, issued by an independent CPA firm.
    type: SOC 2 Type 1 report
  - framework: HIPAA
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: LunaBill operates as a HIPAA business associate, signs BAAs with customers, and maintains a HIPAA security program with regular risk assessments.
    type: business associate and HIPAA security program
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: LunaBill product
    source: https://lunabill.com/trust/
    text: LunaBill is SOC 2 Type II certified.
    type: Type II certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: PHI handled inside the product
    source: https://lunabill.com/trust/
    text: Yes, before any PHI moves.
    type: HIPAA compliant with BAA
  trust_center:
    url: https://trust.lunabill.com
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Lunabill
provenance_date: '2026-11-10'
provider_name: Lunabill
provider_slug: lunabill
slug: lunabill-compliance
source_date: '2026-11-10'
source_filename: lunabill-compliance.yml
source_heading: Compliance
source_page: https://trust.lunabill.com
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Lunabill\naid: lunabill\nurl: https://trust.lunabill.com\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://lunabill.com/trust/\n  - https://trust.lunabill.com\ntrust_center:\n  url: https://trust.lunabill.com\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 examination\n  scope: Security\n  period: Dec 22, 2025 to Mar 22, 2026\n  issuer: independent CPA firm\n  report_access: on_request\n  text: Independent SOC 2 Type 2 examination (Security) covering Dec 22, 2025 to Mar 22, 2026.\n- framework: SOC2\n  type: SOC 2 Type 1 report\n  scope: null\n  period: December 22, 2025\n  issuer: independent CPA firm\n\
  \  report_access: on_request\n  text: SOC 2 Type 1 report as of December 22, 2025, issued by an independent CPA firm.\n- framework: HIPAA\n  type: business associate and HIPAA security program\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: LunaBill operates as a HIPAA business associate, signs BAAs with customers, and maintains a HIPAA security\n    program with regular risk assessments.\n- framework: SOC2\n  type: Type II certification\n  scope: LunaBill product\n  period: null\n  issuer: null\n  report_access: nda\n  text: LunaBill is SOC 2 Type II certified.\n  source: https://lunabill.com/trust/\n- framework: HIPAA\n  type: HIPAA compliant with BAA\n  scope: PHI handled inside the product\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Yes, before any PHI moves.\n  source: https://lunabill.com/trust/\n"
source_yaml_url: https://artifacts.apis.io/lunabill/compliance/lunabill-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Lunabill's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Revenue Cycle Management
- Medical Billing
- Insurance Claims
- AI Agents
- HIPAA
- Health Tech
---
