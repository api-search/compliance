---
api_specs:
- filename: picarro-sam-foup-asyncapi.yml
  format: yaml
  label: Picarro Edge — SAM FOUP gRPC API
  slug: picarro-edge-sam-foup-grpc-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/picarro/asyncapi/picarro-sam-foup-asyncapi.yml
claim_count: 12
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001:2022 Certificate
    type: null
  - framework: ISO27017
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27017:2015 Certificate
    type: null
  - framework: ISO27018
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27018:2019 Certificate
    type: null
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II
    type: Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: null
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA COMPLIANT
    type: null
  - framework: ISO9001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO/IEC 9001:2015
    type: null
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOX IT General Controls
    type: SOX IT General Controls
  - framework: ISO27001
    issuer: accredited provider of cybersecurity compliance programs
    period: null
    report_access: unstated
    scope: Information Security Management Systems
    source: https://www.picarro.com/ensuring_data_security_and_compliance
    text: Picarro has achieved certification for ISO 27001:2022 (Information Security Management Systems)
    type: certification
  - framework: ISO27017
    issuer: accredited provider of cybersecurity compliance programs
    period: null
    report_access: unstated
    scope: Cloud Security
    source: https://www.picarro.com/ensuring_data_security_and_compliance
    text: ISO 27017 (Cloud Security)
    type: certification
  - framework: ISO27018
    issuer: accredited provider of cybersecurity compliance programs
    period: null
    report_access: unstated
    scope: Data Privacy
    source: https://www.picarro.com/ensuring_data_security_and_compliance
    text: ISO 27018 (Data Privacy)
    type: certification
  - framework: SOC2
    issuer: accredited provider of cybersecurity compliance programs
    period: null
    report_access: unstated
    scope: security, availability, processing integrity, confidentiality, and privacy
    source: https://www.picarro.com/ensuring_data_security_and_compliance
    text: has successfully completed its Service Organization Controls 2 (SOC 2) Type 2 examination
    type: Type 2 examination
  trust_center:
    url: https://trust.picarro.com/
frameworks:
- CCPA
- GDPR
- ISO27001
- ISO27017
- ISO27018
- ISO9001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Picarro
provenance_date: '2026-11-10'
provider_name: Picarro
provider_slug: picarro
slug: picarro-compliance
source_date: '2026-11-10'
source_filename: picarro-compliance.yml
source_heading: Compliance
source_page: https://trust.picarro.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Picarro\naid: picarro\nurl: https://trust.picarro.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://trust.picarro.com/\n  - https://www.picarro.com/ensuring_data_security_and_compliance\ntrust_center:\n  url: https://trust.picarro.com/\nattestations:\n- framework: ISO27001\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022 Certificate\n- framework: ISO27017\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27017:2015 Certificate\n- framework: ISO27018\n  type: null\n  scope: null\n  period: null\n\
  \  issuer: null\n  report_access: unstated\n  text: ISO 27018:2019 Certificate\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: CCPA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA COMPLIANT\n- framework: ISO9001\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO/IEC 9001:2015\n- framework: other\n  type: SOX IT General Controls\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOX IT General Controls\n- framework: ISO27001\n  type: certification\n  scope: Information Security Management Systems\n  period: null\n  issuer: accredited provider of cybersecurity compliance programs\n  report_access: unstated\n  text: Picarro has achieved certification\
  \ for ISO 27001:2022 (Information Security Management Systems)\n  source: https://www.picarro.com/ensuring_data_security_and_compliance\n- framework: ISO27017\n  type: certification\n  scope: Cloud Security\n  period: null\n  issuer: accredited provider of cybersecurity compliance programs\n  report_access: unstated\n  text: ISO 27017 (Cloud Security)\n  source: https://www.picarro.com/ensuring_data_security_and_compliance\n- framework: ISO27018\n  type: certification\n  scope: Data Privacy\n  period: null\n  issuer: accredited provider of cybersecurity compliance programs\n  report_access: unstated\n  text: ISO 27018 (Data Privacy)\n  source: https://www.picarro.com/ensuring_data_security_and_compliance\n- framework: SOC2\n  type: Type 2 examination\n  scope: security, availability, processing integrity, confidentiality, and privacy\n  period: null\n  issuer: accredited provider of cybersecurity compliance programs\n  report_access: unstated\n  text: has successfully completed its Service\
  \ Organization Controls 2 (SOC 2) Type 2 examination\n  source: https://www.picarro.com/ensuring_data_security_and_compliance\n"
source_yaml_url: https://artifacts.apis.io/picarro/compliance/picarro-compliance.yml
stated_fields:
- attestations
summary_line: 12 quoted statements, read from Picarro's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Gas Detection
- Environmental Monitoring
- Emissions
- Methane
- Greenhouse Gas
- Scientific Instruments
- Semiconductors
- Industrial IoT
- Sensors
- Analytics
- gRPC
---
