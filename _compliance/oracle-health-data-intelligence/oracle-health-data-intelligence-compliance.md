---
api_specs:
- filename: oracle-health-data-intelligence-populations-api-openapi.yml
  format: yaml
  label: Oracle Health Data Intelligence Populations API
  slug: oracle-health-data-intelligence-populations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oracle-health-data-intelligence/openapi/oracle-health-data-intelligence-populations-api-openapi.yml
claim_count: 13
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Oracle Cloud Infrastructure, Oracle Applications, NetSuite, Oracle Industries, Oracle Health
    text: A SOC 2 report outlines information related to a service organization’s internal controls for security, availability, processing integrity, confidentiality or privacy Trust Criteria.
    type: SOC 2 report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Oracle Cloud Infrastructure, Oracle Applications, NetSuite, Oracle Industries, Oracle Health
    text: 'ISO/IEC 27001: Information Security Management Systems'
    type: ISO/IEC 27001 certification
  - framework: ISO27017
    issuer: null
    period: null
    report_access: unstated
    scope: Oracle Cloud Infrastructure, Oracle Applications, NetSuite, Oracle Industries, Oracle Health
    text: 'ISO/IEC 27017: Cloud Specific Controls'
    type: ISO/IEC 27017 attestation
  - framework: ISO27018
    issuer: null
    period: null
    report_access: unstated
    scope: Oracle Cloud Infrastructure, Oracle Applications, NetSuite, Oracle Industries, Oracle Health
    text: 'ISO/IEC 27018: Personal Information Protection Controls'
    type: ISO/IEC 27018 attestation
  - framework: ISO27701
    issuer: null
    period: null
    report_access: unstated
    scope: Oracle Cloud Infrastructure, Oracle Applications, NetSuite, Oracle Industries, Oracle Health
    text: 'ISO/IEC 27701: Privacy Information Management'
    type: ISO/IEC 27701 attestation
  - framework: ISO42001
    issuer: null
    period: null
    report_access: unstated
    scope: Oracle Cloud Infrastructure, Oracle Applications, NetSuite, Oracle Industries, Oracle Health
    text: 'ISO/IEC 42001:2023: Information technology — Artificial intelligence — Management system'
    type: ISO/IEC 42001:2023 attestation
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Oracle Health
    text: HITRUST created and maintains the Common Security Framework (CSF), a framework against which cloud service providers (CSPs) and covered health entities can demonstrate compliance to US Health Insurance Portability and Accountability Act (HIPAA) requirements.
    type: HIPAA compliance framework
  - framework: HITRUST
    issuer: null
    period: null
    report_access: unstated
    scope: Oracle Health
    text: HITRUST CSF Health Information Trust Alliance Common Security Framework
    type: HITRUST CSF
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: Oracle Cloud Infrastructure, Oracle Applications, NetSuite, Oracle Industries, Oracle Health
    text: FedRAMP Federal Risk and Authorization Management Program
    type: FedRAMP authorization
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: unstated
    scope: Oracle Cloud Infrastructure, Oracle Applications, NetSuite, Oracle Industries, Oracle Health
    text: The CSA Security Trust, Assurance and Risk (STAR) attestation provides for an assessment to be performed by a reputable third-party that affirms implementation of necessary security controls.
    type: CSA STAR attestation
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: Oracle Cloud Infrastructure, Oracle Applications, NetSuite, Oracle Industries, Oracle Health
    text: PCI DSS Payment Card Industry Data Security Standard
    type: PCI DSS attestation
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Oracle Cloud Infrastructure
    text: Oracle Cloud Infrastructure and the General Data Protection Regulation (GDPR) (PDF)
    type: GDPR compliance advisory
  - framework: IRAP
    issuer: null
    period: null
    report_access: unstated
    scope: Oracle Cloud Infrastructure, Oracle Applications, NetSuite, Oracle Industries, Oracle Health
    text: IRAP is the assessors' program developed by the Australian government Cyber Security Centre (ASD/ACSC) for assessing cloud services for government and non-government agency use.
    type: IRAP assessment
  trust_center:
    url: https://www.oracle.com/corporate/cloud-compliance/
