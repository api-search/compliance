---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: AICPA / licensed CPA (third-party audit)
    period: null
    report_access: on_request
    scope: Assembla source code management platform
    text: Full documentation is available on request for your procurement and legal teams.
    type: SOC 2 Type II certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: on_request
    scope: EU personal data processing
    text: Full GDPR documentation is available on request.
    type: GDPR compliance statement
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Transfers of personal data between EU and US
    text: Assembla Cloud Starter & Growth SOC 2 Type II, GDPR, EU-US Data Privacy Framework (DPF)
    type: EU-US Data Privacy Framework (DPF)
  trust_center:
    url: https://get.assembla.com/security/
frameworks:
- GDPR
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Assembla
provenance_date: '2026-11-09'
provider_name: Assembla
provider_slug: assembla
slug: assembla-compliance
source_date: '2026-11-09'
source_filename: assembla-compliance.yml
source_heading: Compliance
source_page: https://get.assembla.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Assembla\naid: assembla\nurl: https://get.assembla.com/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://get.assembla.com/security/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II certification\n  scope: Assembla source code management platform\n  period: null\n  issuer: AICPA / licensed CPA (third-party audit)\n  report_access: on_request\n  text: Full documentation is available on request for your procurement and legal teams.\n- framework: GDPR\n  type: GDPR compliance statement\n  scope: EU personal data processing\n  period: null\n  issuer: null\n  report_access: on_request\n  text:\
  \ Full GDPR documentation is available on request.\n- framework: other\n  type: EU-US Data Privacy Framework (DPF)\n  scope: Transfers of personal data between EU and US\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Assembla Cloud Starter & Growth SOC 2 Type II, GDPR, EU-US Data Privacy Framework (DPF)\n"
source_yaml_url: https://artifacts.apis.io/assembla/compliance/assembla-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Assembla's own page on 2026-11-09.
synthetic: false
tags:
- Version Control
- Cloud Hosting
- DevOps
- Project Management
- Security
---
