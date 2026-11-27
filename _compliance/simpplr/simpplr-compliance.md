---
api_specs:
- filename: simpplr-alerts-api-openapi.yml
  format: yaml
  label: Simpplr Alerts API
  slug: simpplr-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpplr/openapi/simpplr-alerts-api-openapi.yml
- filename: simpplr-analytics-api-openapi.yml
  format: yaml
  label: Simpplr Analytics API
  slug: simpplr-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpplr/openapi/simpplr-analytics-api-openapi.yml
- filename: simpplr-audience-api-openapi.yml
  format: yaml
  label: Simpplr Audience API
  slug: simpplr-audience-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpplr/openapi/simpplr-audience-api-openapi.yml
- filename: simpplr-blogs-api-openapi.yml
  format: yaml
  label: Simpplr Blogs API
  slug: simpplr-blogs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpplr/openapi/simpplr-blogs-api-openapi.yml
- filename: simpplr-carousels-api-openapi.yml
  format: yaml
  label: Simpplr Carousels API
  slug: simpplr-carousels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpplr/openapi/simpplr-carousels-api-openapi.yml
- filename: simpplr-contents-api-openapi.yml
  format: yaml
  label: Simpplr Contents API
  slug: simpplr-contents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpplr/openapi/simpplr-contents-api-openapi.yml
- filename: simpplr-notifications-api-openapi.yml
  format: yaml
  label: Simpplr Notifications API
  slug: simpplr-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpplr/openapi/simpplr-notifications-api-openapi.yml
- filename: simpplr-people-api-openapi.yml
  format: yaml
  label: Simpplr People API
  slug: simpplr-people-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpplr/openapi/simpplr-people-api-openapi.yml
- filename: simpplr-search-api-openapi.yml
  format: yaml
  label: Simpplr Search API
  slug: simpplr-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpplr/openapi/simpplr-search-api-openapi.yml
- filename: simpplr-simpplr-api-gw-search-people-by-id-api-openapi.yml
  format: yaml
  label: Simpplr Simpplr Api Gw Search People By Id API
  slug: simpplr-simpplr-api-gw-search-people-by-id-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpplr/openapi/simpplr-simpplr-api-gw-search-people-by-id-api-openapi.yml
- filename: simpplr-sites-api-openapi.yml
  format: yaml
  label: Simpplr Sites API
  slug: simpplr-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpplr/openapi/simpplr-sites-api-openapi.yml
claim_count: 7
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: independent firm accredited by the ANAB standards body
    period: annually
    report_access: unstated
    scope: information security management system (ISMS)
    text: Simpplr is ISO 27001:2022 certified annually.
    type: certification
  - framework: SOC2
    issuer: independent auditor regulated by the AICPA
    period: null
    report_access: nda
    scope: security controls
    text: SOC 2 attestation reports may be shared under NDA.
    type: Type 2 audit
  - framework: SOC3
    issuer: AICPA
    period: null
    report_access: public
    scope: security, availability, processing integrity, and confidentiality
    text: SOC 3 reports are similar to SOC 2, but they contain less detail and may be shared publicly without an NDA.
    type: report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: data privacy
    text: GDPR (EU and UK)
    type: compliance
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: healthcare
    text: Simpplr complies with HIPAA standards
    type: compliance
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: EU-U.S. and Swiss-U.S. Data Privacy Framework
    text: Simpplr is an active member of the EU-US and Swiss-US Data Privacy Framework program as well as the UK Extension to the EU-U.S. Data Privacy Framework.
    type: Data Privacy Framework participation
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: financial services
    text: Simpplr is 23 NYCRR Part 500-ready
    type: readiness
  trust_center:
    url: https://www.simpplr.com/security-compliance/
frameworks:
- GDPR
- HIPAA
- ISO27001
- SOC2
- SOC3
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Simpplr
provenance_date: '2026-11-10'
provider_name: Simpplr
provider_slug: simpplr
slug: simpplr-compliance
source_date: '2026-11-10'
source_filename: simpplr-compliance.yml
source_heading: Compliance
source_page: https://www.simpplr.com/security-compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Simpplr\naid: simpplr\nurl: https://www.simpplr.com/security-compliance/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.simpplr.com/security-compliance/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: information security management system (ISMS)\n  period: annually\n  issuer: independent firm accredited by the ANAB standards body\n  report_access: unstated\n  text: Simpplr is ISO 27001:2022 certified annually.\n- framework: SOC2\n  type: Type 2 audit\n  scope: security controls\n  period: null\n  issuer: independent auditor regulated by the AICPA\n  report_access: nda\n \
  \ text: SOC 2 attestation reports may be shared under NDA.\n- framework: SOC3\n  type: report\n  scope: security, availability, processing integrity, and confidentiality\n  period: null\n  issuer: AICPA\n  report_access: public\n  text: SOC 3 reports are similar to SOC 2, but they contain less detail and may be shared publicly without an NDA.\n- framework: GDPR\n  type: compliance\n  scope: data privacy\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR (EU and UK)\n- framework: HIPAA\n  type: compliance\n  scope: healthcare\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Simpplr complies with HIPAA standards\n- framework: other\n  type: Data Privacy Framework participation\n  scope: EU-U.S. and Swiss-U.S. Data Privacy Framework\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Simpplr is an active member of the EU-US and Swiss-US Data Privacy Framework program as well as the UK Extension\n    to the EU-U.S. Data Privacy Framework.\n\
  - framework: other\n  type: readiness\n  scope: financial services\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Simpplr is 23 NYCRR Part 500-ready\n"
source_yaml_url: https://artifacts.apis.io/simpplr/compliance/simpplr-compliance.yml
stated_fields:
- attestations
summary_line: 7 quoted statements, read from Simpplr's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Employee Experience
- Intranet
- Employee Communications
- Digital Workplace
- Internal Communications
- Human Resources
- Collaboration
- Enterprise Software
- Salesforce
---
