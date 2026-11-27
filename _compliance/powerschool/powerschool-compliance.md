---
api_specs:
- filename: powerschool-authentication-api-openapi.yml
  format: yaml
  label: PowerSchool Authentication API
  slug: powerschool-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/powerschool/openapi/powerschool-authentication-api-openapi.yml
- filename: powerschool-courses-api-openapi.yml
  format: yaml
  label: PowerSchool Courses API
  slug: powerschool-courses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/powerschool/openapi/powerschool-courses-api-openapi.yml
- filename: powerschool-district-api-openapi.yml
  format: yaml
  label: PowerSchool District API
  slug: powerschool-district-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/powerschool/openapi/powerschool-district-api-openapi.yml
- filename: powerschool-metadata-api-openapi.yml
  format: yaml
  label: PowerSchool Metadata API
  slug: powerschool-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/powerschool/openapi/powerschool-metadata-api-openapi.yml
- filename: powerschool-powerquery-api-openapi.yml
  format: yaml
  label: PowerSchool PowerQuery API
  slug: powerschool-powerquery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/powerschool/openapi/powerschool-powerquery-api-openapi.yml
- filename: powerschool-schools-api-openapi.yml
  format: yaml
  label: PowerSchool Schools API
  slug: powerschool-schools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/powerschool/openapi/powerschool-schools-api-openapi.yml
- filename: powerschool-sections-api-openapi.yml
  format: yaml
  label: PowerSchool Sections API
  slug: powerschool-sections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/powerschool/openapi/powerschool-sections-api-openapi.yml
- filename: powerschool-students-api-openapi.yml
  format: yaml
  label: PowerSchool Students API
  slug: powerschool-students-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/powerschool/openapi/powerschool-students-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: security management system
    text: We perform annual third-party audits of our security management system and have achieved the internationally recognized ISO 27001:2022 certification.
    type: certification
  - framework: SOC2
    issuer: null
    period: annual
    report_access: unstated
    scope: controls relevant to security, availability, and confidentiality for multiple applications
    text: We receive annual SOC 2 Type 2 examinations on our controls relevant to security, availability, and confidentiality for multiple applications to minimize risk and exposure to customer data.
    type: SOC 2 Type 2 examination
  trust_center:
    url: https://www.powerschool.com/security/
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: PowerSchool
provenance_date: '2026-11-10'
provider_name: PowerSchool
provider_slug: powerschool
slug: powerschool-compliance
source_date: '2026-11-10'
source_filename: powerschool-compliance.yml
source_heading: Compliance
source_page: https://www.powerschool.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: PowerSchool\naid: powerschool\nurl: https://www.powerschool.com/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/powerschool-trust-center.yml\ntrust_center:\n  url: https://www.powerschool.com/security/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: security management system\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We perform annual third-party audits of our security management system and have achieved the internationally\n    recognized ISO 27001:2022 certification.\n- framework: SOC2\n  type: SOC 2 Type 2 examination\n  scope: controls\
  \ relevant to security, availability, and confidentiality for multiple applications\n  period: annual\n  issuer: null\n  report_access: unstated\n  text: We receive annual SOC 2 Type 2 examinations on our controls relevant to security, availability, and confidentiality\n    for multiple applications to minimize risk and exposure to customer data.\n"
source_yaml_url: https://artifacts.apis.io/powerschool/compliance/powerschool-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from PowerSchool's own page on 2026-11-10.
synthetic: false
tags:
- K-12
- Education
- Student Information System
- SIS
- Students
- Grades
- Attendance
- Enrollment
- Scheduling
- EdTech
---
