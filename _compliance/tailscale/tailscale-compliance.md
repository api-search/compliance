---
api_specs:
- filename: tailscale-devices-api-openapi.yml
  format: yaml
  label: Tailscale Devices API
  slug: tailscale-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tailscale/openapi/tailscale-devices-api-openapi.yml
- filename: tailscale-dns-api-openapi.yml
  format: yaml
  label: Tailscale DNS API
  slug: tailscale-dns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tailscale/openapi/tailscale-dns-api-openapi.yml
- filename: tailscale-invites-api-openapi.yml
  format: yaml
  label: Tailscale Invites API
  slug: tailscale-invites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tailscale/openapi/tailscale-invites-api-openapi.yml
- filename: tailscale-keys-api-openapi.yml
  format: yaml
  label: Tailscale Keys API
  slug: tailscale-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tailscale/openapi/tailscale-keys-api-openapi.yml
- filename: tailscale-logging-api-openapi.yml
  format: yaml
  label: Tailscale Logging API
  slug: tailscale-logging-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tailscale/openapi/tailscale-logging-api-openapi.yml
- filename: tailscale-policy-api-openapi.yml
  format: yaml
  label: Tailscale Policy API
  slug: tailscale-policy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tailscale/openapi/tailscale-policy-api-openapi.yml
- filename: tailscale-tailnet-api-openapi.yml
  format: yaml
  label: Tailscale Tailnet API
  slug: tailscale-tailnet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tailscale/openapi/tailscale-tailnet-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: security, availability, and confidentiality (AICPA Trust Services Criteria)
    text: Tailscale has completed a SOC 2 Type II certification, meeting AICPA's Trust Services Criteria for security, availability, and confidentiality.
    type: SOC 2 Type II
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Tailscale has completed the SAQ A form
    type: SAQ A self-assessment
  trust_center:
    url: https://tailscale.com/security
frameworks:
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Tailscale
provenance_date: '2026-11-10'
provider_name: Tailscale
provider_slug: tailscale
slug: tailscale-compliance
source_date: '2026-11-10'
source_filename: tailscale-compliance.yml
source_heading: Compliance
source_page: https://tailscale.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Tailscale\naid: tailscale\nurl: https://tailscale.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/tailscale-trust-center.yml\ntrust_center:\n  url: https://tailscale.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: security, availability, and confidentiality (AICPA Trust Services Criteria)\n  period: null\n  issuer: null\n  report_access: nda\n  text: Tailscale has completed a SOC 2 Type II certification, meeting AICPA's Trust Services Criteria for security,\n    availability, and confidentiality.\n- framework: PCI-DSS\n  type: SAQ A self-assessment\n  scope:\
  \ null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Tailscale has completed the SAQ A form\n"
source_yaml_url: https://artifacts.apis.io/tailscale/compliance/tailscale-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Tailscale's own page on 2026-11-10.
synthetic: false
tags:
- VPN
- Mesh Networking
- WireGuard
- Zero Trust
- Networking
- Identity
---
