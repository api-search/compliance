---
api_specs:
- filename: teachable-courses-api-openapi.yml
  format: yaml
  label: Teachable Courses API
  slug: teachable-courses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teachable/openapi/teachable-courses-api-openapi.yml
- filename: teachable-enrollments-api-openapi.yml
  format: yaml
  label: Teachable Enrollments API
  slug: teachable-enrollments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teachable/openapi/teachable-enrollments-api-openapi.yml
- filename: teachable-lectures-api-openapi.yml
  format: yaml
  label: Teachable Lectures API
  slug: teachable-lectures-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teachable/openapi/teachable-lectures-api-openapi.yml
- filename: teachable-quizzes-api-openapi.yml
  format: yaml
  label: Teachable Quizzes API
  slug: teachable-quizzes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teachable/openapi/teachable-quizzes-api-openapi.yml
- filename: teachable-transactions-api-openapi.yml
  format: yaml
  label: Teachable Transactions API
  slug: teachable-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teachable/openapi/teachable-transactions-api-openapi.yml
- filename: teachable-users-api-openapi.yml
  format: yaml
  label: Teachable Users API
  slug: teachable-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teachable/openapi/teachable-users-api-openapi.yml
- filename: teachable-videos-api-openapi.yml
  format: yaml
  label: Teachable Videos API
  slug: teachable-videos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teachable/openapi/teachable-videos-api-openapi.yml
- filename: teachable-webhooks-api-openapi.yml
  format: yaml
  label: Teachable Webhooks API
  slug: teachable-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teachable/openapi/teachable-webhooks-api-openapi.yml
- filename: teachable-current-user-api-openapi.yml
  format: yaml
  label: Teachable Current User API
  slug: teachable-current-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teachable/openapi/teachable-current-user-api-openapi.yml
- filename: teachable-pricing-plans-api-openapi.yml
  format: yaml
  label: Teachable Pricing Plans API
  slug: teachable-pricing-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teachable/openapi/teachable-pricing-plans-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: A-lign
    period: null
    report_access: nda
    scope: systems, processes, and controls supporting the Teachable platform
    text: We provide our SOC 2 report under NDA.
    type: Type II accreditation
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: all our gateways
    text: All our gateways are PCI SAQ A Level 3 compliant.
    type: SAQ A Level 3 compliance for gateways
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: platform
    text: Teachable complies with applicable data privacy laws such as GDPR and CCPA.
    type: compliance with applicable data privacy law
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: platform
    text: Teachable complies with applicable data privacy laws such as GDPR and CCPA.
    type: compliance with applicable data privacy law
  trust_center:
    url: https://www.teachable.com/security
frameworks:
- CCPA
- GDPR
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Teachable
provenance_date: '2026-11-10'
provider_name: Teachable
provider_slug: teachable
slug: teachable-compliance
source_date: '2026-11-10'
source_filename: teachable-compliance.yml
source_heading: Compliance
source_page: https://www.teachable.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Teachable\naid: teachable\nurl: https://www.teachable.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/teachable-trust-center.yml\ntrust_center:\n  url: https://www.teachable.com/security\nattestations:\n- framework: SOC2\n  type: Type II accreditation\n  scope: systems, processes, and controls supporting the Teachable platform\n  period: null\n  issuer: A-lign\n  report_access: nda\n  text: We provide our SOC 2 report under NDA.\n- framework: PCI-DSS\n  type: SAQ A Level 3 compliance for gateways\n  scope: all our gateways\n  period: null\n  issuer: null\n  report_access: unstated\n  text:\
  \ All our gateways are PCI SAQ A Level 3 compliant.\n- framework: GDPR\n  type: compliance with applicable data privacy law\n  scope: platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Teachable complies with applicable data privacy laws such as GDPR and CCPA.\n- framework: CCPA\n  type: compliance with applicable data privacy law\n  scope: platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Teachable complies with applicable data privacy laws such as GDPR and CCPA.\n"
source_yaml_url: https://artifacts.apis.io/teachable/compliance/teachable-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Teachable's own page on 2026-11-10.
synthetic: false
tags:
- Online Courses
- E-Learning
- Education
- Course Management
- Enrollment
- Coaching
- Membership
- Transaction
- Creator Economy
---
