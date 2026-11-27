---
api_specs:
- filename: appcheck-ng-openapi-generated.yml
  format: yaml
  label: APPCHECK API
  slug: appcheck-ng-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appcheck-ng/openapi/_ae-authored/appcheck-ng-openapi-generated.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: AppCheck holds ISO27001:2022 certification which is continually assessed through a schedule of internal audits and annually audits via external auditors.
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: AppCheck is committed to providing robust and best-practice data protection measures in line with the GDPR.
    type: compliance commitment
  trust_center:
    url: https://appcheck-ng.com/compliance/
frameworks:
- GDPR
- ISO27001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: APPCHECK
provenance_date: '2026-11-09'
provider_name: APPCHECK
provider_slug: appcheck-ng
slug: appcheck-ng-compliance
source_date: '2026-11-09'
source_filename: appcheck-ng-compliance.yml
source_heading: Compliance
source_page: https://appcheck-ng.com/compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: APPCHECK\naid: appcheck-ng\nurl: https://appcheck-ng.com/compliance/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://appcheck-ng.com/compliance/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AppCheck holds ISO27001:2022 certification which is continually assessed through a schedule of internal\n    audits and annually audits via external auditors.\n- framework: GDPR\n  type: compliance commitment\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: AppCheck is committed to providing\
  \ robust and best-practice data protection measures in line with the GDPR.\n"
source_yaml_url: https://artifacts.apis.io/appcheck-ng/compliance/appcheck-ng-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from APPCHECK's own page on 2026-11-09.
synthetic: false
tags:
- Web Application Scanning
- API Security
- Infrastructure Scanning
- CMS Security
- Single Page Application Scanning
- Automated Penetration Testing
---