frameworks:
- CSA-STAR
- FedRAMP
- GDPR
- HIPAA
- HITRUST
- IRAP
- ISO27001
- ISO27017
- ISO27018
- ISO27701
- ISO42001
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Oracle Health Data Intelligence
provenance_date: '2026-11-10'
provider_name: Oracle Health Data Intelligence
provider_slug: oracle-health-data-intelligence
slug: oracle-health-data-intelligence-compliance
source_date: '2026-11-10'
source_filename: oracle-health-data-intelligence-compliance.yml
source_heading: Compliance
source_page: https://www.oracle.com/corporate/cloud-compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Oracle Health Data Intelligence\naid: oracle-health-data-intelligence\nurl: https://www.oracle.com/corporate/cloud-compliance/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ntrust_center:\n  url: https://www.oracle.com/corporate/cloud-compliance/\nattestations:\n- framework: SOC2\n  type: SOC 2 report\n  scope: Oracle Cloud Infrastructure, Oracle Applications, NetSuite, Oracle Industries, Oracle Health\n  period: null\n  issuer: null\n  report_access: unstated\n  text: A SOC 2 report outlines information related to a service organization’s internal controls for security,\n    availability, processing integrity,\
  \ confidentiality or privacy Trust Criteria.\n- framework: ISO27001\n  type: ISO/IEC 27001 certification\n  scope: Oracle Cloud Infrastructure, Oracle Applications, NetSuite, Oracle Industries, Oracle Health\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'ISO/IEC 27001: Information Security Management Systems'\n- framework: ISO27017\n  type: ISO/IEC 27017 attestation\n  scope: Oracle Cloud Infrastructure, Oracle Applications, NetSuite, Oracle Industries, Oracle Health\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'ISO/IEC 27017: Cloud Specific Controls'\n- framework: ISO27018\n  type: ISO/IEC 27018 attestation\n  scope: Oracle Cloud Infrastructure, Oracle Applications, NetSuite, Oracle Industries, Oracle Health\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'ISO/IEC 27018: Personal Information Protection Controls'\n- framework: ISO27701\n  type: ISO/IEC 27701 attestation\n  scope: Oracle Cloud Infrastructure, Oracle Applications,\
  \ NetSuite, Oracle Industries, Oracle Health\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'ISO/IEC 27701: Privacy Information Management'\n- framework: ISO42001\n  type: ISO/IEC 42001:2023 attestation\n  scope: Oracle Cloud Infrastructure, Oracle Applications, NetSuite, Oracle Industries, Oracle Health\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'ISO/IEC 42001:2023: Information technology — Artificial intelligence — Management system'\n- framework: HIPAA\n  type: HIPAA compliance framework\n  scope: Oracle Health\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HITRUST created and maintains the Common Security Framework (CSF), a framework against which cloud service\n    providers (CSPs) and covered health entities can demonstrate compliance to US Health Insurance Portability and\n    Accountability Act (HIPAA) requirements.\n- framework: HITRUST\n  type: HITRUST CSF\n  scope: Oracle Health\n  period: null\n  issuer: null\n\
  \  report_access: unstated\n  text: HITRUST CSF Health Information Trust Alliance Common Security Framework\n- framework: FedRAMP\n  type: FedRAMP authorization\n  scope: Oracle Cloud Infrastructure, Oracle Applications, NetSuite, Oracle Industries, Oracle Health\n  period: null\n  issuer: null\n  report_access: unstated\n  text: FedRAMP Federal Risk and Authorization Management Program\n- framework: CSA-STAR\n  type: CSA STAR attestation\n  scope: Oracle Cloud Infrastructure, Oracle Applications, NetSuite, Oracle Industries, Oracle Health\n  period: null\n  issuer: null\n  report_access: unstated\n  text: The CSA Security Trust, Assurance and Risk (STAR) attestation provides for an assessment to be performed\n    by a reputable third-party that affirms implementation of necessary security controls.\n- framework: PCI-DSS\n  type: PCI DSS attestation\n  scope: Oracle Cloud Infrastructure, Oracle Applications, NetSuite, Oracle Industries, Oracle Health\n  period: null\n  issuer: null\n \
  \ report_access: unstated\n  text: PCI DSS Payment Card Industry Data Security Standard\n- framework: GDPR\n  type: GDPR compliance advisory\n  scope: Oracle Cloud Infrastructure\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Oracle Cloud Infrastructure and the General Data Protection Regulation (GDPR) (PDF)\n- framework: IRAP\n  type: IRAP assessment\n  scope: Oracle Cloud Infrastructure, Oracle Applications, NetSuite, Oracle Industries, Oracle Health\n  period: null\n  issuer: null\n  report_access: unstated\n  text: IRAP is the assessors' program developed by the Australian government Cyber Security Centre (ASD/ACSC) for\n    assessing cloud services for government and non-government agency use.\n"
source_yaml_url: https://artifacts.apis.io/oracle-health-data-intelligence/compliance/oracle-health-data-intelligence-compliance.yml
stated_fields:
- attestations
summary_line: 13 quoted statements, read from Oracle Health Data Intelligence's own page on 2026-11-10.
synthetic: false
tags:
- Genomic
- Health Records
- Healthcare
- Population Health
- Longitudinal Record
- Interoperability
- Clinical Data
- Analytics
---
