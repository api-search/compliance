---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: platform security, availability, and confidentiality standards
    text: VComply is SOC 2 Type 2 certified, demonstrating our commitment to maintaining strict security, availability, and confidentiality standards.
    type: SOC 2 Type 2 certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: sensitive health information
    text: We are also HIPAA compliant, protecting sensitive health information in line with regulatory requirements.
    type: HIPAA compliance
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: These certifications together with our ISO/IEC 27001 compliant status underscore our commitment to maintaining strong internal controls and rigorous security practices.
    type: ISO/IEC 27001 compliant status
  trust_center:
    url: https://www.v-comply.com/security/
frameworks:
- HIPAA
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: VComply
provenance_date: '2026-11-10'
provider_name: VComply
provider_slug: vcomply
slug: vcomply-compliance
source_date: '2026-11-10'
source_filename: vcomply-compliance.yml
source_heading: Compliance
source_page: https://www.v-comply.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: VComply\naid: vcomply\nurl: https://www.v-comply.com/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.v-comply.com/security/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 certification\n  scope: platform security, availability, and confidentiality standards\n  period: null\n  issuer: null\n  report_access: unstated\n  text: VComply is SOC 2 Type 2 certified, demonstrating our commitment to maintaining strict security, availability,\n    and confidentiality standards.\n- framework: HIPAA\n  type: HIPAA compliance\n  scope: sensitive health information\n  period: null\n  issuer:\
  \ null\n  report_access: unstated\n  text: We are also HIPAA compliant, protecting sensitive health information in line with regulatory requirements.\n- framework: ISO27001\n  type: ISO/IEC 27001 compliant status\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: These certifications together with our ISO/IEC 27001 compliant status underscore our commitment to maintaining\n    strong internal controls and rigorous security practices.\n"
source_yaml_url: https://artifacts.apis.io/vcomply/compliance/vcomply-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from VComply's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise
- GRC
- Compliance
- Risk Management
- Policy Management
- Audit
- Incident Management
- Software-as-a-Service
---
