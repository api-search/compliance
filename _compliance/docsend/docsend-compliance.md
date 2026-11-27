---
claim_count: 9
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: October 1, 2024 through September 30, 2025
    report_access: unstated
    scope: Dropbox DocSend
    text: Dropbox’s updated SOC reports for the period of October 1, 2024 through September 30, 2025 are now available for download in the Trust Center.
    type: SOC 2 report
  - framework: SOC3
    issuer: null
    period: null
    report_access: unstated
    scope: Dropbox DocSend
    text: Dropbox DocSend SOC 3
    type: SOC 3 report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Dropbox
    text: Dropbox ISO 27001
    type: ISO/IEC 27001 certificate
  - framework: ISO27018
    issuer: null
    period: null
    report_access: unstated
    scope: Dropbox
    text: ISO/IEC 27018:2019
    type: ISO/IEC 27018:2019
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Dropbox Sign
    text: HIPAA COMPLIANCE
    type: HIPAA compliance
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: Dropbox
    text: PCI DSS
    type: PCI DSS compliance
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Dropbox
    text: GDPR
    type: GDPR compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: Dropbox
    text: CCPA
    type: CCPA compliance
  - framework: SOC2
    issuer: independent third-party auditors
    period: annual
    report_access: on_request
    scope: unstated
    source: https://www.docsend.com/trust-center/
    text: We comply with standards and regulations like SOC 2. On an annual basis our independent third-party auditors test our controls and provide their reports and opinions which we can provide to you upon request.
    type: third-party audit report
  trust_center:
    url: https://trust.dropbox.com/?product=docsend&itemName=certifications&source=click&itemUid=4064ac33-7b48-407b-aed7-ce02971d1ec1
frameworks:
- CCPA
- GDPR
- HIPAA
- ISO27001
- ISO27018
- PCI-DSS
- SOC2
- SOC3
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: DocSend
provenance_date: '2026-11-09'
provider_name: DocSend
provider_slug: docsend
slug: docsend-compliance
source_date: '2026-11-09'
source_filename: docsend-compliance.yml
source_heading: Compliance
source_page: https://trust.dropbox.com/?product=docsend&itemName=certifications&source=click&itemUid=4064ac33-7b48-407b-aed7-ce02971d1ec1
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: DocSend\naid: docsend\nurl: https://trust.dropbox.com/?product=docsend&itemName=certifications&source=click&itemUid=4064ac33-7b48-407b-aed7-ce02971d1ec1\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/docsend-trust-center.yml\n  sources:\n  - https://trust.dropbox.com/?product=docsend&itemName=certifications&source=click&itemUid=4064ac33-7b48-407b-aed7-ce02971d1ec1\n  - https://www.docsend.com/trust-center/\ntrust_center:\n  url: https://trust.dropbox.com/?product=docsend&itemName=certifications&source=click&itemUid=4064ac33-7b48-407b-aed7-ce02971d1ec1\nattestations:\n- framework: SOC2\n  type: SOC\
  \ 2 report\n  scope: Dropbox DocSend\n  period: October 1, 2024 through September 30, 2025\n  issuer: null\n  report_access: unstated\n  text: Dropbox’s updated SOC reports for the period of October 1, 2024 through September 30, 2025 are now available\n    for download in the Trust Center.\n- framework: SOC3\n  type: SOC 3 report\n  scope: Dropbox DocSend\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Dropbox DocSend SOC 3\n- framework: ISO27001\n  type: ISO/IEC 27001 certificate\n  scope: Dropbox\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Dropbox ISO 27001\n- framework: ISO27018\n  type: ISO/IEC 27018:2019\n  scope: Dropbox\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO/IEC 27018:2019\n- framework: HIPAA\n  type: HIPAA compliance\n  scope: Dropbox Sign\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA COMPLIANCE\n- framework: PCI-DSS\n  type: PCI DSS compliance\n  scope: Dropbox\n  period: null\n\
  \  issuer: null\n  report_access: unstated\n  text: PCI DSS\n- framework: GDPR\n  type: GDPR compliance\n  scope: Dropbox\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: CCPA\n  type: CCPA compliance\n  scope: Dropbox\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA\n- framework: SOC2\n  type: third-party audit report\n  scope: unstated\n  period: annual\n  issuer: independent third-party auditors\n  report_access: on_request\n  text: We comply with standards and regulations like SOC 2. On an annual basis our independent third-party auditors\n    test our controls and provide their reports and opinions which we can provide to you upon request.\n  source: https://www.docsend.com/trust-center/\n"
source_yaml_url: https://artifacts.apis.io/docsend/compliance/docsend-compliance.yml
stated_fields:
- attestations
summary_line: 9 quoted statements, read from DocSend's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Enterprise
- Document Sharing
- Sales Enablement
- Analytics
- Virtual Data Room
- E-Signature
- MCP
- Dropbox
---
