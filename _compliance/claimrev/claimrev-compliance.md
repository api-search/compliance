---
api_specs:
- filename: claimrev-openapi-generated.yml
  format: yaml
  label: Claim.Revolution API
  slug: claimrev-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/claimrev/openapi/_ae-authored/claimrev-openapi-generated.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: ClaimRev clearinghouse operations
    text: ClaimRev is a HIPAA-covered entity operating as a business associate for every provider we serve.
    type: Business associate compliance
  - framework: other
    issuer: X12
    period: null
    report_access: unstated
    scope: EDI transaction sets required under HIPAA
    text: ClaimRev is licensed through X12, the standards body responsible for the EDI transaction sets required under HIPAA.
    type: X12 license
  trust_center:
    url: https://www.claimrev.com/security/
frameworks:
- HIPAA
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Claim.Revolution
provenance_date: '2026-11-09'
provider_name: Claim.Revolution
provider_slug: claimrev
slug: claimrev-compliance
source_date: '2026-11-09'
source_filename: claimrev-compliance.yml
source_heading: Compliance
source_page: https://www.claimrev.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Claim.Revolution\naid: claimrev\nurl: https://www.claimrev.com/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.claimrev.com/security/\nattestations:\n- framework: HIPAA\n  type: Business associate compliance\n  scope: ClaimRev clearinghouse operations\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ClaimRev is a HIPAA-covered entity operating as a business associate for every provider we serve.\n- framework: other\n  type: X12 license\n  scope: EDI transaction sets required under HIPAA\n  period: null\n  issuer: X12\n  report_access: unstated\n  text: ClaimRev is licensed\
  \ through X12, the standards body responsible for the EDI transaction sets required under\n    HIPAA.\n"
source_yaml_url: https://artifacts.apis.io/claimrev/compliance/claimrev-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Claim.Revolution's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Claims
- Billing
---
