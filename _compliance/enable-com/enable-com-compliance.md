---
api_specs:
- filename: enable-com-openapi-generated.yml
  format: yaml
  label: Enable API
  slug: enable-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/enable-com/openapi/_ae-authored/enable-com-openapi-generated.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC1
    issuer: KirkpatrickPrice
    period: null
    report_access: unstated
    scope: Internal controls relevant to internal control over financial reporting
    text: We completed our SOC 1 and 2 type I and II report audit inspections which were performed by KirkpatrickPrice.
    type: SOC 1 Type I and Type II audit
  - framework: SOC2
    issuer: KirkpatrickPrice
    period: null
    report_access: unstated
    scope: Security, availability, processing integrity, confidentiality, and system privacy controls
    text: During the audit, a service organization’s non-financial reporting controls and their relationship to security, availability, processing integrity, confidentiality, and system privacy are tested.
    type: SOC 2 Type I and Type II audit
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Information security management system
    text: Enable have been compliant with ISO 27001 since 2013.
    type: ISO/IEC 27001 certification
  - framework: ISO9001
    issuer: null
    period: null
    report_access: unstated
    scope: Quality management system
    text: Enable have been compliant with ISO 9001 since 2013.
    type: ISO 9001 certification
  trust_center:
    url: https://developers.enable.com/articles/certifications-and-compliance
frameworks:
- ISO27001
- ISO9001
- SOC1
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Enable
provenance_date: '2026-11-09'
provider_name: Enable
provider_slug: enable-com
slug: enable-com-compliance
source_date: '2026-11-09'
source_filename: enable-com-compliance.yml
source_heading: Compliance
source_page: https://developers.enable.com/articles/certifications-and-compliance
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Enable\naid: enable-com\nurl: https://developers.enable.com/articles/certifications-and-compliance\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://developers.enable.com/articles/certifications-and-compliance\nattestations:\n- framework: SOC1\n  type: SOC 1 Type I and Type II audit\n  scope: Internal controls relevant to internal control over financial reporting\n  period: null\n  issuer: KirkpatrickPrice\n  report_access: unstated\n  text: We completed our SOC 1 and 2 type I and II report audit inspections which were performed by KirkpatrickPrice.\n- framework: SOC2\n  type: SOC 2 Type I and Type II\
  \ audit\n  scope: Security, availability, processing integrity, confidentiality, and system privacy controls\n  period: null\n  issuer: KirkpatrickPrice\n  report_access: unstated\n  text: During the audit, a service organization’s non-financial reporting controls and their relationship to security,\n    availability, processing integrity, confidentiality, and system privacy are tested.\n- framework: ISO27001\n  type: ISO/IEC 27001 certification\n  scope: Information security management system\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Enable have been compliant with ISO 27001 since 2013.\n- framework: ISO9001\n  type: ISO 9001 certification\n  scope: Quality management system\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Enable have been compliant with ISO 9001 since 2013.\n"
source_yaml_url: https://artifacts.apis.io/enable-com/compliance/enable-com-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Enable's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Pricing
- Rebate
- Software-as-a-Service
---
