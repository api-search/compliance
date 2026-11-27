---
api_specs:
- filename: bynn-com-age-verification-api-openapi.yml
  format: yaml
  label: Bynn Intelligence Age Verification API
  slug: bynn-com-age-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bynn-com/openapi/bynn-com-age-verification-api-openapi.yml
- filename: bynn-com-aml-api-openapi.yml
  format: yaml
  label: Bynn Intelligence Aml API
  slug: bynn-com-aml-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bynn-com/openapi/bynn-com-aml-api-openapi.yml
- filename: bynn-com-api-keys-api-openapi.yml
  format: yaml
  label: Bynn Intelligence API Keys API
  slug: bynn-com-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bynn-com/openapi/bynn-com-api-keys-api-openapi.yml
- filename: bynn-com-autodoc-api-openapi.yml
  format: yaml
  label: Bynn Intelligence Autodoc API
  slug: bynn-com-autodoc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bynn-com/openapi/bynn-com-autodoc-api-openapi.yml
- filename: bynn-com-documents-api-openapi.yml
  format: yaml
  label: Bynn Intelligence Documents API
  slug: bynn-com-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bynn-com/openapi/bynn-com-documents-api-openapi.yml
- filename: bynn-com-dossiers-api-openapi.yml
  format: yaml
  label: Bynn Intelligence Dossiers API
  slug: bynn-com-dossiers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bynn-com/openapi/bynn-com-dossiers-api-openapi.yml
- filename: bynn-com-face-collections-api-openapi.yml
  format: yaml
  label: Bynn Intelligence Face Collections API
  slug: bynn-com-face-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bynn-com/openapi/bynn-com-face-collections-api-openapi.yml
- filename: bynn-com-face-enrollment-api-openapi.yml
  format: yaml
  label: Bynn Intelligence Face Enrollment API
  slug: bynn-com-face-enrollment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bynn-com/openapi/bynn-com-face-enrollment-api-openapi.yml
- filename: bynn-com-face-search-api-openapi.yml
  format: yaml
  label: Bynn Intelligence Face Search API
  slug: bynn-com-face-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bynn-com/openapi/bynn-com-face-search-api-openapi.yml
- filename: bynn-com-moderation-api-openapi.yml
  format: yaml
  label: Bynn Intelligence Moderation API
  slug: bynn-com-moderation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bynn-com/openapi/bynn-com-moderation-api-openapi.yml
- filename: bynn-com-nfc-api-openapi.yml
  format: yaml
  label: Bynn Intelligence Nfc API
  slug: bynn-com-nfc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bynn-com/openapi/bynn-com-nfc-api-openapi.yml
- filename: bynn-com-sessions-api-openapi.yml
  format: yaml
  label: Bynn Intelligence Sessions API
  slug: bynn-com-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bynn-com/openapi/bynn-com-sessions-api-openapi.yml
claim_count: 7
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: Information security management
    text: ISO 27001:2022 Information security management, certified
    type: Certification (ISO/IEC 27001:2022)
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: SOC 2 report, monitored continuously
    type: SOC 2 report
  - framework: ISO42001
    issuer: null
    period: null
    report_access: unstated
    scope: AI management controls
    text: Standard AI management system, controls mapped to ISO/IEC 42001:2023
    type: Controls mapped to standard
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Customer personal data
    text: Processor terms under Article 28 in the Data Processing Addendum, part of every account and engagement
    type: Processor terms (Article 28) in DPA
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Service-provider terms in the Data Processing Addendum
    type: Service-provider terms in DPA
  - framework: HIPAA
    issuer: null
    period: null
    report_access: on_request
    scope: Protected health information
    text: Protected health information only under a signed Business Associate Agreement, available on request
    type: Business Associate Agreement available
  - framework: NIST-CSF
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Controls mapped to the NIST CSF
    type: Controls mapped to framework
  trust_center:
    url: https://bynn.com/company/trust
frameworks:
- CCPA
- GDPR
- HIPAA
- ISO27001
- ISO42001
- NIST-CSF
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Bynn Intelligence
provenance_date: '2026-11-09'
provider_name: Bynn Intelligence
provider_slug: bynn-com
slug: bynn-com-compliance
source_date: '2026-11-09'
source_filename: bynn-com-compliance.yml
source_heading: Compliance
source_page: https://bynn.com/company/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Bynn Intelligence\naid: bynn-com\nurl: https://bynn.com/company/trust\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://bynn.com/company/trust\nattestations:\n- framework: ISO27001\n  type: Certification (ISO/IEC 27001:2022)\n  scope: Information security management\n  period: null\n  issuer: null\n  report_access: on_request\n  text: ISO 27001:2022 Information security management, certified\n- framework: SOC2\n  type: SOC 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 2 report, monitored continuously\n- framework: ISO42001\n  type: Controls mapped to\
  \ standard\n  scope: AI management controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Standard AI management system, controls mapped to ISO/IEC 42001:2023\n- framework: GDPR\n  type: Processor terms (Article 28) in DPA\n  scope: Customer personal data\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Processor terms under Article 28 in the Data Processing Addendum, part of every account and engagement\n- framework: CCPA\n  type: Service-provider terms in DPA\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Service-provider terms in the Data Processing Addendum\n- framework: HIPAA\n  type: Business Associate Agreement available\n  scope: Protected health information\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Protected health information only under a signed Business Associate Agreement, available on request\n- framework: NIST-CSF\n  type: Controls mapped to framework\n  scope: null\n\
  \  period: null\n  issuer: null\n  report_access: unstated\n  text: Controls mapped to the NIST CSF\n"
source_yaml_url: https://artifacts.apis.io/bynn-com/compliance/bynn-com-compliance.yml
stated_fields:
- attestations
summary_line: 7 quoted statements, read from Bynn Intelligence's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Enterprise
- Frontier Research
- Identity Verification
- Digital Trust
---
