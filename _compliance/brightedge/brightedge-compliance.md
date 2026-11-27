---
api_specs:
- filename: brightedge-auth-api-openapi.yml
  format: yaml
  label: BrightEdge Auth API
  slug: brightedge-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brightedge/openapi/brightedge-auth-api-openapi.yml
- filename: brightedge-authorize-api-openapi.yml
  format: yaml
  label: BrightEdge Authorize API
  slug: brightedge-authorize-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brightedge/openapi/brightedge-authorize-api-openapi.yml
- filename: brightedge-feedback-api-openapi.yml
  format: yaml
  label: BrightEdge Feedback API
  slug: brightedge-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brightedge/openapi/brightedge-feedback-api-openapi.yml
- filename: brightedge-oauth-api-openapi.yml
  format: yaml
  label: BrightEdge OAuth API
  slug: brightedge-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brightedge/openapi/brightedge-oauth-api-openapi.yml
- filename: brightedge-ping-api-openapi.yml
  format: yaml
  label: BrightEdge Ping API
  slug: brightedge-ping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brightedge/openapi/brightedge-ping-api-openapi.yml
- filename: brightedge-saml-api-openapi.yml
  format: yaml
  label: BrightEdge SAML API
  slug: brightedge-saml-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brightedge/openapi/brightedge-saml-api-openapi.yml
- filename: brightedge-sso-api-openapi.yml
  format: yaml
  label: BrightEdge SSO API
  slug: brightedge-sso-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brightedge/openapi/brightedge-sso-api-openapi.yml
- filename: brightedge-token-api-openapi.yml
  format: yaml
  label: BrightEdge Token API
  slug: brightedge-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brightedge/openapi/brightedge-token-api-openapi.yml
- filename: brightedge-well-known-api-openapi.yml
  format: yaml
  label: BrightEdge .well Known API
  slug: brightedge-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brightedge/openapi/brightedge-well-known-api-openapi.yml
claim_count: 9
description: ''
doc:
  attestations:
  - framework: ISO42001
    issuer: null
    period: null
    report_access: unstated
    scope: AI management system
    text: BrightEdge is ISO/IEC 42001 certified
    type: certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: information security management system
    text: ISO 27001:2022 The ISO/IEC 27001 standard provides companies of any size
    type: certification
  - framework: ISO27701
    issuer: null
    period: null
    report_access: unstated
    scope: privacy information management system
    text: ISO 27701:2019 ISO/IEC 27701 is designed to specify requirements
    type: certification
  - framework: NIST-CSF
    issuer: null
    period: null
    report_access: unstated
    scope: information security program
    text: BrightEdge has established an information security program that conforms to CSF, and its compliance is audited regularly.
    type: framework conformance
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: NIST AI Risk Management Framework
    text: BrightEdge uses NIST AI Risk Management Framework (AI RMF)
    type: framework use
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: SOC 2 examination description
    text: SOC2 A SOC 2 examination is a report on controls at a service organization
    type: report reference
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: EU-U.S., UK Extension and Swiss-U.S. Data Privacy Framework
    text: BrightEdge is compliant to the Data Privacy Framework and audited annually for its certification.
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: personal data processing
    text: BrightEdge is GDPR compliant.
    type: compliance statement
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: internal privacy process
    text: BrightEdge’s internal process is based on privacy principles that fully comply with CCPA
    type: compliance statement
  trust_center:
    url: https://www.brightedge.com/trust
frameworks:
- CCPA
- GDPR
- ISO27001
- ISO27701
- ISO42001
- NIST-CSF
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: BrightEdge
provenance_date: '2026-11-09'
provider_name: BrightEdge
provider_slug: brightedge
slug: brightedge-compliance
source_date: '2026-11-09'
source_filename: brightedge-compliance.yml
source_heading: Compliance
source_page: https://www.brightedge.com/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: BrightEdge\naid: brightedge\nurl: https://www.brightedge.com/trust\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.brightedge.com/trust\nattestations:\n- framework: ISO42001\n  type: certification\n  scope: AI management system\n  period: null\n  issuer: null\n  report_access: unstated\n  text: BrightEdge is ISO/IEC 42001 certified\n- framework: ISO27001\n  type: certification\n  scope: information security management system\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022 The ISO/IEC 27001 standard provides companies of any size\n- framework: ISO27701\n  type: certification\n\
  \  scope: privacy information management system\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27701:2019 ISO/IEC 27701 is designed to specify requirements\n- framework: NIST-CSF\n  type: framework conformance\n  scope: information security program\n  period: null\n  issuer: null\n  report_access: unstated\n  text: BrightEdge has established an information security program that conforms to CSF, and its compliance is audited\n    regularly.\n- framework: other\n  type: framework use\n  scope: NIST AI Risk Management Framework\n  period: null\n  issuer: null\n  report_access: unstated\n  text: BrightEdge uses NIST AI Risk Management Framework (AI RMF)\n- framework: SOC2\n  type: report reference\n  scope: SOC 2 examination description\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC2 A SOC 2 examination is a report on controls at a service organization\n- framework: other\n  type: certification\n  scope: EU-U.S., UK Extension and Swiss-U.S.\
  \ Data Privacy Framework\n  period: null\n  issuer: null\n  report_access: unstated\n  text: BrightEdge is compliant to the Data Privacy Framework and audited annually for its certification.\n- framework: GDPR\n  type: compliance statement\n  scope: personal data processing\n  period: null\n  issuer: null\n  report_access: unstated\n  text: BrightEdge is GDPR compliant.\n- framework: CCPA\n  type: compliance statement\n  scope: internal privacy process\n  period: null\n  issuer: null\n  report_access: unstated\n  text: BrightEdge’s internal process is based on privacy principles that fully comply with CCPA\n"
source_yaml_url: https://artifacts.apis.io/brightedge/compliance/brightedge-compliance.yml
stated_fields:
- attestations
summary_line: 9 quoted statements, read from BrightEdge's own page on 2026-11-09.
synthetic: false
tags:
- Company
- SEO
- Search
- Content
- Marketing
- Analytics
- Keywords
- Enterprise
- AI Search
---
