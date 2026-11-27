---
api_specs:
- filename: ubicquia-authcheck-api-openapi.yml
  format: yaml
  label: Ubicquia Auth Check API
  slug: ubicquia-authcheck-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ubicquia/openapi/ubicquia-authcheck-api-openapi.yml
- filename: ubicquia-customer-detail-api-openapi.yml
  format: yaml
  label: Ubicquia Customer Detail API
  slug: ubicquia-customer-detail-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ubicquia/openapi/ubicquia-customer-detail-api-openapi.yml
- filename: ubicquia-fulfillment-details-api-openapi.yml
  format: yaml
  label: Ubicquia Fulfillment Details API
  slug: ubicquia-fulfillment-details-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ubicquia/openapi/ubicquia-fulfillment-details-api-openapi.yml
- filename: ubicquia-iccid-master-api-openapi.yml
  format: yaml
  label: Ubicquia ICCID Master API
  slug: ubicquia-iccid-master-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ubicquia/openapi/ubicquia-iccid-master-api-openapi.yml
- filename: ubicquia-sales-order-api-openapi.yml
  format: yaml
  label: Ubicquia Sales Order API
  slug: ubicquia-sales-order-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ubicquia/openapi/ubicquia-sales-order-api-openapi.yml
- filename: ubicquia-serial-number-api-openapi.yml
  format: yaml
  label: Ubicquia Serial Number API
  slug: ubicquia-serial-number-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ubicquia/openapi/ubicquia-serial-number-api-openapi.yml
- filename: ubicquia-transformer-details-api-openapi.yml
  format: yaml
  label: Ubicquia Transformer Details API
  slug: ubicquia-transformer-details-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ubicquia/openapi/ubicquia-transformer-details-api-openapi.yml
- filename: ubicquia-user-api-openapi.yml
  format: yaml
  label: Ubicquia User API
  slug: ubicquia-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ubicquia/openapi/ubicquia-user-api-openapi.yml
claim_count: 7
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Full Information Security Management System (ISMS)
    text: ISO 27001 certification (audited)
    type: ISO 27001 / 27002 certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Operational effectiveness of security controls
    text: SOC 2 Type 2 attestation (audited)
    type: SOC 2 Type 2 attestation
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Controlled unclassified information
    text: aligned to NIST 800-171, NIST CSF, PCI SAQ-C, CMMC level 1, and CTIA IoT device certification standards
    type: NIST 800-171 alignment
  - framework: NIST-CSF
    issuer: null
    period: null
    report_access: unstated
    scope: Cybersecurity risk management across critical infrastructure sectors
    text: NIST 800-171 & NIST CSF Aligned to the federal frameworks used for controlled unclassified information (CUI)
    type: NIST CSF alignment
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: UbiCell device, CTIA IoT security level 1 v1.2.3
    text: UbiCell certified under CTIA IoT security level 1 v1.2.3.
    type: CTIA IoT device certification
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CMMC level 1 performed through SPRS.
    type: CMMC level 1
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: Cardholder data segments where applicable
    text: PCI SAQ-C compliant for cardholder data segments where applicable.
    type: PCI SAQ-C
  trust_center:
    url: https://www.ubicquia.com/insights/the-ubicquia-security-program
frameworks:
- ISO27001
- NIST-CSF
- PCI-DSS
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Ubicquia
provenance_date: '2026-11-10'
provider_name: Ubicquia
provider_slug: ubicquia
slug: ubicquia-compliance
source_date: '2026-11-10'
source_filename: ubicquia-compliance.yml
source_heading: Compliance
source_page: https://www.ubicquia.com/insights/the-ubicquia-security-program
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Ubicquia\naid: ubicquia\nurl: https://www.ubicquia.com/insights/the-ubicquia-security-program\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.ubicquia.com/insights/the-ubicquia-security-program\nattestations:\n- framework: ISO27001\n  type: ISO 27001 / 27002 certification\n  scope: Full Information Security Management System (ISMS)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001 certification (audited)\n- framework: SOC2\n  type: SOC 2 Type 2 attestation\n  scope: Operational effectiveness of security controls\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: SOC 2 Type 2 attestation (audited)\n- framework: other\n  type: NIST 800-171 alignment\n  scope: Controlled unclassified information\n  period: null\n  issuer: null\n  report_access: unstated\n  text: aligned to NIST 800-171, NIST CSF, PCI SAQ-C, CMMC level 1, and CTIA IoT device certification standards\n- framework: NIST-CSF\n  type: NIST CSF alignment\n  scope: Cybersecurity risk management across critical infrastructure sectors\n  period: null\n  issuer: null\n  report_access: unstated\n  text: NIST 800-171 & NIST CSF Aligned to the federal frameworks used for controlled unclassified information (CUI)\n- framework: other\n  type: CTIA IoT device certification\n  scope: UbiCell device, CTIA IoT security level 1 v1.2.3\n  period: null\n  issuer: null\n  report_access: unstated\n  text: UbiCell certified under CTIA IoT security level 1 v1.2.3.\n- framework: other\n  type: CMMC level 1\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CMMC level\
  \ 1 performed through SPRS.\n- framework: PCI-DSS\n  type: PCI SAQ-C\n  scope: Cardholder data segments where applicable\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI SAQ-C compliant for cardholder data segments where applicable.\n"
source_yaml_url: https://artifacts.apis.io/ubicquia/compliance/ubicquia-compliance.yml
stated_fields:
- attestations
summary_line: 7 quoted statements, read from Ubicquia's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Smart Cities
- IoT
- Energy
- Utilities
- Electric Grid
- Streetlights
- Public Safety
- Infrastructure
- Sensors
- Edge AI
- Transformer Monitoring
---
