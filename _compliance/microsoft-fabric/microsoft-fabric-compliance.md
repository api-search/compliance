---
api_specs:
- filename: microsoft-fabric-fabriccapacities-api-openapi.yml
  format: yaml
  label: Microsoft Fabric Fabric Capacities API
  slug: microsoft-fabric-fabriccapacities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/microsoft-fabric/openapi/microsoft-fabric-fabriccapacities-api-openapi.yml
- filename: microsoft-fabric-operations-api-openapi.yml
  format: yaml
  label: Microsoft Fabric Operations API
  slug: microsoft-fabric-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/microsoft-fabric/openapi/microsoft-fabric-operations-api-openapi.yml
claim_count: 8
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Microsoft Fabric has HIPAA BAA, ISO/IEC 27017, ISO/IEC 27018, ISO/IEC 27001, and ISO/IEC 27701 compliance certifications.
    type: certification
  - framework: ISO27017
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Microsoft Fabric has HIPAA BAA, ISO/IEC 27017, ISO/IEC 27018, ISO/IEC 27001, and ISO/IEC 27701 compliance certifications.
    type: certification
  - framework: ISO27018
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Microsoft Fabric has HIPAA BAA, ISO/IEC 27017, ISO/IEC 27018, ISO/IEC 27001, and ISO/IEC 27701 compliance certifications.
    type: certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Microsoft Fabric has HIPAA BAA, ISO/IEC 27017, ISO/IEC 27018, ISO/IEC 27001, and ISO/IEC 27701 compliance certifications.
    type: certification
  - framework: ISO27701
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Microsoft Fabric has HIPAA BAA, ISO/IEC 27017, ISO/IEC 27018, ISO/IEC 27001, and ISO/IEC 27701 compliance certifications.
    type: certification
  - framework: other
    issuer: null
    period: July 1, 2026 - September 30, 2026
    report_access: unstated
    scope: Azure + Dynamics 365 + Online Services (Public & Government)
    source: https://servicetrust.microsoft.com/
    text: Azure + Dynamics 365 + Online Services (Public & Government) SOC Bridge Letter (July 1, 2026 - September 30, 2026)
    type: SOC Bridge Letter
  - framework: other
    issuer: null
    period: October 2026
    report_access: unstated
    scope: Microsoft 365
    source: https://servicetrust.microsoft.com/
    text: Microsoft 365 - SOC Bridge Letter (October 2026)
    type: SOC Bridge Letter
  - framework: other
    issuer: null
    period: October 1st 2025 through September 30th 2026
    report_access: unstated
    scope: Azure DevOps
    source: https://servicetrust.microsoft.com/
    text: Azure DevOps SOC Bridge Letter for the period of October 1st 2025 through September 30th 2026
    type: SOC Bridge Letter
  trust_center:
    url: https://learn.microsoft.com/en-us/fabric/governance/governance-compliance-overview
frameworks:
- HIPAA
- ISO27001
- ISO27017
- ISO27018
- ISO27701
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Microsoft Fabric
provenance_date: '2026-11-10'
provider_name: Microsoft Fabric
provider_slug: microsoft-fabric
slug: microsoft-fabric-compliance
source_date: '2026-11-10'
source_filename: microsoft-fabric-compliance.yml
source_heading: Compliance
source_page: https://learn.microsoft.com/en-us/fabric/governance/governance-compliance-overview
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Microsoft Fabric\naid: microsoft-fabric\nurl: https://learn.microsoft.com/en-us/fabric/governance/governance-compliance-overview\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/microsoft-fabric-trust-center.yml\n  sources:\n  - https://learn.microsoft.com/en-us/fabric/governance/governance-compliance-overview\n  - https://servicetrust.microsoft.com/\ntrust_center:\n  url: https://learn.microsoft.com/en-us/fabric/governance/governance-compliance-overview\nattestations:\n- framework: HIPAA\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Microsoft\
  \ Fabric has HIPAA BAA, ISO/IEC 27017, ISO/IEC 27018, ISO/IEC 27001, and ISO/IEC 27701 compliance\n    certifications.\n- framework: ISO27017\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Microsoft Fabric has HIPAA BAA, ISO/IEC 27017, ISO/IEC 27018, ISO/IEC 27001, and ISO/IEC 27701 compliance\n    certifications.\n- framework: ISO27018\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Microsoft Fabric has HIPAA BAA, ISO/IEC 27017, ISO/IEC 27018, ISO/IEC 27001, and ISO/IEC 27701 compliance\n    certifications.\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Microsoft Fabric has HIPAA BAA, ISO/IEC 27017, ISO/IEC 27018, ISO/IEC 27001, and ISO/IEC 27701 compliance\n    certifications.\n- framework: ISO27701\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: Microsoft Fabric has HIPAA BAA, ISO/IEC 27017, ISO/IEC 27018, ISO/IEC 27001, and ISO/IEC 27701 compliance\n    certifications.\n- framework: other\n  type: SOC Bridge Letter\n  scope: Azure + Dynamics 365 + Online Services (Public & Government)\n  period: July 1, 2026 - September 30, 2026\n  issuer: null\n  report_access: unstated\n  text: Azure + Dynamics 365 + Online Services (Public & Government) SOC Bridge Letter (July 1, 2026 - September\n    30, 2026)\n  source: https://servicetrust.microsoft.com/\n- framework: other\n  type: SOC Bridge Letter\n  scope: Microsoft 365\n  period: October 2026\n  issuer: null\n  report_access: unstated\n  text: Microsoft 365 - SOC Bridge Letter (October 2026)\n  source: https://servicetrust.microsoft.com/\n- framework: other\n  type: SOC Bridge Letter\n  scope: Azure DevOps\n  period: October 1st 2025 through September 30th 2026\n  issuer: null\n  report_access: unstated\n  text: Azure DevOps SOC Bridge Letter for the period of October 1st\
  \ 2025 through September 30th 2026\n  source: https://servicetrust.microsoft.com/\n"
source_yaml_url: https://artifacts.apis.io/microsoft-fabric/compliance/microsoft-fabric-compliance.yml
stated_fields:
- attestations
summary_line: 8 quoted statements, read from Microsoft Fabric's own page on 2026-11-10.
synthetic: false
tags:
- Data Analytics
- Data Engineering
- Data Platform
- Lakehouse
- Microsoft
---
