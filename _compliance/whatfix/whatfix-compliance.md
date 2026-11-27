---
api_specs:
- filename: whatfix-analytics-api-openapi.yml
  format: yaml
  label: Whatfix Analytics API
  slug: whatfix-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whatfix/openapi/whatfix-analytics-api-openapi.yml
- filename: whatfix-content-api-openapi.yml
  format: yaml
  label: Whatfix Content API
  slug: whatfix-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whatfix/openapi/whatfix-content-api-openapi.yml
- filename: whatfix-end-users-api-openapi.yml
  format: yaml
  label: Whatfix End Users API
  slug: whatfix-end-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whatfix/openapi/whatfix-end-users-api-openapi.yml
- filename: whatfix-reports-api-openapi.yml
  format: yaml
  label: Whatfix Reports API
  slug: whatfix-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whatfix/openapi/whatfix-reports-api-openapi.yml
- filename: whatfix-segments-api-openapi.yml
  format: yaml
  label: Whatfix Segments API
  slug: whatfix-segments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whatfix/openapi/whatfix-segments-api-openapi.yml
claim_count: 14
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: nda
    scope: null
    text: ISO 27001 v2022 Compliant
    type: Compliant
  - framework: ISO42001
    issuer: null
    period: null
    report_access: nda
    scope: null
    text: ISO 42001 Certified
    type: Certified
  - framework: ISO27701
    issuer: null
    period: null
    report_access: nda
    scope: null
    text: ISO 27701 Compliant
    type: Compliant
  - framework: ISO27017
    issuer: null
    period: null
    report_access: nda
    scope: null
    text: ISO 27017 Compliant
    type: Compliant
  - framework: ISO27018
    issuer: null
    period: null
    report_access: nda
    scope: null
    text: ISO 27018 Compliant
    type: Compliant
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: nda
    scope: null
    text: CSA Star Compliant
    type: Compliant
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: null
    text: SOC 2 Compliant
    type: Compliant
  - framework: GDPR
    issuer: null
    period: null
    report_access: nda
    scope: null
    text: GDPR Compliant
    type: Compliant
  - framework: HIPAA
    issuer: null
    period: null
    report_access: nda
    scope: null
    text: HIPAA Compliant
    type: Compliant
  - framework: CCPA
    issuer: null
    period: null
    report_access: nda
    scope: null
    text: CPRA (formerly CCPA) Compliant
    type: Compliant
  - framework: CyberEssentials
    issuer: null
    period: null
    report_access: nda
    scope: Cyber Essentials Plus
    text: Cyber Essentials Plus Compliant
    type: Compliant
  - framework: TISAX
    issuer: null
    period: null
    report_access: nda
    scope: null
    text: TISAX Compliant
    type: Compliant
  - framework: other
    issuer: null
    period: null
    report_access: nda
    scope: GxP
    text: GxP Compliant
    type: Compliant
  - framework: other
    issuer: null
    period: null
    report_access: nda
    scope: EU Artificial Intelligence Act
    text: EU Artificial Intelligence Act Compliant
    type: Compliant
  trust_center:
    url: https://trust.whatfix.com/
frameworks:
- CCPA
- CSA-STAR
- CyberEssentials
- GDPR
- HIPAA
- ISO27001
- ISO27017
- ISO27018
- ISO27701
- ISO42001
- SOC2
- TISAX
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Whatfix
provenance_date: '2026-11-10'
provider_name: Whatfix
provider_slug: whatfix
slug: whatfix-compliance
source_date: '2026-11-10'
source_filename: whatfix-compliance.yml
source_heading: Compliance
source_page: https://trust.whatfix.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Whatfix\naid: whatfix\nurl: https://trust.whatfix.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/whatfix-trust-center.yml\ntrust_center:\n  url: https://trust.whatfix.com/\nattestations:\n- framework: ISO27001\n  type: Compliant\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: ISO 27001 v2022 Compliant\n- framework: ISO42001\n  type: Certified\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: ISO 42001 Certified\n- framework: ISO27701\n  type: Compliant\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: ISO 27701\
  \ Compliant\n- framework: ISO27017\n  type: Compliant\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: ISO 27017 Compliant\n- framework: ISO27018\n  type: Compliant\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: ISO 27018 Compliant\n- framework: CSA-STAR\n  type: Compliant\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: CSA Star Compliant\n- framework: SOC2\n  type: Compliant\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: SOC 2 Compliant\n- framework: GDPR\n  type: Compliant\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: GDPR Compliant\n- framework: HIPAA\n  type: Compliant\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: HIPAA Compliant\n- framework: CCPA\n  type: Compliant\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: CPRA (formerly CCPA) Compliant\n- framework: CyberEssentials\n\
  \  type: Compliant\n  scope: Cyber Essentials Plus\n  period: null\n  issuer: null\n  report_access: nda\n  text: Cyber Essentials Plus Compliant\n- framework: TISAX\n  type: Compliant\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: TISAX Compliant\n- framework: other\n  type: Compliant\n  scope: GxP\n  period: null\n  issuer: null\n  report_access: nda\n  text: GxP Compliant\n- framework: other\n  type: Compliant\n  scope: EU Artificial Intelligence Act\n  period: null\n  issuer: null\n  report_access: nda\n  text: EU Artificial Intelligence Act Compliant\n"
source_yaml_url: https://artifacts.apis.io/whatfix/compliance/whatfix-compliance.yml
stated_fields:
- attestations
summary_line: 14 quoted statements, read from Whatfix's own page on 2026-11-10.
synthetic: false
tags:
- Digital Adoption
- In-App Guidance
- Onboarding
- Analytics
- Self-Help
---
