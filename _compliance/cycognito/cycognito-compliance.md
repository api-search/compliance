---
api_specs:
- filename: cycognito-assets-api-openapi.yml
  format: yaml
  label: CyCognito Assets API
  slug: cycognito-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cycognito/openapi/cycognito-assets-api-openapi.yml
- filename: cycognito-audit-logs-api-openapi.yml
  format: yaml
  label: CyCognito Audit Logs API
  slug: cycognito-audit-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cycognito/openapi/cycognito-audit-logs-api-openapi.yml
- filename: cycognito-cloud-connectors-api-openapi.yml
  format: yaml
  label: CyCognito Cloud Connectors API
  slug: cycognito-cloud-connectors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cycognito/openapi/cycognito-cloud-connectors-api-openapi.yml
- filename: cycognito-export-data-api-openapi.yml
  format: yaml
  label: CyCognito Export Data API
  slug: cycognito-export-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cycognito/openapi/cycognito-export-data-api-openapi.yml
- filename: cycognito-issues-api-openapi.yml
  format: yaml
  label: CyCognito Issues API
  slug: cycognito-issues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cycognito/openapi/cycognito-issues-api-openapi.yml
- filename: cycognito-organizations-api-openapi.yml
  format: yaml
  label: CyCognito Organizations API
  slug: cycognito-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cycognito/openapi/cycognito-organizations-api-openapi.yml
- filename: cycognito-realm-api-openapi.yml
  format: yaml
  label: CyCognito Realm API
  slug: cycognito-realm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cycognito/openapi/cycognito-realm-api-openapi.yml
- filename: cycognito-reports-api-openapi.yml
  format: yaml
  label: CyCognito Reports API
  slug: cycognito-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cycognito/openapi/cycognito-reports-api-openapi.yml
- filename: cycognito-revalidation-api-openapi.yml
  format: yaml
  label: CyCognito Revalidation API
  slug: cycognito-revalidation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cycognito/openapi/cycognito-revalidation-api-openapi.yml
- filename: cycognito-scope-management-api-openapi.yml
  format: yaml
  label: CyCognito Scope Management API
  slug: cycognito-scope-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cycognito/openapi/cycognito-scope-management-api-openapi.yml
- filename: cycognito-users-api-openapi.yml
  format: yaml
  label: CyCognito Users API
  slug: cycognito-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cycognito/openapi/cycognito-users-api-openapi.yml
- filename: cycognito-verify-ips-api-openapi.yml
  format: yaml
  label: CyCognito Verify IPs API
  slug: cycognito-verify-ips-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cycognito/openapi/cycognito-verify-ips-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: security controls in place during coverage period
    text: The following is the current list of reports available to all Customers and Prospects under NDA.
    type: SOC 2 Type II report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: information security management system
    text: ISO 27001 is a rigorous certification that demonstrates CyCognito's adherence to international standards set by the International Organization for Standardization.
    type: ISO/IEC 27001 certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: personal data for account creation and platform access
    text: CyCognito collects personal data required to create an account and authorize access to our platform and processes such data in accordance with the GDPR.
    type: GDPR compliance statement
  trust_center:
    url: https://www.cycognito.com/company/trust.php
frameworks:
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: CyCognito
provenance_date: '2026-11-09'
provider_name: CyCognito
provider_slug: cycognito
slug: cycognito-compliance
source_date: '2026-11-09'
source_filename: cycognito-compliance.yml
source_heading: Compliance
source_page: https://www.cycognito.com/company/trust.php
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: CyCognito\naid: cycognito\nurl: https://www.cycognito.com/company/trust.php\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.cycognito.com/company/trust.php\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: security controls in place during coverage period\n  period: null\n  issuer: null\n  report_access: nda\n  text: The following is the current list of reports available to all Customers and Prospects under NDA.\n- framework: ISO27001\n  type: ISO/IEC 27001 certification\n  scope: information security management system\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: ISO 27001 is a rigorous certification that demonstrates CyCognito's adherence to international standards\n    set by the International Organization for Standardization.\n- framework: GDPR\n  type: GDPR compliance statement\n  scope: personal data for account creation and platform access\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CyCognito collects personal data required to create an account and authorize access to our platform and\n    processes such data in accordance with the GDPR.\n"
source_yaml_url: https://artifacts.apis.io/cycognito/compliance/cycognito-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from CyCognito's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- Attack Surface Management
- Exposure Management
- Security
- Vulnerability Management
- Cloud Security
- API Security
---
