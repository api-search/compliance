---
claim_count: 8
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: Standard Backplain SaaS
    text: 'SOC 2 Type II In progress (target: Q3 2026)'
    type: SOC 2 Type II
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Enterprise tier
    text: HIPAA — BAA available Enterprise tier
    type: BAA available
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Sovereign (San Diego DC) via colocation facility
    text: Hardware Backplain owns, colocated in a SOC 2 Type II certified Tier 3 facility.
    type: SOC 2 Type II facility (inherited)
  - framework: HITRUST
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HITRUST CSF Roadmap Inherited from facility
    type: HITRUST CSF
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001 Roadmap Inherited from facility
    type: ISO 27001
  - framework: NIST-800-53
    issuer: null
    period: null
    report_access: unstated
    scope: Mapped controls
    text: NIST 800-53 / 800-171 (CMMC L2 baseline) Mapped controls Inherited from facility
    type: NIST 800-53 / 800-171 (CMMC L2 baseline)
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: FedRAMP Pursuing — not yet listed on the Marketplace
    type: FedRAMP
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR / DPA DPA available; SCCs included
    type: DPA available; SCCs included
  trust_center:
    url: https://backplain.com/security
frameworks:
- FedRAMP
- GDPR
- HIPAA
- HITRUST
- ISO27001
- NIST-800-53
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Backplain
provenance_date: '2026-11-09'
provider_name: Backplain
provider_slug: backplain
slug: backplain-compliance
source_date: '2026-11-09'
source_filename: backplain-compliance.yml
source_heading: Compliance
source_page: https://backplain.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Backplain\naid: backplain\nurl: https://backplain.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://backplain.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: Standard Backplain SaaS\n  period: null\n  issuer: null\n  report_access: nda\n  text: 'SOC 2 Type II In progress (target: Q3 2026)'\n- framework: HIPAA\n  type: BAA available\n  scope: Enterprise tier\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA — BAA available Enterprise tier\n- framework: SOC2\n  type: SOC 2 Type II facility (inherited)\n  scope: Sovereign (San Diego DC)\
  \ via colocation facility\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Hardware Backplain owns, colocated in a SOC 2 Type II certified Tier 3 facility.\n- framework: HITRUST\n  type: HITRUST CSF\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HITRUST CSF Roadmap Inherited from facility\n- framework: ISO27001\n  type: ISO 27001\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001 Roadmap Inherited from facility\n- framework: NIST-800-53\n  type: NIST 800-53 / 800-171 (CMMC L2 baseline)\n  scope: Mapped controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: NIST 800-53 / 800-171 (CMMC L2 baseline) Mapped controls Inherited from facility\n- framework: FedRAMP\n  type: FedRAMP\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: FedRAMP Pursuing — not yet listed on the Marketplace\n- framework: GDPR\n  type: DPA available; SCCs included\n  scope:\
  \ null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR / DPA DPA available; SCCs included\n"
source_yaml_url: https://artifacts.apis.io/backplain/compliance/backplain-compliance.yml
stated_fields:
- attestations
summary_line: 8 quoted statements, read from Backplain's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Data Governance
- Security
- Enterprise
---
