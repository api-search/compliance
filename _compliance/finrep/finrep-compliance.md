---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent auditor
    period: null
    report_access: on_request
    scope: Security, Availability, and Confidentiality
    text: Certified SOC 2 Type II Security, Availability, and Confidentiality. Controls validated over time by an independent auditor.
    type: SOC 2 Type II
  - framework: ISO27001
    issuer: independent firms
    period: null
    report_access: on_request
    scope: Full Information Security Management System covering risk, access, incident, and continuity governance
    text: Full Information Security Management System covering risk, access, incident, and continuity governance.
    type: ISO/IEC 27001 certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: on_request
    scope: Data processing aligned to GDPR principles, with DPAs available on request
    text: In progress GDPR-aligned Data processing aligned to GDPR principles, with DPAs available on request.
    type: GDPR-aligned data processing (in progress)
  trust_center:
    url: https://www.finrep.ai/security
frameworks:
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Finrep
provenance_date: '2026-11-09'
provider_name: Finrep
provider_slug: finrep
slug: finrep-compliance
source_date: '2026-11-09'
source_filename: finrep-compliance.yml
source_heading: Compliance
source_page: https://www.finrep.ai/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Finrep\naid: finrep\nurl: https://www.finrep.ai/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/finrep-trust-center.yml\ntrust_center:\n  url: https://www.finrep.ai/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: Security, Availability, and Confidentiality\n  period: null\n  issuer: independent auditor\n  report_access: on_request\n  text: Certified SOC 2 Type II Security, Availability, and Confidentiality. Controls validated over time by an\n    independent auditor.\n- framework: ISO27001\n  type: ISO/IEC 27001 certification\n  scope: Full Information Security\
  \ Management System covering risk, access, incident, and continuity governance\n  period: null\n  issuer: independent firms\n  report_access: on_request\n  text: Full Information Security Management System covering risk, access, incident, and continuity governance.\n- framework: GDPR\n  type: GDPR-aligned data processing (in progress)\n  scope: Data processing aligned to GDPR principles, with DPAs available on request\n  period: null\n  issuer: null\n  report_access: on_request\n  text: In progress GDPR-aligned Data processing aligned to GDPR principles, with DPAs available on request.\n"
source_yaml_url: https://artifacts.apis.io/finrep/compliance/finrep-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Finrep's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Financial Reporting
- SEC Filings
- Accounting
- Fintech
- Compliance
- Disclosure
- EDGAR
---
