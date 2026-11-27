---
api_specs:
- filename: akuity-argocdservice-api-openapi.yml
  format: yaml
  label: Akuity Argo CD Service API
  slug: akuity-argocdservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/akuity/openapi/akuity-argocdservice-api-openapi.yml
- filename: akuity-customroleservice-api-openapi.yml
  format: yaml
  label: Akuity Custom Role Service API
  slug: akuity-customroleservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/akuity/openapi/akuity-customroleservice-api-openapi.yml
- filename: akuity-extensionservice-api-openapi.yml
  format: yaml
  label: Akuity Extension Service API
  slug: akuity-extensionservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/akuity/openapi/akuity-extensionservice-api-openapi.yml
- filename: akuity-kargoservice-api-openapi.yml
  format: yaml
  label: Akuity Kargo Service API
  slug: akuity-kargoservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/akuity/openapi/akuity-kargoservice-api-openapi.yml
- filename: akuity-organizationservice-api-openapi.yml
  format: yaml
  label: Akuity Organization Service API
  slug: akuity-organizationservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/akuity/openapi/akuity-organizationservice-api-openapi.yml
- filename: akuity-systemservice-api-openapi.yml
  format: yaml
  label: Akuity System Service API
  slug: akuity-systemservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/akuity/openapi/akuity-systemservice-api-openapi.yml
- filename: akuity-api-key-service-api-openapi.yml
  format: yaml
  label: Akuity Api Key Service API
  slug: akuity-api-key-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/akuity/openapi/akuity-api-key-service-api-openapi.yml
- filename: akuity-auth-service-api-openapi.yml
  format: yaml
  label: Akuity Auth Service API
  slug: akuity-auth-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/akuity/openapi/akuity-auth-service-api-openapi.yml
claim_count: 6
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Security Trust Service Criteria
    text: SOC 2 Type II Independently audited controls covering the Security Trust Service Criteria, with operational effectiveness validated over time.
    type: SOC 2 Type II
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Information Security Management System (ISMS)
    text: ISO/IEC 27001:2022 Certified Information Security Management System (ISMS)
    type: Certified ISMS
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: platform and operational controls
    text: PCI DSS v4.0.1 (Service Provider) Report on Compliance (ROC) completed
    type: Service Provider Report on Compliance (ROC)
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: administrative, technical, and operational safeguards
    text: HIPAA Administrative, technical, and operational safeguards aligned with HIPAA requirements.
    type: aligned safeguards
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: unstated
    scope: Cloud Controls Matrix (CCM)
    text: CSA STAR Level 1 Public self-assessment aligned with the Cloud Controls Matrix (CCM).
    type: Level 1 public self-assessment
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: data protection and privacy principles
    text: GDPR Alignment Platform and operational practices designed to support data protection and privacy principles under GDPR.
    type: alignment
  trust_center:
    url: https://akuity.io/security-compliance
frameworks:
- CSA-STAR
- GDPR
- HIPAA
- ISO27001
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Akuity
provenance_date: '2026-11-09'
provider_name: Akuity
provider_slug: akuity
slug: akuity-compliance
source_date: '2026-11-09'
source_filename: akuity-compliance.yml
source_heading: Compliance
source_page: https://akuity.io/security-compliance
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Akuity\naid: akuity\nurl: https://akuity.io/security-compliance\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://akuity.io/security-compliance\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: Security Trust Service Criteria\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II Independently audited controls covering the Security Trust Service Criteria, with operational\n    effectiveness validated over time.\n- framework: ISO27001\n  type: Certified ISMS\n  scope: Information Security Management System (ISMS)\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: ISO/IEC 27001:2022 Certified Information Security Management System (ISMS)\n- framework: PCI-DSS\n  type: Service Provider Report on Compliance (ROC)\n  scope: platform and operational controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI DSS v4.0.1 (Service Provider) Report on Compliance (ROC) completed\n- framework: HIPAA\n  type: aligned safeguards\n  scope: administrative, technical, and operational safeguards\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA Administrative, technical, and operational safeguards aligned with HIPAA requirements.\n- framework: CSA-STAR\n  type: Level 1 public self-assessment\n  scope: Cloud Controls Matrix (CCM)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CSA STAR Level 1 Public self-assessment aligned with the Cloud Controls Matrix (CCM).\n- framework: GDPR\n  type: alignment\n  scope: data protection and privacy principles\n  period: null\n  issuer: null\n\
  \  report_access: unstated\n  text: GDPR Alignment Platform and operational practices designed to support data protection and privacy principles\n    under GDPR.\n"
source_yaml_url: https://artifacts.apis.io/akuity/compliance/akuity-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from Akuity's own page on 2026-11-09.
synthetic: false
tags:
- GitOps
- Continuous Delivery
- Kubernetes
- ArgoCD
- Kargo
- Platform Engineering
- DevOps
- Progressive Delivery
- Cloud-Native
- AIOps
- Developer Tools
---
