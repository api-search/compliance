---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: TÜV Süd
    period: null
    report_access: unstated
    scope: Lunaweb GmbH ISMS supporting security, availability, processing integrity, confidentiality and privacy
    text: The ISMS of Lunaweb GmbH has received ISO 27001 certification from TÜV Süd
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: General Data Protection Regulation
    text: we’re committed to comply with the General Data Protection Regulation (GDPR)
    type: compliance commitment
  trust_center:
    url: https://cloudconvert.com/security
frameworks:
- GDPR
- ISO27001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: CloudConvert
provenance_date: '2026-11-09'
provider_name: CloudConvert
provider_slug: cloudconvert
slug: cloudconvert-compliance
source_date: '2026-11-09'
source_filename: cloudconvert-compliance.yml
source_heading: Compliance
source_page: https://cloudconvert.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: CloudConvert\naid: cloudconvert\nurl: https://cloudconvert.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/cloudconvert-trust-center.yml\ntrust_center:\n  url: https://cloudconvert.com/security\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: Lunaweb GmbH ISMS supporting security, availability, processing integrity, confidentiality and privacy\n  period: null\n  issuer: TÜV Süd\n  report_access: unstated\n  text: The ISMS of Lunaweb GmbH has received ISO 27001 certification from TÜV Süd\n- framework: GDPR\n  type: compliance commitment\n  scope: General Data Protection\
  \ Regulation\n  period: null\n  issuer: null\n  report_access: unstated\n  text: we’re committed to comply with the General Data Protection Regulation (GDPR)\n"
source_yaml_url: https://artifacts.apis.io/cloudconvert/compliance/cloudconvert-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from CloudConvert's own page on 2026-11-09.
synthetic: false
tags:
- Public APIs
- File Conversion
- Document Conversion
---
