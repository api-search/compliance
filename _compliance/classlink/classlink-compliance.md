---
api_specs:
- filename: v1p1
  format: yaml
  label: ClassLink OneRoster API
  slug: classlink-oneroster-api
  spec_type: OpenAPI
  url: https://sandbox-vn-v2.oneroster.com/ims/oneroster/v1p1
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: third-party security firms
    period: null
    report_access: unstated
    scope: Security, Availability, Processing Integrity, Confidentiality or Privacy
    text: SOC 2 Type II – Report on Controls at a Service Organization Relevant to Security, Availability, Processing Integrity, Confidentiality or Privacy.
    type: SOC 2 Type II audit
  - framework: CSA-STAR
    issuer: third-party independent assessor
    period: null
    report_access: unstated
    scope: security of cloud service
    text: CSA STAR – Rigorous third-party independent assessment of the security of a cloud service provider.
    type: CSA STAR third-party assessment
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: information risk management process
    text: ISO 27001 – Framework of policies and procedures for an organization’s information risk management process.
    type: ISO 27001 framework
  trust_center:
    url: https://www.classlink.com/company/security
frameworks:
- CSA-STAR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: ClassLink
provenance_date: '2026-11-09'
provider_name: ClassLink
provider_slug: classlink
slug: classlink-compliance
source_date: '2026-11-09'
source_filename: classlink-compliance.yml
source_heading: Compliance
source_page: https://www.classlink.com/company/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: ClassLink\naid: classlink\nurl: https://www.classlink.com/company/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/classlink-trust-center.yml\ntrust_center:\n  url: https://www.classlink.com/company/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II audit\n  scope: Security, Availability, Processing Integrity, Confidentiality or Privacy\n  period: null\n  issuer: third-party security firms\n  report_access: unstated\n  text: SOC 2 Type II – Report on Controls at a Service Organization Relevant to Security, Availability, Processing\n    Integrity, Confidentiality or Privacy.\n\
  - framework: CSA-STAR\n  type: CSA STAR third-party assessment\n  scope: security of cloud service\n  period: null\n  issuer: third-party independent assessor\n  report_access: unstated\n  text: CSA STAR – Rigorous third-party independent assessment of the security of a cloud service provider.\n- framework: ISO27001\n  type: ISO 27001 framework\n  scope: information risk management process\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001 – Framework of policies and procedures for an organization’s information risk management process.\n"
source_yaml_url: https://artifacts.apis.io/classlink/compliance/classlink-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from ClassLink's own page on 2026-11-09.
synthetic: false
tags:
- EdTech
- Education
- Identity
- SSO
- OneRoster
- Rostering
- Provisioning
- Analytics
- K-12
- LTI
- OAuth
- Student Data
- Authentication
---
