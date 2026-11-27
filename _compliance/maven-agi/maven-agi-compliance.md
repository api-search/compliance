---
api_specs:
- filename: maven-agi-actions-api-openapi.yml
  format: yaml
  label: Maven AGI Actions API
  slug: maven-agi-actions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/maven-agi/openapi/maven-agi-actions-api-openapi.yml
- filename: maven-agi-agents-api-openapi.yml
  format: yaml
  label: Maven AGI Agents API
  slug: maven-agi-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/maven-agi/openapi/maven-agi-agents-api-openapi.yml
- filename: maven-agi-analytics-api-openapi.yml
  format: yaml
  label: Maven AGI Analytics API
  slug: maven-agi-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/maven-agi/openapi/maven-agi-analytics-api-openapi.yml
- filename: maven-agi-app-settings-api-openapi.yml
  format: yaml
  label: Maven AGI App Settings API
  slug: maven-agi-app-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/maven-agi/openapi/maven-agi-app-settings-api-openapi.yml
- filename: maven-agi-conversations-api-openapi.yml
  format: yaml
  label: Maven AGI Conversations API
  slug: maven-agi-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/maven-agi/openapi/maven-agi-conversations-api-openapi.yml
- filename: maven-agi-events-api-openapi.yml
  format: yaml
  label: Maven AGI Events API
  slug: maven-agi-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/maven-agi/openapi/maven-agi-events-api-openapi.yml
- filename: maven-agi-knowledge-api-openapi.yml
  format: yaml
  label: Maven AGI Knowledge API
  slug: maven-agi-knowledge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/maven-agi/openapi/maven-agi-knowledge-api-openapi.yml
- filename: maven-agi-triggers-api-openapi.yml
  format: yaml
  label: Maven AGI Triggers API
  slug: maven-agi-triggers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/maven-agi/openapi/maven-agi-triggers-api-openapi.yml
- filename: maven-agi-users-api-openapi.yml
  format: yaml
  label: Maven AGI Users API
  slug: maven-agi-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/maven-agi/openapi/maven-agi-users-api-openapi.yml
claim_count: 11
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: Information Security Management
    text: 'Maven holds the following active certifications: ISO 27001 (Information Security Management)'
    type: certification
  - framework: ISO42001
    issuer: null
    period: null
    report_access: on_request
    scope: AI Management Systems
    text: ISO/IEC 42001:2023 AI Management Systems Independent certification of Maven's AI Management System
    type: certification
  - framework: ISO27701
    issuer: null
    period: null
    report_access: on_request
    scope: Privacy Information Management
    text: ISO/IEC 27701:2019 Privacy Information Management Independent certification extending Maven's ISMS
    type: certification
  - framework: ISO27017
    issuer: null
    period: null
    report_access: on_request
    scope: Cloud Security
    text: ISO 27017 (Cloud Security)
    type: certification
  - framework: ISO27018
    issuer: null
    period: null
    report_access: on_request
    scope: Protection of PII in Public Clouds
    text: ISO 27018 (Protection of PII in Public Clouds)
    type: certification
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: on_request
    scope: Level 1, cardholder data handling
    text: PCI-DSS 4.0.1 Attestation of Compliance (AOC) This PCI-DSS 4.0.1 AOC is an independent attestation confirming compliance with PCI-DSS Level 1 requirements
    type: attestation of compliance
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Security, availability, confidentiality criteria
    text: Maven also maintains SOC 2 Type II and HIPAA/HITECH independent assessment reports.
    type: independent assessment report
  - framework: HIPAA
    issuer: null
    period: '2026'
    report_access: on_request
    scope: HIPAA Security and Privacy Rule
    text: HIPAA + HITECH + SOC2 Type II (2026) Final Report includes an Attestation of SOC 2 Type II, HIPAA, and HITECH Assessments
    type: independent assessment report
  - framework: GDPR
    issuer: null
    period: null
    report_access: on_request
    scope: EU and UK operations
    text: This independent assessment confirms Maven AGI's compliance with the General Data Protection Regulation (GDPR)
    type: independent assessment
  - framework: CCPA
    issuer: null
    period: null
    report_access: on_request
    scope: California consumer privacy law
    text: This independent assessment confirms Maven AGI's compliance with the California Consumer Privacy Act (CCPA) and the California Privacy Rights Act (CPRA)
    type: independent assessment
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: unstated
    scope: Corporate member of Cloud Security Alliance
    text: Maven AGI is a corporate member of the Cloud Security Alliance (CSA)
    type: membership
  trust_center:
    url: https://trust.mavenagi.com/
