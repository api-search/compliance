---
api_specs:
- filename: accredible-analytics-api-openapi.yml
  format: yaml
  label: Accredible Analytics API
  slug: accredible-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/accredible/openapi/accredible-analytics-api-openapi.yml
- filename: accredible-credentials-api-openapi.yml
  format: yaml
  label: Accredible Credentials API
  slug: accredible-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/accredible/openapi/accredible-credentials-api-openapi.yml
- filename: accredible-departments-api-openapi.yml
  format: yaml
  label: Accredible Departments API
  slug: accredible-departments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/accredible/openapi/accredible-departments-api-openapi.yml
- filename: accredible-designs-api-openapi.yml
  format: yaml
  label: Accredible Designs API
  slug: accredible-designs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/accredible/openapi/accredible-designs-api-openapi.yml
- filename: accredible-evidence-items-api-openapi.yml
  format: yaml
  label: Accredible Evidence Items API
  slug: accredible-evidence-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/accredible/openapi/accredible-evidence-items-api-openapi.yml
- filename: accredible-groups-api-openapi.yml
  format: yaml
  label: Accredible Groups API
  slug: accredible-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/accredible/openapi/accredible-groups-api-openapi.yml
- filename: accredible-references-api-openapi.yml
  format: yaml
  label: Accredible References API
  slug: accredible-references-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/accredible/openapi/accredible-references-api-openapi.yml
- filename: accredible-sso-api-openapi.yml
  format: yaml
  label: Accredible SSO API
  slug: accredible-sso-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/accredible/openapi/accredible-sso-api-openapi.yml
- filename: accredible-team-members-api-openapi.yml
  format: yaml
  label: Accredible Team Members API
  slug: accredible-team-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/accredible/openapi/accredible-team-members-api-openapi.yml
- filename: accredible-attributes-api-openapi.yml
  format: yaml
  label: Accredible Attributes API
  slug: accredible-attributes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/accredible/openapi/accredible-attributes-api-openapi.yml
- filename: accredible-collections-api-openapi.yml
  format: yaml
  label: Accredible Collections API
  slug: accredible-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/accredible/openapi/accredible-collections-api-openapi.yml
- filename: accredible-data-exports-api-openapi.yml
  format: yaml
  label: Accredible Data Exports API
  slug: accredible-data-exports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/accredible/openapi/accredible-data-exports-api-openapi.yml
- filename: accredible-issuers-api-openapi.yml
  format: yaml
  label: Accredible Issuers API
  slug: accredible-issuers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/accredible/openapi/accredible-issuers-api-openapi.yml
- filename: accredible-skills-frameworks-api-openapi.yml
  format: yaml
  label: Accredible Skills Frameworks API
  slug: accredible-skills-frameworks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/accredible/openapi/accredible-skills-frameworks-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Accredible platform
    text: Accredible adheres to the highest security standards and regulatory requirements, including GDPR, SOC 2 Type II, and more.
    type: SOC 2 Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Accredible platform
    text: Accredible adheres to the highest security standards and regulatory requirements, including GDPR, SOC 2 Type II, and more.
    type: regulatory adherence
  trust_center:
    url: https://www.accredible.com/features
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Accredible
provenance_date: '2026-11-09'
provider_name: Accredible
provider_slug: accredible
slug: accredible-compliance
source_date: '2026-11-09'
source_filename: accredible-compliance.yml
source_heading: Compliance
source_page: https://www.accredible.com/features
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Accredible\naid: accredible\nurl: https://www.accredible.com/features\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/accredible-trust-center.yml\ntrust_center:\n  url: https://www.accredible.com/features\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: Accredible platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Accredible adheres to the highest security standards and regulatory requirements, including GDPR, SOC 2\n    Type II, and more.\n- framework: GDPR\n  type: regulatory adherence\n  scope: Accredible platform\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: Accredible adheres to the highest security standards and regulatory requirements, including GDPR, SOC 2\n    Type II, and more.\n"
source_yaml_url: https://artifacts.apis.io/accredible/compliance/accredible-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Accredible's own page on 2026-11-09.
synthetic: false
tags:
- Digital Credentials
- Certificates
- Badges
- Open Badges
- Credentialing
- Verification
- Digital Badges
---
