---
api_specs:
- filename: yubico-validation-api-openapi.yml
  format: yaml
  label: Yubico Validation API
  slug: yubico-validation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yubico/openapi/yubico-validation-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: YubiKey 5 FIPS Series
    text: They are also Department of Defense Cybersecurity Maturity Model Certification (CMMC) Level III and FedRAMP compliant
    type: compliance
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: YubiKey 5 FIPS Series
    text: They are also Department of Defense Cybersecurity Maturity Model Certification (CMMC) Level III and FedRAMP compliant
    type: CMMC Level III certification
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: YubiKey 5 FIPS Series
    text: YubiKey 5 FIPS Series are FIPS 140-3 validated (Overall Level 2, Physical Security Level 3)
    type: FIPS 140-3 validation (Overall Level 2, Physical Security Level 3)
  trust_center:
    url: https://www.yubico.com/solutions/cybersecurity-compliance/
frameworks:
- FedRAMP
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Yubico
provenance_date: '2026-11-10'
provider_name: Yubico
provider_slug: yubico
slug: yubico-compliance
source_date: '2026-11-10'
source_filename: yubico-compliance.yml
source_heading: Compliance
source_page: https://www.yubico.com/solutions/cybersecurity-compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Yubico\naid: yubico\nurl: https://www.yubico.com/solutions/cybersecurity-compliance/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.yubico.com/solutions/cybersecurity-compliance/\nattestations:\n- framework: FedRAMP\n  type: compliance\n  scope: YubiKey 5 FIPS Series\n  period: null\n  issuer: null\n  report_access: unstated\n  text: They are also Department of Defense Cybersecurity Maturity Model Certification (CMMC) Level III and FedRAMP\n    compliant\n- framework: other\n  type: CMMC Level III certification\n  scope: YubiKey 5 FIPS Series\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: They are also Department of Defense Cybersecurity Maturity Model Certification (CMMC) Level III and FedRAMP\n    compliant\n- framework: other\n  type: FIPS 140-3 validation (Overall Level 2, Physical Security Level 3)\n  scope: YubiKey 5 FIPS Series\n  period: null\n  issuer: null\n  report_access: unstated\n  text: YubiKey 5 FIPS Series are FIPS 140-3 validated (Overall Level 2, Physical Security Level 3)\n"
source_yaml_url: https://artifacts.apis.io/yubico/compliance/yubico-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Yubico's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise
- Authentication
- Security
- Identity
- Hardware Security
- FIDO2
- WebAuthn
- One-Time Password
---
