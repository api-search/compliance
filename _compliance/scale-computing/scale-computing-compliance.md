---
api_specs:
- filename: scale-computing-api-keys-api-openapi.yml
  format: yaml
  label: Scale Computing API Keys API
  slug: scale-computing-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scale-computing/openapi/scale-computing-api-keys-api-openapi.yml
- filename: scale-computing-clusters-api-openapi.yml
  format: yaml
  label: Scale Computing Clusters API
  slug: scale-computing-clusters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scale-computing/openapi/scale-computing-clusters-api-openapi.yml
- filename: scale-computing-conditions-api-openapi.yml
  format: yaml
  label: Scale Computing Conditions API
  slug: scale-computing-conditions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scale-computing/openapi/scale-computing-conditions-api-openapi.yml
- filename: scale-computing-health-api-openapi.yml
  format: yaml
  label: Scale Computing Health API
  slug: scale-computing-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scale-computing/openapi/scale-computing-health-api-openapi.yml
- filename: scale-computing-metrics-api-openapi.yml
  format: yaml
  label: Scale Computing Metrics API
  slug: scale-computing-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scale-computing/openapi/scale-computing-metrics-api-openapi.yml
- filename: scale-computing-nodes-api-openapi.yml
  format: yaml
  label: Scale Computing Nodes API
  slug: scale-computing-nodes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scale-computing/openapi/scale-computing-nodes-api-openapi.yml
- filename: scale-computing-organization-activities-api-openapi.yml
  format: yaml
  label: Scale Computing Organization Activities API
  slug: scale-computing-organization-activities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scale-computing/openapi/scale-computing-organization-activities-api-openapi.yml
- filename: scale-computing-organization-api-openapi.yml
  format: yaml
  label: Scale Computing Organization API
  slug: scale-computing-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scale-computing/openapi/scale-computing-organization-api-openapi.yml
- filename: scale-computing-organization-salesforce-account-api-openapi.yml
  format: yaml
  label: Scale Computing Organization Salesforce Account API
  slug: scale-computing-organization-salesforce-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scale-computing/openapi/scale-computing-organization-salesforce-account-api-openapi.yml
- filename: scale-computing-organizations-api-openapi.yml
  format: yaml
  label: Scale Computing Organizations API
  slug: scale-computing-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scale-computing/openapi/scale-computing-organizations-api-openapi.yml
- filename: scale-computing-organizationuser-api-openapi.yml
  format: yaml
  label: Scale Computing Organization User API
  slug: scale-computing-organizationuser-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scale-computing/openapi/scale-computing-organizationuser-api-openapi.yml
- filename: scale-computing-salesforce-api-openapi.yml
  format: yaml
  label: Scale Computing Salesforce API
  slug: scale-computing-salesforce-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scale-computing/openapi/scale-computing-salesforce-api-openapi.yml
- filename: scale-computing-staged-clusters-api-openapi.yml
  format: yaml
  label: Scale Computing Staged Clusters API
  slug: scale-computing-staged-clusters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scale-computing/openapi/scale-computing-staged-clusters-api-openapi.yml
- filename: scale-computing-users-api-openapi.yml
  format: yaml
  label: Scale Computing Users API
  slug: scale-computing-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scale-computing/openapi/scale-computing-users-api-openapi.yml
- filename: scale-computing-vms-api-openapi.yml
  format: yaml
  label: Scale Computing Vms API
  slug: scale-computing-vms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scale-computing/openapi/scale-computing-vms-api-openapi.yml
- filename: scale-computing-organization-roles-api-openapi.yml
  format: yaml
  label: Scale Computing Organization Roles API
  slug: scale-computing-organization-roles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scale-computing/openapi/scale-computing-organization-roles-api-openapi.yml
- filename: scale-computing-organization-users-api-openapi.yml
  format: yaml
  label: Scale Computing Organization Users API
  slug: scale-computing-organization-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scale-computing/openapi/scale-computing-organization-users-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Scale Computing solutions
    text: For more details or to request a copy of our reports, please contact us .
    type: SOC 2 Type 2 report
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: on_request
    scope: Scale Computing operations for payment processing or retail compliance needs
    text: Scale Computing operates under a formal PCI DSS Attestation of Compliance (AOC)
    type: Attestation of Compliance (AOC)
  trust_center:
    url: https://www.scalecomputing.com/security
frameworks:
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Scale Computing
provenance_date: '2026-11-10'
provider_name: Scale Computing
provider_slug: scale-computing
slug: scale-computing-compliance
source_date: '2026-11-10'
source_filename: scale-computing-compliance.yml
source_heading: Compliance
source_page: https://www.scalecomputing.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Scale Computing\naid: scale-computing\nurl: https://www.scalecomputing.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/scale-computing-trust-center.yml\ntrust_center:\n  url: https://www.scalecomputing.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: Scale Computing solutions\n  period: null\n  issuer: null\n  report_access: on_request\n  text: For more details or to request a copy of our reports, please contact us .\n- framework: PCI-DSS\n  type: Attestation of Compliance (AOC)\n  scope: Scale Computing operations for payment processing or retail compliance\
  \ needs\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Scale Computing operates under a formal PCI DSS Attestation of Compliance (AOC)\n"
source_yaml_url: https://artifacts.apis.io/scale-computing/compliance/scale-computing-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Scale Computing's own page on 2026-11-10.
synthetic: false
tags:
- Edge Computing
- Hyperconverged Infrastructure
- Virtualization
- Infrastructure Management
- Fleet Management
- Virtual Machines
- Observability
- Infrastructure as Code
- Kubernetes
---
