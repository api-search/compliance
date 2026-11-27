---
api_specs:
- filename: upguard-breaches-api-openapi.yml
  format: yaml
  label: UpGuard Breaches API
  slug: upguard-breaches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upguard/openapi/upguard-breaches-api-openapi.yml
- filename: upguard-bulk-api-openapi.yml
  format: yaml
  label: UpGuard Bulk API
  slug: upguard-bulk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upguard/openapi/upguard-bulk-api-openapi.yml
- filename: upguard-dataleaks-api-openapi.yml
  format: yaml
  label: UpGuard Dataleaks API
  slug: upguard-dataleaks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upguard/openapi/upguard-dataleaks-api-openapi.yml
- filename: upguard-domains-api-openapi.yml
  format: yaml
  label: UpGuard Domains API
  slug: upguard-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upguard/openapi/upguard-domains-api-openapi.yml
- filename: upguard-labels-api-openapi.yml
  format: yaml
  label: UpGuard Labels API
  slug: upguard-labels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upguard/openapi/upguard-labels-api-openapi.yml
- filename: upguard-notifications-api-openapi.yml
  format: yaml
  label: UpGuard Notifications API
  slug: upguard-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upguard/openapi/upguard-notifications-api-openapi.yml
- filename: upguard-organisation-api-openapi.yml
  format: yaml
  label: UpGuard Organisation API
  slug: upguard-organisation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upguard/openapi/upguard-organisation-api-openapi.yml
- filename: upguard-reports-api-openapi.yml
  format: yaml
  label: UpGuard Reports API
  slug: upguard-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upguard/openapi/upguard-reports-api-openapi.yml
- filename: upguard-risks-api-openapi.yml
  format: yaml
  label: UpGuard Risks API
  slug: upguard-risks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upguard/openapi/upguard-risks-api-openapi.yml
- filename: upguard-subsidiaries-api-openapi.yml
  format: yaml
  label: UpGuard Subsidiaries API
  slug: upguard-subsidiaries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upguard/openapi/upguard-subsidiaries-api-openapi.yml
- filename: upguard-threatmonitoring-api-openapi.yml
  format: yaml
  label: UpGuard Threatmonitoring API
  slug: upguard-threatmonitoring-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upguard/openapi/upguard-threatmonitoring-api-openapi.yml
- filename: upguard-trust-exchange-api-openapi.yml
  format: yaml
  label: UpGuard Trust Exchange API
  slug: upguard-trust-exchange-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upguard/openapi/upguard-trust-exchange-api-openapi.yml
- filename: upguard-typosquat-api-openapi.yml
  format: yaml
  label: UpGuard Typosquat API
  slug: upguard-typosquat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upguard/openapi/upguard-typosquat-api-openapi.yml
- filename: upguard-userrisk-api-openapi.yml
  format: yaml
  label: UpGuard Userrisk API
  slug: upguard-userrisk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upguard/openapi/upguard-userrisk-api-openapi.yml
- filename: upguard-vendors-api-openapi.yml
  format: yaml
  label: UpGuard Vendors API
  slug: upguard-vendors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upguard/openapi/upguard-vendors-api-openapi.yml
- filename: upguard-vulnerabilities-api-openapi.yml
  format: yaml
  label: UpGuard Vulnerabilities API
  slug: upguard-vulnerabilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upguard/openapi/upguard-vulnerabilities-api-openapi.yml
- filename: upguard-webhooks-api-openapi.yml
  format: yaml
  label: UpGuard Webhooks API
  slug: upguard-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upguard/openapi/upguard-webhooks-api-openapi.yml
- filename: upguard-ips-api-openapi.yml
  format: yaml
  label: UpGuard Ips API
  slug: upguard-ips-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upguard/openapi/upguard-ips-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: annual
    report_access: on_request
    scope: UpGuard
    text: UpGuard is SOC 2, Type II compliant, and undergoes attestation on an annual basis.
    type: SOC 2 Type II attestation
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: UpGuard security program
    text: The UpGuard security program is maintained in alignment with ISO/IEC 27001 to systematically identify, assess, and manage information security risks.
    type: alignment
  trust_center:
    url: https://www.upguard.com/security
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: UpGuard
provenance_date: '2026-11-10'
provider_name: UpGuard
provider_slug: upguard
slug: upguard-compliance
source_date: '2026-11-10'
source_filename: upguard-compliance.yml
source_heading: Compliance
source_page: https://www.upguard.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: UpGuard\naid: upguard\nurl: https://www.upguard.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.upguard.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II attestation\n  scope: UpGuard\n  period: annual\n  issuer: null\n  report_access: on_request\n  text: UpGuard is SOC 2, Type II compliant, and undergoes attestation on an annual basis.\n- framework: ISO27001\n  type: alignment\n  scope: UpGuard security program\n  period: null\n  issuer: null\n  report_access: unstated\n  text: The UpGuard security program is maintained in alignment with ISO/IEC 27001 to systematically\
  \ identify, assess,\n    and manage information security risks.\n"
source_yaml_url: https://artifacts.apis.io/upguard/compliance/upguard-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from UpGuard's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cybersecurity
- Third-Party Risk Management
- Attack Surface Management
- Vendor Risk
- Security Ratings
- Data Leaks
- Threat Intelligence
- Risk Management
---