frameworks:
- CCPA
- CSA-STAR
- GDPR
- HIPAA
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
name: Maven AGI
provenance_date: '2026-11-10'
provider_name: Maven AGI
provider_slug: maven-agi
slug: maven-agi-compliance
source_date: '2026-11-10'
source_filename: maven-agi-compliance.yml
source_heading: Compliance
source_page: https://trust.mavenagi.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Maven AGI\naid: maven-agi\nurl: https://trust.mavenagi.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/maven-agi-trust-center.yml\ntrust_center:\n  url: https://trust.mavenagi.com/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: Information Security Management\n  period: null\n  issuer: null\n  report_access: on_request\n  text: 'Maven holds the following active certifications: ISO 27001 (Information Security Management)'\n- framework: ISO42001\n  type: certification\n  scope: AI Management Systems\n  period: null\n  issuer: null\n  report_access: on_request\n  text: ISO/IEC\
  \ 42001:2023 AI Management Systems Independent certification of Maven's AI Management System\n- framework: ISO27701\n  type: certification\n  scope: Privacy Information Management\n  period: null\n  issuer: null\n  report_access: on_request\n  text: ISO/IEC 27701:2019 Privacy Information Management Independent certification extending Maven's ISMS\n- framework: ISO27017\n  type: certification\n  scope: Cloud Security\n  period: null\n  issuer: null\n  report_access: on_request\n  text: ISO 27017 (Cloud Security)\n- framework: ISO27018\n  type: certification\n  scope: Protection of PII in Public Clouds\n  period: null\n  issuer: null\n  report_access: on_request\n  text: ISO 27018 (Protection of PII in Public Clouds)\n- framework: PCI-DSS\n  type: attestation of compliance\n  scope: Level 1, cardholder data handling\n  period: null\n  issuer: null\n  report_access: on_request\n  text: PCI-DSS 4.0.1 Attestation of Compliance (AOC) This PCI-DSS 4.0.1 AOC is an independent attestation confirming\n\
  \    compliance with PCI-DSS Level 1 requirements\n- framework: SOC2\n  type: independent assessment report\n  scope: Security, availability, confidentiality criteria\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Maven also maintains SOC 2 Type II and HIPAA/HITECH independent assessment reports.\n- framework: HIPAA\n  type: independent assessment report\n  scope: HIPAA Security and Privacy Rule\n  period: '2026'\n  issuer: null\n  report_access: on_request\n  text: HIPAA + HITECH + SOC2 Type II (2026) Final Report includes an Attestation of SOC 2 Type II, HIPAA, and HITECH\n    Assessments\n- framework: GDPR\n  type: independent assessment\n  scope: EU and UK operations\n  period: null\n  issuer: null\n  report_access: on_request\n  text: This independent assessment confirms Maven AGI's compliance with the General Data Protection Regulation\n    (GDPR)\n- framework: CCPA\n  type: independent assessment\n  scope: California consumer privacy law\n  period: null\n\
  \  issuer: null\n  report_access: on_request\n  text: This independent assessment confirms Maven AGI's compliance with the California Consumer Privacy Act (CCPA)\n    and the California Privacy Rights Act (CPRA)\n- framework: CSA-STAR\n  type: membership\n  scope: Corporate member of Cloud Security Alliance\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Maven AGI is a corporate member of the Cloud Security Alliance (CSA)\n"
source_yaml_url: https://artifacts.apis.io/maven-agi/compliance/maven-agi-compliance.yml
stated_fields:
- attestations
summary_line: 11 quoted statements, read from Maven AGI's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Agents
- Customer Service
- Customer Experience
- Conversational AI
- Knowledge
---
