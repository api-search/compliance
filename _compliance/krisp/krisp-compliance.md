---
api_specs:
- filename: krisp-sdk-distribution-api-openapi.yml
  format: yaml
  label: Krisp SDK Distribution API
  slug: krisp-sdk-distribution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/krisp/openapi/krisp-sdk-distribution-api-openapi.yml
- filename: krisp-voice-translation-api-openapi.yml
  format: yaml
  label: Krisp Voice Translation API
  slug: krisp-voice-translation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/krisp/openapi/krisp-voice-translation-api-openapi.yml
claim_count: 7
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent auditor
    period: full observation period every year
    report_access: nda
    scope: Krisp controls
    text: SOC 2 Type II An independent auditor tests our controls over a full observation period every year. Download the report from the Trust Center.
    type: SOC 2 Type II audit
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: how cardholder data customers may say on calls is protected
    text: Our PCI DSS certification covers how that data is protected.
    type: PCI DSS certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Enterprise plan teams of 100 or more seats
    text: Business Associate Agreements are available on the Enterprise plan for teams of 100 or more seats.
    type: HIPAA safeguards and BAAs
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: personal data transfers out of the EEA
    text: Transfers of personal data out of the EEA rely on Standard Contractual Clauses.
    type: GDPR data subject rights and SCCs
  - framework: SOC2
    issuer: Grant Thornton
    period: null
    report_access: on_request
    scope: null
    source: https://trust.krisp.ai/
    text: Krisp has successfully completed its SOC 2 Type II audit, conducted by Grant Thornton, with an unqualified (clean) opinion and no material control deficiencies.
    type: SOC 2 Type II
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: on_request
    scope: null
    source: https://trust.krisp.ai/
    text: PCI-DSS V4.0.1 AOC
    type: PCI-DSS 4.0 AOC
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.krisp.ai/
    text: Compliance SOC 2 Type II PCI-DSS 4.0 HIPAA GDPR
    type: GDPR compliance
  trust_center:
    url: https://krisp.ai/security-for-ai-meeting-assistant/
frameworks:
- GDPR
- HIPAA
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Krisp
provenance_date: '2026-11-09'
provider_name: Krisp
provider_slug: krisp
slug: krisp-compliance
source_date: '2026-11-09'
source_filename: krisp-compliance.yml
source_heading: Compliance
source_page: https://krisp.ai/security-for-ai-meeting-assistant/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Krisp\naid: krisp\nurl: https://krisp.ai/security-for-ai-meeting-assistant/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://krisp.ai/security-for-ai-meeting-assistant/\n  - https://trust.krisp.ai/\ntrust_center:\n  url: https://krisp.ai/security-for-ai-meeting-assistant/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II audit\n  scope: Krisp controls\n  period: full observation period every year\n  issuer: independent auditor\n  report_access: nda\n  text: SOC 2 Type II An independent auditor tests our controls over a full observation period every year. Download\n    the report from the Trust Center.\n\
  - framework: PCI-DSS\n  type: PCI DSS certification\n  scope: how cardholder data customers may say on calls is protected\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our PCI DSS certification covers how that data is protected.\n- framework: HIPAA\n  type: HIPAA safeguards and BAAs\n  scope: Enterprise plan teams of 100 or more seats\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Business Associate Agreements are available on the Enterprise plan for teams of 100 or more seats.\n- framework: GDPR\n  type: GDPR data subject rights and SCCs\n  scope: personal data transfers out of the EEA\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Transfers of personal data out of the EEA rely on Standard Contractual Clauses.\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: null\n  issuer: Grant Thornton\n  report_access: on_request\n  text: Krisp has successfully completed its SOC 2 Type II audit, conducted by Grant Thornton,\
  \ with an unqualified\n    (clean) opinion and no material control deficiencies.\n  source: https://trust.krisp.ai/\n- framework: PCI-DSS\n  type: PCI-DSS 4.0 AOC\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: PCI-DSS V4.0.1 AOC\n  source: https://trust.krisp.ai/\n- framework: GDPR\n  type: GDPR compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliance SOC 2 Type II PCI-DSS 4.0 HIPAA GDPR\n  source: https://trust.krisp.ai/\n"
source_yaml_url: https://artifacts.apis.io/krisp/compliance/krisp-compliance.yml
stated_fields:
- attestations
summary_line: 7 quoted statements, read from Krisp's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Voice AI
- Speech
- Audio
- Noise Cancellation
- Speech Translation
- Real-Time Communication
- WebRTC
- Conversational AI
- SDK
- Machine Learning
- Real-Time
---
