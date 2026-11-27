---
api_specs:
- filename: arch-accounts-api-openapi.yml
  format: yaml
  label: Arch Accounts API
  slug: arch-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arch/openapi/arch-accounts-api-openapi.yml
- filename: arch-activities-api-openapi.yml
  format: yaml
  label: Arch Activities API
  slug: arch-activities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arch/openapi/arch-activities-api-openapi.yml
- filename: arch-addepar-api-openapi.yml
  format: yaml
  label: Arch Addepar API
  slug: arch-addepar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arch/openapi/arch-addepar-api-openapi.yml
- filename: arch-authentication-api-openapi.yml
  format: yaml
  label: Arch Authentication API
  slug: arch-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arch/openapi/arch-authentication-api-openapi.yml
- filename: arch-cash-flows-api-openapi.yml
  format: yaml
  label: Arch Cash Flows API
  slug: arch-cash-flows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arch/openapi/arch-cash-flows-api-openapi.yml
- filename: arch-firms-api-openapi.yml
  format: yaml
  label: Arch Firms API
  slug: arch-firms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arch/openapi/arch-firms-api-openapi.yml
- filename: arch-holdings-api-openapi.yml
  format: yaml
  label: Arch Holdings API
  slug: arch-holdings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arch/openapi/arch-holdings-api-openapi.yml
- filename: arch-investing-entities-api-openapi.yml
  format: yaml
  label: Arch Investing Entities API
  slug: arch-investing-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arch/openapi/arch-investing-entities-api-openapi.yml
- filename: arch-issuing-entities-api-openapi.yml
  format: yaml
  label: Arch Issuing Entities API
  slug: arch-issuing-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arch/openapi/arch-issuing-entities-api-openapi.yml
- filename: arch-lookthroughs-api-openapi.yml
  format: yaml
  label: Arch Lookthroughs API
  slug: arch-lookthroughs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arch/openapi/arch-lookthroughs-api-openapi.yml
- filename: arch-offerings-api-openapi.yml
  format: yaml
  label: Arch Offerings API
  slug: arch-offerings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arch/openapi/arch-offerings-api-openapi.yml
- filename: arch-tasks-api-openapi.yml
  format: yaml
  label: Arch Tasks API
  slug: arch-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arch/openapi/arch-tasks-api-openapi.yml
- filename: arch-tax-documents-api-openapi.yml
  format: yaml
  label: Arch Tax Documents API
  slug: arch-tax-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arch/openapi/arch-tax-documents-api-openapi.yml
- filename: arch-user-roles-api-openapi.yml
  format: yaml
  label: Arch User Roles API
  slug: arch-user-roles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arch/openapi/arch-user-roles-api-openapi.yml
- filename: arch-users-api-openapi.yml
  format: yaml
  label: Arch Users API
  slug: arch-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arch/openapi/arch-users-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Arch Labs
    text: Arch Labs SOC 2 Type II 10.31.25.pdf
    type: SOC 2 Type II report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Arch Labs
    text: Arch Labs GDPR 08.27.25.pdf
    type: GDPR documentation
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: EU and EEA personal data
    source: https://arch.com/legal#gdpr-compliance-policy
    text: Arch is committed to protecting the security, confidentiality, and privacy of its information resources including EU and EEA personal data in accordance with the requirements set forth in the General Data Protection Regulation (EU) 2016/679 ("GDPR", "Regulation").
    type: self-declared policy commitment
  trust_center:
    url: https://trust.arch.com/
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Arch
provenance_date: '2026-11-09'
provider_name: Arch
provider_slug: arch
slug: arch-compliance
source_date: '2026-11-09'
source_filename: arch-compliance.yml
source_heading: Compliance
source_page: https://trust.arch.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Arch\naid: arch\nurl: https://trust.arch.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/arch-trust-center.yml\n  sources:\n  - https://arch.com/legal#gdpr-compliance-policy\n  - https://trust.arch.com/\ntrust_center:\n  url: https://trust.arch.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: Arch Labs\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Arch Labs SOC 2 Type II 10.31.25.pdf\n- framework: GDPR\n  type: GDPR documentation\n  scope: Arch Labs\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Arch Labs GDPR 08.27.25.pdf\n\
  - framework: GDPR\n  type: self-declared policy commitment\n  scope: EU and EEA personal data\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Arch is committed to protecting the security, confidentiality, and privacy of its information resources\n    including EU and EEA personal data in accordance with the requirements set forth in the General Data Protection\n    Regulation (EU) 2016/679 (\"GDPR\", \"Regulation\").\n  source: https://arch.com/legal#gdpr-compliance-policy\n"
source_yaml_url: https://artifacts.apis.io/arch/compliance/arch-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Arch's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Private Markets
- Alternative Investments
- Fintech
- Wealth Management
- Investment Administration
- Portfolio Management
- Documents
---
