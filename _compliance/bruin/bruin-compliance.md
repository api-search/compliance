---
claim_count: 6
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: Prescient Security LLC
    period: null
    report_access: public
    scope: design, development, operation, and maintenance of the Bruin platform, including infrastructure hosted on Google Cloud Platform and DigitalOcean
    text: Certificate number 123371 (Issue 1) Certification body Prescient Security LLC Issued August 19, 2026 Valid until August 18, 2029
    type: certification
  - framework: SOC2
    issuer: Prescient Assurance LLC
    period: null
    report_access: nda
    scope: security, availability, and confidentiality
    text: The report is a restricted-use document, so we share it under NDA.
    type: Type 2 attestation
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: lawful processing, data subject rights, and EU data residency; Bruin acts as a processor
    text: GDPR Lawful processing, data subject rights, and EU data residency. We act as a processor on behalf of our customers.
    type: compliance statement
  - framework: ISO27001
    issuer: Prescient Security LLC
    period: null
    report_access: unstated
    scope: design, development, operation, and maintenance of the Bruin platform, including Bruin CLI, Bruin Cloud, and infrastructure hosted on Google Cloud Platform and DigitalOcean
    source: https://getbruin.com/security/
    text: Our information security management system is certified to ISO/IEC 27001:2022 by Prescient Security.
    type: certification
  - framework: SOC2
    issuer: Prescient Assurance LLC
    period: null
    report_access: nda
    scope: security, availability, and confidentiality under the AICPA Trust Services Criteria
    source: https://getbruin.com/security/
    text: The report is a restricted-use document, so we share it under NDA.
    type: Type 2 attestation
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: lawful processing, data subject rights, and EU data residency; provider acts as processor
    source: https://getbruin.com/security/
    text: GDPR Lawful processing, data subject rights, and EU data residency. We act as a processor on behalf of our customers.
    type: compliance statement
  trust_center:
    url: https://getbruin.com/security/
frameworks:
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Bruin
provenance_date: '2026-11-09'
provider_name: Bruin
provider_slug: bruin
slug: bruin-compliance
source_date: '2026-11-09'
source_filename: bruin-compliance.yml
source_heading: Compliance
source_page: https://getbruin.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Bruin\naid: bruin\nurl: https://getbruin.com/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/bruin-trust-center.yml\n  sources:\n  - https://getbruin.com/security/\ntrust_center:\n  url: https://getbruin.com/security/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: design, development, operation, and maintenance of the Bruin platform, including infrastructure hosted\n    on Google Cloud Platform and DigitalOcean\n  period: null\n  issuer: Prescient Security LLC\n  report_access: public\n  text: Certificate number 123371 (Issue 1) Certification body Prescient Security\
  \ LLC Issued August 19, 2026 Valid\n    until August 18, 2029\n- framework: SOC2\n  type: Type 2 attestation\n  scope: security, availability, and confidentiality\n  period: null\n  issuer: Prescient Assurance LLC\n  report_access: nda\n  text: The report is a restricted-use document, so we share it under NDA.\n- framework: GDPR\n  type: compliance statement\n  scope: lawful processing, data subject rights, and EU data residency; Bruin acts as a processor\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR Lawful processing, data subject rights, and EU data residency. We act as a processor on behalf of our\n    customers.\n- framework: ISO27001\n  type: certification\n  scope: design, development, operation, and maintenance of the Bruin platform, including Bruin CLI, Bruin Cloud,\n    and infrastructure hosted on Google Cloud Platform and DigitalOcean\n  period: null\n  issuer: Prescient Security LLC\n  report_access: unstated\n  text: Our information security management\
  \ system is certified to ISO/IEC 27001:2022 by Prescient Security.\n  source: https://getbruin.com/security/\n- framework: SOC2\n  type: Type 2 attestation\n  scope: security, availability, and confidentiality under the AICPA Trust Services Criteria\n  period: null\n  issuer: Prescient Assurance LLC\n  report_access: nda\n  text: The report is a restricted-use document, so we share it under NDA.\n  source: https://getbruin.com/security/\n- framework: GDPR\n  type: compliance statement\n  scope: lawful processing, data subject rights, and EU data residency; provider acts as processor\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR Lawful processing, data subject rights, and EU data residency. We act as a processor on behalf of our\n    customers.\n  source: https://getbruin.com/security/\n"
source_yaml_url: https://artifacts.apis.io/bruin/compliance/bruin-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from Bruin's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- Data Engineering
- Data Pipeline
- ETL
- ELT
- Analytics
- Data Quality
- CLI
- MCP
- Open Source
---
