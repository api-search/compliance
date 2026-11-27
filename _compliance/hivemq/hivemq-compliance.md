---
api_specs:
- filename: hivemq-asyncapi.yml
  format: yaml
  label: HiveMQ MQTT over WebSocket
  slug: mqtt-websocket
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/hivemq/asyncapi/hivemq-asyncapi.yml
- filename: hivemq-data-hub-api-openapi.yml
  format: yaml
  label: HiveMQ Data Hub API
  slug: hivemq-data-hub-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hivemq/openapi/hivemq-data-hub-api-openapi.yml
- filename: hivemq-management-api-openapi.yml
  format: yaml
  label: HiveMQ Management API
  slug: hivemq-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hivemq/openapi/hivemq-management-api-openapi.yml
- filename: hivemq-mqtt-api-openapi.yml
  format: yaml
  label: HiveMQ Mqtt API
  slug: hivemq-mqtt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hivemq/openapi/hivemq-mqtt-api-openapi.yml
claim_count: 6
description: ''
doc:
  attestations:
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: The collection and processing of personal data is made in accordance with relevant data protection regulations and safeguards for confidential information.
    type: data protection regulation
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: 'The globally-recognized ISO/IEC 27001: 2022 certification signifies HiveMQ meets the high standard of excellence for information security management systems.'
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Being SOC 2 Type 1 certified ensures that our systems and controls are designed to meet rigorous security, availability, processing integrity, confidentiality, and privacy standards.
    type: Type I
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: 'five trust criteria: security, availability, processing integrity, confidentiality, and privacy'
    text: 'HiveMQ is now SOC 2 Type II compliant across all five trust criteria: security, availability, processing integrity, confidentiality, and privacy.'
    type: Type II
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: unstated
    scope: HiveMQ Cloud
    text: HiveMQ Cloud is listed on the Security, Trust, Assurance, and Risk (STAR) Registry which documents the security and privacy controls provided by cloud computing offerings.
    type: STAR Registry listing
  - framework: TISAX
    issuer: null
    period: null
    report_access: unstated
    scope: automotive industry
    text: HiveMQ is now TiSAX-compliant (Trusted Information Security Assessment Exchange), demonstrating our commitment to top-tier security standards for the automotive industry.
    type: compliance
  trust_center:
    url: https://www.hivemq.com/solutions/technology/hivemq-security/
frameworks:
- CSA-STAR
- GDPR
- ISO27001
- SOC2
- TISAX
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: HiveMQ
provenance_date: '2026-11-09'
provider_name: HiveMQ
provider_slug: hivemq
slug: hivemq-compliance
source_date: '2026-11-09'
source_filename: hivemq-compliance.yml
source_heading: Compliance
source_page: https://www.hivemq.com/solutions/technology/hivemq-security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: HiveMQ\naid: hivemq\nurl: https://www.hivemq.com/solutions/technology/hivemq-security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.hivemq.com/solutions/technology/hivemq-security/\nattestations:\n- framework: GDPR\n  type: data protection regulation\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: The collection and processing of personal data is made in accordance with relevant data protection regulations\n    and safeguards for confidential information.\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: 'The globally-recognized ISO/IEC 27001: 2022 certification signifies HiveMQ meets the high standard of excellence\n    for information security management systems.'\n- framework: SOC2\n  type: Type I\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Being SOC 2 Type 1 certified ensures that our systems and controls are designed to meet rigorous security,\n    availability, processing integrity, confidentiality, and privacy standards.\n- framework: SOC2\n  type: Type II\n  scope: 'five trust criteria: security, availability, processing integrity, confidentiality, and privacy'\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'HiveMQ is now SOC 2 Type II compliant across all five trust criteria: security, availability, processing\n    integrity, confidentiality, and privacy.'\n- framework: CSA-STAR\n  type: STAR Registry listing\n  scope: HiveMQ Cloud\n  period: null\n  issuer: null\n  report_access: unstated\n  text:\
  \ HiveMQ Cloud is listed on the Security, Trust, Assurance, and Risk (STAR) Registry which documents the security\n    and privacy controls provided by cloud computing offerings.\n- framework: TISAX\n  type: compliance\n  scope: automotive industry\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HiveMQ is now TiSAX-compliant (Trusted Information Security Assessment Exchange), demonstrating our commitment\n    to top-tier security standards for the automotive industry.\n"
source_yaml_url: https://artifacts.apis.io/hivemq/compliance/hivemq-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from HiveMQ's own page on 2026-11-09.
synthetic: false
tags:
- MQTT
- IoT
- Messaging
- Message Broker
- Pub/Sub
- WebSocket
- Real-Time
---
