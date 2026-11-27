---
api_specs:
- filename: cognism-compliance-api-openapi.yml
  format: yaml
  label: Cognism Compliance API
  slug: cognism-compliance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cognism/openapi/cognism-compliance-api-openapi.yml
- filename: cognism-enrich-api-openapi.yml
  format: yaml
  label: Cognism Enrich API
  slug: cognism-enrich-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cognism/openapi/cognism-enrich-api-openapi.yml
- filename: cognism-entitlement-api-openapi.yml
  format: yaml
  label: Cognism Entitlement API
  slug: cognism-entitlement-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cognism/openapi/cognism-entitlement-api-openapi.yml
- filename: cognism-filter-api-openapi.yml
  format: yaml
  label: Cognism Filter API
  slug: cognism-filter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cognism/openapi/cognism-filter-api-openapi.yml
- filename: cognism-redeem-api-openapi.yml
  format: yaml
  label: Cognism Redeem API
  slug: cognism-redeem-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cognism/openapi/cognism-redeem-api-openapi.yml
- filename: cognism-search-api-openapi.yml
  format: yaml
  label: Cognism Search API
  slug: cognism-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cognism/openapi/cognism-search-api-openapi.yml
claim_count: 10
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: company certification
    text: We are ISO 27001 & ISO 27701 certified
    type: certification
  - framework: ISO27701
    issuer: null
    period: null
    report_access: unstated
    scope: company certification
    text: We are ISO 27001 & ISO 27701 certified
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: security and availability
    text: We’re also attested for SOC2 Type II in security and availability.
    type: Type II report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: data collection and processing practices
    text: Our data collection and processing practices adhere to GDPR and CCPA guidelines
    type: regulatory compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: data collection and processing practices
    text: Our data collection and processing practices adhere to GDPR and CCPA guidelines
    type: regulatory compliance
  - framework: ISO27001
    issuer: UKAS-accredited certification body
    period: null
    report_access: unstated
    scope: information security management
    source: https://www.cognism.com/security
    text: Cognism is delighted to share that we have officially confirmed dual ISO 27001 and ISO 27701 certifications, certified by a UKAS-accredited certification body.
    type: certification
  - framework: ISO27701
    issuer: UKAS-accredited certification body
    period: null
    report_access: unstated
    scope: privacy information management
    source: https://www.cognism.com/security
    text: ISO 27001 & 27701 Certified information security and privacy management frameworks.
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Security and Availability
    source: https://www.cognism.com/security
    text: SOC 2 Type II (Security and Availability)
    type: SOC 2 Type II report (Security and Availability)
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: data protection
    source: https://www.cognism.com/security
    text: Fully aligned with EU data protection regulations and privacy-first data handling.
    type: stated alignment
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: US state-level privacy laws including California regulations
    source: https://www.cognism.com/security
    text: Compliant with US state-level privacy laws including California regulations.
    type: stated compliance
  trust_center:
    url: https://www.cognism.com/compliance
frameworks:
- CCPA
- GDPR
- ISO27001
- ISO27701
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Cognism
provenance_date: '2026-11-09'
provider_name: Cognism
provider_slug: cognism
slug: cognism-compliance
source_date: '2026-11-09'
source_filename: cognism-compliance.yml
source_heading: Compliance
source_page: https://www.cognism.com/compliance
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Cognism\naid: cognism\nurl: https://www.cognism.com/compliance\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/cognism-trust-center.yml\n  sources:\n  - https://www.cognism.com/compliance\n  - https://www.cognism.com/security\ntrust_center:\n  url: https://www.cognism.com/compliance\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: company certification\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We are ISO 27001 & ISO 27701 certified\n- framework: ISO27701\n  type: certification\n  scope: company certification\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: We are ISO 27001 & ISO 27701 certified\n- framework: SOC2\n  type: Type II report\n  scope: security and availability\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We’re also attested for SOC2 Type II in security and availability.\n- framework: GDPR\n  type: regulatory compliance\n  scope: data collection and processing practices\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our data collection and processing practices adhere to GDPR and CCPA guidelines\n- framework: CCPA\n  type: regulatory compliance\n  scope: data collection and processing practices\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our data collection and processing practices adhere to GDPR and CCPA guidelines\n- framework: ISO27001\n  type: certification\n  scope: information security management\n  period: null\n  issuer: UKAS-accredited certification body\n  report_access: unstated\n  text: Cognism is delighted to share that we have\
  \ officially confirmed dual ISO 27001 and ISO 27701 certifications,\n    certified by a UKAS-accredited certification body.\n  source: https://www.cognism.com/security\n- framework: ISO27701\n  type: certification\n  scope: privacy information management\n  period: null\n  issuer: UKAS-accredited certification body\n  report_access: unstated\n  text: ISO 27001 & 27701 Certified information security and privacy management frameworks.\n  source: https://www.cognism.com/security\n- framework: SOC2\n  type: SOC 2 Type II report (Security and Availability)\n  scope: Security and Availability\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II (Security and Availability)\n  source: https://www.cognism.com/security\n- framework: GDPR\n  type: stated alignment\n  scope: data protection\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Fully aligned with EU data protection regulations and privacy-first data handling.\n  source: https://www.cognism.com/security\n\
  - framework: CCPA\n  type: stated compliance\n  scope: US state-level privacy laws including California regulations\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliant with US state-level privacy laws including California regulations.\n  source: https://www.cognism.com/security\n"
source_yaml_url: https://artifacts.apis.io/cognism/compliance/cognism-compliance.yml
stated_fields:
- attestations
summary_line: 10 quoted statements, read from Cognism's own page on 2026-11-09.
synthetic: false
tags:
- Sales Intelligence
- B2B
- Data Enrichment
- Contact Data
- GDPR
- Intent Data
- Lead Generation
- Firmographics
- Technographics
- Company Data
- Prospecting
- Data as a Service
---
