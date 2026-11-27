---
api_specs:
- filename: semaphore-dashboards-api-openapi.yml
  format: yaml
  label: Semaphore Dashboards API
  slug: semaphore-dashboards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/semaphore/openapi/semaphore-dashboards-api-openapi.yml
- filename: semaphore-deploymenttargets-api-openapi.yml
  format: yaml
  label: Semaphore DeploymentTargets API
  slug: semaphore-deploymenttargets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/semaphore/openapi/semaphore-deploymenttargets-api-openapi.yml
- filename: semaphore-notifications-api-openapi.yml
  format: yaml
  label: Semaphore Notifications API
  slug: semaphore-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/semaphore/openapi/semaphore-notifications-api-openapi.yml
- filename: semaphore-pipelines-api-openapi.yml
  format: yaml
  label: Semaphore Pipelines API
  slug: semaphore-pipelines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/semaphore/openapi/semaphore-pipelines-api-openapi.yml
- filename: semaphore-projects-api-openapi.yml
  format: yaml
  label: Semaphore Projects API
  slug: semaphore-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/semaphore/openapi/semaphore-projects-api-openapi.yml
- filename: semaphore-projectsecrets-api-openapi.yml
  format: yaml
  label: Semaphore ProjectSecrets API
  slug: semaphore-projectsecrets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/semaphore/openapi/semaphore-projectsecrets-api-openapi.yml
- filename: semaphore-secrets-api-openapi.yml
  format: yaml
  label: Semaphore Secrets API
  slug: semaphore-secrets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/semaphore/openapi/semaphore-secrets-api-openapi.yml
- filename: semaphore-selfhostedagents-api-openapi.yml
  format: yaml
  label: Semaphore SelfHostedAgents API
  slug: semaphore-selfhostedagents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/semaphore/openapi/semaphore-selfhostedagents-api-openapi.yml
- filename: semaphore-selfhostedagenttypes-api-openapi.yml
  format: yaml
  label: Semaphore SelfHostedAgentTypes API
  slug: semaphore-selfhostedagenttypes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/semaphore/openapi/semaphore-selfhostedagenttypes-api-openapi.yml
- filename: semaphore-tasks-api-openapi.yml
  format: yaml
  label: Semaphore Tasks API
  slug: semaphore-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/semaphore/openapi/semaphore-tasks-api-openapi.yml
- filename: semaphore-workflows-api-openapi.yml
  format: yaml
  label: Semaphore Workflows API
  slug: semaphore-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/semaphore/openapi/semaphore-workflows-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: service organization controls
    text: Access to our SOC 2 Type 2 report available on request under NDA.
    type: SOC 2 Type 2 audit
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: Information Security Management System
    text: Proof of certification is available on request .
    type: ISO 27001:2022 certification
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: payments made on Semaphore via FastSpring
    text: All payments made on Semaphore go through FastSpring , a PCI-DSS Level 1 compliant service.
    type: PCI-DSS Level 1 compliance of payment service
  trust_center:
    url: https://semaphore.io/security
frameworks:
- ISO27001
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Semaphore
provenance_date: '2026-11-10'
provider_name: Semaphore
provider_slug: semaphore
slug: semaphore-compliance
source_date: '2026-11-10'
source_filename: semaphore-compliance.yml
source_heading: Compliance
source_page: https://semaphore.io/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Semaphore\naid: semaphore\nurl: https://semaphore.io/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/semaphore-trust-center.yml\ntrust_center:\n  url: https://semaphore.io/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 audit\n  scope: service organization controls\n  period: null\n  issuer: null\n  report_access: nda\n  text: Access to our SOC 2 Type 2 report available on request under NDA.\n- framework: ISO27001\n  type: ISO 27001:2022 certification\n  scope: Information Security Management System\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Proof\
  \ of certification is available on request .\n- framework: PCI-DSS\n  type: PCI-DSS Level 1 compliance of payment service\n  scope: payments made on Semaphore via FastSpring\n  period: null\n  issuer: null\n  report_access: unstated\n  text: All payments made on Semaphore go through FastSpring , a PCI-DSS Level 1 compliant service.\n"
source_yaml_url: https://artifacts.apis.io/semaphore/compliance/semaphore-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Semaphore's own page on 2026-11-10.
synthetic: false
tags:
- CI/CD
- Continuous Integration
- Continuous Delivery
- Pipelines
- Workflows
- DevOps
- Build Automation
- Software Delivery
- Deployment
- Artifacts
- Developer Tools
---
