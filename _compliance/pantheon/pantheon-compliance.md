---
api_specs:
- filename: openapi.yml
  format: yaml
  label: Pantheon REST API
  slug: pantheon-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pantheon/openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Security and Availability Trust Services Criteria
    text: Our SOC 2 Type 2 compliance covers the Security and Availability Trust Services Criteria.
    type: SOC 2 Type 2
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Pantheon complies with all applicable data privacy laws including GDPR.
    type: regulatory compliance
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Pantheon's security policies and infrastructure allow customers to be FERPA compliant.
    type: FERPA compliance (customers can be FERPA compliant)
  trust_center:
    url: https://pantheon.io/security
frameworks:
- GDPR
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Pantheon
provenance_date: '2026-11-10'
provider_name: Pantheon
provider_slug: pantheon
slug: pantheon-compliance
source_date: '2026-11-10'
source_filename: pantheon-compliance.yml
source_heading: Compliance
source_page: https://pantheon.io/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Pantheon\naid: pantheon\nurl: https://pantheon.io/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/pantheon-trust-center.yml\ntrust_center:\n  url: https://pantheon.io/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2\n  scope: Security and Availability Trust Services Criteria\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our SOC 2 Type 2 compliance covers the Security and Availability Trust Services Criteria.\n- framework: GDPR\n  type: regulatory compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Pantheon complies\
  \ with all applicable data privacy laws including GDPR.\n- framework: other\n  type: FERPA compliance (customers can be FERPA compliant)\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Pantheon's security policies and infrastructure allow customers to be FERPA compliant.\n"
source_yaml_url: https://artifacts.apis.io/pantheon/compliance/pantheon-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Pantheon's own page on 2026-11-10.
synthetic: false
tags:
- WebOps
- WordPress
- Drupal
- CMS
- Hosting
- CDN
- DevOps
- Deployment
- Sites
- Environment
---
