---
claim_count: 10
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: 31 March 2024 - 31 March 2025
    report_access: unstated
    scope: null
    text: 'Valid8 Financial SOC 2 Type II report: 31 March 2024 - 31 March 2025'
    type: SOC 2 Type II report
  - framework: SOC3
    issuer: null
    period: 1 April 2024 - 31 March 2025
    report_access: unstated
    scope: null
    text: 'Valid8 Financial SOC 3 Type II report: 1 April 2024 - 31 March 2025'
    type: SOC 3 Type II report
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Valid8 Financial Inc HIPAA Report
    type: HIPAA Compliance report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: The Company is fully HIPAA, SOC 2, GDPR, CCPA, and TX-RAMP compliant
    type: compliance statement
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: The Company is fully HIPAA, SOC 2, GDPR, CCPA, and TX-RAMP compliant
    type: compliance statement
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: The Company is fully HIPAA, SOC 2, GDPR, CCPA, and TX-RAMP compliant
    type: TX-RAMP compliance statement
  - framework: SOC2
    issuer: AICPA
    period: null
    report_access: on_request
    scope: null
    source: https://www.valid8financial.com/security-compliance
    text: Since 2021, Valid8 has achieved the AICPA SOC 2 Type II attestation annually.
    type: SOC 2 Type II attestation
  - framework: HIPAA
    issuer: AICPA
    period: null
    report_access: unstated
    scope: Clients in the healthcare sector
    source: https://www.valid8financial.com/security-compliance
    text: Our HIPAA compliant service, in accordance with AT-C 315 as defined by the AICPA, addresses the needs of clients in the healthcare sector.
    type: HIPAA compliant service
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: State agencies, institutions of higher education, and public community colleges in the State of Texas
    source: https://www.valid8financial.com/security-compliance
    text: Valid8 supports TX-RAMP requirements which apply to state agencies, institutions of higher education, and public community colleges in the State of Texas.
    type: TX-RAMP support
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://www.valid8financial.com/security-compliance
    text: Valid8 is designed to support applicable GDPR requirements.
    type: Designed to support applicable GDPR requirements
  trust_center:
    url: https://trust.valid8financial.com/
frameworks:
- CCPA
- GDPR
- HIPAA
- SOC2
- SOC3
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: VALID8 Financial
provenance_date: '2026-11-10'
provider_name: VALID8 Financial
provider_slug: valid8-financial
slug: valid8-financial-compliance
source_date: '2026-11-10'
source_filename: valid8-financial-compliance.yml
source_heading: Compliance
source_page: https://trust.valid8financial.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: VALID8 Financial\naid: valid8-financial\nurl: https://trust.valid8financial.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/valid8-financial-trust-center.yml\n  sources:\n  - https://trust.valid8financial.com/\n  - https://www.valid8financial.com/security-compliance\ntrust_center:\n  url: https://trust.valid8financial.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: null\n  period: 31 March 2024 - 31 March 2025\n  issuer: null\n  report_access: unstated\n  text: 'Valid8 Financial SOC 2 Type II report: 31 March 2024 - 31 March 2025'\n- framework: SOC3\n  type: SOC\
  \ 3 Type II report\n  scope: null\n  period: 1 April 2024 - 31 March 2025\n  issuer: null\n  report_access: unstated\n  text: 'Valid8 Financial SOC 3 Type II report: 1 April 2024 - 31 March 2025'\n- framework: HIPAA\n  type: HIPAA Compliance report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Valid8 Financial Inc HIPAA Report\n- framework: GDPR\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: The Company is fully HIPAA, SOC 2, GDPR, CCPA, and TX-RAMP compliant\n- framework: CCPA\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: The Company is fully HIPAA, SOC 2, GDPR, CCPA, and TX-RAMP compliant\n- framework: other\n  type: TX-RAMP compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: The Company is fully HIPAA, SOC 2, GDPR, CCPA, and TX-RAMP compliant\n- framework: SOC2\n \
  \ type: SOC 2 Type II attestation\n  scope: null\n  period: null\n  issuer: AICPA\n  report_access: on_request\n  text: Since 2021, Valid8 has achieved the AICPA SOC 2 Type II attestation annually.\n  source: https://www.valid8financial.com/security-compliance\n- framework: HIPAA\n  type: HIPAA compliant service\n  scope: Clients in the healthcare sector\n  period: null\n  issuer: AICPA\n  report_access: unstated\n  text: Our HIPAA compliant service, in accordance with AT-C 315 as defined by the AICPA, addresses the needs of\n    clients in the healthcare sector.\n  source: https://www.valid8financial.com/security-compliance\n- framework: other\n  type: TX-RAMP support\n  scope: State agencies, institutions of higher education, and public community colleges in the State of Texas\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Valid8 supports TX-RAMP requirements which apply to state agencies, institutions of higher education, and\n    public community colleges in the\
  \ State of Texas.\n  source: https://www.valid8financial.com/security-compliance\n- framework: GDPR\n  type: Designed to support applicable GDPR requirements\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Valid8 is designed to support applicable GDPR requirements.\n  source: https://www.valid8financial.com/security-compliance\n"
source_yaml_url: https://artifacts.apis.io/valid8-financial/compliance/valid8-financial-compliance.yml
stated_fields:
- attestations
summary_line: 10 quoted statements, read from VALID8 Financial's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Financial Services
- Forensic Accounting
- Fraud Investigation
- Legal Tech
- Artificial Intelligence
- Evidence Management
---
