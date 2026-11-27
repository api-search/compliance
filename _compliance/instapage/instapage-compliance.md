---
api_specs:
- filename: instapage-workspaces-api-openapi.yml
  format: yaml
  label: Instapage Workspaces API
  slug: instapage-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/instapage/openapi/instapage-workspaces-api-openapi.yml
- filename: instapage-analytics-api-openapi.yml
  format: yaml
  label: Instapage Analytics API
  slug: instapage-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/instapage/openapi/instapage-analytics-api-openapi.yml
- filename: instapage-assets-api-openapi.yml
  format: yaml
  label: Instapage Assets API
  slug: instapage-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/instapage/openapi/instapage-assets-api-openapi.yml
- filename: instapage-collections-api-openapi.yml
  format: yaml
  label: Instapage Collections API
  slug: instapage-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/instapage/openapi/instapage-collections-api-openapi.yml
- filename: instapage-domains-api-openapi.yml
  format: yaml
  label: Instapage Domains API
  slug: instapage-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/instapage/openapi/instapage-domains-api-openapi.yml
- filename: instapage-experiments-api-openapi.yml
  format: yaml
  label: Instapage Experiments API
  slug: instapage-experiments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/instapage/openapi/instapage-experiments-api-openapi.yml
- filename: instapage-form-submissions-api-openapi.yml
  format: yaml
  label: Instapage Form Submissions API
  slug: instapage-form-submissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/instapage/openapi/instapage-form-submissions-api-openapi.yml
- filename: instapage-groups-api-openapi.yml
  format: yaml
  label: Instapage Groups API
  slug: instapage-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/instapage/openapi/instapage-groups-api-openapi.yml
- filename: instapage-pages-api-openapi.yml
  format: yaml
  label: Instapage Pages API
  slug: instapage-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/instapage/openapi/instapage-pages-api-openapi.yml
- filename: instapage-personalizations-api-openapi.yml
  format: yaml
  label: Instapage Personalizations API
  slug: instapage-personalizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/instapage/openapi/instapage-personalizations-api-openapi.yml
- filename: instapage-team-members-api-openapi.yml
  format: yaml
  label: Instapage Team Members API
  slug: instapage-team-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/instapage/openapi/instapage-team-members-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: security, availability, processing integrity, confidentiality, and privacy of customer data
    text: Instapage has undergone two types of SOC 2 audits and received certification showing that Intspage has the right security systems that ensure the security, availability, processing integrity, confidentiality, and privacy of customer data.
    type: SOC 2 Type I and Type II audits
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: EU customers' shared data
    text: Instapage complies with GDPR data privacy and security standards giving EU customers more control over their shared data.
    type: compliance
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: information security policies
    text: All our policies align with ISO 27001/2 and NIST 800-53 frameworks, reviewed yearly or after significant changes.
    type: policy alignment
  - framework: NIST-800-53
    issuer: null
    period: null
    report_access: unstated
    scope: information security policies
    text: All our policies align with ISO 27001/2 and NIST 800-53 frameworks, reviewed yearly or after significant changes.
    type: policy alignment
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: California residents' personal data
    text: Instapage follows the California Consumer Privacy Act (CCPA), now updated by the California Privacy Rights Act (CPRA), to enhance the protection of personal data and privacy for California residents.
    type: compliance
  trust_center:
    url: https://instapage.com/security
frameworks:
- CCPA
- GDPR
- ISO27001
- NIST-800-53
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Instapage
provenance_date: '2026-11-09'
provider_name: Instapage
provider_slug: instapage
slug: instapage-compliance
source_date: '2026-11-09'
source_filename: instapage-compliance.yml
source_heading: Compliance
source_page: https://instapage.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Instapage\naid: instapage\nurl: https://instapage.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://instapage.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type I and Type II audits\n  scope: security, availability, processing integrity, confidentiality, and privacy of customer data\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Instapage has undergone two types of SOC 2 audits and received certification showing that Intspage has the\n    right security systems that ensure the security, availability, processing integrity, confidentiality, and privacy\n\
  \    of customer data.\n- framework: GDPR\n  type: compliance\n  scope: EU customers' shared data\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Instapage complies with GDPR data privacy and security standards giving EU customers more control over their\n    shared data.\n- framework: ISO27001\n  type: policy alignment\n  scope: information security policies\n  period: null\n  issuer: null\n  report_access: unstated\n  text: All our policies align with ISO 27001/2 and NIST 800-53 frameworks, reviewed yearly or after significant\n    changes.\n- framework: NIST-800-53\n  type: policy alignment\n  scope: information security policies\n  period: null\n  issuer: null\n  report_access: unstated\n  text: All our policies align with ISO 27001/2 and NIST 800-53 frameworks, reviewed yearly or after significant\n    changes.\n- framework: CCPA\n  type: compliance\n  scope: California residents' personal data\n  period: null\n  issuer: null\n  report_access: unstated\n  text:\
  \ Instapage follows the California Consumer Privacy Act (CCPA), now updated by the California Privacy Rights\n    Act (CPRA), to enhance the protection of personal data and privacy for California residents.\n"
source_yaml_url: https://artifacts.apis.io/instapage/compliance/instapage-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Instapage's own page on 2026-11-09.
synthetic: false
tags:
- Landing Pages
- Conversion Optimization
- Marketing
- A/B Testing
- Post-Click Optimization
- Lead Generation
---
