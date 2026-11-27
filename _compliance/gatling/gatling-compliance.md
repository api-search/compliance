---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: Bastion Technologies
    period: sustained period of operation
    report_access: on_request
    scope: Gatling's own security, availability, and confidentiality controls
    text: Gatling's own security, availability, and confidentiality controls, audited by Bastion Technologies, covering a sustained period of operation, not a single point in time.
    type: Type II audit
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: data processing in line with EU and UK privacy regulations
    text: GDPR & CNIL compliant
    type: compliance
  - framework: other
    issuer: AWS
    period: null
    report_access: unstated
    scope: AWS infrastructure holds ISO 27001, SOC 2, PCI DSS Level 1, and HDS certifications
    text: Gatling is hosted on AWS, which itself holds ISO 27001, SOC 2, PCI DSS Level 1, and HDS certifications.
    type: hosting provider certifications
  trust_center:
    url: https://gatling.io/security
frameworks:
- GDPR
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Gatling
provenance_date: '2026-11-09'
provider_name: Gatling
provider_slug: gatling
slug: gatling-compliance
source_date: '2026-11-09'
source_filename: gatling-compliance.yml
source_heading: Compliance
source_page: https://gatling.io/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Gatling\naid: gatling\nurl: https://gatling.io/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/gatling-trust-center.yml\ntrust_center:\n  url: https://gatling.io/security\nattestations:\n- framework: SOC2\n  type: Type II audit\n  scope: Gatling's own security, availability, and confidentiality controls\n  period: sustained period of operation\n  issuer: Bastion Technologies\n  report_access: on_request\n  text: Gatling's own security, availability, and confidentiality controls, audited by Bastion Technologies, covering\n    a sustained period of operation, not a single point in time.\n- framework:\
  \ GDPR\n  type: compliance\n  scope: data processing in line with EU and UK privacy regulations\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR & CNIL compliant\n- framework: other\n  type: hosting provider certifications\n  scope: AWS infrastructure holds ISO 27001, SOC 2, PCI DSS Level 1, and HDS certifications\n  period: null\n  issuer: AWS\n  report_access: unstated\n  text: Gatling is hosted on AWS, which itself holds ISO 27001, SOC 2, PCI DSS Level 1, and HDS certifications.\n"
source_yaml_url: https://artifacts.apis.io/gatling/compliance/gatling-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Gatling's own page on 2026-11-09.
synthetic: false
tags:
- Load Testing
- Performance Testing
- Testing
---
