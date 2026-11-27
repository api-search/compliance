---
api_specs:
- filename: alteryx-collections-api-openapi.yml
  format: yaml
  label: Alteryx Collections API
  slug: alteryx-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alteryx/openapi/alteryx-collections-api-openapi.yml
- filename: alteryx-credentials-api-openapi.yml
  format: yaml
  label: Alteryx Credentials API
  slug: alteryx-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alteryx/openapi/alteryx-credentials-api-openapi.yml
- filename: alteryx-jobs-api-openapi.yml
  format: yaml
  label: Alteryx Jobs API
  slug: alteryx-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alteryx/openapi/alteryx-jobs-api-openapi.yml
- filename: alteryx-schedules-api-openapi.yml
  format: yaml
  label: Alteryx Schedules API
  slug: alteryx-schedules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alteryx/openapi/alteryx-schedules-api-openapi.yml
- filename: alteryx-users-api-openapi.yml
  format: yaml
  label: Alteryx Users API
  slug: alteryx-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alteryx/openapi/alteryx-users-api-openapi.yml
- filename: alteryx-workflows-api-openapi.yml
  format: yaml
  label: Alteryx Workflows API
  slug: alteryx-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alteryx/openapi/alteryx-workflows-api-openapi.yml
claim_count: 10
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Alteryx Analytics Cloud Platform
    text: The ISO 27001 certified Alteryx Analytics Cloud Platform enhances security, isolates permissions, and manages risk
    type: certificate
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: It offers downloadable certificates, such as ISO 27001 and SOC 2 Type II
    type: SOC 2 Type II certificate
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: personal data relationship with users
    text: Alteryx will comply with applicable data protection law, including the GDPR and CCPA
    type: compliance commitment
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: personal data relationship with users
    text: Alteryx will comply with applicable data protection law, including the GDPR and CCPA
    type: compliance commitment
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Alteryx follows ISO 22301 guidelines for managing and maintaining plans for continuity of operations.
    type: certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: public
    scope: null
    source: https://trust.alteryx.com/
    text: ISO 27001:2022
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: null
    source: https://trust.alteryx.com/
    text: SOC 2 Type II Report
    type: Type II report
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.alteryx.com/
    text: ISO 22301:2019
    type: certification
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.alteryx.com/
    text: CSA STAR 1
    type: CSA STAR 1
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.alteryx.com/
    text: Alteryx HIPAA Report
    type: HIPAA report
  trust_center:
    url: https://www.alteryx.com/trust
frameworks:
- CCPA
- CSA-STAR
- GDPR
- HIPAA
- ISO27001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Alteryx
provenance_date: '2026-11-09'
provider_name: Alteryx
provider_slug: alteryx
slug: alteryx-compliance
source_date: '2026-11-09'
source_filename: alteryx-compliance.yml
source_heading: Compliance
source_page: https://www.alteryx.com/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Alteryx\naid: alteryx\nurl: https://www.alteryx.com/trust\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/alteryx-trust-center.yml\n  sources:\n  - https://trust.alteryx.com/\n  - https://www.alteryx.com/trust\ntrust_center:\n  url: https://www.alteryx.com/trust\nattestations:\n- framework: ISO27001\n  type: certificate\n  scope: Alteryx Analytics Cloud Platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: The ISO 27001 certified Alteryx Analytics Cloud Platform enhances security, isolates permissions, and manages\n    risk\n- framework: SOC2\n  type: SOC 2 Type II certificate\n\
  \  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: It offers downloadable certificates, such as ISO 27001 and SOC 2 Type II\n- framework: GDPR\n  type: compliance commitment\n  scope: personal data relationship with users\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Alteryx will comply with applicable data protection law, including the GDPR and CCPA\n- framework: CCPA\n  type: compliance commitment\n  scope: personal data relationship with users\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Alteryx will comply with applicable data protection law, including the GDPR and CCPA\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Alteryx follows ISO 22301 guidelines for managing and maintaining plans for continuity of operations.\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access:\
  \ public\n  text: ISO 27001:2022\n  source: https://trust.alteryx.com/\n- framework: SOC2\n  type: Type II report\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: SOC 2 Type II Report\n  source: https://trust.alteryx.com/\n- framework: other\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 22301:2019\n  source: https://trust.alteryx.com/\n- framework: CSA-STAR\n  type: CSA STAR 1\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CSA STAR 1\n  source: https://trust.alteryx.com/\n- framework: HIPAA\n  type: HIPAA report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Alteryx HIPAA Report\n  source: https://trust.alteryx.com/\n"
source_yaml_url: https://artifacts.apis.io/alteryx/compliance/alteryx-compliance.yml
stated_fields:
- attestations
summary_line: 10 quoted statements, read from Alteryx's own page on 2026-11-09.
synthetic: false
tags:
- Analytics
- Automation
- Data Engineering
- Data Preparation
- Data Science
- ETL
- Machine Learning
- Predictive Analytics
---
