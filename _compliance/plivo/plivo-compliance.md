---
api_specs:
- filename: plivo-asyncapi.yml
  format: yaml
  label: Plivo Audio Stream API
  slug: plivo-audio-stream-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/plivo/asyncapi/plivo-asyncapi.yml
- filename: plivo-account-api-openapi.yml
  format: yaml
  label: Plivo Account API
  slug: plivo-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plivo/openapi/plivo-account-api-openapi.yml
- filename: plivo-message-api-openapi.yml
  format: yaml
  label: Plivo Message API
  slug: plivo-message-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plivo/openapi/plivo-message-api-openapi.yml
claim_count: 6
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent auditor
    period: null
    report_access: unstated
    scope: null
    text: Plivo is SOC 2 certified.
    type: SOC 2 certified
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Plivo systems are compliant with the data protection principles of the European Union's General Data Protection Regulation.
    type: compliant with data protection principles
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: customers who handle protected health information (PHI)
    text: Plivo is willing to sign a Business Associate Agreement for customers who handle protected health information (PHI).
    type: willing to sign Business Associate Agreement
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Plivo is certified compliant with PCI DSS Level 1.
    type: PCI DSS Level 1 compliant
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Plivo has completed the CSA STAR Level 1 self-assessment, demonstrating transparency and adherence to cloud security controls.
    type: CSA STAR Level 1 self-assessment
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Plivo participates in the EU–U.S. Data Privacy Framework (DPF).
    type: EU-U.S. Data Privacy Framework participant
  trust_center:
    url: https://www.plivo.com/security/
frameworks:
- CSA-STAR
- GDPR
- HIPAA
- PCI-DSS
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Plivo
provenance_date: '2026-11-10'
provider_name: Plivo
provider_slug: plivo
slug: plivo-compliance
source_date: '2026-11-10'
source_filename: plivo-compliance.yml
source_heading: Compliance
source_page: https://www.plivo.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Plivo\naid: plivo\nurl: https://www.plivo.com/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/plivo-trust-center.yml\ntrust_center:\n  url: https://www.plivo.com/security/\nattestations:\n- framework: SOC2\n  type: SOC 2 certified\n  scope: null\n  period: null\n  issuer: independent auditor\n  report_access: unstated\n  text: Plivo is SOC 2 certified.\n- framework: GDPR\n  type: compliant with data protection principles\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Plivo systems are compliant with the data protection principles of the European Union's\
  \ General Data Protection\n    Regulation.\n- framework: HIPAA\n  type: willing to sign Business Associate Agreement\n  scope: customers who handle protected health information (PHI)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Plivo is willing to sign a Business Associate Agreement for customers who handle protected health information\n    (PHI).\n- framework: PCI-DSS\n  type: PCI DSS Level 1 compliant\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Plivo is certified compliant with PCI DSS Level 1.\n- framework: CSA-STAR\n  type: CSA STAR Level 1 self-assessment\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Plivo has completed the CSA STAR Level 1 self-assessment, demonstrating transparency and adherence to cloud\n    security controls.\n- framework: other\n  type: EU-U.S. Data Privacy Framework participant\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Plivo\
  \ participates in the EU–U.S. Data Privacy Framework (DPF).\n"
source_yaml_url: https://artifacts.apis.io/plivo/compliance/plivo-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from Plivo's own page on 2026-11-10.
synthetic: false
tags:
- Communications
- CPaaS
- Voice
- SMS
- Messaging
- WhatsApp
- SIP Trunking
- Verify
- Telecommunications
- Real-Time
---
