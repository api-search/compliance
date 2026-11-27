---
api_specs:
- filename: sonarqube-issues-api-openapi.yml
  format: yaml
  label: SonarQube Issues API
  slug: sonarqube-issues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sonarqube/openapi/sonarqube-issues-api-openapi.yml
- filename: sonarqube-measures-api-openapi.yml
  format: yaml
  label: SonarQube Measures API
  slug: sonarqube-measures-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sonarqube/openapi/sonarqube-measures-api-openapi.yml
- filename: sonarqube-projects-api-openapi.yml
  format: yaml
  label: SonarQube Projects API
  slug: sonarqube-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sonarqube/openapi/sonarqube-projects-api-openapi.yml
- filename: sonarqube-quality-gates-api-openapi.yml
  format: yaml
  label: SonarQube Quality Gates API
  slug: sonarqube-quality-gates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sonarqube/openapi/sonarqube-quality-gates-api-openapi.yml
- filename: sonarqube-rules-api-openapi.yml
  format: yaml
  label: SonarQube Rules API
  slug: sonarqube-rules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sonarqube/openapi/sonarqube-rules-api-openapi.yml
- filename: sonarqube-system-api-openapi.yml
  format: yaml
  label: SonarQube System API
  slug: sonarqube-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sonarqube/openapi/sonarqube-system-api-openapi.yml
- filename: sonarqube-users-api-openapi.yml
  format: yaml
  label: SonarQube Users API
  slug: sonarqube-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sonarqube/openapi/sonarqube-users-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: Nov 1, 2024 through October 31, 2025
    report_access: unstated
    scope: Sonar Operations and commercial products and services (SonarQube Cloud, SonarQube Server, SonarQube for IDE, and supporting services, including AI CodeFix, SonarQube Advanced Security, and others)
    text: 'Reporting Period Assessed: Nov 1, 2024 through October 31, 2025'
    type: SOC 2 Type II
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001:2022 Certificate
    type: certification
  - framework: ISO27018
    issuer: null
    period: null
    report_access: unstated
    scope: all SonarSource products, information, information processing facilities, and personnel related to the delivery of SonarQube Cloud
    text: we have achieved ISO 27018 certification for Privacy for all SonarSource products, information, information processing facilities, and personnel related to our the delivery of SonarQube Cloud.
    type: certification
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: unstated
    scope: SonarQube Cloud
    text: CSA STAR Level 1 Registry - SonarQube Cloud
    type: CSA STAR Level 1 registry listing
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Sonar PCI-DSS SAQ-A
    type: self-assessment questionnaire SAQ-A
  trust_center:
    url: https://trust.sonarsource.com/
frameworks:
- CSA-STAR
- ISO27001
- ISO27018
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: SonarQube
provenance_date: '2026-11-10'
provider_name: SonarQube
provider_slug: sonarqube
slug: sonarqube-compliance
source_date: '2026-11-10'
source_filename: sonarqube-compliance.yml
source_heading: Compliance
source_page: https://trust.sonarsource.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: SonarQube\naid: sonarqube\nurl: https://trust.sonarsource.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.sonarsource.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: Sonar Operations and commercial products and services (SonarQube Cloud, SonarQube Server, SonarQube for\n    IDE, and supporting services, including AI CodeFix, SonarQube Advanced Security, and others)\n  period: Nov 1, 2024 through October 31, 2025\n  issuer: null\n  report_access: unstated\n  text: 'Reporting Period Assessed: Nov 1, 2024 through October 31, 2025'\n- framework: ISO27001\n  type: certification\n\
  \  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022 Certificate\n- framework: ISO27018\n  type: certification\n  scope: all SonarSource products, information, information processing facilities, and personnel related to the\n    delivery of SonarQube Cloud\n  period: null\n  issuer: null\n  report_access: unstated\n  text: we have achieved ISO 27018 certification for Privacy for all SonarSource products, information, information\n    processing facilities, and personnel related to our the delivery of SonarQube Cloud.\n- framework: CSA-STAR\n  type: CSA STAR Level 1 registry listing\n  scope: SonarQube Cloud\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CSA STAR Level 1 Registry - SonarQube Cloud\n- framework: PCI-DSS\n  type: self-assessment questionnaire SAQ-A\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Sonar PCI-DSS SAQ-A\n"
source_yaml_url: https://artifacts.apis.io/sonarqube/compliance/sonarqube-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from SonarQube's own page on 2026-11-10.
synthetic: false
tags:
- Code Quality
- Developer Tools
- DevOps
- Security
- Static Analysis
- Code Security
- SAST
---
