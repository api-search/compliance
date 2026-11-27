---
api_specs:
- filename: sense-talent-labs-appointment-api-openapi.yml
  format: yaml
  label: Sense Talent Labs Appointment API
  slug: sense-talent-labs-appointment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sense-talent-labs/openapi/sense-talent-labs-appointment-api-openapi.yml
- filename: sense-talent-labs-authentication-api-openapi.yml
  format: yaml
  label: Sense Talent Labs Authentication API
  slug: sense-talent-labs-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sense-talent-labs/openapi/sense-talent-labs-authentication-api-openapi.yml
- filename: sense-talent-labs-candidate-api-openapi.yml
  format: yaml
  label: Sense Talent Labs Candidate API
  slug: sense-talent-labs-candidate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sense-talent-labs/openapi/sense-talent-labs-candidate-api-openapi.yml
- filename: sense-talent-labs-certification-api-openapi.yml
  format: yaml
  label: Sense Talent Labs Certification API
  slug: sense-talent-labs-certification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sense-talent-labs/openapi/sense-talent-labs-certification-api-openapi.yml
- filename: sense-talent-labs-company-api-openapi.yml
  format: yaml
  label: Sense Talent Labs Company API
  slug: sense-talent-labs-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sense-talent-labs/openapi/sense-talent-labs-company-api-openapi.yml
- filename: sense-talent-labs-internaluser-api-openapi.yml
  format: yaml
  label: Sense Talent Labs Internal User API
  slug: sense-talent-labs-internaluser-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sense-talent-labs/openapi/sense-talent-labs-internaluser-api-openapi.yml
- filename: sense-talent-labs-joborder-api-openapi.yml
  format: yaml
  label: Sense Talent Labs Job Order API
  slug: sense-talent-labs-joborder-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sense-talent-labs/openapi/sense-talent-labs-joborder-api-openapi.yml
- filename: sense-talent-labs-lead-api-openapi.yml
  format: yaml
  label: Sense Talent Labs Lead API
  slug: sense-talent-labs-lead-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sense-talent-labs/openapi/sense-talent-labs-lead-api-openapi.yml
- filename: sense-talent-labs-placement-api-openapi.yml
  format: yaml
  label: Sense Talent Labs Placement API
  slug: sense-talent-labs-placement-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sense-talent-labs/openapi/sense-talent-labs-placement-api-openapi.yml
- filename: sense-talent-labs-submission-api-openapi.yml
  format: yaml
  label: Sense Talent Labs Submission API
  slug: sense-talent-labs-submission-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sense-talent-labs/openapi/sense-talent-labs-submission-api-openapi.yml
- filename: sense-talent-labs-client-contact-api-openapi.yml
  format: yaml
  label: Sense Talent Labs Client Contact API
  slug: sense-talent-labs-client-contact-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sense-talent-labs/openapi/sense-talent-labs-client-contact-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: other
    issuer: Warden AI
    period: null
    report_access: unstated
    scope: Sense Candidate Matching
    text: 'NYC Bias Audit Regulation: New York City Local Law 144'
    type: Bias audit (NYC Local Law 144)
  - framework: other
    issuer: Warden AI
    period: null
    report_access: unstated
    scope: Sense Candidate Matching
    text: 'EU AI Act Bias Audit Regulation: EU AI Act (Regulation 2024/1689)'
    type: Bias audit (EU AI Act)
  - framework: other
    issuer: Warden AI
    period: null
    report_access: unstated
    scope: Sense Candidate Matching
    text: 'Colorado SB 26-189 Bias Audit Regulation: Colorado SB 26-189'
    type: Bias audit (Colorado SB 26-189)
  - framework: other
    issuer: Warden AI
    period: null
    report_access: unstated
    scope: Sense Candidate Matching
    text: 'California FEHA Bias Audit Regulation: California FEHA'
    type: Bias audit (California FEHA)
  - framework: other
    issuer: Amazon Web Services
    period: null
    report_access: unstated
    scope: Infrastructure hosted on Amazon Web Services (AWS) cloud
    source: https://www.sensehq.com/security
    text: Our services are hosted on Amazon Web Services (AWS) cloud, compliant with PCI DSS, SOC 1/2/3, ITAR, EU-US, and NIST.
    type: hosting provider compliance statement
  trust_center:
    url: https://trust.warden-ai.com/sense/candidate-matching
frameworks:
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Sense Talent Labs
provenance_date: '2026-11-10'
provider_name: Sense Talent Labs
provider_slug: sense-talent-labs
slug: sense-talent-labs-compliance
source_date: '2026-11-10'
source_filename: sense-talent-labs-compliance.yml
source_heading: Compliance
source_page: https://trust.warden-ai.com/sense/candidate-matching
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Sense Talent Labs\naid: sense-talent-labs\nurl: https://trust.warden-ai.com/sense/candidate-matching\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/sense-talent-labs-trust-center.yml\n  sources:\n  - https://trust.warden-ai.com/sense/candidate-matching\n  - https://www.sensehq.com/security\ntrust_center:\n  url: https://trust.warden-ai.com/sense/candidate-matching\nattestations:\n- framework: other\n  type: Bias audit (NYC Local Law 144)\n  scope: Sense Candidate Matching\n  period: null\n  issuer: Warden AI\n  report_access: unstated\n  text: 'NYC Bias Audit Regulation: New York City Local Law 144'\n\
  - framework: other\n  type: Bias audit (EU AI Act)\n  scope: Sense Candidate Matching\n  period: null\n  issuer: Warden AI\n  report_access: unstated\n  text: 'EU AI Act Bias Audit Regulation: EU AI Act (Regulation 2024/1689)'\n- framework: other\n  type: Bias audit (Colorado SB 26-189)\n  scope: Sense Candidate Matching\n  period: null\n  issuer: Warden AI\n  report_access: unstated\n  text: 'Colorado SB 26-189 Bias Audit Regulation: Colorado SB 26-189'\n- framework: other\n  type: Bias audit (California FEHA)\n  scope: Sense Candidate Matching\n  period: null\n  issuer: Warden AI\n  report_access: unstated\n  text: 'California FEHA Bias Audit Regulation: California FEHA'\n- framework: other\n  type: hosting provider compliance statement\n  scope: Infrastructure hosted on Amazon Web Services (AWS) cloud\n  period: null\n  issuer: Amazon Web Services\n  report_access: unstated\n  text: Our services are hosted on Amazon Web Services (AWS) cloud, compliant with PCI DSS, SOC 1/2/3, ITAR,\
  \ EU-US,\n    and NIST.\n  source: https://www.sensehq.com/security\n"
source_yaml_url: https://artifacts.apis.io/sense-talent-labs/compliance/sense-talent-labs-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Sense Talent Labs's own page on 2026-11-10.
synthetic: false
tags:
- Human Resources
- Recruiting
- Talent Acquisition
- Staffing
- Applicant Tracking
- Candidate Engagement
- Recruiting Automation
- Talent CRM
- Messaging
- Interview Scheduling
- Artificial Intelligence
- Software-as-a-Service
---
