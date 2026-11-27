---
api_specs:
- filename: harmony-tickets-api-openapi.yml
  format: yaml
  label: Harmony Tickets API
  slug: harmony-tickets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/harmony/openapi/harmony-tickets-api-openapi.yml
claim_count: 8
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: examined over a period rather than at a point in time
    report_access: nda
    scope: security, availability and confidentiality (AICPA Trust Services Criteria)
    text: SOC 2 Type II AICPA Trust Services Criteria for security, availability and confidentiality, examined over a period rather than at a point in time.
    type: Type II
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: information security management system
    text: ISO 27001 certificate and Statement of Applicability
    type: certificate
  - framework: CyberEssentials
    issuer: null
    period: null
    report_access: on_request
    scope: firewalls, secure configuration, user access control, malware protection and security update management
    text: Cyber Essentials certificate
    type: certificate
  - framework: NIST-800-53
    issuer: null
    period: null
    report_access: unstated
    scope: security and privacy controls, used as reference for control set
    text: NIST SP 800-53 The US federal catalogue of security and privacy controls, used here as the reference our control set is mapped against.
    type: mapping reference
  - framework: GDPR
    issuer: null
    period: null
    report_access: nda
    scope: processor for customer data
    text: We act as a processor for customer data; a DPA is available under NDA.
    type: processor DPA
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: Harmony does not store cardholder data; payments handled by payment processor
    text: Harmony does not store cardholder data; payments are handled by our payment processor.
    type: framework
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: NIST AI Risk Management Framework
    text: 'NIST AI RMF The AI Risk Management Framework: govern, map, measure and manage the risks specific to an AI system.'
    type: framework
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: EU AI Act
    text: EU AI Act The European regulation on AI, which classifies systems by risk and sets obligations for transparency and human oversight.
    type: framework
  trust_center:
    url: https://trust.harmony.io/
frameworks:
- CyberEssentials
- GDPR
- ISO27001
- NIST-800-53
- PCI-DSS
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Harmony
provenance_date: '2026-11-09'
provider_name: Harmony
provider_slug: harmony
slug: harmony-compliance
source_date: '2026-11-09'
source_filename: harmony-compliance.yml
source_heading: Compliance
source_page: https://trust.harmony.io/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Harmony\naid: harmony\nurl: https://trust.harmony.io/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.harmony.io/\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: security, availability and confidentiality (AICPA Trust Services Criteria)\n  period: examined over a period rather than at a point in time\n  issuer: null\n  report_access: nda\n  text: SOC 2 Type II AICPA Trust Services Criteria for security, availability and confidentiality, examined over\n    a period rather than at a point in time.\n- framework: ISO27001\n  type: certificate\n  scope: information security management system\n\
  \  period: null\n  issuer: null\n  report_access: on_request\n  text: ISO 27001 certificate and Statement of Applicability\n- framework: CyberEssentials\n  type: certificate\n  scope: firewalls, secure configuration, user access control, malware protection and security update management\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Cyber Essentials certificate\n- framework: NIST-800-53\n  type: mapping reference\n  scope: security and privacy controls, used as reference for control set\n  period: null\n  issuer: null\n  report_access: unstated\n  text: NIST SP 800-53 The US federal catalogue of security and privacy controls, used here as the reference our\n    control set is mapped against.\n- framework: GDPR\n  type: processor DPA\n  scope: processor for customer data\n  period: null\n  issuer: null\n  report_access: nda\n  text: We act as a processor for customer data; a DPA is available under NDA.\n- framework: PCI-DSS\n  type: framework\n  scope: Harmony does\
  \ not store cardholder data; payments handled by payment processor\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Harmony does not store cardholder data; payments are handled by our payment processor.\n- framework: other\n  type: framework\n  scope: NIST AI Risk Management Framework\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'NIST AI RMF The AI Risk Management Framework: govern, map, measure and manage the risks specific to an\n    AI system.'\n- framework: other\n  type: framework\n  scope: EU AI Act\n  period: null\n  issuer: null\n  report_access: unstated\n  text: EU AI Act The European regulation on AI, which classifies systems by risk and sets obligations for transparency\n    and human oversight.\n"
source_yaml_url: https://artifacts.apis.io/harmony/compliance/harmony-compliance.yml
stated_fields:
- attestations
summary_line: 8 quoted statements, read from Harmony's own page on 2026-11-09.
synthetic: false
tags:
- ITSM
- Service Desk
- Ticketing
- Enterprise Service Management
- AI Agents
- IT Automation
- Help Desk
- Identity
- Company
---
