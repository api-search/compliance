---
api_specs:
- filename: vpn-catalog-api-openapi.yml
  format: yaml
  label: VPN Catalog API
  slug: vpn-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vpn/openapi/vpn-catalog-api-openapi.yml
- filename: vpn-servers-api-openapi.yml
  format: yaml
  label: VPN Servers API
  slug: vpn-servers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vpn/openapi/vpn-servers-api-openapi.yml
- filename: vpn-stats-api-openapi.yml
  format: yaml
  label: VPN Stats API
  slug: vpn-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vpn/openapi/vpn-stats-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: security, availability, and confidentiality Trust Services Criteria
    text: Tailscale has completed a SOC 2 Type II certification, meeting AICPA's Trust Services Criteria for security, availability, and confidentiality.
    type: SOC 2 Type II certification
  trust_center:
    url: https://tailscale.com/security
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: VPN
provenance_date: '2026-11-10'
provider_name: VPN
provider_slug: vpn
slug: vpn-compliance
source_date: '2026-11-10'
source_filename: vpn-compliance.yml
source_heading: Compliance
source_page: https://tailscale.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: VPN\naid: vpn\nurl: https://tailscale.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/vpn-trust-center.yml\ntrust_center:\n  url: https://tailscale.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II certification\n  scope: security, availability, and confidentiality Trust Services Criteria\n  period: null\n  issuer: null\n  report_access: nda\n  text: Tailscale has completed a SOC 2 Type II certification, meeting AICPA's Trust Services Criteria for security,\n    availability, and confidentiality.\n"
source_yaml_url: https://artifacts.apis.io/vpn/compliance/vpn-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from VPN's own page on 2026-11-10.
synthetic: false
tags:
- Encryption
- Networking
- Privacy
- Security
- VPN
---
