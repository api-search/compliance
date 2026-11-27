---
api_specs:
- filename: zendesk-sell.postman_collection.json
  format: json
  label: Zendesk Sell (Sales CRM) API
  slug: sales-crm-api
  spec_type: Postman
  url: https://artifacts.apis.io/zendesk-sell/collections/zendesk-sell.postman_collection.json
- filename: zendesk-sell-contacts-api-openapi.yml
  format: yaml
  label: Zendesk Sell Contacts API
  slug: zendesk-sell-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zendesk-sell/openapi/zendesk-sell-contacts-api-openapi.yml
- filename: zendesk-sell-deals-api-openapi.yml
  format: yaml
  label: Zendesk Sell Deals API
  slug: zendesk-sell-deals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zendesk-sell/openapi/zendesk-sell-deals-api-openapi.yml
- filename: zendesk-sell-leads-api-openapi.yml
  format: yaml
  label: Zendesk Sell Leads API
  slug: zendesk-sell-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zendesk-sell/openapi/zendesk-sell-leads-api-openapi.yml
claim_count: 14
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: Security, Availability, Confidentiality
    text: We undergo routine audits to receive updated SOC 2 Type II reports, available upon request and under NDA.
    type: SOC 2 Type II audit report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: public
    scope: null
    text: Zendesk is ISO 27001:2022 certified.
    type: ISO 27001:2022 certification
  - framework: ISO27018
    issuer: null
    period: null
    report_access: public
    scope: null
    text: Zendesk is ISO 27018:2019 certified.
    type: ISO 27018:2019 certification
  - framework: ISO27701
    issuer: null
    period: null
    report_access: public
    scope: null
    text: Zendesk is ISO 27701:2019 certified.
    type: ISO 27701:2019 certification
  - framework: ISO27017
    issuer: null
    period: null
    report_access: public
    scope: null
    text: Zendesk is ISO 27017:2015 certified.
    type: ISO 27017:2015 certification
  - framework: ISO42001
    issuer: null
    period: null
    report_access: public
    scope: Zendesk AI practices
    text: ISO 42001 is the world’s first international standard for managing artificial intelligence.
    type: ISO 42001 AI management system certification
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: US Government agency subscribers can request access to the Zendesk FedRAMP Security Package by completing a Package Access Request Form
    type: FedRAMP authorized, Low Impact SaaS (LI-SaaS)
  - framework: CyberEssentials
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Cyber Essentials Plus is a UK government-backed certification
    type: Cyber Essentials Plus
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: public
    scope: Cloud security and AI governance
    text: We are among the first in the industry to achieve CSA STAR AI Level 2
    type: CSA STAR AI Levels 1 & 2
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We provide tools to help you handle payment data securely, including automatic redaction of credit card numbers.
    type: PCI-DSS tools for payment data handling
  - framework: HIPAA
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Zendesk enables healthcare organizations to safeguard PHI through our security configuration options and a Business Associate Agreement (BAA).
    type: HIPAA support with Business Associate Agreement
  - framework: other
    issuer: null
    period: null
    report_access: public
    scope: null
    text: Zendesk is HDS 1.1 certified.
    type: HDS 1.1 certification (France health data hosting)
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Zendesk is ISMAP authorized.
    type: ISMAP authorization (Japan)
  - framework: other
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Request the latest FSQS Certificate here .
    type: FSQS supplier qualification registration (UK financial services)
  trust_center:
    url: https://www.zendesk.com/trust-center/
frameworks:
- CSA-STAR
- CyberEssentials
- FedRAMP
- HIPAA
- ISO27001
- ISO27017
- ISO27018
- ISO27701
- ISO42001
- PCI-DSS
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Zendesk Sell
provenance_date: '2026-11-10'
provider_name: Zendesk Sell
provider_slug: zendesk-sell
slug: zendesk-sell-compliance
source_date: '2026-11-10'
source_filename: zendesk-sell-compliance.yml
source_heading: Compliance
source_page: https://www.zendesk.com/trust-center/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Zendesk Sell\naid: zendesk-sell\nurl: https://www.zendesk.com/trust-center/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.zendesk.com/trust-center/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II audit report\n  scope: Security, Availability, Confidentiality\n  period: null\n  issuer: null\n  report_access: nda\n  text: We undergo routine audits to receive updated SOC 2 Type II reports, available upon request and under NDA.\n- framework: ISO27001\n  type: ISO 27001:2022 certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: public\n  text: Zendesk is ISO 27001:2022\
  \ certified.\n- framework: ISO27018\n  type: ISO 27018:2019 certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: public\n  text: Zendesk is ISO 27018:2019 certified.\n- framework: ISO27701\n  type: ISO 27701:2019 certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: public\n  text: Zendesk is ISO 27701:2019 certified.\n- framework: ISO27017\n  type: ISO 27017:2015 certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: public\n  text: Zendesk is ISO 27017:2015 certified.\n- framework: ISO42001\n  type: ISO 42001 AI management system certification\n  scope: Zendesk AI practices\n  period: null\n  issuer: null\n  report_access: public\n  text: ISO 42001 is the world’s first international standard for managing artificial intelligence.\n- framework: FedRAMP\n  type: FedRAMP authorized, Low Impact SaaS (LI-SaaS)\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: US Government agency subscribers\
  \ can request access to the Zendesk FedRAMP Security Package by completing\n    a Package Access Request Form\n- framework: CyberEssentials\n  type: Cyber Essentials Plus\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Cyber Essentials Plus is a UK government-backed certification\n- framework: CSA-STAR\n  type: CSA STAR AI Levels 1 & 2\n  scope: Cloud security and AI governance\n  period: null\n  issuer: null\n  report_access: public\n  text: We are among the first in the industry to achieve CSA STAR AI Level 2\n- framework: PCI-DSS\n  type: PCI-DSS tools for payment data handling\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We provide tools to help you handle payment data securely, including automatic redaction of credit card\n    numbers.\n- framework: HIPAA\n  type: HIPAA support with Business Associate Agreement\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Zendesk enables\
  \ healthcare organizations to safeguard PHI through our security configuration options and\n    a Business Associate Agreement (BAA).\n- framework: other\n  type: HDS 1.1 certification (France health data hosting)\n  scope: null\n  period: null\n  issuer: null\n  report_access: public\n  text: Zendesk is HDS 1.1 certified.\n- framework: other\n  type: ISMAP authorization (Japan)\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Zendesk is ISMAP authorized.\n- framework: other\n  type: FSQS supplier qualification registration (UK financial services)\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Request the latest FSQS Certificate here .\n"
source_yaml_url: https://artifacts.apis.io/zendesk-sell/compliance/zendesk-sell-compliance.yml
stated_fields:
- attestations
summary_line: 14 quoted statements, read from Zendesk Sell's own page on 2026-11-10.
synthetic: false
tags:
- CRM
- Sales
- Sales Automation
- Leads
- Deals
- Pipelines
- Customer Experience
---
