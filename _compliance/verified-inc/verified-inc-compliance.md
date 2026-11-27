---
api_specs:
- filename: verified-inc-openapi-generated.yml
  format: yaml
  label: Verified API
  slug: verified-inc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/verified-inc/openapi/_ae-authored/verified-inc-openapi-generated.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: Zero Day CPA
    period: null
    report_access: nda
    scope: Security; 1-Click Health and platform controls covered
    text: Full reports are shared under NDA. Request them below.
    type: SOC 2 Type II
  - framework: HIPAA
    issuer: Zero Day CPA
    period: null
    report_access: nda
    scope: HIPAA Security, Breach Notification and Privacy Rules as business associate; 1-Click Health
    text: The same audit tested our safeguards against the HIPAA Security, Breach Notification and Privacy Rules, as they apply to business associates.
    type: HIPAA business associate compliance audit
  - framework: other
    issuer: Astra Security
    period: null
    report_access: nda
    scope: Customer dashboard in staging environment
    text: Astra Security tested our customer dashboard in its staging environment. We fixed the vulnerabilities they found and earned an A+ grade.
    type: Penetration test
  trust_center:
    url: https://verified.inc/trust
frameworks:
- HIPAA
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Verified
provenance_date: '2026-11-10'
provider_name: Verified
provider_slug: verified-inc
slug: verified-inc-compliance
source_date: '2026-11-10'
source_filename: verified-inc-compliance.yml
source_heading: Compliance
source_page: https://verified.inc/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Verified\naid: verified-inc\nurl: https://verified.inc/trust\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://verified.inc/trust\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: Security; 1-Click Health and platform controls covered\n  period: null\n  issuer: Zero Day CPA\n  report_access: nda\n  text: Full reports are shared under NDA. Request them below.\n- framework: HIPAA\n  type: HIPAA business associate compliance audit\n  scope: HIPAA Security, Breach Notification and Privacy Rules as business associate; 1-Click Health\n  period: null\n  issuer: Zero Day CPA\n  report_access:\
  \ nda\n  text: The same audit tested our safeguards against the HIPAA Security, Breach Notification and Privacy Rules,\n    as they apply to business associates.\n- framework: other\n  type: Penetration test\n  scope: Customer dashboard in staging environment\n  period: null\n  issuer: Astra Security\n  report_access: nda\n  text: Astra Security tested our customer dashboard in its staging environment. We fixed the vulnerabilities they\n    found and earned an A+ grade.\n"
source_yaml_url: https://artifacts.apis.io/verified-inc/compliance/verified-inc-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Verified's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Identity Verification
- Onboarding
- Phone Verification
- KYC
- Autofill
- Health Insurance
- Fintech
---
