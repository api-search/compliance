---
api_specs:
- filename: bigid-authentication-api-openapi.yml
  format: yaml
  label: BigID Authentication API
  slug: bigid-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bigid/openapi/bigid-authentication-api-openapi.yml
- filename: bigid-data-sources-api-openapi.yml
  format: yaml
  label: BigID Data Sources API
  slug: bigid-data-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bigid/openapi/bigid-data-sources-api-openapi.yml
- filename: bigid-scans-api-openapi.yml
  format: yaml
  label: BigID Scans API
  slug: bigid-scans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bigid/openapi/bigid-scans-api-openapi.yml
- filename: bigid-dsar-api-openapi.yml
  format: yaml
  label: BigID DSAR API
  slug: bigid-dsar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bigid/openapi/bigid-dsar-api-openapi.yml
- filename: bigid-actionable-insights-api-openapi.yml
  format: yaml
  label: BigID Actionable Insights API
  slug: bigid-actionable-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bigid/openapi/bigid-actionable-insights-api-openapi.yml
- filename: bigid-catalog-api-openapi.yml
  format: yaml
  label: BigID Catalog API
  slug: bigid-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bigid/openapi/bigid-catalog-api-openapi.yml
- filename: bigid-clusters-api-openapi.yml
  format: yaml
  label: BigID Clusters API
  slug: bigid-clusters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bigid/openapi/bigid-clusters-api-openapi.yml
- filename: bigid-connector-templates-api-openapi.yml
  format: yaml
  label: BigID Connector Templates API
  slug: bigid-connector-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bigid/openapi/bigid-connector-templates-api-openapi.yml
- filename: bigid-metadata-export-api-openapi.yml
  format: yaml
  label: BigID Metadata Export API
  slug: bigid-metadata-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bigid/openapi/bigid-metadata-export-api-openapi.yml
- filename: bigid-scan-profiles-api-openapi.yml
  format: yaml
  label: BigID Scan Profiles API
  slug: bigid-scan-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bigid/openapi/bigid-scan-profiles-api-openapi.yml
claim_count: 7
description: ''
doc:
  attestations:
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: public
    scope: Cloud platform
    text: BigID has also published its completed CAIQ self-assessment in the CSA STAR Registry.
    type: CAIQ self-assessment published in CSA STAR Registry
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Information security management
    text: BigID is aligned with ISO 27001, an internationally recognized framework for information security management
    type: alignment
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Platform and supporting processes, people, and controls
    text: BigID is SOC 2 certified, demonstrating that the platform and its supporting processes, people, and controls are designed to help keep customer data secure.
    type: SOC 2 certified
  - framework: SOC3
    issuer: null
    period: null
    report_access: public
    scope: Security, confidentiality, availability, and privacy controls
    text: BigID’s SOC 3 report provides a general-use overview of the security, confidentiality, availability, and privacy controls used to protect customer data.
    type: SOC 3 report
  - framework: PCI-DSS
    issuer: independent assessor
    period: null
    report_access: unstated
    scope: Cloud and on-premises PCI environments
    text: Its PCI compliance reflects security controls that have been evaluated by an independent assessor.
    type: PCI compliance evaluated by independent assessor
  - framework: other
    issuer: Texas Department of Information Resources
    period: null
    report_access: unstated
    scope: Cloud services processing confidential or regulated data in Texas state systems
    text: TX-RAMP Level 2 is a rigorous Texas Department of Information Resources standard for cloud services that process confidential or regulated data in moderate- or high-impact state systems.
    type: TX-RAMP Level 2
  - framework: other
    issuer: EDM Council
    period: null
    report_access: unstated
    scope: EDM Council Cloud Data Management Capabilities framework, 14 controls
    text: BigID can help organizations address all 14 controls in the EDM Council’s Cloud Data Management Capabilities framework
    type: CDMC capability coverage
  trust_center:
    url: https://bigid.com/certifications-and-assessments/
frameworks:
- CSA-STAR
- ISO27001
- PCI-DSS
- SOC2
- SOC3
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: BigID
provenance_date: '2026-11-09'
provider_name: BigID
provider_slug: bigid
slug: bigid-compliance
source_date: '2026-11-09'
source_filename: bigid-compliance.yml
source_heading: Compliance
source_page: https://bigid.com/certifications-and-assessments/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: BigID\naid: bigid\nurl: https://bigid.com/certifications-and-assessments/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://bigid.com/certifications-and-assessments/\nattestations:\n- framework: CSA-STAR\n  type: CAIQ self-assessment published in CSA STAR Registry\n  scope: Cloud platform\n  period: null\n  issuer: null\n  report_access: public\n  text: BigID has also published its completed CAIQ self-assessment in the CSA STAR Registry.\n- framework: ISO27001\n  type: alignment\n  scope: Information security management\n  period: null\n  issuer: null\n  report_access: unstated\n  text: BigID is aligned\
  \ with ISO 27001, an internationally recognized framework for information security management\n- framework: SOC2\n  type: SOC 2 certified\n  scope: Platform and supporting processes, people, and controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: BigID is SOC 2 certified, demonstrating that the platform and its supporting processes, people, and controls\n    are designed to help keep customer data secure.\n- framework: SOC3\n  type: SOC 3 report\n  scope: Security, confidentiality, availability, and privacy controls\n  period: null\n  issuer: null\n  report_access: public\n  text: BigID’s SOC 3 report provides a general-use overview of the security, confidentiality, availability, and\n    privacy controls used to protect customer data.\n- framework: PCI-DSS\n  type: PCI compliance evaluated by independent assessor\n  scope: Cloud and on-premises PCI environments\n  period: null\n  issuer: independent assessor\n  report_access: unstated\n  text: Its PCI compliance\
  \ reflects security controls that have been evaluated by an independent assessor.\n- framework: other\n  type: TX-RAMP Level 2\n  scope: Cloud services processing confidential or regulated data in Texas state systems\n  period: null\n  issuer: Texas Department of Information Resources\n  report_access: unstated\n  text: TX-RAMP Level 2 is a rigorous Texas Department of Information Resources standard for cloud services that\n    process confidential or regulated data in moderate- or high-impact state systems.\n- framework: other\n  type: CDMC capability coverage\n  scope: EDM Council Cloud Data Management Capabilities framework, 14 controls\n  period: null\n  issuer: EDM Council\n  report_access: unstated\n  text: BigID can help organizations address all 14 controls in the EDM Council’s Cloud Data Management Capabilities\n    framework\n"
source_yaml_url: https://artifacts.apis.io/bigid/compliance/bigid-compliance.yml
stated_fields:
- attestations
summary_line: 7 quoted statements, read from BigID's own page on 2026-11-09.
synthetic: false
tags:
- Data Security
- DSPM
- DLP
- Privacy
- AI Security
- Data Catalog
- DSAR
- Data Discovery
- Compliance
---
