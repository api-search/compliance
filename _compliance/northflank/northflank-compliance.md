---
api_specs:
- filename: northflank-jobs-api-openapi.yml
  format: yaml
  label: Northflank Jobs API
  slug: northflank-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/northflank/openapi/northflank-jobs-api-openapi.yml
- filename: northflank-projects-api-openapi.yml
  format: yaml
  label: Northflank Projects API
  slug: northflank-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/northflank/openapi/northflank-projects-api-openapi.yml
- filename: northflank-services-api-openapi.yml
  format: yaml
  label: Northflank Services API
  slug: northflank-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/northflank/openapi/northflank-services-api-openapi.yml
- filename: northflank-add-ons-api-openapi.yml
  format: yaml
  label: Northflank Add Ons API
  slug: northflank-add-ons-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/northflank/openapi/northflank-add-ons-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: platform controls
    text: Northflank has achieved SOC 2 Type 2 compliance, demonstrating that the platform meets rigorous independent standards for security, availability, and confidentiality.
    type: SOC 2 Type II report
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: healthcare workloads under Enterprise contract
    text: Northflank is HIPAA compliant, meeting the standards required to handle protected health information (PHI).
    type: HIPAA compliance
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: information security management system
    text: Northflank is ISO 27001 certified, demonstrating that our information security management system meets the internationally recognised standard
    type: ISO 27001 certification
  trust_center:
    url: https://northflank.com/security
frameworks:
- HIPAA
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Northflank
provenance_date: '2026-11-10'
provider_name: Northflank
provider_slug: northflank
slug: northflank-compliance
source_date: '2026-11-10'
source_filename: northflank-compliance.yml
source_heading: Compliance
source_page: https://northflank.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Northflank\naid: northflank\nurl: https://northflank.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/northflank-trust-center.yml\ntrust_center:\n  url: https://northflank.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: platform controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Northflank has achieved SOC 2 Type 2 compliance, demonstrating that the platform meets rigorous independent\n    standards for security, availability, and confidentiality.\n- framework: HIPAA\n  type: HIPAA compliance\n  scope: healthcare workloads\
  \ under Enterprise contract\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Northflank is HIPAA compliant, meeting the standards required to handle protected health information (PHI).\n- framework: ISO27001\n  type: ISO 27001 certification\n  scope: information security management system\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Northflank is ISO 27001 certified, demonstrating that our information security management system meets the\n    internationally recognised standard\n"
source_yaml_url: https://artifacts.apis.io/northflank/compliance/northflank-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Northflank's own page on 2026-11-10.
synthetic: false
tags:
- Cloud Deployment
- Developer Experience
- Internal Developer Platform
- Platform Engineering
---
