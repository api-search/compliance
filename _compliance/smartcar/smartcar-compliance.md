---
api_specs:
- filename: smartcar-charging-api-openapi.yml
  format: yaml
  label: Smartcar Charging API
  slug: smartcar-charging-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartcar/openapi/smartcar-charging-api-openapi.yml
- filename: smartcar-connections-api-openapi.yml
  format: yaml
  label: Smartcar Connections API
  slug: smartcar-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartcar/openapi/smartcar-connections-api-openapi.yml
- filename: smartcar-navigation-api-openapi.yml
  format: yaml
  label: Smartcar Navigation API
  slug: smartcar-navigation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartcar/openapi/smartcar-navigation-api-openapi.yml
- filename: smartcar-security-api-openapi.yml
  format: yaml
  label: Smartcar Security API
  slug: smartcar-security-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartcar/openapi/smartcar-security-api-openapi.yml
- filename: smartcar-vehicle-data-api-openapi.yml
  format: yaml
  label: Smartcar Vehicle Data API
  slug: smartcar-vehicle-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartcar/openapi/smartcar-vehicle-data-api-openapi.yml
claim_count: 8
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: trust services principles
    text: SOC 2 Type 2 Service Organization Controls (SOC 2) (Type II) trust services principles
    type: SOC 2 Type 2 report
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: trust services principles
    text: SOC 2 Type 1 Service Organization Controls (SOC 2) (Type I) trust services principles
    type: SOC 2 Type 1 report
  - framework: SOC3
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Request SOC 3 Service Organization Controls (SOC 3)
    type: SOC 3 report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: information security management systems
    text: ISO/IEC 27001:2022 Information security, cybersecurity and privacy protection - Information security management systems - Requirements
    type: ISO/IEC 27001:2022 certification
  - framework: ISO27701
    issuer: null
    period: null
    report_access: unstated
    scope: privacy information management
    text: ISO/IEC 27701:2019 Security techniques - Extension to ISO/IEC 27001 and ISO/IEC 27002 for privacy information management - Requirements and guidelines
    type: ISO/IEC 27701:2019 certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: personal data of EU citizens
    text: Protect the personal data and privacy of EU citizens for transactions that occur within EU member states.
    type: regulatory compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA In progress. (Last updated August 2024)
    type: regulatory compliance
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: EU-U.S., UK Extension and Swiss-U.S. DPF
    text: EU-U.S. Data Privacy Framework (EU-U.S. DPF), the UK Extension to the EU-U.S. Data Privacy Framework (UK Extension to the EU-U.S. DPF), and the Swiss-U.S. Data Privacy Framework (Swiss-U.S. DPF)
    type: EU-U.S. Data Privacy Framework participation
  trust_center:
    url: https://trust.smartcar.com/
frameworks:
- CCPA
- GDPR
- ISO27001
- ISO27701
- SOC2
- SOC3
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Smartcar
provenance_date: '2026-11-10'
provider_name: Smartcar
provider_slug: smartcar
slug: smartcar-compliance
source_date: '2026-11-10'
source_filename: smartcar-compliance.yml
source_heading: Compliance
source_page: https://trust.smartcar.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Smartcar\naid: smartcar\nurl: https://trust.smartcar.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/smartcar-trust-center.yml\ntrust_center:\n  url: https://trust.smartcar.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: trust services principles\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Type 2 Service Organization Controls (SOC 2) (Type II) trust services principles\n- framework: SOC2\n  type: SOC 2 Type 1 report\n  scope: trust services principles\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Type 1\
  \ Service Organization Controls (SOC 2) (Type I) trust services principles\n- framework: SOC3\n  type: SOC 3 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Request SOC 3 Service Organization Controls (SOC 3)\n- framework: ISO27001\n  type: ISO/IEC 27001:2022 certification\n  scope: information security management systems\n  period: null\n  issuer: null\n  report_access: on_request\n  text: ISO/IEC 27001:2022 Information security, cybersecurity and privacy protection - Information security management\n    systems - Requirements\n- framework: ISO27701\n  type: ISO/IEC 27701:2019 certification\n  scope: privacy information management\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO/IEC 27701:2019 Security techniques - Extension to ISO/IEC 27001 and ISO/IEC 27002 for privacy information\n    management - Requirements and guidelines\n- framework: GDPR\n  type: regulatory compliance\n  scope: personal data of EU citizens\n \
  \ period: null\n  issuer: null\n  report_access: unstated\n  text: Protect the personal data and privacy of EU citizens for transactions that occur within EU member states.\n- framework: CCPA\n  type: regulatory compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA In progress. (Last updated August 2024)\n- framework: other\n  type: EU-U.S. Data Privacy Framework participation\n  scope: EU-U.S., UK Extension and Swiss-U.S. DPF\n  period: null\n  issuer: null\n  report_access: unstated\n  text: EU-U.S. Data Privacy Framework (EU-U.S. DPF), the UK Extension to the EU-U.S. Data Privacy Framework (UK\n    Extension to the EU-U.S. DPF), and the Swiss-U.S. Data Privacy Framework (Swiss-U.S. DPF)\n"
source_yaml_url: https://artifacts.apis.io/smartcar/compliance/smartcar-compliance.yml
stated_fields:
- attestations
summary_line: 8 quoted statements, read from Smartcar's own page on 2026-11-10.
synthetic: false
tags:
- Automotive
- Connected Vehicles
- IoT
- Mobility
- Fleet Management
- EV Management
- Telematics
- Electric Vehicles
---
