---
api_specs:
- filename: oneuptime-projects-api-openapi.yml
  format: yaml
  label: OneUptime Projects API
  slug: oneuptime-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oneuptime/openapi/oneuptime-projects-api-openapi.yml
claim_count: 13
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: renewed annually
    report_access: nda
    scope: security, availability, and confidentiality controls
    text: SOC 2 Type II Security, availability, and confidentiality controls. Renewed annually, report under NDA.
    type: SOC 2 Type II
  - framework: SOC3
    issuer: null
    period: null
    report_access: public
    scope: general-use summary of the same examination
    text: SOC 3 report, the general-use summary of the same examination. Shareable without an NDA.
    type: SOC 3
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: OneUptime Cloud and the organisation that builds the platform
    text: Certificate of registration, including scope, on request.
    type: ISO/IEC 27001 certification
  - framework: ISO27017
    issuer: null
    period: null
    report_access: on_request
    scope: cloud-services security controls extending ISO 27001
    text: ISO/IEC 27017 cloud-services security controls, audited alongside ISO 27001.
    type: ISO/IEC 27017 certification
  - framework: ISO27018
    issuer: null
    period: null
    report_access: on_request
    scope: protection of personally identifiable information in public clouds
    text: ISO/IEC 27018 controls for protecting personally identifiable information in public clouds.
    type: ISO/IEC 27018 certification
  - framework: ISO9001
    issuer: null
    period: null
    report_access: on_request
    scope: quality management system covering how the service is built and operated
    text: ISO 9001 certified quality management system.
    type: ISO 9001 certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Data Processing Addendum, Standard Contractual Clauses, EU data residency available
    text: GDPR compliant as a processor, with a Data Processing Addendum, Standard Contractual Clauses, and EU data residency available.
    type: GDPR compliance as processor
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: consumer privacy rights honoured for all customers
    text: CCPA and CPRA compliant, with consumer privacy rights honoured for all customers.
    type: CCPA / CPRA compliance
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Business Associate Agreement available for covered entities
    text: HIPAA compliant as a business associate, with a Business Associate Agreement available for covered entities.
    type: HIPAA compliance as business associate
  - framework: PCI-DSS
    issuer: Qualified Security Assessor
    period: null
    report_access: on_request
    scope: cardholder data handled by payment providers; OneUptime does not store primary account numbers
    text: PCI DSS compliance validated by a Qualified Security Assessor, with a signed Attestation of Compliance.
    type: PCI DSS attestation
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: public
    scope: Cloud Controls Matrix, with CAIQ published to the STAR registry
    text: CSA STAR Level 2 certified against the Cloud Controls Matrix, with our CAIQ published to the STAR registry.
    type: CSA STAR Level 2 certification
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: OneUptime Cloud
    text: FedRAMP Moderate authorization is in progress. Not yet authorized, and no date is promised.
    type: FedRAMP Moderate authorization
  - framework: other
    issuer: null
    period: at least annually
    report_access: nda
    scope: independent third-party penetration testing
    text: Independent third-party penetration testing at least annually. Summary reports are available under NDA to qualifying customers.
    type: Penetration testing
  trust_center:
    url: https://oneuptime.com/trust
frameworks:
- CCPA
- CSA-STAR
- FedRAMP
- GDPR
- HIPAA
- ISO27001
- ISO27017
- ISO27018
- ISO9001
- PCI-DSS
- SOC2
- SOC3
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: OneUptime
provenance_date: '2026-11-10'
provider_name: OneUptime
provider_slug: oneuptime
slug: oneuptime-compliance
source_date: '2026-11-10'
source_filename: oneuptime-compliance.yml
source_heading: Compliance
source_page: https://oneuptime.com/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: OneUptime\naid: oneuptime\nurl: https://oneuptime.com/trust\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/oneuptime-trust-center.yml\ntrust_center:\n  url: https://oneuptime.com/trust\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: security, availability, and confidentiality controls\n  period: renewed annually\n  issuer: null\n  report_access: nda\n  text: SOC 2 Type II Security, availability, and confidentiality controls. Renewed annually, report under NDA.\n- framework: SOC3\n  type: SOC 3\n  scope: general-use summary of the same examination\n  period: null\n  issuer: null\n\
  \  report_access: public\n  text: SOC 3 report, the general-use summary of the same examination. Shareable without an NDA.\n- framework: ISO27001\n  type: ISO/IEC 27001 certification\n  scope: OneUptime Cloud and the organisation that builds the platform\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Certificate of registration, including scope, on request.\n- framework: ISO27017\n  type: ISO/IEC 27017 certification\n  scope: cloud-services security controls extending ISO 27001\n  period: null\n  issuer: null\n  report_access: on_request\n  text: ISO/IEC 27017 cloud-services security controls, audited alongside ISO 27001.\n- framework: ISO27018\n  type: ISO/IEC 27018 certification\n  scope: protection of personally identifiable information in public clouds\n  period: null\n  issuer: null\n  report_access: on_request\n  text: ISO/IEC 27018 controls for protecting personally identifiable information in public clouds.\n- framework: ISO9001\n  type: ISO 9001 certification\n\
  \  scope: quality management system covering how the service is built and operated\n  period: null\n  issuer: null\n  report_access: on_request\n  text: ISO 9001 certified quality management system.\n- framework: GDPR\n  type: GDPR compliance as processor\n  scope: Data Processing Addendum, Standard Contractual Clauses, EU data residency available\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR compliant as a processor, with a Data Processing Addendum, Standard Contractual Clauses, and EU data\n    residency available.\n- framework: CCPA\n  type: CCPA / CPRA compliance\n  scope: consumer privacy rights honoured for all customers\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA and CPRA compliant, with consumer privacy rights honoured for all customers.\n- framework: HIPAA\n  type: HIPAA compliance as business associate\n  scope: Business Associate Agreement available for covered entities\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: HIPAA compliant as a business associate, with a Business Associate Agreement available for covered entities.\n- framework: PCI-DSS\n  type: PCI DSS attestation\n  scope: cardholder data handled by payment providers; OneUptime does not store primary account numbers\n  period: null\n  issuer: Qualified Security Assessor\n  report_access: on_request\n  text: PCI DSS compliance validated by a Qualified Security Assessor, with a signed Attestation of Compliance.\n- framework: CSA-STAR\n  type: CSA STAR Level 2 certification\n  scope: Cloud Controls Matrix, with CAIQ published to the STAR registry\n  period: null\n  issuer: null\n  report_access: public\n  text: CSA STAR Level 2 certified against the Cloud Controls Matrix, with our CAIQ published to the STAR registry.\n- framework: FedRAMP\n  type: FedRAMP Moderate authorization\n  scope: OneUptime Cloud\n  period: null\n  issuer: null\n  report_access: unstated\n  text: FedRAMP Moderate authorization is in progress. Not\
  \ yet authorized, and no date is promised.\n- framework: other\n  type: Penetration testing\n  scope: independent third-party penetration testing\n  period: at least annually\n  issuer: null\n  report_access: nda\n  text: Independent third-party penetration testing at least annually. Summary reports are available under NDA to\n    qualifying customers.\n"
source_yaml_url: https://artifacts.apis.io/oneuptime/compliance/oneuptime-compliance.yml
stated_fields:
- attestations
summary_line: 13 quoted statements, read from OneUptime's own page on 2026-11-10.
synthetic: false
tags:
- Observability
- Open Source
---
