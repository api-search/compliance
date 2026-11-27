---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: unstated
    period: annual
    report_access: unstated
    scope: security controls
    text: Our security controls are validated through annual SOC 2 Type II and ISO 27001 audits
    type: Type II audit
  - framework: ISO27001
    issuer: unstated
    period: annual
    report_access: unstated
    scope: security controls
    text: Our security controls are validated through annual SOC 2 Type II and ISO 27001 audits
    type: audit
  - framework: GDPR
    issuer: unstated
    period: null
    report_access: unstated
    scope: contract documents
    text: Agency’s contract documents include enforceable commitments around data protection, data access, and incident response, aligned with leading security and privacy standards including SOC 2, ISO 27001, and GDPR.
    type: aligned with standard
  trust_center:
    url: https://www.agency.inc/security
frameworks:
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Agency
provenance_date: '2026-11-09'
provider_name: Agency
provider_slug: agency
slug: agency-compliance
source_date: '2026-11-09'
source_filename: agency-compliance.yml
source_heading: Compliance
source_page: https://www.agency.inc/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Agency\naid: agency\nurl: https://www.agency.inc/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.agency.inc/security\nattestations:\n- framework: SOC2\n  type: Type II audit\n  scope: security controls\n  period: annual\n  issuer: unstated\n  report_access: unstated\n  text: Our security controls are validated through annual SOC 2 Type II and ISO 27001 audits\n- framework: ISO27001\n  type: audit\n  scope: security controls\n  period: annual\n  issuer: unstated\n  report_access: unstated\n  text: Our security controls are validated through annual SOC 2 Type II and ISO 27001 audits\n- framework:\
  \ GDPR\n  type: aligned with standard\n  scope: contract documents\n  period: null\n  issuer: unstated\n  report_access: unstated\n  text: Agency’s contract documents include enforceable commitments around data protection, data access, and incident\n    response, aligned with leading security and privacy standards including SOC 2, ISO 27001, and GDPR.\n"
source_yaml_url: https://artifacts.apis.io/agency/compliance/agency-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Agency's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Customer Success
- Software-as-a-Service
- Revenue Operations
---
