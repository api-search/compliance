---
api_specs:
- filename: workday-extend-app-configurations-api-openapi.yml
  format: yaml
  label: Workday Extend App Configurations API
  slug: workday-extend-app-configurations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-extend/openapi/workday-extend-app-configurations-api-openapi.yml
- filename: workday-extend-app-deployments-api-openapi.yml
  format: yaml
  label: Workday Extend App Deployments API
  slug: workday-extend-app-deployments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-extend/openapi/workday-extend-app-deployments-api-openapi.yml
- filename: workday-extend-app-versions-api-openapi.yml
  format: yaml
  label: Workday Extend App Versions API
  slug: workday-extend-app-versions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-extend/openapi/workday-extend-app-versions-api-openapi.yml
- filename: workday-extend-apps-api-openapi.yml
  format: yaml
  label: Workday Extend Apps API
  slug: workday-extend-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-extend/openapi/workday-extend-apps-api-openapi.yml
- filename: workday-extend-custom-object-definitions-api-openapi.yml
  format: yaml
  label: Workday Extend Custom Object Definitions API
  slug: workday-extend-custom-object-definitions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-extend/openapi/workday-extend-custom-object-definitions-api-openapi.yml
- filename: workday-extend-custom-object-fields-api-openapi.yml
  format: yaml
  label: Workday Extend Custom Object Fields API
  slug: workday-extend-custom-object-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-extend/openapi/workday-extend-custom-object-fields-api-openapi.yml
- filename: workday-extend-custom-object-instances-api-openapi.yml
  format: yaml
  label: Workday Extend Custom Object Instances API
  slug: workday-extend-custom-object-instances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-extend/openapi/workday-extend-custom-object-instances-api-openapi.yml
- filename: workday-extend-graph-query-api-openapi.yml
  format: yaml
  label: Workday Extend Graph Query API
  slug: workday-extend-graph-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-extend/openapi/workday-extend-graph-query-api-openapi.yml
- filename: workday-extend-orchestration-executions-api-openapi.yml
  format: yaml
  label: Workday Extend Orchestration Executions API
  slug: workday-extend-orchestration-executions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-extend/openapi/workday-extend-orchestration-executions-api-openapi.yml
- filename: workday-extend-orchestration-steps-api-openapi.yml
  format: yaml
  label: Workday Extend Orchestration Steps API
  slug: workday-extend-orchestration-steps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-extend/openapi/workday-extend-orchestration-steps-api-openapi.yml
- filename: workday-extend-orchestration-triggers-api-openapi.yml
  format: yaml
  label: Workday Extend Orchestration Triggers API
  slug: workday-extend-orchestration-triggers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-extend/openapi/workday-extend-orchestration-triggers-api-openapi.yml
- filename: workday-extend-orchestrations-api-openapi.yml
  format: yaml
  label: Workday Extend Orchestrations API
  slug: workday-extend-orchestrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-extend/openapi/workday-extend-orchestrations-api-openapi.yml
- filename: workday-extend-schema-introspection-api-openapi.yml
  format: yaml
  label: Workday Extend Schema Introspection API
  slug: workday-extend-schema-introspection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-extend/openapi/workday-extend-schema-introspection-api-openapi.yml
- filename: workday-extend-wql-query-api-openapi.yml
  format: yaml
  label: Workday Extend WQL Query API
  slug: workday-extend-wql-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-extend/openapi/workday-extend-wql-query-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Workday is engineered on a defense-in-depth security architecture aligned with ISO 27001, SOC 2 Type II, and NIST Cybersecurity Framework controls.
    type: null
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Workday is engineered on a defense-in-depth security architecture aligned with ISO 27001, SOC 2 Type II, and NIST Cybersecurity Framework controls.
    type: Type II
  - framework: NIST-CSF
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Workday is engineered on a defense-in-depth security architecture aligned with ISO 27001, SOC 2 Type II, and NIST Cybersecurity Framework controls.
    type: null
  trust_center:
    url: https://security.workday.com/
frameworks:
- ISO27001
- NIST-CSF
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Workday Extend
provenance_date: '2026-11-10'
provider_name: Workday Extend
provider_slug: workday-extend
slug: workday-extend-compliance
source_date: '2026-11-10'
source_filename: workday-extend-compliance.yml
source_heading: Compliance
source_page: https://security.workday.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Workday Extend\naid: workday-extend\nurl: https://security.workday.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/workday-extend-trust-center.yml\ntrust_center:\n  url: https://security.workday.com/\nattestations:\n- framework: ISO27001\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Workday is engineered on a defense-in-depth security architecture aligned with ISO 27001, SOC 2 Type II,\n    and NIST Cybersecurity Framework controls.\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: Workday is engineered on a defense-in-depth security architecture aligned with ISO 27001, SOC 2 Type II,\n    and NIST Cybersecurity Framework controls.\n- framework: NIST-CSF\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Workday is engineered on a defense-in-depth security architecture aligned with ISO 27001, SOC 2 Type II,\n    and NIST Cybersecurity Framework controls.\n"
source_yaml_url: https://artifacts.apis.io/workday-extend/compliance/workday-extend-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Workday Extend's own page on 2026-11-10.
synthetic: false
tags:
- Automation
- Custom Applications
- Enterprise
- Extensions
- HCM
- Integration
- Orchestration
- Platform-as-a-Service
---
