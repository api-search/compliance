---
claim_count: 9
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II
    type: SOC 2 Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: GDPR badge
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA
    type: HIPAA badge
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PCI
    type: PCI badge
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: FedRAMP Moderate
    type: FedRAMP Moderate badge
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001
    type: ISO 27001 badge
  - framework: ISO27017
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27017
    type: ISO 27017 badge
  - framework: ISO27018
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27018
    type: ISO 27018 badge
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CSA STAR 2
    type: CSA STAR 2 badge
  trust_center:
    url: https://customertrust.splunk.com/
frameworks:
- CSA-STAR
- FedRAMP
- GDPR
- HIPAA
- ISO27001
- ISO27017
- ISO27018
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Splunk SOAR
provenance_date: '2026-11-10'
provider_name: Splunk SOAR
provider_slug: splunk-soar
slug: splunk-soar-compliance
source_date: '2026-11-10'
source_filename: splunk-soar-compliance.yml
source_heading: Compliance
source_page: https://customertrust.splunk.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Splunk SOAR\naid: splunk-soar\nurl: https://customertrust.splunk.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/splunk-soar-trust-center.yml\ntrust_center:\n  url: https://customertrust.splunk.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II\n- framework: GDPR\n  type: GDPR badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: HIPAA\n  type: HIPAA badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text:\
  \ HIPAA\n- framework: PCI-DSS\n  type: PCI badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI\n- framework: FedRAMP\n  type: FedRAMP Moderate badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: FedRAMP Moderate\n- framework: ISO27001\n  type: ISO 27001 badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001\n- framework: ISO27017\n  type: ISO 27017 badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27017\n- framework: ISO27018\n  type: ISO 27018 badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27018\n- framework: CSA-STAR\n  type: CSA STAR 2 badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CSA STAR 2\n"
source_yaml_url: https://artifacts.apis.io/splunk-soar/compliance/splunk-soar-compliance.yml
stated_fields:
- attestations
summary_line: 9 quoted statements, read from Splunk SOAR's own page on 2026-11-10.
synthetic: false
tags:
- Security
- SOAR
- Automation
- Orchestration
- Incident Response
- SOC
- Security Operations
- Playbooks
- Case Management
- Threat Intelligence
---
