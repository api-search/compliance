---
api_specs:
- filename: binance.us-websocket-api-asyncapi.yml
  format: yaml
  label: Binance.US WebSocket API
  slug: websocket-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/binance.us/asyncapi/binance.us-websocket-api-asyncapi.yml
- filename: binance.us-websocket-streams-asyncapi.yml
  format: yaml
  label: Binance.US WebSocket Streams
  slug: websocket-streams
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/binance.us/asyncapi/binance.us-websocket-streams-asyncapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent auditors
    period: null
    report_access: unstated
    scope: security, confidentiality, processing integrity, availability, and privacy of customer data
    text: Binance.US completed a SOC 2 Type II audit and holds ISO 27001:2022 and ISO 27701:2019 certifications, all issued by independent auditors.
    type: SOC 2 Type II audit
  - framework: SOC2
    issuer: independent auditor
    period: null
    report_access: unstated
    scope: null
    text: Binance.US has completed SOC 2 Type I and SOC 2 Type II audits [ 5 ] .
    type: SOC 2 Type I audit
  - framework: ISO27001
    issuer: independent auditors
    period: null
    report_access: unstated
    scope: information security (27001:2022)
    text: The ISO certifications cover information security (27001:2022) and data privacy (27701:2019).
    type: certification
  - framework: ISO27701
    issuer: independent auditors
    period: null
    report_access: unstated
    scope: data privacy (27701:2019)
    text: The ISO certifications cover information security (27001:2022) and data privacy (27701:2019).
    type: certification
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: AML program
    source: https://www.binance.us/compliance
    text: in compliance with the Bank Secrecy Act (BSA)
    type: Bank Secrecy Act compliance
  trust_center:
    url: https://www.binance.us/trust
frameworks:
- ISO27001
- ISO27701
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Binance.US
provenance_date: '2026-11-09'
provider_name: Binance.US
provider_slug: binance.us
slug: binance.us-compliance
source_date: '2026-11-09'
source_filename: binance.us-compliance.yml
source_heading: Compliance
source_page: https://www.binance.us/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Binance.US\naid: binance.us\nurl: https://www.binance.us/trust\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/binance.us-trust-center.yml\n  sources:\n  - https://www.binance.us/compliance\n  - https://www.binance.us/trust\ntrust_center:\n  url: https://www.binance.us/trust\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II audit\n  scope: security, confidentiality, processing integrity, availability, and privacy of customer data\n  period: null\n  issuer: independent auditors\n  report_access: unstated\n  text: Binance.US completed a SOC 2 Type II audit and holds ISO 27001:2022 and ISO 27701:2019\
  \ certifications, all\n    issued by independent auditors.\n- framework: SOC2\n  type: SOC 2 Type I audit\n  scope: null\n  period: null\n  issuer: independent auditor\n  report_access: unstated\n  text: Binance.US has completed SOC 2 Type I and SOC 2 Type II audits [ 5 ] .\n- framework: ISO27001\n  type: certification\n  scope: information security (27001:2022)\n  period: null\n  issuer: independent auditors\n  report_access: unstated\n  text: The ISO certifications cover information security (27001:2022) and data privacy (27701:2019).\n- framework: ISO27701\n  type: certification\n  scope: data privacy (27701:2019)\n  period: null\n  issuer: independent auditors\n  report_access: unstated\n  text: The ISO certifications cover information security (27001:2022) and data privacy (27701:2019).\n- framework: other\n  type: Bank Secrecy Act compliance\n  scope: AML program\n  period: null\n  issuer: null\n  report_access: unstated\n  text: in compliance with the Bank Secrecy Act (BSA)\n  source:\
  \ https://www.binance.us/compliance\n"
source_yaml_url: https://artifacts.apis.io/binance.us/compliance/binance.us-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Binance.US's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cryptocurrency
- Digital Assets
- Exchange
- Trading
- Market Data
- Financial Services
- WebSocket
- Custody
- Staking
- Real-Time
---
