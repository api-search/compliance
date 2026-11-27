---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Wasabi products and physical data center locations
    text: Wasabi's products and physical data center locations are ISO 27001 compliant.
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: top tier data centers
    text: Wasabi is deployed worldwide in top tier data centers that are SOC 2 compliant and certified for PCI-DSS.
    type: attestation
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: payments
    text: All payments are PCI-DSS certified.
    type: certification
  trust_center:
    url: https://wasabi.com/cloud-object-storage/security
frameworks:
- ISO27001
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Wasabi
provenance_date: '2026-11-10'
provider_name: Wasabi
provider_slug: wasabi
slug: wasabi-compliance
source_date: '2026-11-10'
source_filename: wasabi-compliance.yml
source_heading: Compliance
source_page: https://wasabi.com/cloud-object-storage/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Wasabi\naid: wasabi\nurl: https://wasabi.com/cloud-object-storage/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/wasabi-trust-center.yml\ntrust_center:\n  url: https://wasabi.com/cloud-object-storage/security\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: Wasabi products and physical data center locations\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Wasabi's products and physical data center locations are ISO 27001 compliant.\n- framework: SOC2\n  type: attestation\n  scope: top tier data centers\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: Wasabi is deployed worldwide in top tier data centers that are SOC 2 compliant and certified for PCI-DSS.\n- framework: PCI-DSS\n  type: certification\n  scope: payments\n  period: null\n  issuer: null\n  report_access: unstated\n  text: All payments are PCI-DSS certified.\n"
source_yaml_url: https://artifacts.apis.io/wasabi/compliance/wasabi-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Wasabi's own page on 2026-11-10.
synthetic: false
tags:
- Cloud Storage
- Object Storage
- S3 Compatible
- REST API
- Hot Storage
- Buckets
- Objects
- Media Storage
- Backup
- Enterprise Storage
- Storage
---
