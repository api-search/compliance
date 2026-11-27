---
api_specs:
- filename: emplifi-io-ads-api-openapi.yml
  format: yaml
  label: Emplifi Ads API
  slug: emplifi-io-ads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emplifi-io/openapi/emplifi-io-ads-api-openapi.yml
- filename: emplifi-io-assets-api-openapi.yml
  format: yaml
  label: Emplifi Assets API
  slug: emplifi-io-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emplifi-io/openapi/emplifi-io-assets-api-openapi.yml
- filename: emplifi-io-care-api-openapi.yml
  format: yaml
  label: Emplifi Care API
  slug: emplifi-io-care-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emplifi-io/openapi/emplifi-io-care-api-openapi.yml
- filename: emplifi-io-community-api-openapi.yml
  format: yaml
  label: Emplifi Community API
  slug: emplifi-io-community-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emplifi-io/openapi/emplifi-io-community-api-openapi.yml
- filename: emplifi-io-listening-api-openapi.yml
  format: yaml
  label: Emplifi Listening API
  slug: emplifi-io-listening-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emplifi-io/openapi/emplifi-io-listening-api-openapi.yml
- filename: emplifi-io-posts-api-openapi.yml
  format: yaml
  label: Emplifi Posts API
  slug: emplifi-io-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emplifi-io/openapi/emplifi-io-posts-api-openapi.yml
- filename: emplifi-io-profile-metrics-api-openapi.yml
  format: yaml
  label: Emplifi Profile Metrics API
  slug: emplifi-io-profile-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emplifi-io/openapi/emplifi-io-profile-metrics-api-openapi.yml
- filename: emplifi-io-reference-api-openapi.yml
  format: yaml
  label: Emplifi Reference API
  slug: emplifi-io-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emplifi-io/openapi/emplifi-io-reference-api-openapi.yml
claim_count: 6
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: security controls
    text: SOC 2 Type II Independent audit of security controls; report available under NDA
    type: Type II
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: information security management system
    text: ISO/IEC 27001:2022 Certified information security management system
    type: certification
  - framework: SOC1
    issuer: null
    period: null
    report_access: unstated
    scope: controls relevant to financial reporting
    text: SOC 1 Type II Independent audit of controls relevant to financial reporting
    type: Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: data protection laws applicable to services
    text: We comply with the data protection laws that apply to our services, including the EU and UK GDPR, the California Consumer Privacy Act, Brazil’s LGPD, Quebec Law 25 and Singapore’s PDPA
    type: legal compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: data protection laws applicable to services
    text: We comply with the data protection laws that apply to our services, including the EU and UK GDPR, the California Consumer Privacy Act, Brazil’s LGPD, Quebec Law 25 and Singapore’s PDPA
    type: legal compliance
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: EU AI Act transparency obligations
    text: we apply the transparency obligations of the EU AI Act within the timeframes the Act sets
    type: AI regulation compliance
  trust_center:
    url: https://emplifi.io/legal/trust-center/
frameworks:
- CCPA
- GDPR
- ISO27001
- SOC1
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Emplifi
provenance_date: '2026-11-09'
provider_name: Emplifi
provider_slug: emplifi-io
slug: emplifi-io-compliance
source_date: '2026-11-09'
source_filename: emplifi-io-compliance.yml
source_heading: Compliance
source_page: https://emplifi.io/legal/trust-center/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Emplifi\naid: emplifi-io\nurl: https://emplifi.io/legal/trust-center/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://emplifi.io/legal/trust-center/\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: security controls\n  period: null\n  issuer: null\n  report_access: nda\n  text: SOC 2 Type II Independent audit of security controls; report available under NDA\n- framework: ISO27001\n  type: certification\n  scope: information security management system\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO/IEC 27001:2022 Certified information security management system\n- framework:\
  \ SOC1\n  type: Type II\n  scope: controls relevant to financial reporting\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 1 Type II Independent audit of controls relevant to financial reporting\n- framework: GDPR\n  type: legal compliance\n  scope: data protection laws applicable to services\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We comply with the data protection laws that apply to our services, including the EU and UK GDPR, the California\n    Consumer Privacy Act, Brazil’s LGPD, Quebec Law 25 and Singapore’s PDPA\n- framework: CCPA\n  type: legal compliance\n  scope: data protection laws applicable to services\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We comply with the data protection laws that apply to our services, including the EU and UK GDPR, the California\n    Consumer Privacy Act, Brazil’s LGPD, Quebec Law 25 and Singapore’s PDPA\n- framework: other\n  type: AI regulation compliance\n  scope: EU\
  \ AI Act transparency obligations\n  period: null\n  issuer: null\n  report_access: unstated\n  text: we apply the transparency obligations of the EU AI Act within the timeframes the Act sets\n"
source_yaml_url: https://artifacts.apis.io/emplifi-io/compliance/emplifi-io-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from Emplifi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketing
- Social Media
- Analytics
- Social Media Analytics
- Social Listening
- Marketing Analytics
- Digital Asset Management
- Customer Care
- Emplifi
---
